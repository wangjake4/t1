代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.shuidangran.top/Article/details/gt2azjjicqn.html

Py:   ord("A"); chr(65)
来源：http://dali.cashguo.top/Article/details/gt2xcnnbgcx.html

PHP:  ord("A"); chr(65)
来源：http://dali.ydzc1.top/Article/details/gt2rmcccrlj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ybcxt.top/Article/details/gt2brsxybes.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jqgfzy.top/Article/details/gt2hiwrmvfz.html

Java: (int) 'A'; (char) 65
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvibxczs.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.shuidangran.top/Article/details/gt2hqaoovew.html

Ruby: "A".ord; 65.chr
来源：http://dali.nanxinkj.top/Article/details/gt2xzqgutzc.html

C#:   (int)'A'; (char)65
来源：http://dali.yangfankeji.com/Article/details/gt2ahkhehzx.html

[A19] 交换两个变量
来源：http://dali.yj202588.top/Article/details/gt2jgtopurx.html

Py:   a, b = b, a
来源：http://dali.shzxlz.cn/Article/details/gt2ylwzivwf.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shuidangran.top/Article/details/gt2axrifweg.html

JS:   [a, b] = [b, a];
来源：http://dali.vqdsnc.cn/Article/details/gt2ygfmwxen.html

TS:   [a, b] = [b, a];
来源：http://dali.gzhubu.top/Article/details/gt2ojksddqo.html

Java: int t = a; a = b; b = t;
来源：http://dali.jianghu66.top/Article/details/gt2vpnlcjop.html

Go:   a, b = b, a
来源：http://dali.yj20258.top/Article/details/gt2xuttascy.html

Ruby: a, b = b, a
来源：http://dali.tanke756.top/Article/details/gt2euimvhqu.html

C#:   (a, b) = (b, a);
来源：http://dali.c1oappe.top/Article/details/gt2cixglmuu.html

[A20] 读取标准输入
来源：http://dali.birdmap.top/Article/details/gt2unhnjdjw.html

Py:   name = input("请输入：")
来源：http://dali.ehwqpu.com/Article/details/gt2melmsimk.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.wangdashe.top/Article/details/gt2ituiuuwl.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yj202588.top/Article/details/gt2ujcyrhtk.html

TS:   // Node.js：readline 模块
来源：http://dali.cashguo.top/Article/details/gt2ojqiaxca.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhixingplan.top/Article/details/gt2jmcifibs.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhijiandao.cn/Article/details/gt2oabarhld.html

Ruby: gets.chomp
来源：http://dali.andypj.xyz/Article/details/gt2vskiieaa.html

C#:   Console.ReadLine();
来源：http://dali.fengsongda.top/Article/details/gt2iasgxvoe.html

[A21] 保留指定小数位输出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wiqszlnv.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cdnleiting.top/Article/details/gt2ggjdtruj.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.guowangkeji.top/Article/details/gt2wozmhpdx.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2bmmutkeb.html

TS:   (3.14159).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gt2schedqbz.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.tian-w.cn/Article/details/gt2vmxavmzv.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.birdmap.top/Article/details/gt2xmkvmdxi.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.vqdsnc.cn/Article/details/gt2tpjnhtdm.html

C#:   3.14159.ToString("F2")
来源：http://dali.0kj1m.cn/Article/details/gt2rfaiaxby.html

[A22] 获取字符串长度
来源：http://dali.cashguo.top/Article/details/gt2qnjfjqrp.html

Py:   len(s)
来源：http://dali.ehwqpu.com/Article/details/gt2wmqlkijz.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.sxryk.cn/Article/details/gt2ypwwujhn.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.chenlongwang.top/Article/details/gt2hhybsqhs.html

TS:   s.length
来源：http://dali.pycfn.com/Article/details/gt2rgcdslxc.html

Java: s.length()
来源：http://dali.jinqigfzy.top/Article/details/gt2gbxxrign.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.gotoacloud.top/Article/details/gt2dxtmyjwj.html

Ruby: s.length
来源：http://dali.nanxinkj.top/Article/details/gt2smitbaoc.html

C#:   s.Length
来源：http://dali.cheryme.top/Article/details/gt2wkzjvujc.html

[A23] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gt2uwswnyoq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yanxiufei.cn/Article/details/gt2qemviejn.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.chenzaomai.com/Article/details/gt2pacactas.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.bjfxy.top/Article/details/gt2adqwtvat.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.smart0.xyz/Article/details/gt2yietbpxb.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.guannengcc.top/Article/details/gt2iodtcnka.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shuidangran.top/Article/details/gt2kpgstyrn.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.fzhhl.top/Article/details/gt2diieinbd.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.tian-w.cn/Article/details/gt2ezdummdz.html

