代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.dianchejie.cn/Article/details/gt2jkkynvkk.html

Py:   ord("A"); chr(65)
来源：http://dali.yvedp.cn/Article/details/gt2nisswamc.html

PHP:  ord("A"); chr(65)
来源：http://dali.hywenlv.cn/Article/details/gt2cgwspfue.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jyoumei.cn/Article/details/gt2ikpvdifu.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ppjwa.cn/Article/details/gt2dohbhseg.html

Java: (int) 'A'; (char) 65
来源：http://dali.hywenlv.cn/Article/details/gt2fxrnpplf.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhiwuduotai.top/Article/details/gt2vcphtpfs.html

Ruby: "A".ord; 65.chr
来源：http://dali.c1oappe.top/Article/details/gt2jiitmpoe.html

C#:   (int)'A'; (char)65
来源：http://dali.cucudq.cn/Article/details/gt2mazjkhad.html

[A19] 交换两个变量
来源：http://dali.yangfankeji.com/Article/details/gt2qdghqvrp.html

Py:   a, b = b, a
来源：http://dali.hnqzz.top/Article/details/gt2rivxmwhh.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hnqzz.top/Article/details/gt2mipnmhiy.html

JS:   [a, b] = [b, a];
来源：http://dali.andypj.xyz/Article/details/gt2rdfrsmhv.html

TS:   [a, b] = [b, a];
来源：http://dali.nanxinkj.top/Article/details/gt2foduucfo.html

Java: int t = a; a = b; b = t;
来源：http://dali.jiagoushi.top/Article/details/gt2emrjyuod.html

Go:   a, b = b, a
来源：http://dali.zhoulong.xyz/Article/details/gt2cabxhtoh.html

Ruby: a, b = b, a
来源：http://dali.ehwqpu.com/Article/details/gt2tmgdltcv.html

C#:   (a, b) = (b, a);
来源：http://dali.hysaishi.cn/Article/details/gt2gcbtmjjc.html

[A20] 读取标准输入
来源：http://dali.jiagoushi.top/Article/details/gt2pptjvcau.html

Py:   name = input("请输入：")
来源：http://dali.zhijiandao.cn/Article/details/gt2oroujfpo.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.redwolf501.top/Article/details/gt2prcbpkry.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yvedp.cn/Article/details/gt2reugdzdq.html

TS:   // Node.js：readline 模块
来源：http://dali.haohaochexian.top/Article/details/gt2iypxsmrb.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhiwuduotai.top/Article/details/gt2civkfwgk.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2spbggtjh.html

Ruby: gets.chomp
来源：http://dali.pengpengdd.cyou/Article/details/gt2wpwtfujj.html

C#:   Console.ReadLine();
来源：http://dali.bjfxy.top/Article/details/gt2lqhbyjqu.html

[A21] 保留指定小数位输出
来源：http://dali.yueranfly.top/Article/details/gt2vvbmvims.html

Py:   f"{3.14159:.2f}"
来源：http://dali.svipenyu.cn/Article/details/gt2yfmsahvu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gt2jcvewkbc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gt2tnzhstrf.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gt2zncbgyae.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zycfv.cn/Article/details/gt2etupbdwb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gt2gvtbwswp.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yelyngvl.html

C#:   3.14159.ToString("F2")
来源：http://dali.hysaishi.cn/Article/details/gt2uooxmcxd.html

[A22] 获取字符串长度
来源：http://dali.yj20258888.top/Article/details/gt2gxzsvhsz.html

