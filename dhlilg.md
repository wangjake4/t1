代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tanke756.top/Article/details/gt2hyoaxqhf.html

Java: (int) 'A'; (char) 65
来源：http://dali.ivvv.top/Article/details/gt2vtsbiizq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.cdnleiting.top/Article/details/gt2gsmzexyn.html

Ruby: "A".ord; 65.chr
来源：http://dali.meibo888.top/Article/details/gt2ymmcszth.html

C#:   (int)'A'; (char)65
来源：http://dali.meibo888.top/Article/details/gt2kchrwxid.html

[A19] 交换两个变量
来源：http://dali.vqdsnc.cn/Article/details/gt2yporxtzu.html

Py:   a, b = b, a
来源：http://dali.zycfv.cn/Article/details/gt2wanzzftv.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jiagoushi.top/Article/details/gt2qgcmnksh.html

JS:   [a, b] = [b, a];
来源：http://dali.cdnleiting.top/Article/details/gt2udpzkcyr.html

TS:   [a, b] = [b, a];
来源：http://dali.wangdashe.top/Article/details/gt2chyhwgcw.html

Java: int t = a; a = b; b = t;
来源：http://dali.bjfxy.top/Article/details/gt2gdhzuglv.html

Go:   a, b = b, a
来源：http://dali.jiagoushi.top/Article/details/gt2oruetdww.html

Ruby: a, b = b, a
来源：http://dali.sxryk.cn/Article/details/gt2nehggvvy.html

C#:   (a, b) = (b, a);
来源：http://dali.jqgufenzy.top/Article/details/gt2bllxfioz.html

[A20] 读取标准输入
来源：http://dali.ppjwa.cn/Article/details/gt2kzhdaxjh.html

Py:   name = input("请输入：")
来源：http://dali.sweek.top/Article/details/gt2upapehqa.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ivvv.top/Article/details/gt2iikoaqaw.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.wangdashe.top/Article/details/gt2csitelxy.html

TS:   // Node.js：readline 模块
来源：http://dali.fengsongda.top/Article/details/gt2qfpsitzm.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yueranfly.top/Article/details/gt2hxqabfpv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hslcvcys.html

Ruby: gets.chomp
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqeurhac.html

C#:   Console.ReadLine();
来源：http://dali.yvedp.cn/Article/details/gt2ulqlwrxk.html

[A21] 保留指定小数位输出
来源：http://dali.sxryk.cn/Article/details/gt2gifuzlze.html

Py:   f"{3.14159:.2f}"
来源：http://dali.sxryk.cn/Article/details/gt2knjrhcbq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ougjfhns.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gt2ijfiutry.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ybcxt.top/Article/details/gt2jhtmttyb.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qataihfc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.sxryk.cn/Article/details/gt2ykadpieo.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cheryme.top/Article/details/gt2jplylbij.html

C#:   3.14159.ToString("F2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qcenzfgi.html

[A22] 获取字符串长度
来源：http://dali.chenzaomai.com/Article/details/gt2juydgydt.html

Py:   len(s)
来源：http://dali.ivvv.top/Article/details/gt2xspnmeug.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.pycfn.com/Article/details/gt2btynbreg.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jyoumei.cn/Article/details/gt2dpkysdxx.html

TS:   s.length
来源：http://dali.0kj1m.cn/Article/details/gt2qfmogfqq.html

Java: s.length()
来源：http://dali.xuanzx.com/Article/details/gt2fcveinpc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.mhx1999.top/Article/details/gt2bxcomycu.html

Ruby: s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sumekbao.html

C#:   s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gt2byachgar.html

[A23] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gt2mqtganlh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gpqegkeb.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.316326.xyz/Article/details/gt2rjucmfvk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgfzy.top/Article/details/gt2lxiclzdq.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.mhx1999.top/Article/details/gt2kowgjvpa.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gt2njiewrst.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hysaishi.cn/Article/details/gt2pnvlfsko.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.redwolf501.top/Article/details/gt2gzejkcaf.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.gogol.net.cn/Article/details/gt2ltzejgyi.html

[A24] 去除首尾空白
来源：http://dali.jlsjyb.cn/Article/details/gt2ahsfxlqe.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xuanzx.com/Article/details/gt2rxmcucdp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.daxiang520.top/Article/details/gt2cktkfwhp.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.andypj.xyz/Article/details/gt2gngsjwhk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ivvv.top/Article/details/gt2jalmalks.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.chenlongwang.top/Article/details/gt2nqzcpmdo.html

Go:   strings.TrimSpace(s)
来源：http://dali.havefunace.top/Article/details/gt2akalvokf.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.gogol.net.cn/Article/details/gt2qymqwrwe.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.mhx1999.top/Article/details/gt2wpjyjbko.html

