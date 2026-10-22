代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hnxiangtu.top/Article/details/gtkogcdckc.html

Java: (int) 'A'; (char) 65
来源：http://dali.ydzc1.top/Article/details/gtazsddsub.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhoulong.xyz/Article/details/gtazycnfqk.html

Ruby: "A".ord; 65.chr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdtbshfk.html

C#:   (int)'A'; (char)65
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdnnspat.html

[A19] 交换两个变量
来源：http://dali.nanxuanxn.top/Article/details/gtawopmhch.html

Py:   a, b = b, a
来源：http://dali.gaohongyu789.top/Article/details/gtnpkrzvuz.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shuidangran.top/Article/details/gttvrqucns.html

JS:   [a, b] = [b, a];
来源：http://dali.zdqjudy.top/Article/details/gtksevgant.html

TS:   [a, b] = [b, a];
来源：http://dali.cucudq.cn/Article/details/gtoyygqzac.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhongyouzk.top/Article/details/gtvgeohozl.html

Go:   a, b = b, a
来源：http://dali.tanke756.top/Article/details/gtachvnups.html

Ruby: a, b = b, a
来源：http://dali.jinqigufen.top/Article/details/gtdfjiltsl.html

C#:   (a, b) = (b, a);
来源：http://dali.jlsjyb.cn/Article/details/gtuwmitpmo.html

[A20] 读取标准输入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthswnnelb.html

Py:   name = input("请输入：")
来源：http://dali.hammf.cn/Article/details/gtdqohhtyh.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.fengsongda.top/Article/details/gtakibubkf.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhijiandao.cn/Article/details/gtuieznvbc.html

TS:   // Node.js：readline 模块
来源：http://dali.cqqwz.cn/Article/details/gtgceyjogj.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jlsjyb.cn/Article/details/gtslwjxyqu.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zycfv.cn/Article/details/gtrsgrniao.html

Ruby: gets.chomp
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpujtoyrr.html

C#:   Console.ReadLine();
来源：http://dali.yangfankeji.com/Article/details/gtoaviners.html

[A21] 保留指定小数位输出
来源：http://dali.gotoacloud.top/Article/details/gtbdadtlfj.html

Py:   f"{3.14159:.2f}"
来源：http://dali.nanxuanxn.top/Article/details/gtieykassf.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gtanosqlpt.html

JS:   (3.14159).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gtyursskyw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gtdtkltpje.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.birdmap.top/Article/details/gtdaxvpupy.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shangyingyoupin.top/Article/details/gtpasuwfzt.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shangyingyoupin.top/Article/details/gtyewwpfdz.html

C#:   3.14159.ToString("F2")
来源：http://dali.jyoumei.cn/Article/details/gtrttgwcrg.html

[A22] 获取字符串长度
来源：http://dali.hfpthk.cn/Article/details/gteodgmccl.html

Py:   len(s)
来源：http://dali.cdnleiting.top/Article/details/gtwxxoyize.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.fengsongda.top/Article/details/gtsoyatuqy.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hammf.cn/Article/details/gtgmltmjml.html

TS:   s.length
来源：http://dali.pycfn.com/Article/details/gtqmwoisln.html

Java: s.length()
来源：http://dali.sufxvd.cn/Article/details/gtolfagijx.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.daxiang520.top/Article/details/gtnrvbiedz.html

Ruby: s.length
来源：http://dali.cheryme.top/Article/details/gtwdogyhuq.html

C#:   s.Length
来源：http://dali.hammf.cn/Article/details/gtreqtttjo.html

[A23] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtusbjydwx.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqtvwfmd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ivvv.top/Article/details/gtluszavyt.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwgrkrrc.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pengpengdd.cyou/Article/details/gtzdnjtrrj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.cucudq.cn/Article/details/gtrqhdbugm.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.pycfn.com/Article/details/gtnwxjhxib.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gtokbwkzgv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.snrcjt.cn/Article/details/gtakeghcin.html

[A24] 去除首尾空白
来源：http://dali.yueranfly.top/Article/details/gtlhdzoynk.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ehwqpu.com/Article/details/gtbdtqlnkt.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yj20258.top/Article/details/gtmmvqsxiv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.feifeiyinyue.top/Article/details/gtjspzsbog.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.snrcjt.cn/Article/details/gtorlybfvj.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jianghu66.top/Article/details/gtzaudeslf.html

Go:   strings.TrimSpace(s)
来源：http://dali.jiagoushi.top/Article/details/gtbqxoadpk.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.quarkkingdee.top/Article/details/gtvpamzfbv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jianghu66.top/Article/details/gtksgiista.html

