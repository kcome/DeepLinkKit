xcodeproj 'DeepLinkKit.xcodeproj', 'Test' => :debug
inhibit_all_warnings!


target 'SenderDemo', :exclusive => true do
    pod 'DeepLinkKit', :path => '.'
end

target 'ReceiverDemo', :exclusive => true do
    pod 'DeepLinkKit', :path => '.'
end

target 'ReceiverDemoSwift', :exclusive => true do
    pod 'DeepLinkKit', :path => '.'
end

target 'Tests', :exclusive => true do
    pod 'Specta'
    pod 'Expecta'
    pod 'OCMock'
    pod 'KIF'
end