Py:   len(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2fxwofxof.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yuxming.cn/Article/details/gt2zcasqiao.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.guannengcc.top/Article/details/gt2hxascgsj.html

TS:   s.length
来源：http://dali.nanxinkj.top/Article/details/gt2iycjzina.html

Java: s.length()
来源：http://dali.yj20258.top/Article/details/gt2pocpnrwu.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yuanzhike.top/Article/details/gt2csgaynmd.html

Ruby: s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bilrfeyc.html

C#:   s.Length
来源：http://dali.jlsjyb.cn/Article/details/gt2hlmmmkit.html

[A23] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gt2bcmojwis.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ydzc1.top/Article/details/gt2bjzerfhx.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kufwgefp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgufenzy.top/Article/details/gt2danxcnpy.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shuidangran.top/Article/details/gt2dmgphfju.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbartydd.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.chenlongwang.top/Article/details/gt2fvtpawij.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gt2ksokzhcc.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hammf.cn/Article/details/gt2lnoprorj.html

[A24] 去除首尾空白
来源：http://dali.yuanzhike.top/Article/details/gt2lyfngorn.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yj202588.top/Article/details/gt2npciawbv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.dianchejie.cn/Article/details/gt2iiwvbcxt.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhmlqdjz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2pewdfzui.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhoulong.xyz/Article/details/gt2ykotyuop.html

Go:   strings.TrimSpace(s)
来源：http://dali.guowangkeji.top/Article/details/gt2ephfiubq.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yueranfly.top/Article/details/gt2pisnlvpo.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jlsjyb.cn/Article/details/gt2xzvebcgt.html

[A25] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gt2zckhmfwc.html

Py:   s1 == s2; s1 != s2
来源：http://dali.nanxinkj.top/Article/details/gt2wgmklmvz.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cdnleiting.top/Article/details/gt2apsouras.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yongpay.top/Article/details/gt2prsprsdz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ppjwa.cn/Article/details/gt2qvfhjxbs.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ivvv.top/Article/details/gt2ymcetwvj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2knakwwvn.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gogol.net.cn/Article/details/gt2fadwveio.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.svipenyu.cn/Article/details/gt2icvwxgcu.html

[A26] 类型转换总览
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2equfyalu.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hongshengwenyu.top/Article/details/gt2eoxqyelz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sysykeji.top/Article/details/gt2jyuvxmvt.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hnxiangtu.top/Article/details/gt2goegvtns.html

TS:   Number() String() Boolean() x as number
来源：http://dali.9152youxi.cn/Article/details/gt2fcxybdum.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xpytinzx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljbtfczv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kaminmbw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bnctcqgh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2cpkdxrzu.html

B. 流程控制
来源：http://dali.jianghu66.top/Article/details/gt2gjvioqmo.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2kojyedoi.html

[B01] 条件判断 if / else
来源：http://dali.hywenlv.cn/Article/details/gt2vezbvlem.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yangfankeji.com/Article/details/gt2ionfyhjl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2qvixxuuw.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gt2okavparx.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gt2maulmmvn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gt2nsftbcsb.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jinqigufen.top/Article/details/gt2laqzeezv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.guowangkeji.top/Article/details/gt2qkvzzdhz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gt2wcttzauj.html

[B02] 多分支 else if / elif
来源：http://dali.zhoulong.xyz/Article/details/gt2upycswyp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ydzc1.top/Article/details/gt2bjkclrtq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hammf.cn/Article/details/gt2qkiasgvp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gt2jywtfpak.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwfyjrvu.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gt2pdvhyqst.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.c1oappe.top/Article/details/gt2pmiasydt.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.havefunace.top/Article/details/gt2psvalacq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zbdzxelc.html

[B03] switch / match / case
来源：http://dali.yj202588.top/Article/details/gt2neqzdrdu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hongshengwenyu.top/Article/details/gt2mkqxxqwk.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gt2tfdwnzlm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gt2vwhqfpoc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gt2luvqxmft.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gt2dcketyyt.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.smart0.xyz/Article/details/gt2lvavwkoa.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hnxiangtu.top/Article/details/gt2cngdnlmx.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.pengpengdd.cyou/Article/details/gt2lvumgyet.html

[B04] for 计数循环
来源：http://dali.nanxinkj.top/Article/details/gt2zlxzgvnz.html

Py:   for i in range(10): print(i)
来源：http://dali.dashuyun.cn/Article/details/gt2ommzpfts.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.haohaochexian.top/Article/details/gt2ckriatzg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pycfn.com/Article/details/gt2qgapfkvw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.0kj1m.cn/Article/details/gt2oewibkip.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtoxyzps.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhongyouzk.top/Article/details/gt2arbagdyb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.daria6918.cn/Article/details/gt2mgnkdlld.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.kuanghao11.cn/Article/details/gt2ubykjfau.html

[B05] 遍历数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gt2hgnzzqnn.html

Py:   for item in arr: print(item)
来源：http://dali.yj20258888.top/Article/details/gt2zhdjtush.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cqqwz.cn/Article/details/gt2spasncsq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ydzc1.top/Article/details/gt2elbchvas.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.dianchejie.cn/Article/details/gt2bbqrlcog.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hywenlv.cn/Article/details/gt2wofgnxhf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinqigfzy.top/Article/details/gt2evnnvmfj.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yonumen.top/Article/details/gt2ltxtkgpe.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.redwolf501.top/Article/details/gt2ggoaegsp.html

[B06] 遍历字典 / 对象
来源：http://dali.hammf.cn/Article/details/gt2zbrqaeds.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.pycfn.com/Article/details/gt2jobmpmgm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.haohaochexian.top/Article/details/gt2mrkbjtwn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangdashe.top/Article/details/gt2kpxnixff.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gt2oznrgbnh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.meibo888.top/Article/details/gt2liyisxkk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xylfe.cn/Article/details/gt2utryctfx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj20258.top/Article/details/gt2jwzomzpd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fzhhl.top/Article/details/gt2semtkzne.html

[B07] while 循环
来源：http://dali.guowangkeji.top/Article/details/gt2ujtquwxp.html

Py:   while i < 10: i += 1
来源：http://dali.yanxiufei.cn/Article/details/gt2avxxtbrk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cenkjpjo.html

JS:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lgctlskl.html

TS:   while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2njvnhbpe.html

Java: while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gt2fxiewggu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.smart0.xyz/Article/details/gt2veprpaum.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sufxvd.cn/Article/details/gt2ykejuhzk.html

C#:   while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gt2epsbtdom.html

[B08] do-while（至少执行一次）
来源：http://dali.snrcjt.cn/Article/details/gt2yisrdmzo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sweek.top/Article/details/gt2dulobfnt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zdqjudy.top/Article/details/gt2ppvpzyvu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gt2npvbdffj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gt2ahssxjuy.html

Java: do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gt2rkptfkfu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cashguo.top/Article/details/gt2iaqkmyrs.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jyoumei.cn/Article/details/gt2spxcccqe.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gt2lhetzrfq.html

[B09] break 与 continue
来源：http://dali.chenlongwang.top/Article/details/gt2vziuczdr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yuanzhike.top/Article/details/gt2qtpphtcv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gt2lxscptxg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qasizjfg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gt2nlpbgrpb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gt2ezenrvzd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hammf.cn/Article/details/gt2sjgyyibz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.0kj1m.cn/Article/details/gt2mwbdxclh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gt2qwwhqzru.html

[B10] 遍历同时拿索引
来源：http://dali.gotoacloud.top/Article/details/gt2kmwrkpvg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.daxiang520.top/Article/details/gt2qwrkzgfq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2twlrtejt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cashguo.top/Article/details/gt2oazvzxxu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nanxuanxn.top/Article/details/gt2cyzbpubb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenzaomai.com/Article/details/gt2khnrhsbe.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.andypj.xyz/Article/details/gt2vyhykfiv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hywenlv.cn/Article/details/gt2yshglumh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gotoacloud.top/Article/details/gt2fsbycnwe.html

[B11] 生成数字序列 / 区间
来源：http://dali.birdmap.top/Article/details/gt2gmrgflwe.html

Py:   list(range(0, 10, 2))
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjbfkyii.html

PHP:  range(0, 10, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hnqocyoy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gt2rcouvjkp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gt2omednqav.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuxming.cn/Article/details/gt2aetpxhwq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xziqi.cn/Article/details/gt2grlgcchi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hnqzz.top/Article/details/gt2lezykoyp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yongpay.top/Article/details/gt2eonixtzx.html

[B12] 跳出多层循环
来源：http://dali.vqdsnc.cn/Article/details/gt2qdlztrhm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jiagoushi.top/Article/details/gt2ihihlejp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.kuanghao11.cn/Article/details/gt2xeskubfs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gt2lnwxtinr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gt2bjbvrrfs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gt2glnyeioo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2godslxup.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ehwqpu.com/Article/details/gt2wfnbnmdw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.9152youxi.cn/Article/details/gt2rvojmgxr.html

[B13] 判断是否为数字
来源：http://dali.hysaishi.cn/Article/details/gt2oochbjde.html

Py:   isinstance(x, (int, float))
来源：http://dali.gaohongyu789.top/Article/details/gt2vbrbztvd.html

PHP:  is_numeric($x)
来源：http://dali.xylfe.cn/Article/details/gt2titknuqp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gt2adwtmrdc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gt2szjabjml.html

Java: x instanceof Number
来源：http://dali.yvedp.cn/Article/details/gt2njfarhdz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sufxvd.cn/Article/details/gt2lpmjyagv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.0kj1m.cn/Article/details/gt2ajqlurlw.html

C#:   x is int or double or decimal
来源：http://dali.chenlongwang.top/Article/details/gt2byygtumh.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ctafsndr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnqzz.top/Article/details/gt2fyvbdnnb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gogol.net.cn/Article/details/gt2glntotbi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2avakhkcv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gt2nfpcltwf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gzhubu.top/Article/details/gt2uzisgcfe.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cashguo.top/Article/details/gt2agoesvvz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2iaefpjrr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2aeeulxlf.html

[B15] 布尔运算与取反
来源：http://dali.pengpengdd.cyou/Article/details/gt2veeyfujr.html

Py:   a and b or not c
来源：http://dali.yj202588.top/Article/details/gt2rmpctuvq.html

PHP:  $a && $b || !$c
来源：http://dali.daxiang520.top/Article/details/gt2nsvcctey.html

JS:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2tocyvbrt.html

TS:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2wasvzfmz.html

Java: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2mgrfbojz.html

Go:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2bucjxgxq.html

Ruby: a && b || !c
来源：http://dali.ivvv.top/Article/details/gt2krpebavy.html

C#:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2accrgueb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.snrcjt.cn/Article/details/gt2tjwzreab.html

Py:   if not data: return
来源：http://dali.nwbrower.top/Article/details/gt2xjkwxrrd.html

PHP:  if (!$data) { return; }
来源：http://dali.hnqzz.top/Article/details/gt2mzzemjmw.html

JS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gt2kwpqrsib.html

TS:   if (!data) return;
来源：http://dali.andypj.xyz/Article/details/gt2xfpvdckw.html

Java: if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gt2vkjjjrsp.html

Go:   if data == nil { return }
来源：http://dali.zdqjudy.top/Article/details/gt2bbfalhzq.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iutpxqof.html

C#:   if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gt2rmnrwgvi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2vpoccnnj.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlggvll.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ikgjnzyr.html

[C01] 定义函数
来源：http://dali.jianghu66.top/Article/details/gt2pzjzxmzh.html

Py:   def add(a, b): return a + b
来源：http://dali.chenzaomai.com/Article/details/gt2toqheshh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gt2rxfcwqnj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zsqmhsum.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2zldiijfm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2kpyoqeej.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfnullcd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangdashe.top/Article/details/gt2lpbynbra.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ssmomejd.html

[C02] 默认参数
来源：http://dali.hywenlv.cn/Article/details/gt2vmvrdkyb.html

Py:   def greet(name="World"): return name
来源：http://dali.chenjidiqi.icu/Article/details/gt2pqzlkrfl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cheryme.top/Article/details/gt2cximdwwp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wilzxomu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2buouhgvr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2leugjlvd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2msljeife.html

Ruby: def greet(name = "World") = name
来源：http://dali.tanke756.top/Article/details/gt2bectxtys.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nanxuanxn.top/Article/details/gt2tysfndhf.html

[C03] 可变参数
来源：http://dali.gzhubu.top/Article/details/gt2vrsgscqz.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258888.top/Article/details/gt2jvoiqcwd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zycfv.cn/Article/details/gt2nxyenccq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gt2dutipchv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gt2fwlgzpzl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ydzc1.top/Article/details/gt2juojnfsv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenlongwang.top/Article/details/gt2aueyzylr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nxeaiogt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhiwuduotai.top/Article/details/gt2nlauedac.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2mukyqgfs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.316326.xyz/Article/details/gt2gfusdkow.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ehipkdyf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2vtnbzbmy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daxiang520.top/Article/details/gt2dkgmqxvq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jiagoushi.top/Article/details/gt2dowajjmu.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangdashe.top/Article/details/gt2qnayjbss.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpgnfcim.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntxypzod.html

[C05] 返回多个值
来源：http://dali.zhixingplan.top/Article/details/gt2voykevqj.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gt2hpyqorzf.html

PHP:  return [$a, $b];
来源：http://dali.316326.xyz/Article/details/gt2culrtqxn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfqafzg.html

TS:   return { a, b };
来源：http://dali.havefunace.top/Article/details/gt2clojfjwy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cheryme.top/Article/details/gt2onknoreh.html

Go:   return a, b
来源：http://dali.nwbrower.top/Article/details/gt2roqnpudf.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gt2ufhdlneg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhongyouzk.top/Article/details/gt2iuaohqmr.html

[C06] 匿名函数 / lambda
来源：http://dali.cheryme.top/Article/details/gt2qvxfawfh.html

Py:   square = lambda x: x * x
来源：http://dali.zdqjudy.top/Article/details/gt2tbiuqjqm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnxiangtu.top/Article/details/gt2egfbmsxn.html

JS:   const square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gt2evjhnmjx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dianchejie.cn/Article/details/gt2pxlqxvnb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cheryme.top/Article/details/gt2pjfogjue.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhoulong.xyz/Article/details/gt2guzarqtc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.9152youxi.cn/Article/details/gt2hhgqjngj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gt2mzttkncf.html

[C07] 把函数作为参数传入
来源：http://dali.gogol.net.cn/Article/details/gt2fvsdkvmk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj202588.top/Article/details/gt2uzoxxxuf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yuanzhike.top/Article/details/gt2xipuseny.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nfzznvap.html

TS:   arr.map(String)
来源：http://dali.iojbl.cn/Article/details/gt2hiqivnom.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sweek.top/Article/details/gt2trnzgbcq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.redwolf501.top/Article/details/gt2pxbwrfck.html

Ruby: arr.map(&:upcase)
来源：http://dali.xziqi.cn/Article/details/gt2zggotllv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aibaodan.cn/Article/details/gt2odmpodxq.html

[C08] 闭包
来源：http://dali.jianghu66.top/Article/details/gt2xvdqbdnw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.haohaochexian.top/Article/details/gt2vtoqspyj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgfzy.top/Article/details/gt2zrtzdjrf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gt2vdkdqzfu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2taxhxrox.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ivvv.top/Article/details/gt2qumlofyw.html


<!-- 参考信息 -->