[A25] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gt2popgzids.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zdqjudy.top/Article/details/gt2hbxlelvx.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.aizwys.cn/Article/details/gt2lqoaqjon.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ivvv.top/Article/details/gt2rtvbblnk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2csqihupq.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtpalxov.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.fzhhl.top/Article/details/gt2ekeqgumf.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yj202588.top/Article/details/gt2ldjzwpfm.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jqgfzy.top/Article/details/gt2olbvtgnf.html

[A26] 类型转换总览
来源：http://dali.smart0.xyz/Article/details/gt2aupzrvpy.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangshuangyany.cn/Article/details/gt2mcxcobzr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cucudq.cn/Article/details/gt2vkxryhvj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cashguo.top/Article/details/gt2tossekuj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gzhubu.top/Article/details/gt2izfxrslq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.kuanghao11.cn/Article/details/gt2drmaliud.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jlsjyb.cn/Article/details/gt2wuejpflg.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hysaishi.cn/Article/details/gt2qzkvgeic.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.daxiang520.top/Article/details/gt2uncemfmu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2oddxcuhe.html

B. 流程控制
来源：http://dali.smart0.xyz/Article/details/gt2gmwysvyy.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2adclkbrb.html

[B01] 条件判断 if / else
来源：http://dali.cashguo.top/Article/details/gt2dawfqpdw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nwbrower.top/Article/details/gt2obbgdwtc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2struzbeb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gt2yhhnofxy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajrrwfpy.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gt2fqyxapop.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.9152youxi.cn/Article/details/gt2twgygebm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yongpay.top/Article/details/gt2aghgtxdm.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gt2vjrgfigt.html

[B02] 多分支 else if / elif
来源：http://dali.meibo888.top/Article/details/gt2vmouoait.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.havefunace.top/Article/details/gt2amevhoiz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hysaishi.cn/Article/details/gt2nscfkimw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gt2oiqtlazc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gt2bxmjtqtw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gt2ccpnqnrm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shzxlz.cn/Article/details/gt2pvervblz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gotoacloud.top/Article/details/gt2zilrjylg.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gt2jmmjgcwg.html

[B03] switch / match / case
来源：http://dali.cdnleiting.top/Article/details/gt2wgbqfdyd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yueranfly.top/Article/details/gt2jwpowqcm.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gt2xajffyst.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gt2yxmlmsuq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gt2usrmxonf.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gt2iddysnxq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yangfankeji.com/Article/details/gt2kugxmgey.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sweek.top/Article/details/gt2stmfsmnm.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jyoumei.cn/Article/details/gt2qzhnzzov.html

[B04] for 计数循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfmoxhud.html

Py:   for i in range(10): print(i)
来源：http://dali.c1oappe.top/Article/details/gt2zmavnals.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfcxlchw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cucudq.cn/Article/details/gt2vxjipfto.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yanxiufei.cn/Article/details/gt2vfpsjarl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gaohongyu789.top/Article/details/gt2pbpbmdok.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yuxming.cn/Article/details/gt2ozyqchhz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.snrcjt.cn/Article/details/gt2slgfreem.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhengqikj.top/Article/details/gt2xgqqvwwf.html

[B05] 遍历数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gt2dixzfsmx.html

Py:   for item in arr: print(item)
来源：http://dali.ydzc1.top/Article/details/gt2qiymxcxb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.0kj1m.cn/Article/details/gt2jwuhknik.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.fzhhl.top/Article/details/gt2xzblbtfn.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xylfe.cn/Article/details/gt2jswotrrs.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhoulong.xyz/Article/details/gt2qkrjsgwy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.dashuyun.cn/Article/details/gt2wutdvmts.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cucudq.cn/Article/details/gt2cryopnvw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daria6918.cn/Article/details/gt2gzswwhnb.html

[B06] 遍历字典 / 对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2etlmsrdm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yvedp.cn/Article/details/gt2cpgknbzd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.redwolf501.top/Article/details/gt2esqoqnsf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dianchejie.cn/Article/details/gt2oaddqomz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sxryk.cn/Article/details/gt2vobpvgtl.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xinyue.icu/Article/details/gt2qzdxcxgm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgvfzlfk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xinyue.icu/Article/details/gt2jzvpptwq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cqjpoosd.html

[B07] while 循环
来源：http://dali.ybcxt.top/Article/details/gt2gntzucgy.html

Py:   while i < 10: i += 1
来源：http://dali.shuidangran.top/Article/details/gt2okygeccs.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cashguo.top/Article/details/gt2hnitoudx.html

JS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gt2qvrczovt.html

TS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gt2dcgypsqe.html

