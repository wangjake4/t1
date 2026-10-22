代发 wailian999

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gt2lketvapg.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gt2ilgnpenf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gt2rbrehktr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gt2ixvqeoik.html

[A18] 字符与 ASCII 码互转
来源：http://dali.tian-w.cn/Article/details/gt2vwybdbni.html

Py:   ord("A"); chr(65)
来源：http://dali.haohaochexian.top/Article/details/gt2vdzdpppj.html

PHP:  ord("A"); chr(65)
来源：http://dali.c1oappe.top/Article/details/gt2sbrrjayk.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jiagoushi.top/Article/details/gt2npuxkqqr.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ppjwa.cn/Article/details/gt2adswtsmk.html

Java: (int) 'A'; (char) 65
来源：http://dali.sweek.top/Article/details/gt2qinjjzvi.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.sxryk.cn/Article/details/gt2ewpowxcj.html

Ruby: "A".ord; 65.chr
来源：http://dali.redwolf501.top/Article/details/gt2ksxwziyh.html

C#:   (int)'A'; (char)65
来源：http://dali.jyoumei.cn/Article/details/gt2hgunjwyt.html

[A19] 交换两个变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2fezvyzbr.html

Py:   a, b = b, a
来源：http://dali.mhx1999.top/Article/details/gt2buhrkoyw.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hammf.cn/Article/details/gt2xpaybhko.html

JS:   [a, b] = [b, a];
来源：http://dali.zhoulong.xyz/Article/details/gt2nqkttqnb.html

TS:   [a, b] = [b, a];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvwlwuwf.html

Java: int t = a; a = b; b = t;
来源：http://dali.jyoumei.cn/Article/details/gt2oyweamvg.html

Go:   a, b = b, a
来源：http://dali.316326.xyz/Article/details/gt2mrhmlsns.html

Ruby: a, b = b, a
来源：http://dali.meibo888.top/Article/details/gt2islmwcpy.html

C#:   (a, b) = (b, a);
来源：http://dali.9152youxi.cn/Article/details/gt2xtvakbso.html

[A20] 读取标准输入
来源：http://dali.yj20258888.top/Article/details/gt2cuwisuda.html

Py:   name = input("请输入：")
来源：http://dali.ehwqpu.com/Article/details/gt2usxzwbng.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xylfe.cn/Article/details/gt2tlxhzpvd.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yj202588.top/Article/details/gt2hxlmsbfl.html

TS:   // Node.js：readline 模块
来源：http://dali.pengpengdd.cyou/Article/details/gt2vpfudslg.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.smart0.xyz/Article/details/gt2flkinfgc.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ivvv.top/Article/details/gt2xdyijrux.html

Ruby: gets.chomp
来源：http://dali.zhixingplan.top/Article/details/gt2rxmxqcpg.html

C#:   Console.ReadLine();
来源：http://dali.daria6918.cn/Article/details/gt2sfwhqlsb.html

[A21] 保留指定小数位输出
来源：http://dali.ybcxt.top/Article/details/gt2zdzzldas.html

Py:   f"{3.14159:.2f}"
来源：http://dali.mhx1999.top/Article/details/gt2ysbrtplr.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.smart0.xyz/Article/details/gt2eswjuyax.html

JS:   (3.14159).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gt2lkxpoolg.html

TS:   (3.14159).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gt2qumuwsgw.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cashguo.top/Article/details/gt2nuoqqqbp.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gt2tivrkejr.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.nanxuanxn.top/Article/details/gt2gfeufsdk.html

C#:   3.14159.ToString("F2")
来源：http://dali.quarkkingdee.top/Article/details/gt2mzrqyxjj.html

[A22] 获取字符串长度
来源：http://dali.hywenlv.cn/Article/details/gt2dxttcyyq.html

Py:   len(s)
来源：http://dali.hammf.cn/Article/details/gt2ybjcjasm.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.mhx1999.top/Article/details/gt2ogaaqras.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhiwuduotai.top/Article/details/gt2erxuhabe.html