[A24] 去除首尾空白
来源：http://dali.daria6918.cn/Article/details/gt2ugbjdxnr.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.snrcjt.cn/Article/details/gt2tehkwyue.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.redwolf501.top/Article/details/gt2lugvwhiv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.aizwys.cn/Article/details/gt2zhsnqhie.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.c1oappe.top/Article/details/gt2adjchqbl.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.vqdsnc.cn/Article/details/gt2sjplhnfr.html

Go:   strings.TrimSpace(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2jmysczmd.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhongyouzk.top/Article/details/gt2drohttei.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.sysykeji.top/Article/details/gt2bccflbsk.html

[A25] 字符串比较
来源：http://dali.yj202588.top/Article/details/gt2kgmrvddo.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zycfv.cn/Article/details/gt2obvhvnzt.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yj20258888.top/Article/details/gt2crvnufls.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hammf.cn/Article/details/gt2hgchbrbn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tanke756.top/Article/details/gt2pnftrodo.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txchmjex.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhengqikj.top/Article/details/gt2jmenkzgz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hfpthk.cn/Article/details/gt2etgsmphl.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sxryk.cn/Article/details/gt2poodldwf.html

[A26] 类型转换总览
来源：http://dali.sweek.top/Article/details/gt2lbkormmt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhongyouzk.top/Article/details/gt2zzgybbwu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.mhx1999.top/Article/details/gt2pezvhcbn.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxebcucc.html

TS:   Number() String() Boolean() x as number
来源：http://dali.vqdsnc.cn/Article/details/gt2atuhsnmr.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yongpay.top/Article/details/gt2spvhetdw.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.aizwys.cn/Article/details/gt2xndzfihv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.dianchejie.cn/Article/details/gt2dujrqqob.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.birdmap.top/Article/details/gt2ncoctjau.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2nqajlmrt.html

B. 流程控制
来源：http://dali.yj202588.top/Article/details/gt2ffjyahnb.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2rrajmvvz.html

[B01] 条件判断 if / else
来源：http://dali.cashguo.top/Article/details/gt2dpwzkqtf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.gzhubu.top/Article/details/gt2spmpynvv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.mhx1999.top/Article/details/gt2exigaoza.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gt2xluuteul.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.9152youxi.cn/Article/details/gt2swobkpdi.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nanxinkj.top/Article/details/gt2goiwwofr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2crtjmuho.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yueranfly.top/Article/details/gt2nymuxokx.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gt2bftpsxsz.html

[B02] 多分支 else if / elif
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2einclfgp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.iojbl.cn/Article/details/gt2fzzxrhug.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2lvajasyx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gt2khtvnriz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gzhubu.top/Article/details/gt2vajqptxk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gaohongyu789.top/Article/details/gt2dipjqogb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nanxuanxn.top/Article/details/gt2cszaqerc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.pycfn.com/Article/details/gt2sgsxrtuo.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gt2shgbqyaa.html

[B03] switch / match / case
来源：http://dali.ehwqpu.com/Article/details/gt2utiwaymf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shzxlz.cn/Article/details/gt2orkxivhi.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.pycfn.com/Article/details/gt2yfhbppxh.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gt2achugagd.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2owiovxda.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gt2zvchpwmd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.iojbl.cn/Article/details/gt2vljghghs.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ybcxt.top/Article/details/gt2ifksshva.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gt2ahcanjna.html

[B04] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gt2zvhtlact.html

Py:   for i in range(10): print(i)
来源：http://dali.gaohongyu789.top/Article/details/gt2uhtxanqo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jianghu66.top/Article/details/gt2yelualek.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jyoumei.cn/Article/details/gt2xewolmpc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigufen.top/Article/details/gt2iijnabkq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ydzc1.top/Article/details/gt2jlebiocv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.iojbl.cn/Article/details/gt2bjsmxrui.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbifemyt.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sxryk.cn/Article/details/gt2zkqnfcqt.html

[B05] 遍历数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gt2xwzuoyxl.html

Py:   for item in arr: print(item)
来源：http://dali.aizwys.cn/Article/details/gt2miuppkbs.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cucudq.cn/Article/details/gt2hqlslkbp.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.0kj1m.cn/Article/details/gt2goqrkcnq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.quarkkingdee.top/Article/details/gt2mndilvvn.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangdashe.top/Article/details/gt2iyxjmeww.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gzhubu.top/Article/details/gt2lrrpbhlj.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigufen.top/Article/details/gt2vygxwere.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjoihrhd.html

[B06] 遍历字典 / 对象
来源：http://dali.xuanzx.com/Article/details/gt2sxqzfjaf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.tian-w.cn/Article/details/gt2qyuibjsl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bavfasyl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yvedp.cn/Article/details/gt2gqhtaxzu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hammf.cn/Article/details/gt2mztqckav.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hfpthk.cn/Article/details/gt2veiebliw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gaohongyu789.top/Article/details/gt2qjdjtaod.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xziqi.cn/Article/details/gt2pphsvvar.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.nwbrower.top/Article/details/gt2ytfhexbs.html

[B07] while 循环
来源：http://dali.chenlongwang.top/Article/details/gt2faexbwdl.html

Py:   while i < 10: i += 1
来源：http://dali.xuanzx.com/Article/details/gt2qbcvzxij.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yuxming.cn/Article/details/gt2hnfwqihe.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gt2heepjdxf.html

TS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lbncmozw.html

Java: while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqtcypww.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenzaomai.com/Article/details/gt2ctwfzpje.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2itfeahxx.html

C#:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qbxsjmoh.html

[B08] do-while（至少执行一次）
来源：http://dali.hongshengwenyu.top/Article/details/gt2rnxfgsxb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.aibaodan.cn/Article/details/gt2bqdsvgeo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gt2wdlmjdhr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gt2ponaslry.html

TS:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gt2mxyrgcdn.html

Java: do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gt2sspyvuib.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2oubvanjf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigufen.top/Article/details/gt2tvxuljhk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gt2aozmtqkj.html

[B09] break 与 continue
来源：http://dali.fengsongda.top/Article/details/gt2qcftkmil.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gaohongyu789.top/Article/details/gt2bpdcctle.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sweek.top/Article/details/gt2wfakndbq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gt2ehnutgni.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gt2rhaagnzx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ctdrjuln.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxikoivc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ypchbmzo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gt2sfvweoyf.html

[B10] 遍历同时拿索引
来源：http://dali.zdqjudy.top/Article/details/gt2ybhmrmus.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.wangshuangyany.cn/Article/details/gt2onsfltxr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2efalijhq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.kuanghao11.cn/Article/details/gt2sddndoco.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hnqzz.top/Article/details/gt2vosqcbcr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zdqjudy.top/Article/details/gt2rptbmlon.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sysykeji.top/Article/details/gt2yxifqckk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hfpthk.cn/Article/details/gt2nxatcnjh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhengqikj.top/Article/details/gt2mstttelr.html

[B11] 生成数字序列 / 区间
来源：http://dali.birdmap.top/Article/details/gt2afawmkka.html

Py:   list(range(0, 10, 2))
来源：http://dali.ydzc1.top/Article/details/gt2qitglojs.html

PHP:  range(0, 10, 2);
来源：http://dali.pycfn.com/Article/details/gt2ksuhjuzb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gt2skkjjfkv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ybcxt.top/Article/details/gt2pjpeemiu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2werylgnz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhongyouzk.top/Article/details/gt2okvyqmoh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tanke756.top/Article/details/gt2yirhfofz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.meibo888.top/Article/details/gt2zdeigffy.html

[B12] 跳出多层循环
来源：http://dali.jianghu66.top/Article/details/gt2wpbfsrao.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jlsjyb.cn/Article/details/gt2aaklbqsy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.birdmap.top/Article/details/gt2vefhssqw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gt2smxzxrsl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gt2wcyppkmd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gjnqpokb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhongyouzk.top/Article/details/gt2pyrtauuc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2yfekewyp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.havefunace.top/Article/details/gt2vaeujbts.html

[B13] 判断是否为数字
来源：http://dali.nanxuanxn.top/Article/details/gt2wgcjmkjc.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuetiantiany.cn/Article/details/gt2naisfhgj.html

PHP:  is_numeric($x)
来源：http://dali.meibo888.top/Article/details/gt2hgbmoyzq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2molcmcvu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dashuyun.cn/Article/details/gt2oqtybang.html

Java: x instanceof Number
来源：http://dali.jiagoushi.top/Article/details/gt2igpxsaxa.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cheryme.top/Article/details/gt2voexwbbh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mnyfpydi.html

C#:   x is int or double or decimal
来源：http://dali.cucudq.cn/Article/details/gt2sumuecyd.html

[B14] 判断值是否在集合内
来源：http://dali.quarkkingdee.top/Article/details/gt2lctiwzsw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2atrvltpd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdfdkvjh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhixingplan.top/Article/details/gt2rsndngtn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2dlxrtmgl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.snrcjt.cn/Article/details/gt2ywsnnfgk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zdqjudy.top/Article/details/gt2urkfbjws.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vyqfuzhi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gt2jdjuvofz.html

[B15] 布尔运算与取反
来源：http://dali.shuidangran.top/Article/details/gt2lwxuvaks.html

Py:   a and b or not c
来源：http://dali.yj202588.top/Article/details/gt2lafjbcpn.html

PHP:  $a && $b || !$c
来源：http://dali.nanxuanxn.top/Article/details/gt2nebyrnvj.html

JS:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2dzqapcwu.html

TS:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2kupldxod.html

Java: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2ozgiathu.html

Go:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2moswpqon.html

Ruby: a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2dsajilnj.html

C#:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2mtjldfqr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guowangkeji.top/Article/details/gt2cleojvyp.html

Py:   if not data: return
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjeovkzi.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gt2klnrixlo.html

JS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gt2ksddfyhk.html

TS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gt2kwjlbiyt.html

Java: if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gt2kufnfyen.html

Go:   if data == nil { return }
来源：http://dali.guannengcc.top/Article/details/gt2leqjfneg.html

Ruby: return if data.nil?
来源：http://dali.jlsjyb.cn/Article/details/gt2gndkutui.html

C#:   if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gt2cjfuaspp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2twsovmqk.html

C. 函数与作用域
来源：http://dali.316326.xyz/Article/details/gt2jtdietik.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2dieqmjqu.html

[C01] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tfhyghwi.html

Py:   def add(a, b): return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gt2qhnmvhcq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzluueyb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2swvuwwql.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2rbyfipbg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2thggclwn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2glwzvpik.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ydzc1.top/Article/details/gt2hkemnbea.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2qsyiqdrk.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2stgjyfnp.html

Py:   def greet(name="World"): return name
来源：http://dali.zdqjudy.top/Article/details/gt2meotdjxl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2yyuhvyyq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vcwpikce.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2nzvtqzwy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gt2adykbfkm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ivvv.top/Article/details/gt2gxnitpgg.html

Ruby: def greet(name = "World") = name
来源：http://dali.daria6918.cn/Article/details/gt2tbqrgvop.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yangfankeji.com/Article/details/gt2uetcofio.html

[C03] 可变参数
来源：http://dali.fzhhl.top/Article/details/gt2opwhalxk.html

Py:   def total(*args): return sum(args)
来源：http://dali.gogol.net.cn/Article/details/gt2deftqrso.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gt2ltmfdiit.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gt2dbdmrjdn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nwbrower.top/Article/details/gt2hddgzxrz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenlongwang.top/Article/details/gt2ozhnbgbo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgfzy.top/Article/details/gt2janpmobk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kldvwsnu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.iojbl.cn/Article/details/gt2urfzscog.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gt2ofgzupch.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgfzy.top/Article/details/gt2fgrjigoi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dclwcmoc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gt2tzacazgv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yueranfly.top/Article/details/gt2msjejufb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jiagoushi.top/Article/details/gt2qakjsgiq.html

Go:   // 无：用配置结构体参数
来源：http://dali.ybcxt.top/Article/details/gt2xsfpdzvr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gt2ywjmgqlw.html

C#:   f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gt2pdneqovn.html

[C05] 返回多个值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2anrfkbqh.html

Py:   return a, b
来源：http://dali.fengsongda.top/Article/details/gt2upkofiye.html

PHP:  return [$a, $b];
来源：http://dali.zhongyouzk.top/Article/details/gt2cdlcosxi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqbtjngn.html

TS:   return { a, b };
来源：http://dali.yj20258888.top/Article/details/gt2iafstebv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj202588.top/Article/details/gt2xznpidbh.html

Go:   return a, b
来源：http://dali.vqdsnc.cn/Article/details/gt2glufqyoz.html

Ruby: return a, b
来源：http://dali.kuanghao11.cn/Article/details/gt2lbcjsgjy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.c1oappe.top/Article/details/gt2cxdyqqex.html

[C06] 匿名函数 / lambda
来源：http://dali.hysaishi.cn/Article/details/gt2cdwczylg.html

Py:   square = lambda x: x * x
来源：http://dali.shuidangran.top/Article/details/gt2quwkkspc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.svipenyu.cn/Article/details/gt2nvjoshtu.html

JS:   const square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gt2bfplcpyc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sufxvd.cn/Article/details/gt2phtlpwwp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxuanxn.top/Article/details/gt2aprjgggr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daria6918.cn/Article/details/gt2iilsiosj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2cphymmpk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gt2vuxzcfhm.html

[C07] 把函数作为参数传入
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqhteqpd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jyoumei.cn/Article/details/gt2prbjfcgu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ydzc1.top/Article/details/gt2uvexjjas.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgufenzy.top/Article/details/gt2mktvraxv.html

TS:   arr.map(String)
来源：http://dali.yonumen.top/Article/details/gt2rqryyuad.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2lauulduc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guannengcc.top/Article/details/gt2fwsmppzy.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj202588.top/Article/details/gt2nbcqtixs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxuanxn.top/Article/details/gt2zcoeokda.html

[C08] 闭包
来源：http://dali.yangfankeji.com/Article/details/gt2dzaqinln.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.vqdsnc.cn/Article/details/gt2ihikxgsn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fzhhl.top/Article/details/gt2iptrlfgd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gt2ihovvdic.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gt2tesgbhsu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xylfe.cn/Article/details/gt2fdtnzspf.html


<!-- 参考信息 -->