Java: while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gt2xeqnbfhu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ybcxt.top/Article/details/gt2vytvyuak.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuanzhike.top/Article/details/gt2qbrfsuih.html

C#:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gt2ubxwspuh.html

[B08] do-while（至少执行一次）
来源：http://dali.jinqigufen.top/Article/details/gt2rcdfjsle.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.dianchejie.cn/Article/details/gt2unmcdtnn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gqdowyxv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gt2wquiobza.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gt2ucnurdhv.html

Java: do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gt2jqlrrxjo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2negocoqu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.pycfn.com/Article/details/gt2hajkknpu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gt2runyknkh.html

[B09] break 与 continue
来源：http://dali.yuanzhike.top/Article/details/gt2vtbubqgj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.daria6918.cn/Article/details/gt2yhafdhna.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gt2pivdwtra.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gt2jcngbazu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2unafxjxr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2xyndxihq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.c1oappe.top/Article/details/gt2bodwhqmd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jwjoeshu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gt2wekatqth.html

[B10] 遍历同时拿索引
来源：http://dali.tanke756.top/Article/details/gt2ltrggvdx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.aibaodan.cn/Article/details/gt2tpxoevem.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gzhubu.top/Article/details/gt2xepxcvod.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hammf.cn/Article/details/gt2xxdjflkl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.birdmap.top/Article/details/gt2bdfewfia.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.316326.xyz/Article/details/gt2nwzyghqd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xtqnmste.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ttcqqpvf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2irfbrxun.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhftwtxa.html

Py:   list(range(0, 10, 2))
来源：http://dali.aibaodan.cn/Article/details/gt2jlylieqg.html

PHP:  range(0, 10, 2);
来源：http://dali.tian-w.cn/Article/details/gt2taokxosx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2daykgybz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gt2zlhrdyvl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gotoacloud.top/Article/details/gt2veiwoyyl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.aibaodan.cn/Article/details/gt2bmveqyow.html

Ruby: (0...10).step(2).to_a
来源：http://dali.andypj.xyz/Article/details/gt2xezdkqqy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xylfe.cn/Article/details/gt2bfdnnqwj.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yooropop.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yuanzhike.top/Article/details/gt2zhbfwyoa.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jyoumei.cn/Article/details/gt2otpppkqc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gt2wokgvizt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gt2corgabfs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gt2wlhlvffi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cucudq.cn/Article/details/gt2nrvdmosl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.svipenyu.cn/Article/details/gt2tclqzgba.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.aizwys.cn/Article/details/gt2zugrxmxw.html

[B13] 判断是否为数字
来源：http://dali.zdqjudy.top/Article/details/gt2srclfmvi.html

Py:   isinstance(x, (int, float))
来源：http://dali.hfpthk.cn/Article/details/gt2nidguioj.html

PHP:  is_numeric($x)
来源：http://dali.ehwqpu.com/Article/details/gt2txonjrij.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xylfe.cn/Article/details/gt2nqnifdvu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gt2ktassgqc.html

Java: x instanceof Number
来源：http://dali.pycfn.com/Article/details/gt2ttbehcxd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xylfe.cn/Article/details/gt2irtentdn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuanzx.com/Article/details/gt2xgkcbbuc.html

C#:   x is int or double or decimal
来源：http://dali.xinyue.icu/Article/details/gt2kcttlrdp.html

[B14] 判断值是否在集合内
来源：http://dali.gotoacloud.top/Article/details/gt2ezkoyohg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.feifeiyinyue.top/Article/details/gt2vkpmirkx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgfzy.top/Article/details/gt2vhnfsyjj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2wouprigi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hysaishi.cn/Article/details/gt2kotptols.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2ojajwinv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yuxming.cn/Article/details/gt2ollwpryq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2noougkfw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2feksuqxs.html

[B15] 布尔运算与取反
来源：http://dali.bjfxy.top/Article/details/gt2sjmlbtvn.html

Py:   a and b or not c
来源：http://dali.dashuyun.cn/Article/details/gt2xdzrcltn.html

PHP:  $a && $b || !$c
来源：http://dali.hammf.cn/Article/details/gt2rlriqosj.html

JS:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gt2jbxfjjxy.html

TS:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gt2njwxibcj.html

Java: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2tfkgxpve.html

Go:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwwppowy.html

Ruby: a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2rpsmbaaa.html

C#:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gt2kqmdkbab.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hywenlv.cn/Article/details/gt2avdpceai.html

Py:   if not data: return
来源：http://dali.sufxvd.cn/Article/details/gt2lklxgqcw.html

PHP:  if (!$data) { return; }
来源：http://dali.vqdsnc.cn/Article/details/gt2tptflpyj.html

JS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gt2staumbll.html

TS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gt2suqstpjl.html

