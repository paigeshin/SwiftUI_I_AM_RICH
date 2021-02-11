```swift

//
//  ContentView.swift
//  SwiftUI-MICard
//
//  Created by paigeshin on 2021/02/11.
//

import SwiftUI

struct ContentView: View {
    var body: some View {
        ZStack {
            Color(.systemTeal)
                .edgesIgnoringSafeArea(.all)
            VStack {
                Text("Hello, world! This is amazing")
                    .font(.system(size: 40))
                    .fontWeight(.bold)
                    .foregroundColor(Color.white)
                Image("image1")
                    .resizable()
                    .aspectRatio(contentMode: .fit)
                    .frame(width: 200, height: 200, alignment: .center)
            }
        }

    }
}

struct ContentView_Previews: PreviewProvider {
    static var previews: some View {
        ContentView()
        //Use different device for previews
//            .previewDevice(PreviewDevice(rawValue: "iPhone SE"))
    }
}





```