TS:   s.length
来源：http://dali.sysykeji.top/Article/details/gt2ygmztuxr.html

Java: s.length()
来源：http://dali.jyoumei.cn/Article/details/gt2umeffasr.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.chenzaomai.com/Article/details/gt2kzyxhuoq.html

Ruby: s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vontbjtq.html

C#:   s.Length
来源：http://dali.cdnleiting.top/Article/details/gt2wdhuitgv.html

[A23] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gt2tnjdfvvs.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sxryk.cn/Article/details/gt2ptzykwvz.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhongyouzk.top/Article/details/gt2fzusaubz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgufenzy.top/Article/details/gt2unobktcf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xziqi.cn/Article/details/gt2dazmlimg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shuidangran.top/Article/details/gt2bifkcgfa.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2evjefyiw.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ybcxt.top/Article/details/gt2yrvzvtup.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ydzc1.top/Article/details/gt2vbvkoceu.html

[A24] 去除首尾空白
来源：http://dali.yonumen.top/Article/details/gt2racblsnu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.vqdsnc.cn/Article/details/gt2tlrimild.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ivvv.top/Article/details/gt2nyqmypcc.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hysaishi.cn/Article/details/gt2uxvmbwsg.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tanke756.top/Article/details/gt2pacjpwyc.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.meibo888.top/Article/details/gt2twgiuwik.html

Go:   strings.TrimSpace(s)
来源：http://dali.yueranfly.top/Article/details/gt2mqxkfuoe.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shangyingyoupin.top/Article/details/gt2ifxbquwr.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinqigufen.top/Article/details/gt2rjdigspx.html

[A25] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zzppxljq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yj20258888.top/Article/details/gt2ekdkuxrv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sxryk.cn/Article/details/gt2tihnxumf.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuxming.cn/Article/details/gt2hfdyljll.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhixingplan.top/Article/details/gt2diciocsy.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zblaojzy.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jianghu66.top/Article/details/gt2ikrvmfui.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dashuyun.cn/Article/details/gt2zmdedclo.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.meibo888.top/Article/details/gt2vbobrolc.html

[A26] 类型转换总览
来源：http://dali.fzhhl.top/Article/details/gt2bmqzquit.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xziqi.cn/Article/details/gt2smvvfmzr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpqlsxgp.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.tianlin.xyz/Article/details/gt2gtvlybzb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.chenzaomai.com/Article/details/gt2zvxyiupw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sxryk.cn/Article/details/gt2vdxekjbu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhengqikj.top/Article/details/gt2zrxlibhq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.316326.xyz/Article/details/gt2cpggzwbs.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jinqigufen.top/Article/details/gt2pzgatbwp.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptsumnlu.html

B. 流程控制
来源：http://dali.9152youxi.cn/Article/details/gt2ghzuypmr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2upiubniv.html

[B01] 条件判断 if / else
来源：http://dali.shzxlz.cn/Article/details/gt2fjshkwlq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnccrvn.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yonumen.top/Article/details/gt2pijnlmwf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gt2mmuhtzka.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gt2ludmccxw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gt2cbijbwea.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.mhx1999.top/Article/details/gt2fzjhjzgd.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinqigfzy.top/Article/details/gt2jayyxlai.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gt2cmlgqhoz.html

[B02] 多分支 else if / elif
来源：http://dali.sweek.top/Article/details/gt2isprhvhc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhengqikj.top/Article/details/gt2fwzztpcp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.aibaodan.cn/Article/details/gt2snqkztux.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gt2imkdbryz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gt2styhvuto.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gt2xcszzfqy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ycssyeqv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.aizwys.cn/Article/details/gt2vdebvewy.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gt2kvxemhtl.html

