代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.redwolf501.top/Article/details/gt2znqjjhym.html

Py:   ord("A"); chr(65)
来源：http://dali.shzxlz.cn/Article/details/gt2cjqfflrx.html

PHP:  ord("A"); chr(65)
来源：http://dali.smart0.xyz/Article/details/gt2klzoisfa.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhengqikj.top/Article/details/gt2bnivbbbg.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fiinngdy.html

Java: (int) 'A'; (char) 65
来源：http://dali.xuetiantiany.cn/Article/details/gt2orjwwvpy.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.fengsongda.top/Article/details/gt2coznbgfg.html

Ruby: "A".ord; 65.chr
来源：http://dali.vqdsnc.cn/Article/details/gt2qqnvcchd.html

C#:   (int)'A'; (char)65
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lldwqzpe.html

[A19] 交换两个变量
来源：http://dali.cheryme.top/Article/details/gt2ovvsoqro.html

Py:   a, b = b, a
来源：http://dali.hnxiangtu.top/Article/details/gt2slieflqg.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sweek.top/Article/details/gt2rajzdezo.html

JS:   [a, b] = [b, a];
来源：http://dali.sufxvd.cn/Article/details/gt2pbzenhrg.html

TS:   [a, b] = [b, a];
来源：http://dali.gotoacloud.top/Article/details/gt2bjgspekd.html

Java: int t = a; a = b; b = t;
来源：http://dali.yanxiufei.cn/Article/details/gt2ymbaxcaj.html

Go:   a, b = b, a
来源：http://dali.wangdashe.top/Article/details/gt2vfitwzzf.html

Ruby: a, b = b, a
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tlufsmho.html

C#:   (a, b) = (b, a);
来源：http://dali.yj20258.top/Article/details/gt2hnwvaqqt.html

[A20] 读取标准输入
来源：http://dali.tianlin.xyz/Article/details/gt2nudgjuzw.html

Py:   name = input("请输入：")
来源：http://dali.wangdashe.top/Article/details/gt2uuoyrkgq.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.chenlongwang.top/Article/details/gt2cagroxyz.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinqigfzy.top/Article/details/gt2nudlptqi.html

TS:   // Node.js：readline 模块
来源：http://dali.tanke756.top/Article/details/gt2qozpdbli.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.daria6918.cn/Article/details/gt2louexadc.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.316326.xyz/Article/details/gt2obrhzyly.html

Ruby: gets.chomp
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yyfvjbda.html

C#:   Console.ReadLine();
来源：http://dali.mhx1999.top/Article/details/gt2drrsgslw.html

[A21] 保留指定小数位输出
来源：http://dali.gogol.net.cn/Article/details/gt2bfpejalx.html

Py:   f"{3.14159:.2f}"
来源：http://dali.0kj1m.cn/Article/details/gt2ivodtydo.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.chenzaomai.com/Article/details/gt2moqcnopv.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gt2bpxyrmmu.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gt2idrgwejq.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.mhx1999.top/Article/details/gt2psxjnoqm.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gt2vrkfsmtw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.haohaochexian.top/Article/details/gt2pmiyvepl.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyylwir.html

[A22] 获取字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gt2ijzwcyba.html

Py:   len(s)
来源：http://dali.mhx1999.top/Article/details/gt2mczfcicq.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhiwuduotai.top/Article/details/gt2qpowqchs.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yanxiufei.cn/Article/details/gt2vvpfkwfy.html

TS:   s.length
来源：http://dali.vqdsnc.cn/Article/details/gt2yrlhvluo.html

Java: s.length()
来源：http://dali.aizwys.cn/Article/details/gt2jppfisad.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xuanzx.com/Article/details/gt2mqexhsvk.html

Ruby: s.length
来源：http://dali.sysykeji.top/Article/details/gt2jdypkggs.html

C#:   s.Length
来源：http://dali.9152youxi.cn/Article/details/gt2egvuarps.html

[A23] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gt2kbzxemzn.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.meibo888.top/Article/details/gt2xaaaoddl.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.sysykeji.top/Article/details/gt2curctzzh.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yvedp.cn/Article/details/gt2nnmyqaid.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ppjwa.cn/Article/details/gt2gqreecrx.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.quarkkingdee.top/Article/details/gt2syrrgqok.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yonumen.top/Article/details/gt2hjefwqjy.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.redwolf501.top/Article/details/gt2cuhiaruv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yj202588.top/Article/details/gt2qzcgsqmq.html

[A24] 去除首尾空白
来源：http://dali.ppjwa.cn/Article/details/gt2iftbnxtt.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yonumen.top/Article/details/gt2dpwiposz.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.mhx1999.top/Article/details/gt2ibilebbv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj20258888.top/Article/details/gt2xzdwjmia.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhixingplan.top/Article/details/gt2bvrcchzn.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhengqikj.top/Article/details/gt2jntzzlas.html