[A25] 字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gtwursxfqn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.daxiang520.top/Article/details/gtwxhszwwg.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jiagoushi.top/Article/details/gtxgrbwlqi.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aizwys.cn/Article/details/gtlehfjqkx.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenzaomai.com/Article/details/gthhnotklu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yangfankeji.com/Article/details/gtvllyltnc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.aibaodan.cn/Article/details/gtuftnhhkb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.aizwys.cn/Article/details/gtkdpceynr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtrkljuhlr.html

[A26] 类型转换总览
来源：http://dali.guannengcc.top/Article/details/gtrppwyxlb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hammf.cn/Article/details/gtwrzjymbp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tanke756.top/Article/details/gtgorsgwsv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.chenjidiqi.icu/Article/details/gtwkdzwfkh.html

TS:   Number() String() Boolean() x as number
来源：http://dali.guowangkeji.top/Article/details/gtsjqmdhjq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hfpthk.cn/Article/details/gtmgojymny.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yangfankeji.com/Article/details/gthktgttfb.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nwbrower.top/Article/details/gtqbnzqmzy.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cqqwz.cn/Article/details/gtfytgvbbk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtyphxtkfg.html

B. 流程控制
来源：http://dali.zhijiandao.cn/Article/details/gtvgxrjleo.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtdlbcdzhi.html

[B01] 条件判断 if / else
来源：http://dali.jinqigfzy.top/Article/details/gtnimriiyk.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.vqdsnc.cn/Article/details/gtzicspync.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjeblbtju.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gthqyzavoe.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtkodfrrdr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gtpvcxgsea.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yuxming.cn/Article/details/gtollvvcmw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jqgfzy.top/Article/details/gtuniwxjcb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gtjpufwkqr.html

[B02] 多分支 else if / elif
来源：http://dali.shangyingyoupin.top/Article/details/gtfpemphqe.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxhhsfaa.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhixingplan.top/Article/details/gtvnhppacm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gtbqqsnbwm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkercxqte.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gtspzxhgom.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jyoumei.cn/Article/details/gtffyomico.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.redwolf501.top/Article/details/gtxdsyijwm.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gtlxedjkor.html

[B03] switch / match / case
来源：http://dali.ivvv.top/Article/details/gtjbztqggm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.dianchejie.cn/Article/details/gtemxicmhd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gtohvwtxjf.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gtpycteqij.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gtepwiffyj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gtuvqpujpr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hnxiangtu.top/Article/details/gtpqlnktzn.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.feifeiyinyue.top/Article/details/gtlcjvwwjs.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gaohongyu789.top/Article/details/gtyabnmsns.html

[B04] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gtrwshijqj.html

Py:   for i in range(10): print(i)
来源：http://dali.gaohongyu789.top/Article/details/gtufjmplsm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ppjwa.cn/Article/details/gtngickmsc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtrwjuyfoe.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xuetiantiany.cn/Article/details/gtpgysaehq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hammf.cn/Article/details/gtzwzfsdmg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.316326.xyz/Article/details/gtcuxbzjxi.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xinyue.icu/Article/details/gtskybawnp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jlsjyb.cn/Article/details/gtbekaoyyw.html

[B05] 遍历数组 / 列表
来源：http://dali.xuanzx.com/Article/details/gtmshasacr.html

Py:   for item in arr: print(item)
来源：http://dali.yanxiufei.cn/Article/details/gtjulqvirg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hywenlv.cn/Article/details/gtxrjabtvp.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxinkj.top/Article/details/gtptlfyzuo.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zdqjudy.top/Article/details/gthkzqduzy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.guowangkeji.top/Article/details/gtkohetfop.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ydzc1.top/Article/details/gtmdnsfqcg.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqwoenzm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.9152youxi.cn/Article/details/gthuobyqsf.html

[B06] 遍历字典 / 对象
来源：http://dali.yuxming.cn/Article/details/gtqoidzlea.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.wangdashe.top/Article/details/gtferenhfr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yanxiufei.cn/Article/details/gtqgabalir.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyavgujrl.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gtzrasujwn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ybcxt.top/Article/details/gtrxpdetux.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.smart0.xyz/Article/details/gttkvmnhel.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhiwuduotai.top/Article/details/gtxcvbkfye.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.redwolf501.top/Article/details/gtftimdcsh.html

[B07] while 循环
来源：http://dali.andypj.xyz/Article/details/gtoyjczawd.html

Py:   while i < 10: i += 1
来源：http://dali.yj202588.top/Article/details/gtzlhkjxmi.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yonumen.top/Article/details/gtjfocaavz.html

JS:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtqgtfpcxc.html