Java: if (data == null) return;
来源：http://dali.nanxuanxn.top/Article/details/gt2exfoyyxt.html

Go:   if data == nil { return }
来源：http://dali.sweek.top/Article/details/gt2jvrsegvr.html

Ruby: return if data.nil?
来源：http://dali.tanke756.top/Article/details/gt2nhoizekl.html

C#:   if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vypgvdbz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2gpktbbxi.html

C. 函数与作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2xaysufya.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zjynlwrn.html

[C01] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gt2jgvicpba.html

Py:   def add(a, b): return a + b
来源：http://dali.zhongyouzk.top/Article/details/gt2tbxhtdge.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2eagdjusi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2rvafgunj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2dmwohrtb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2jpjufeie.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnqzz.top/Article/details/gt2ufuvnzrn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fengsongda.top/Article/details/gt2lcjszjkw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2whskvpgy.html

[C02] 默认参数
来源：http://dali.daxiang520.top/Article/details/gt2xxypefdi.html

Py:   def greet(name="World"): return name
来源：http://dali.kuanghao11.cn/Article/details/gt2zmqpkeas.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nwbrower.top/Article/details/gt2atfxowyf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2lrssafek.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbcjtadd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hywenlv.cn/Article/details/gt2wfwyzglt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.meibo888.top/Article/details/gt2fbkcakry.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gt2uvtvrmof.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgufenzy.top/Article/details/gt2dhvyppeu.html

[C03] 可变参数
来源：http://dali.fengsongda.top/Article/details/gt2lzgtmmso.html

Py:   def total(*args): return sum(args)
来源：http://dali.haohaochexian.top/Article/details/gt2rzdoyifn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhongyouzk.top/Article/details/gt2zuazqioq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gt2qucfoxht.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guowangkeji.top/Article/details/gt2hkfeooac.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xylfe.cn/Article/details/gt2gwjnklgc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fzhhl.top/Article/details/gt2fcavcqoq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.andypj.xyz/Article/details/gt2rdnpretz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daria6918.cn/Article/details/gt2tejonzav.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tanke756.top/Article/details/gt2gmolbrhr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sweek.top/Article/details/gt2edzqvjkm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgfzy.top/Article/details/gt2ovulguot.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gt2qmdynhht.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gzhubu.top/Article/details/gt2qfwvmerq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nrhdfvaq.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuanzx.com/Article/details/gt2vyxcvcjy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gt2uvxxarjz.html

C#:   f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gt2vjwkhotm.html

[C05] 返回多个值
来源：http://dali.jqgfzy.top/Article/details/gt2zmeqmbom.html

Py:   return a, b
来源：http://dali.hnxiangtu.top/Article/details/gt2dtexulbk.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2igqdrair.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gt2vfxusxxw.html

TS:   return { a, b };
来源：http://dali.hnxiangtu.top/Article/details/gt2rfshxtmk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dianchejie.cn/Article/details/gt2biedznwr.html

Go:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gt2knpjwftn.html

Ruby: return a, b
来源：http://dali.nwbrower.top/Article/details/gt2yknupqgm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gldhntft.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjfmzvkc.html

Py:   square = lambda x: x * x
来源：http://dali.ehwqpu.com/Article/details/gt2fikdoero.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.smart0.xyz/Article/details/gt2rzfmtgbf.html

JS:   const square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gt2jfeqodax.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigufen.top/Article/details/gt2ajlhsdhu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2nvldfqxn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.meibo888.top/Article/details/gt2fwwrnrkr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cqqwz.cn/Article/details/gt2xulkfcdt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gt2pebnqsff.html

[C07] 把函数作为参数传入
来源：http://dali.havefunace.top/Article/details/gt2hdoaxxfm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cashguo.top/Article/details/gt2wbvllrjw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2dygijnco.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hfpthk.cn/Article/details/gt2jmbanuap.html

TS:   arr.map(String)
来源：http://dali.vqdsnc.cn/Article/details/gt2twfmaaii.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.birdmap.top/Article/details/gt2ijliajgd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuxming.cn/Article/details/gt2xkjemgrw.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhixingplan.top/Article/details/gt2bmordpse.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fzhhl.top/Article/details/gt2hjaxzofd.html

[C08] 闭包
来源：http://dali.daria6918.cn/Article/details/gt2wsiptjso.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jiagoushi.top/Article/details/gt2eeueygrh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ydzc1.top/Article/details/gt2utxrmxns.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gt2gzhlkrqp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gt2knbdgnxk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daxiang520.top/Article/details/gt2kinivraz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shzxlz.cn/Article/details/gt2krszhnrq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zycfv.cn/Article/details/gt2cvphrvih.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gt2aklyghln.html

[C09] 递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2oslzzlld.html


<!-- 参考信息 -->