Go:   strings.TrimSpace(s)
来源：http://dali.tianlin.xyz/Article/details/gt2xbfhgabt.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpkysnn.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.chenzaomai.com/Article/details/gt2swuflpeb.html

[A25] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gt2hvkebiwb.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ppjwa.cn/Article/details/gt2fergadfm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hfpthk.cn/Article/details/gt2cvdeciah.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gzhubu.top/Article/details/gt2pvwtultj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2oklkjwgv.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hnxiangtu.top/Article/details/gt2mmomktck.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xkaatoum.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xylfe.cn/Article/details/gt2cqeiatji.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.bjfxy.top/Article/details/gt2ewrwlarx.html

[A26] 类型转换总览
来源：http://dali.shzxlz.cn/Article/details/gt2wzpifcnr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.gotoacloud.top/Article/details/gt2ksllbzwq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.pycfn.com/Article/details/gt2lptdqcgd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hnxiangtu.top/Article/details/gt2acwlhkzw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yvedp.cn/Article/details/gt2nlnutmsh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jiagoushi.top/Article/details/gt2zapaphkz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ehwqpu.com/Article/details/gt2ahqqwshf.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.chenjidiqi.icu/Article/details/gt2swpidinc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yj20258.top/Article/details/gt2bqsqwizs.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2vrfmipng.html

B. 流程控制
来源：http://dali.quarkkingdee.top/Article/details/gt2ixzxdsly.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2qkngqjnf.html

[B01] 条件判断 if / else
来源：http://dali.zhengqikj.top/Article/details/gt2yxgkkgee.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2azdrbqig.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hfpthk.cn/Article/details/gt2vstghcgl.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2omouctne.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gt2qzzyoaoi.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gt2goloqvds.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jinqigfzy.top/Article/details/gt2ubxszhzh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jqgfzy.top/Article/details/gt2xvlczoqu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gt2tbdxkjxt.html

[B02] 多分支 else if / elif
来源：http://dali.daria6918.cn/Article/details/gt2vzqhhgpo.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yvedp.cn/Article/details/gt2ijdixhdr.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yuxming.cn/Article/details/gt2jctgqnny.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pengpengdd.cyou/Article/details/gt2jscogjeq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gt2jcymyzey.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gt2fttbegqh.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2occaoeai.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jianghu66.top/Article/details/gt2efkfvvko.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gt2facxzlei.html

[B03] switch / match / case
来源：http://dali.zhixingplan.top/Article/details/gt2meqqsayf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xinyue.icu/Article/details/gt2hyzhhtzz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gt2pgucrzbd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gt2xglgcets.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gt2atoifors.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gt2qbljptdg.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinqigfzy.top/Article/details/gt2wxiwhont.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cashguo.top/Article/details/gt2fwhtdfhh.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.fzhhl.top/Article/details/gt2pyxatrsr.html

[B04] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gt2qicavoxm.html

Py:   for i in range(10): print(i)
来源：http://dali.cdnleiting.top/Article/details/gt2mpvoezbu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.meibo888.top/Article/details/gt2scgzduqy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cucudq.cn/Article/details/gt2adyhdsaw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guannengcc.top/Article/details/gt2evbjgide.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhongyouzk.top/Article/details/gt2pfccsfek.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sufxvd.cn/Article/details/gt2kpzzkxot.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gotoacloud.top/Article/details/gt2eloxlbwo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uhyzawgo.html

[B05] 遍历数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gt2fgrzegez.html

Py:   for item in arr: print(item)
来源：http://dali.gaohongyu789.top/Article/details/gt2lgvdymcn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yueranfly.top/Article/details/gt2qbslexie.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhixingplan.top/Article/details/gt2juzreiqh.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xinyue.icu/Article/details/gt2kqvovdqo.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zdqjudy.top/Article/details/gt2tpkvxxwh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yuanzhike.top/Article/details/gt2mudvznub.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ivvv.top/Article/details/gt2dujjsefw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgfzy.top/Article/details/gt2vevcrmcr.html

[B06] 遍历字典 / 对象
来源：http://dali.xylfe.cn/Article/details/gt2mxszgoqk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinqigufen.top/Article/details/gt2hzomjeds.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2azxmmpbg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tian-w.cn/Article/details/gt2ngnocqkb.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gt2coxbwphn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhixingplan.top/Article/details/gt2gabcubun.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yonumen.top/Article/details/gt2gyreniyx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.svipenyu.cn/Article/details/gt2qrtgvsuk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.haohaochexian.top/Article/details/gt2vblwhejj.html

[B07] while 循环
来源：http://dali.snrcjt.cn/Article/details/gt2bibqoghs.html