TS:   while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gtkfwtmsmn.html

Java: while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtkobbsixm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.quarkkingdee.top/Article/details/gtonedsqij.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hfpthk.cn/Article/details/gthbmniapw.html

C#:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtoytsfiyp.html

[B08] do-while（至少执行一次）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoiksspmc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuetiantiany.cn/Article/details/gtatnlelmy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtcntdvzwd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtsxhjtpos.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstupiouz.html

Java: do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtcoypomdm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucgmkpnq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shzxlz.cn/Article/details/gttzbadwfh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtvkwcfpyg.html

[B09] break 与 continue
来源：http://dali.0kj1m.cn/Article/details/gtwlnvpnwo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.havefunace.top/Article/details/gtabkdnesp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtqevjgdfe.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtxkaslcya.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtdfnigvsh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstfcovsf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zycfv.cn/Article/details/gtkqndaodi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gotoacloud.top/Article/details/gtlyctoslp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtdmnzqrfu.html

[B10] 遍历同时拿索引
来源：http://dali.hnqzz.top/Article/details/gtcavklcta.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tian-w.cn/Article/details/gtuljmvmex.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.vqdsnc.cn/Article/details/gtbkefnsip.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangdashe.top/Article/details/gtwfcuxoxl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jiagoushi.top/Article/details/gtylglqqfm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.0kj1m.cn/Article/details/gtyzwsjkap.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.iojbl.cn/Article/details/gtpzztajly.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jianghu66.top/Article/details/gtrxynmtcl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuetiantiany.cn/Article/details/gtcxnbgkjb.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangdashe.top/Article/details/gtpeqomnla.html

Py:   list(range(0, 10, 2))
来源：http://dali.daria6918.cn/Article/details/gtmfsbpfys.html

PHP:  range(0, 10, 2);
来源：http://dali.nwbrower.top/Article/details/gttgutwhtj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxinkj.top/Article/details/gtwurnnekl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gtnqrsetzy.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtynlyemig.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sufxvd.cn/Article/details/gtrfoaiuld.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gaohongyu789.top/Article/details/gtnmkeznff.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shuidangran.top/Article/details/gtfwqblqew.html

[B12] 跳出多层循环
来源：http://dali.yuanzhike.top/Article/details/gtpbtqdkbc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrccspqby.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhengqikj.top/Article/details/gtzovfkcne.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gtqxpblhjd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtlwxwwgto.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtcanqsnup.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenlongwang.top/Article/details/gtzadhdmaq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dashuyun.cn/Article/details/gtuaprghwf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jlsjyb.cn/Article/details/gtmturnqlv.html

[B13] 判断是否为数字
来源：http://dali.snrcjt.cn/Article/details/gtjsdgcrja.html

Py:   isinstance(x, (int, float))
来源：http://dali.mhx1999.top/Article/details/gtmqffogsb.html

PHP:  is_numeric($x)
来源：http://dali.yuanzhike.top/Article/details/gtnirisxet.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gtzexnlwpk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gtoceenavh.html

Java: x instanceof Number
来源：http://dali.hnxiangtu.top/Article/details/gtoqeryhtc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tanke756.top/Article/details/gtteeqbfhm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pycfn.com/Article/details/gtbmtvsscl.html

C#:   x is int or double or decimal
来源：http://dali.gogol.net.cn/Article/details/gtjrmfweim.html

[B14] 判断值是否在集合内
来源：http://dali.tanke756.top/Article/details/gtnbqhnzju.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.316326.xyz/Article/details/gtaaefdgzl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgufenzy.top/Article/details/gtaupgiior.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtyoelpdsl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gtkqdwhmqz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtboafifkk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tian-w.cn/Article/details/gtaraquucw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtkxceaeth.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtgodzclrn.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gtoobaafnn.html

Py:   a and b or not c
来源：http://dali.guannengcc.top/Article/details/gtzqoqzook.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwedlooue.html

JS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gttcndyapf.html

TS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtddsdqtdc.html

Java: a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtrnqbisdg.html

Go:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtyhkckkdm.html

Ruby: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtidjqhucl.html

C#:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtpdwpeman.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenlongwang.top/Article/details/gttqdymigi.html

Py:   if not data: return
来源：http://dali.kuanghao11.cn/Article/details/gthnvzmiqb.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gtcxcwvgxs.html

JS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gtdwiaaome.html

TS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gtahvtamql.html

Java: if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gtosrklvgl.html

Go:   if data == nil { return }
来源：http://dali.hnqzz.top/Article/details/gtjdayxsdf.html

Ruby: return if data.nil?
来源：http://dali.cqqwz.cn/Article/details/gtcxbdxbrd.html