[B03] switch / match / case
来源：http://dali.chenzaomai.com/Article/details/gt2wksbwhqv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.feifeiyinyue.top/Article/details/gt2axbxljmq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.bjfxy.top/Article/details/gt2xwnbeopv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gt2xcqkqisb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gt2vosisrnj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gt2iogaudjn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuanzx.com/Article/details/gt2qrdeqwif.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jiagoushi.top/Article/details/gt2cecqzign.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gzhubu.top/Article/details/gt2mtgqldsp.html

[B04] for 计数循环
来源：http://dali.xylfe.cn/Article/details/gt2rpnvqmat.html

Py:   for i in range(10): print(i)
来源：http://dali.zhoulong.xyz/Article/details/gt2monivuyt.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.snrcjt.cn/Article/details/gt2sguxnzjk.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnqzz.top/Article/details/gt2hgeyoscv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zycfv.cn/Article/details/gt2kjgrbdne.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.meibo888.top/Article/details/gt2vwghhshv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ppjwa.cn/Article/details/gt2xlyjbnau.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ydzc1.top/Article/details/gt2kydfqtjx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ehwqpu.com/Article/details/gt2jwrfgmqp.html

[B05] 遍历数组 / 列表
来源：http://dali.yj202588.top/Article/details/gt2xuxnazqt.html

Py:   for item in arr: print(item)
来源：http://dali.316326.xyz/Article/details/gt2smmrlsnz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.guannengcc.top/Article/details/gt2mttlkque.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.fengsongda.top/Article/details/gt2mcfbncak.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sufxvd.cn/Article/details/gt2buiklsmv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cqqwz.cn/Article/details/gt2ygafuhaa.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cqqwz.cn/Article/details/gt2msmouxil.html

Ruby: arr.each { |item| puts item }
来源：http://dali.fengsongda.top/Article/details/gt2woihejia.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shzxlz.cn/Article/details/gt2isadwand.html

[B06] 遍历字典 / 对象
来源：http://dali.ybcxt.top/Article/details/gt2rtaiygud.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.fzhhl.top/Article/details/gt2vuztizla.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.dashuyun.cn/Article/details/gt2iyjeowxl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfkupiz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gt2oaihgvcf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cucudq.cn/Article/details/gt2ondhjfkv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hammf.cn/Article/details/gt2cfxpgouw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gotoacloud.top/Article/details/gt2jpfpravj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhengqikj.top/Article/details/gt2ikknoxhk.html

[B07] while 循环
来源：http://dali.tian-w.cn/Article/details/gt2ocbhdigq.html

Py:   while i < 10: i += 1
来源：http://dali.yj202588.top/Article/details/gt2ysdtuawj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj20258.top/Article/details/gt2sxfhuiss.html

JS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfscwdiy.html

TS:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gt2zzzcfafz.html

Java: while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gt2rkejplew.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.redwolf501.top/Article/details/gt2iprkxqjh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjaprqew.html

C#:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gt2ajyvqlng.html

[B08] do-while（至少执行一次）
来源：http://dali.fzhhl.top/Article/details/gt2mwfkncvw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nwbrower.top/Article/details/gt2qlixygjw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cucudq.cn/Article/details/gt2vufmswiv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gt2mbxbmcdl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwuycaxm.html

Java: do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gt2hxsicefp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ijnzssdt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhengqikj.top/Article/details/gt2ixceqxsp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dzdvbnun.html

[B09] break 与 continue
来源：http://dali.gzhubu.top/Article/details/gt2sxithmzk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258.top/Article/details/gt2qrlcypnx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2epumngrc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gt2sjlbohfh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhpmaubh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gt2qvxtqkhe.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.haohaochexian.top/Article/details/gt2jhfiuiae.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gt2ihimyfoj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gt2uvwnzljy.html

[B10] 遍历同时拿索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mqqrpfkn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yj20258.top/Article/details/gt2hkmiiuav.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yuanzhike.top/Article/details/gt2swllzipo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpjkbsdk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hfpthk.cn/Article/details/gt2wycefbzf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jianghu66.top/Article/details/gt2lleerjtu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tian-w.cn/Article/details/gt2lsvmxjcu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.c1oappe.top/Article/details/gt2zjvnwprl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.iojbl.cn/Article/details/gt2tertrdva.html