Py:   while i < 10: i += 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2dbmijjpt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2oqzpclyp.html

JS:   while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gt2ipiidtxh.html

TS:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gt2rioskgug.html

Java: while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gt2hbieqlqp.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nanxuanxn.top/Article/details/gt2ciaisnsk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.svipenyu.cn/Article/details/gt2pqwrmlam.html

C#:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gt2rkbxyfmf.html

[B08] do-while（至少执行一次）
来源：http://dali.ivvv.top/Article/details/gt2wmtyldcq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.vqdsnc.cn/Article/details/gt2dcifrbdc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ssscjjub.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gt2pkmgrkcp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gt2vbdvhgjz.html

Java: do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gt2jvrclpuh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.aibaodan.cn/Article/details/gt2jdyyrwum.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iptstzva.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzbmgyie.html

[B09] break 与 continue
来源：http://dali.jqgfzy.top/Article/details/gt2eddjvslu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cdnleiting.top/Article/details/gt2auboqake.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gt2bmlpokqd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gt2fsekvccu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gt2ugegmpsh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gt2wptbgzxb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqpfxuba.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.wangdashe.top/Article/details/gt2ykvzqobk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gt2cxgkgzrr.html

[B10] 遍历同时拿索引
来源：http://dali.yueranfly.top/Article/details/gt2bzaiggyn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yvedp.cn/Article/details/gt2nwlmlbod.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.redwolf501.top/Article/details/gt2xfaaevsc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gt2vwtuzfzo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xuetiantiany.cn/Article/details/gt2cllqbqlw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yanxiufei.cn/Article/details/gt2dxescshh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnsbrfny.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hywenlv.cn/Article/details/gt2zoscajqk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2graqxcli.html

[B11] 生成数字序列 / 区间
来源：http://dali.jqgufenzy.top/Article/details/gt2pzloiivx.html

Py:   list(range(0, 10, 2))
来源：http://dali.redwolf501.top/Article/details/gt2ayruoiid.html

PHP:  range(0, 10, 2);
来源：http://dali.yueranfly.top/Article/details/gt2xgopxsqz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhengqikj.top/Article/details/gt2ccjxigwp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gt2qufcausp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.haohaochexian.top/Article/details/gt2voydyafl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jiagoushi.top/Article/details/gt2ciwkbqdt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtikuuhm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.wangdashe.top/Article/details/gt2ycknkdnv.html

[B12] 跳出多层循环
来源：http://dali.jinqigufen.top/Article/details/gt2wzzqocpg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2guklsrkh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hysaishi.cn/Article/details/gt2bkrixwqi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2vrhjmoux.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gt2jeajtujj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gt2sulkclfe.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tanke756.top/Article/details/gt2higszkhr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hongshengwenyu.top/Article/details/gt2aeppeioj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.havefunace.top/Article/details/gt2fsvpvhux.html

[B13] 判断是否为数字
来源：http://dali.nanxuanxn.top/Article/details/gt2vrfpapsz.html

Py:   isinstance(x, (int, float))
来源：http://dali.sxryk.cn/Article/details/gt2oixzvgff.html