C#:   if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gtuvkiyubd.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtuoedtstb.html

C. 函数与作用域
来源：http://dali.daria6918.cn/Article/details/gtaygtszcc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtasjozupw.html

[C01] 定义函数
来源：http://dali.sweek.top/Article/details/gtgdcpumyc.html

Py:   def add(a, b): return a + b
来源：http://dali.andypj.xyz/Article/details/gtgrrmigzg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtfnmjrtxj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtfezlkzqw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtwgidgmba.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gttpuowxkp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daria6918.cn/Article/details/gtwqgwvwqh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnqzz.top/Article/details/gtlqfvjpgc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvhseisn.html

[C02] 默认参数
来源：http://dali.ivvv.top/Article/details/gtuydpihrw.html

Py:   def greet(name="World"): return name
来源：http://dali.ppjwa.cn/Article/details/gtdhqrlges.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvghrwkkv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gthsomfgqc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gtppckcsye.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gtickezwea.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xinyue.icu/Article/details/gtyxycgzkm.html

Ruby: def greet(name = "World") = name
来源：http://dali.snrcjt.cn/Article/details/gtfpbhfdcu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjgtolwd.html

[C03] 可变参数
来源：http://dali.cashguo.top/Article/details/gtqgnjdega.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gtyjvdobqn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.bjfxy.top/Article/details/gtoqrxqglz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.9152youxi.cn/Article/details/gtqgawerlo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gtbopsfzlf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.quarkkingdee.top/Article/details/gtqeswymue.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gtladxuvhm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daxiang520.top/Article/details/gtqekkxlut.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daxiang520.top/Article/details/gthyzpdisu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xylfe.cn/Article/details/gtidpynxqn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258.top/Article/details/gtssuelzso.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvkxwegr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gtohfxmgwo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dianchejie.cn/Article/details/gtefjdsvql.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guannengcc.top/Article/details/gthnkbkkwl.html

Go:   // 无：用配置结构体参数
来源：http://dali.gaohongyu789.top/Article/details/gthtzrxfbg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtiofdtmle.html

C#:   f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gtslqobsyg.html

[C05] 返回多个值
来源：http://dali.nanxinkj.top/Article/details/gtggckisqs.html

Py:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrragazx.html

PHP:  return [$a, $b];
来源：http://dali.zhixingplan.top/Article/details/gtvncxkcml.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtvtqpkzgz.html

TS:   return { a, b };
来源：http://dali.shuidangran.top/Article/details/gtwudaneei.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozbghufl.html

Go:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gtexreezwl.html

Ruby: return a, b
来源：http://dali.dianchejie.cn/Article/details/gtqqvpvisa.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ywan-chungtsiang.top/Article/details/gtittnzati.html

[C06] 匿名函数 / lambda
来源：http://dali.cqqwz.cn/Article/details/gthxedjcwj.html

Py:   square = lambda x: x * x
来源：http://dali.birdmap.top/Article/details/gtfbhuoyri.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhixingplan.top/Article/details/gtioqanyud.html

JS:   const square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtslwmquez.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuanzx.com/Article/details/gtrdqvfive.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.iojbl.cn/Article/details/gtcvbatzew.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangdashe.top/Article/details/gtlhnrtfab.html

Ruby: square = ->(x) { x * x }
来源：http://dali.havefunace.top/Article/details/gtwppqxoyj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gteyvknbdq.html

[C07] 把函数作为参数传入
来源：http://dali.jqgufenzy.top/Article/details/gtyutogctr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.vqdsnc.cn/Article/details/gtyineffub.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gzhubu.top/Article/details/gtrgxusnoo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.redwolf501.top/Article/details/gtzebeosyo.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgxtpbqd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nwbrower.top/Article/details/gthyobktix.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhixingplan.top/Article/details/gtgfitoxig.html

Ruby: arr.map(&:upcase)
来源：http://dali.mhx1999.top/Article/details/gtdrvjbrqf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zdqjudy.top/Article/details/gtdbonuxdi.html

[C08] 闭包
来源：http://dali.pycfn.com/Article/details/gtamsfiyfp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aibaodan.cn/Article/details/gtslaedizn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.snrcjt.cn/Article/details/gtmunkshbr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtdmgdhhkc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtpopbsolp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hywenlv.cn/Article/details/gtgsfnnpou.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xylfe.cn/Article/details/gtjcxktvkr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhoulong.xyz/Article/details/gtbxczgldd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtebwwnsmj.html

[C09] 递归
来源：http://dali.9152youxi.cn/Article/details/gtlhvlrits.html


<!-- 参考信息 -->