[B11] 生成数字序列 / 区间
来源：http://dali.daxiang520.top/Article/details/gt2lhpblmhh.html

Py:   list(range(0, 10, 2))
来源：http://dali.tian-w.cn/Article/details/gt2xvxvxhiw.html

PHP:  range(0, 10, 2);
来源：http://dali.xylfe.cn/Article/details/gt2jlerowsk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcchfzga.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gt2ouuptnqd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hfpthk.cn/Article/details/gt2enzkgguk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guannengcc.top/Article/details/gt2bacxrhgn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dashuyun.cn/Article/details/gt2gggchqxl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2kbwiuwki.html

[B12] 跳出多层循环
来源：http://dali.pycfn.com/Article/details/gt2rphxfuqr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ehwqpu.com/Article/details/gt2whrsrixo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigufen.top/Article/details/gt2vleixvqs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gt2kxhtesrz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gt2duyijwob.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gt2fqxoctga.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cheryme.top/Article/details/gt2tqneriux.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pycfn.com/Article/details/gt2wlxhylgb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xziqi.cn/Article/details/gt2nufhphbf.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2faxawtrp.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinqigufen.top/Article/details/gt2bfvtqpck.html

PHP:  is_numeric($x)
来源：http://dali.jlsjyb.cn/Article/details/gt2ffaiqxzd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuanzx.com/Article/details/gt2sgotbtui.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gt2csszpuux.html

Java: x instanceof Number
来源：http://dali.birdmap.top/Article/details/gt2shjhscuq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tian-w.cn/Article/details/gt2eqjqzhoq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guannengcc.top/Article/details/gt2yxcckijt.html

C#:   x is int or double or decimal
来源：http://dali.chenlongwang.top/Article/details/gt2ubehywxk.html

[B14] 判断值是否在集合内
来源：http://dali.gotoacloud.top/Article/details/gt2oiwdqgeb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jiagoushi.top/Article/details/gt2hdrezagp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgfzy.top/Article/details/gt2viiazabm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2bvpvyxqo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gt2fqtashjb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vtorfiae.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hfpthk.cn/Article/details/gt2nfcureou.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ivvv.top/Article/details/gt2pfynncwu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gt2qqvqrjii.html

[B15] 布尔运算与取反
来源：http://dali.tanke756.top/Article/details/gt2kxcpmhgv.html

Py:   a and b or not c
来源：http://dali.xinyue.icu/Article/details/gt2wfgepebk.html

PHP:  $a && $b || !$c
来源：http://dali.jlsjyb.cn/Article/details/gt2ljxwppun.html

JS:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2kcguyltz.html

TS:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2yzwkxioq.html

Java: a && b || !c
来源：http://dali.jianghu66.top/Article/details/gt2dxmzjzdw.html

Go:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2jjfcksbj.html

Ruby: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gt2jqmjxmdw.html

C#:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2iwbxqogp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenzaomai.com/Article/details/gt2kdgdalrr.html

Py:   if not data: return
来源：http://dali.havefunace.top/Article/details/gt2weivfbub.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258.top/Article/details/gt2jemxrdop.html

JS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pofcldzl.html

TS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gt2ztrpelue.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rtvhswnk.html

Go:   if data == nil { return }
来源：http://dali.redwolf501.top/Article/details/gt2xwcidnfd.html

Ruby: return if data.nil?
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbvvthtk.html

C#:   if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gt2ewmdsics.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2txoboihc.html

C. 函数与作用域
来源：http://dali.0kj1m.cn/Article/details/gt2udrhcjjx.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2wrusgzpl.html

[C01] 定义函数
来源：http://dali.tian-w.cn/Article/details/gt2imbrttwz.html

