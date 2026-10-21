代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.jinqigufen.top/Article/details/gtjohqbghy.html

TS:   const value = data ?? "默认值";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzfrknne.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hongshengwenyu.top/Article/details/gttveaoyvk.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jinqigfzy.top/Article/details/gtlvxhyssg.html

Ruby: value = data || "默认值"
来源：http://dali.zhoulong.xyz/Article/details/gtxmhejxqm.html

C#:   var value = data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gtvakknqls.html

[A16] 真假值判断规则
来源：http://dali.sysykeji.top/Article/details/gtnxubwisc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.gotoacloud.top/Article/details/gtuzyhxorl.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shzxlz.cn/Article/details/gtvbqumaqk.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.vqdsnc.cn/Article/details/gtxaurfwhq.html

TS:   if (!x) {}
来源：http://dali.shzxlz.cn/Article/details/gtmwzecvve.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtgserbpyx.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ybcxt.top/Article/details/gtnfvhwfwe.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.gaohongyu789.top/Article/details/gtmsmjgaiz.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.tianlin.xyz/Article/details/gtnxudkzbk.html

[A17] 位运算
来源：http://dali.cashguo.top/Article/details/gtqhfhzsti.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gtqzylrmdp.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shuidangran.top/Article/details/gtjkfwrwcv.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gtiyzjajrm.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gtjdywhmtm.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtactphlks.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gtxstzagky.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gtoegkzewn.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gtlukfgwuy.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yj202588.top/Article/details/gtlkitfdiu.html

Py:   ord("A"); chr(65)
来源：http://dali.wangdashe.top/Article/details/gtgivawzak.html

PHP:  ord("A"); chr(65)
来源：http://dali.gotoacloud.top/Article/details/gtkabyiapw.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoatqkwne.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ppjwa.cn/Article/details/gtfngvbzpb.html

Java: (int) 'A'; (char) 65
来源：http://dali.yj20258.top/Article/details/gtdsjggkua.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.sufxvd.cn/Article/details/gthxzuqeqm.html

Ruby: "A".ord; 65.chr
来源：http://dali.ppjwa.cn/Article/details/gtinxyentf.html

C#:   (int)'A'; (char)65
来源：http://dali.zhiwuduotai.top/Article/details/gtrgqzcgli.html

[A19] 交换两个变量
来源：http://dali.sweek.top/Article/details/gtrpujdumy.html

Py:   a, b = b, a
来源：http://dali.hfpthk.cn/Article/details/gthpqatsme.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.gogol.net.cn/Article/details/gtwmdhggul.html

JS:   [a, b] = [b, a];
来源：http://dali.yuxming.cn/Article/details/gtbywexfpz.html

TS:   [a, b] = [b, a];
来源：http://dali.feifeiyinyue.top/Article/details/gtxgjkzlfu.html

Java: int t = a; a = b; b = t;
来源：http://dali.nwbrower.top/Article/details/gtsbstnurn.html

Go:   a, b = b, a
来源：http://dali.zdqjudy.top/Article/details/gtutylrshv.html

Ruby: a, b = b, a
来源：http://dali.redwolf501.top/Article/details/gtsozgvxyw.html

C#:   (a, b) = (b, a);
来源：http://dali.fzhhl.top/Article/details/gtrsqqjyos.html

[A20] 读取标准输入
来源：http://dali.shuidangran.top/Article/details/gtympbtopi.html

Py:   name = input("请输入：")
来源：http://dali.jinqigufen.top/Article/details/gtxmdqqutk.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.andypj.xyz/Article/details/gtioyyrmso.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.tian-w.cn/Article/details/gtdufowejj.html

TS:   // Node.js：readline 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvvysjlf.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.wangdashe.top/Article/details/gtbcpkybqu.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzzuoyhi.html

Ruby: gets.chomp
来源：http://dali.tian-w.cn/Article/details/gtyhvphkfc.html

C#:   Console.ReadLine();
来源：http://dali.cqqwz.cn/Article/details/gtkueuzlwh.html

[A21] 保留指定小数位输出
来源：http://dali.sxryk.cn/Article/details/gtumaaxcni.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zycfv.cn/Article/details/gtpltgnnrq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gtejauylqn.html

JS:   (3.14159).toFixed(2)
来源：http://dali.bjfxy.top/Article/details/gtbyvtvujh.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtutrnqpot.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cdnleiting.top/Article/details/gtizrunwjb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.smart0.xyz/Article/details/gtjaalzgqx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmaxfyfqp.html