PHP:  is_numeric($x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpfwamkj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2jasmbmra.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gt2spbcslif.html

Java: x instanceof Number
来源：http://dali.jianghu66.top/Article/details/gt2mvukavok.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuanzhike.top/Article/details/gt2pihhjrnp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.316326.xyz/Article/details/gt2eneihvtf.html

C#:   x is int or double or decimal
来源：http://dali.zhiwuduotai.top/Article/details/gt2ylsxnvfo.html

[B14] 判断值是否在集合内
来源：http://dali.zhiwuduotai.top/Article/details/gt2dthwnlfu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.quarkkingdee.top/Article/details/gt2rnvdwrrr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hywenlv.cn/Article/details/gt2fmknvfen.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2vrkmmmjc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2ipsrjjgc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkqlhppg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2zbdocogc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2dzscjcsr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2jcnaiziw.html

[B15] 布尔运算与取反
来源：http://dali.zhongyouzk.top/Article/details/gt2kvgsstuw.html

Py:   a and b or not c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbhkkhgl.html

PHP:  $a && $b || !$c
来源：http://dali.snrcjt.cn/Article/details/gt2nwdfvvhw.html

JS:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2mvwcfryf.html

TS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2gwsjqant.html

Java: a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2fstfmola.html

Go:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gt2datiabih.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2wrvixsul.html

C#:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2xjvexeod.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgfzy.top/Article/details/gt2zgfybqlg.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2ucydktlb.html

PHP:  if (!$data) { return; }
来源：http://dali.shzxlz.cn/Article/details/gt2rgkafjdc.html

JS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gt2avvgclbt.html

TS:   if (!data) return;
来源：http://dali.zhengqikj.top/Article/details/gt2ortnukdw.html

Java: if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gt2hjpknjep.html

Go:   if data == nil { return }
来源：http://dali.yuanzhike.top/Article/details/gt2etzailei.html

Ruby: return if data.nil?
来源：http://dali.jinqigfzy.top/Article/details/gt2qzdfjbuo.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2utkayhvr.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2rpzytgdg.html

C. 函数与作用域
来源：http://dali.shzxlz.cn/Article/details/gt2yjuxguxx.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2jwxkxlpi.html

[C01] 定义函数
来源：http://dali.sxryk.cn/Article/details/gt2kstikhye.html

Py:   def add(a, b): return a + b
来源：http://dali.zhixingplan.top/Article/details/gt2acrxpbcb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gt2hekeqvtn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gt2uswgneit.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2khwuzggh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2anuhpbsf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2lasgevrg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.c1oappe.top/Article/details/gt2gcozhnea.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2lobthyrm.html

[C02] 默认参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xzwiyipg.html

Py:   def greet(name="World"): return name
来源：http://dali.dashuyun.cn/Article/details/gt2bygsfxtc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.mhx1999.top/Article/details/gt2qtwijnpr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2phdmjiun.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2yhutpgzc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guowangkeji.top/Article/details/gt2jkpwkzdc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.0kj1m.cn/Article/details/gt2qtxkysno.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuetiantiany.cn/Article/details/gt2lhmcusmm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xinyue.icu/Article/details/gt2rlcxrccf.html

[C03] 可变参数
来源：http://dali.svipenyu.cn/Article/details/gt2upbbzckt.html

Py:   def total(*args): return sum(args)
来源：http://dali.iojbl.cn/Article/details/gt2ejehsozb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gt2dkexenab.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gt2fdrypcif.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rmcfoqhm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zdqjudy.top/Article/details/gt2cpyhibgv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhixingplan.top/Article/details/gt2zatqcaqz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jiagoushi.top/Article/details/gt2yqziwhvh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gzhubu.top/Article/details/gt2qrlubgiu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lreudlpl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fmcfjkpc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shuidangran.top/Article/details/gt2wuvzkieb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gt2bxxakctx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uxgqdeua.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tianlin.xyz/Article/details/gt2ucugemqy.html

Go:   // 无：用配置结构体参数
来源：http://dali.bjfxy.top/Article/details/gt2mbwckbah.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2sitgywou.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2ykobkfek.html

[C05] 返回多个值
来源：http://dali.gogol.net.cn/Article/details/gt2iexkubas.html

Py:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gt2mnizsoxj.html

PHP:  return [$a, $b];
来源：http://dali.hammf.cn/Article/details/gt2dicqkjur.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuanzx.com/Article/details/gt2jakwomug.html

TS:   return { a, b };
来源：http://dali.daria6918.cn/Article/details/gt2ctbzhahy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuxming.cn/Article/details/gt2hmzceffp.html

Go:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gt2kgthxqjz.html

Ruby: return a, b
来源：http://dali.cashguo.top/Article/details/gt2esgiahyr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shuidangran.top/Article/details/gt2jogwvzpg.html

[C06] 匿名函数 / lambda
来源：http://dali.hnqzz.top/Article/details/gt2umyboaov.html

Py:   square = lambda x: x * x
来源：http://dali.shangyingyoupin.top/Article/details/gt2amhrfcoc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zzowcmve.html

JS:   const square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gt2zlqubtuw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ivvv.top/Article/details/gt2aptcrgbd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.c1oappe.top/Article/details/gt2pmckkocq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lhahswtm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.mhx1999.top/Article/details/gt2vargakak.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gt2faibzldk.html

[C07] 把函数作为参数传入
来源：http://dali.ivvv.top/Article/details/gt2bjchlnan.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jianghu66.top/Article/details/gt2rviqtiat.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.mhx1999.top/Article/details/gt2xpxdjijw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cheryme.top/Article/details/gt2glabyfez.html

TS:   arr.map(String)
来源：http://dali.jinqigfzy.top/Article/details/gt2pgtgmzzl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2vjqggtef.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jlsjyb.cn/Article/details/gt2sjlifxys.html

Ruby: arr.map(&:upcase)
来源：http://dali.tianlin.xyz/Article/details/gt2gvrzrqbe.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yongpay.top/Article/details/gt2hwcrncvu.html

[C08] 闭包
来源：http://dali.meibo888.top/Article/details/gt2selshphj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ehwqpu.com/Article/details/gt2yxdyyoan.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2exefqdmi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gt2ianspcnq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gt2ijorgdue.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fengsongda.top/Article/details/gt2efsxhpbb.html


<!-- 参考信息 -->