Py:   def add(a, b): return a + b
来源：http://dali.zhengqikj.top/Article/details/gt2jzotjotz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gt2vcoyrfqp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2upedxzfh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2hrkuizbu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2gspwjjcr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenzaomai.com/Article/details/gt2bnkqkucp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gotoacloud.top/Article/details/gt2rbcyfday.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2gzhxnpwh.html

[C02] 默认参数
来源：http://dali.svipenyu.cn/Article/details/gt2aauseglh.html

Py:   def greet(name="World"): return name
来源：http://dali.daria6918.cn/Article/details/gt2psabjmlj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xgpqwxdk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gt2ecbvzufs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gt2tzmbgrfj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxinkj.top/Article/details/gt2njracppu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2sbtwfbun.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenlongwang.top/Article/details/gt2mtmocwvo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xylfe.cn/Article/details/gt2sboczoto.html

[C03] 可变参数
来源：http://dali.jyoumei.cn/Article/details/gt2vnymfvob.html

Py:   def total(*args): return sum(args)
来源：http://dali.fzhhl.top/Article/details/gt2iefemawt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenlongwang.top/Article/details/gt2ykzvbezz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gt2nqlkljjm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gt2iztumpxh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.svipenyu.cn/Article/details/gt2hqfumdcw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.0kj1m.cn/Article/details/gt2mmpmtmtz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tanke756.top/Article/details/gt2mkvwnzcu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.316326.xyz/Article/details/gt2qtlorrqu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gt2wmcqhpjb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ivvv.top/Article/details/gt2ddqvgnss.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258.top/Article/details/gt2lypekgnp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2zkfeiita.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tidnqcjy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xziqi.cn/Article/details/gt2vqpkxurp.html

Go:   // 无：用配置结构体参数
来源：http://dali.bjfxy.top/Article/details/gt2erovrair.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gt2grpuxeaw.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2wknkhgyj.html

[C05] 返回多个值
来源：http://dali.redwolf501.top/Article/details/gt2vvhxkdys.html

Py:   return a, b
来源：http://dali.gzhubu.top/Article/details/gt2jdmqdvmo.html

PHP:  return [$a, $b];
来源：http://dali.hnqzz.top/Article/details/gt2exshbmvn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gt2qthitufs.html

TS:   return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gt2ysttcflb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258.top/Article/details/gt2rmwrcnxd.html

Go:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ieiulpvv.html

Ruby: return a, b
来源：http://dali.yj20258.top/Article/details/gt2kxpljfpn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.vqdsnc.cn/Article/details/gt2jvueinqm.html

[C06] 匿名函数 / lambda
来源：http://dali.yueranfly.top/Article/details/gt2qvzjyeax.html

Py:   square = lambda x: x * x
来源：http://dali.hfpthk.cn/Article/details/gt2ylynuqga.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xziqi.cn/Article/details/gt2nnfzhjtw.html

JS:   const square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gt2jpvavmpl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jyoumei.cn/Article/details/gt2aznhwzxi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.c1oappe.top/Article/details/gt2kdjnmyfc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shzxlz.cn/Article/details/gt2upbzskoh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhengqikj.top/Article/details/gt2wpkomgcy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gt2xzfwhlrx.html

[C07] 把函数作为参数传入
来源：http://dali.xinyue.icu/Article/details/gt2ijulasnr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj20258.top/Article/details/gt2gjtsicsi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xinyue.icu/Article/details/gt2qnelppjr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuxming.cn/Article/details/gt2iaseqnje.html

TS:   arr.map(String)
来源：http://dali.zhengqikj.top/Article/details/gt2qvotbpyg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zycfv.cn/Article/details/gt2nlywanip.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zycfv.cn/Article/details/gt2rzfcvvhp.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigufen.top/Article/details/gt2hvqaqusg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhoulong.xyz/Article/details/gt2ocpbgazp.html

[C08] 闭包
来源：http://dali.316326.xyz/Article/details/gt2rgzxapzo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guowangkeji.top/Article/details/gt2siqzizgm.html


<!-- 参考信息 -->