C#:   3.14159.ToString("F2")
来源：http://dali.xinyue.icu/Article/details/gtodkcqpqd.html

[A22] 获取字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtpwtbnsoh.html

Py:   len(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlexdxevu.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.wangshuangyany.cn/Article/details/gtatetfyei.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.iojbl.cn/Article/details/gtlstyzigv.html

TS:   s.length
来源：http://dali.hfpthk.cn/Article/details/gtrnqvctkx.html

Java: s.length()
来源：http://dali.tian-w.cn/Article/details/gtwrlkklfv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.cdnleiting.top/Article/details/gtxbjfltdb.html

Ruby: s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtyzwxsqww.html

C#:   s.Length
来源：http://dali.yvedp.cn/Article/details/gtediezbne.html

[A23] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtkwujusmj.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zycfv.cn/Article/details/gtnkrzgfvt.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.dianchejie.cn/Article/details/gtpfvujwhy.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.bjfxy.top/Article/details/gtuzcbxxxh.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangshuangyany.cn/Article/details/gtbajkfcvb.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.gogol.net.cn/Article/details/gtrklhpyno.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yongpay.top/Article/details/gtpxqgbcws.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmfablli.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hammf.cn/Article/details/gtiowjtjcm.html

[A24] 去除首尾空白
来源：http://dali.daxiang520.top/Article/details/gtjsfkwpqt.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hnqzz.top/Article/details/gtfehmhxuf.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ppjwa.cn/Article/details/gtbuliqhxl.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.redwolf501.top/Article/details/gttauadqvs.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuanzhike.top/Article/details/gtmmautpkh.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jqgufenzy.top/Article/details/gtlnfuvdoq.html

Go:   strings.TrimSpace(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtbaiccsku.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cashguo.top/Article/details/gtvxaodhmg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.pengpengdd.cyou/Article/details/gtxruxgffo.html

[A25] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtbcikuhhm.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sxryk.cn/Article/details/gtjgufiwhd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ydzc1.top/Article/details/gtlvuigkcw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cdnleiting.top/Article/details/gtwcfkpuvf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nanxuanxn.top/Article/details/gtuzcbworb.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtjwcphxfr.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gzhubu.top/Article/details/gtuirfrsvh.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.sysykeji.top/Article/details/gtdeglpaou.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yangfankeji.com/Article/details/gthhhowhvl.html

[A26] 类型转换总览
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskpmhxdq.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxuujcjh.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxuanxn.top/Article/details/gtscdqkvmr.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrbbmbpn.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jinqigufen.top/Article/details/gtbxanuslm.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sxryk.cn/Article/details/gttakkeeyh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yonumen.top/Article/details/gtgakqmiyw.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhixingplan.top/Article/details/gthrlpeyfw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cucudq.cn/Article/details/gtuuspxerc.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtgvdhynra.html

B. 流程控制
来源：http://dali.wangdashe.top/Article/details/gtuibwxlhl.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtyihnypjs.html

[B01] 条件判断 if / else
来源：http://dali.0kj1m.cn/Article/details/gtwqjgvwhc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.gaohongyu789.top/Article/details/gtloicxdph.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jqgfzy.top/Article/details/gteqdzfbza.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gtdbzhsuym.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gthyanoder.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gthwhvdkly.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sufxvd.cn/Article/details/gtgwhbjdki.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hnxiangtu.top/Article/details/gtjhkbqzwu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gtqponecmf.html

[B02] 多分支 else if / elif
来源：http://dali.cqqwz.cn/Article/details/gtersqjmdm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.c1oappe.top/Article/details/gtwtnhlwoi.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdazwdck.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtvqgfyzbw.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gtyckdoble.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gtienfjwfo.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gotoacloud.top/Article/details/gtdczwgusk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tian-w.cn/Article/details/gtriuqfvef.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtdakyffuk.html

[B03] switch / match / case
来源：http://dali.zhiwuduotai.top/Article/details/gtquhglivb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.nanxinkj.top/Article/details/gtnbntvpsd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtubbrosiz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gttiofwcjt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtizbmlzoz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gtnvqijftd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yangfankeji.com/Article/details/gtqyvjdnxc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.fzhhl.top/Article/details/gtraoymbfm.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xuanzx.com/Article/details/gtbavrpsng.html

[B04] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gtwzlamkmy.html

Py:   for i in range(10): print(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtglphysob.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.redwolf501.top/Article/details/gtgecvzynl.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxinkj.top/Article/details/gttcxaepjv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gzhubu.top/Article/details/gtcfvksmmb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nwbrower.top/Article/details/gtpxeekjjq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.birdmap.top/Article/details/gtufuwdccn.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xziqi.cn/Article/details/gtmudazfqq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.aizwys.cn/Article/details/gtapomqpyj.html

[B05] 遍历数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gtxrrahpgn.html

Py:   for item in arr: print(item)
来源：http://dali.feifeiyinyue.top/Article/details/gttatjtyva.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tian-w.cn/Article/details/gtrzaomhqk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gtuvquzntl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xziqi.cn/Article/details/gtvqanwpbg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aizwys.cn/Article/details/gttbfxwasx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaivdecxl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.smart0.xyz/Article/details/gtywlgismq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cheryme.top/Article/details/gtkvqqzmge.html

[B06] 遍历字典 / 对象
来源：http://dali.andypj.xyz/Article/details/gthbqtvsmw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nwbrower.top/Article/details/gtmduhfrby.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cashguo.top/Article/details/gtbpmvheph.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.9152youxi.cn/Article/details/gtsmkblfvb.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xylfe.cn/Article/details/gtuqdcwwsh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yanxiufei.cn/Article/details/gtqtwjcgcg.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.redwolf501.top/Article/details/gtlfejvbxx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hysaishi.cn/Article/details/gtyseqitlj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gtttqjdnam.html

[B07] while 循环
来源：http://dali.bjfxy.top/Article/details/gtclzsnkwl.html

Py:   while i < 10: i += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnkjokyt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj20258888.top/Article/details/gtduuawhnp.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvflttmbi.html

TS:   while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gteqqrepsv.html

Java: while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgpmjjipq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.316326.xyz/Article/details/gtdcgzzonu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gtdakusofd.html

C#:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtogjbqcdc.html

[B08] do-while（至少执行一次）
来源：http://dali.wangdashe.top/Article/details/gtyaabuujv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jiagoushi.top/Article/details/gtlciycnqc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtgednwooj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtecffdfuv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtbcnzvxsv.html

Java: do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtvzspvjpe.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jianghu66.top/Article/details/gtjdztztzp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zycfv.cn/Article/details/gtpwzfbjvk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gtqstxsopx.html

[B09] break 与 continue
来源：http://dali.xziqi.cn/Article/details/gtiyjvjxxp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinqigfzy.top/Article/details/gtgwshuitu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtcfshcrrg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtuhungpde.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtrjyqxqof.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gthmidqzsd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sweek.top/Article/details/gthzvoswvv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.meibo888.top/Article/details/gttpborpai.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtnkcjvxub.html

[B10] 遍历同时拿索引
来源：http://dali.guowangkeji.top/Article/details/gtzgulfyyt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.vqdsnc.cn/Article/details/gtypzdqhin.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangdashe.top/Article/details/gtifnurgae.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sweek.top/Article/details/gtoiqykdyo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sweek.top/Article/details/gtrktthlir.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhongyouzk.top/Article/details/gtowhuuaym.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yonumen.top/Article/details/gtdwxryvdw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuxming.cn/Article/details/gtluxtugmx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yanxiufei.cn/Article/details/gtlluqwesq.html

[B11] 生成数字序列 / 区间
来源：http://dali.zycfv.cn/Article/details/gtkfpevxun.html

Py:   list(range(0, 10, 2))
来源：http://dali.redwolf501.top/Article/details/gtudyckguj.html

PHP:  range(0, 10, 2);
来源：http://dali.daxiang520.top/Article/details/gttlzfwkem.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gtfhxpyzyq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnxiangtu.top/Article/details/gtiylwhzvq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.316326.xyz/Article/details/gtlheojqem.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgfzy.top/Article/details/gtkavxlyyw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nanxuanxn.top/Article/details/gtqpzgzwgx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.snrcjt.cn/Article/details/gtcpltqssw.html

[B12] 跳出多层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyiibpcr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinqigufen.top/Article/details/gtqhkkhcal.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqqxrzwc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gticshmkmp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gtntwvkqrt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtglhuabcq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hfpthk.cn/Article/details/gtqptpgzgm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfuvknfq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.0kj1m.cn/Article/details/gtiggcnsyw.html

[B13] 判断是否为数字
来源：http://dali.guannengcc.top/Article/details/gtljdfnabt.html

Py:   isinstance(x, (int, float))
来源：http://dali.hammf.cn/Article/details/gtdcjhadij.html

PHP:  is_numeric($x)
来源：http://dali.nwbrower.top/Article/details/gttlgcpcmx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gthvnkidsx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gtdogduphi.html

Java: x instanceof Number
来源：http://dali.jqgufenzy.top/Article/details/gtwbzmdcjt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigufen.top/Article/details/gtdojkwqpe.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sweek.top/Article/details/gttaxnmefx.html

C#:   x is int or double or decimal
来源：http://dali.smart0.xyz/Article/details/gtpxpbiudz.html

[B14] 判断值是否在集合内
来源：http://dali.hywenlv.cn/Article/details/gtvchpaasd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258.top/Article/details/gtseruidmw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sweek.top/Article/details/gtshadwgxc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gteiytesrh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtgaxcwlso.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pycfn.com/Article/details/gtllullwif.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj202588.top/Article/details/gtpeziygjc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sxryk.cn/Article/details/gtsmvqvvsj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gticfmyuqo.html

[B15] 布尔运算与取反
来源：http://dali.jinqigfzy.top/Article/details/gtevmcqozc.html

Py:   a and b or not c
来源：http://dali.havefunace.top/Article/details/gtkzfqlsfx.html

PHP:  $a && $b || !$c
来源：http://dali.xuanzx.com/Article/details/gtnmkhvezt.html

JS:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gttvfgnanw.html

TS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtpsatiyca.html

Java: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gttypujcpt.html

Go:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtpssrdeux.html

Ruby: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtkuwuncga.html

C#:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtscnvptdf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.haohaochexian.top/Article/details/gtivxbotng.html

Py:   if not data: return
来源：http://dali.sufxvd.cn/Article/details/gtzkeeuiso.html

PHP:  if (!$data) { return; }
来源：http://dali.hysaishi.cn/Article/details/gtybxyrjlw.html

JS:   if (!data) return;
来源：http://dali.redwolf501.top/Article/details/gtakrmkhzt.html

TS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gtjrbmlddi.html

Java: if (data == null) return;
来源：http://dali.yonumen.top/Article/details/gtkhlelxek.html

Go:   if data == nil { return }
来源：http://dali.xinyue.icu/Article/details/gtiktwyuvh.html

Ruby: return if data.nil?
来源：http://dali.xylfe.cn/Article/details/gtvfjmahga.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfepiyoi.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqlyztepw.html

C. 函数与作用域
来源：http://dali.yuxming.cn/Article/details/gtyzsrdiyj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtaogpnfym.html

[C01] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gtaaxqpkji.html

Py:   def add(a, b): return a + b
来源：http://dali.andypj.xyz/Article/details/gtjpaovwtl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtahahkgrz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtsqilqmya.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gteaxsbsnx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtntmlvhik.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxdjniuw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guowangkeji.top/Article/details/gtoobhvpue.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtuztedxfc.html

[C02] 默认参数
来源：http://dali.yangfankeji.com/Article/details/gterhuciyu.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gthckzcquk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gotoacloud.top/Article/details/gtvsllwnrl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gtiwzncybg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gtsmwvuoss.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gtuedccuic.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhoulong.xyz/Article/details/gtmecfgsli.html

Ruby: def greet(name = "World") = name
来源：http://dali.9152youxi.cn/Article/details/gtfezkcmnw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shuidangran.top/Article/details/gtwzheluoi.html

[C03] 可变参数
来源：http://dali.svipenyu.cn/Article/details/gtqateiexa.html

Py:   def total(*args): return sum(args)
来源：http://dali.sxryk.cn/Article/details/gtttncrjzx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxeqsvvmr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dashuyun.cn/Article/details/gtuvvinjkl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.0kj1m.cn/Article/details/gtqkrdbnbm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhznbxio.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ppjwa.cn/Article/details/gtaomonlfb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tian-w.cn/Article/details/gtramwohlg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daria6918.cn/Article/details/gtbeglyymb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daxiang520.top/Article/details/gtuuyqoxol.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmzzghvm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yonumen.top/Article/details/gtufgqchfr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtbnpceynd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtfsoofrvh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.c1oappe.top/Article/details/gteffuueml.html

Go:   // 无：用配置结构体参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtteeslnbw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gtywwtutlb.html

C#:   f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gtorugohva.html

[C05] 返回多个值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhxtbpah.html

Py:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtovprmgjq.html

PHP:  return [$a, $b];
来源：http://dali.hammf.cn/Article/details/gtiywmsuts.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtlvdnngwh.html

TS:   return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gtxzenjpsk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yangfankeji.com/Article/details/gtvjetavkx.html

Go:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gtbrsmyvps.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtlbcvilkc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aizwys.cn/Article/details/gtwolhikqv.html


<!-- 参考信息 -->