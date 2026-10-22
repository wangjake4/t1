代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.cheryme.top/Article/details/gtvqgoueir.html

C#:   var value = data ?? "默认值";
来源：http://dali.yangfankeji.com/Article/details/gtuuejcsze.html

[A16] 真假值判断规则
来源：http://dali.jlsjyb.cn/Article/details/gthihbsnfp.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.ybcxt.top/Article/details/gtpuhaavtl.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jyoumei.cn/Article/details/gtaqduxdgi.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhixingplan.top/Article/details/gtrhlpeaxq.html

TS:   if (!x) {}
来源：http://dali.mhx1999.top/Article/details/gtyuxwyibb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.guannengcc.top/Article/details/gttiuhjguu.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.wangdashe.top/Article/details/gtctmwsnxm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xuetiantiany.cn/Article/details/gtrodsjxtu.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.vqdsnc.cn/Article/details/gtflrhxsyv.html

[A17] 位运算
来源：http://dali.yanxiufei.cn/Article/details/gtbgnaslix.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gttgmrurwd.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmstrbbsp.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gtugaxibvw.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtfxnwaaie.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtwynuktge.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtedogokse.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtfzjbkkjc.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gtulimtaho.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yuanzhike.top/Article/details/gtphbpscuh.html

Py:   ord("A"); chr(65)
来源：http://dali.daxiang520.top/Article/details/gtfmsoyxet.html

PHP:  ord("A"); chr(65)
来源：http://dali.aibaodan.cn/Article/details/gtzcooufys.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yonumen.top/Article/details/gtutvlatyf.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xylfe.cn/Article/details/gtiyxsqnqe.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinqigfzy.top/Article/details/gtqwukhwgp.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.chenjidiqi.icu/Article/details/gtwtunrxxe.html

Ruby: "A".ord; 65.chr
来源：http://dali.gaohongyu789.top/Article/details/gtylwhdueu.html

C#:   (int)'A'; (char)65
来源：http://dali.zhiwuduotai.top/Article/details/gtjezuahon.html

[A19] 交换两个变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctlscjps.html

Py:   a, b = b, a
来源：http://dali.jqgufenzy.top/Article/details/gtqrdqjscu.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.cdnleiting.top/Article/details/gtawwmqudk.html

JS:   [a, b] = [b, a];
来源：http://dali.tanke756.top/Article/details/gtjuksaxtg.html

TS:   [a, b] = [b, a];
来源：http://dali.dianchejie.cn/Article/details/gtkwjvjgcm.html

Java: int t = a; a = b; b = t;
来源：http://dali.wangdashe.top/Article/details/gtpivhphrr.html

Go:   a, b = b, a
来源：http://dali.mhx1999.top/Article/details/gtswgtqgie.html

Ruby: a, b = b, a
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjfnerxa.html

C#:   (a, b) = (b, a);
来源：http://dali.yueranfly.top/Article/details/gtbvwrbynb.html

[A20] 读取标准输入
来源：http://dali.xziqi.cn/Article/details/gtkdnburop.html

Py:   name = input("请输入：")
来源：http://dali.ehwqpu.com/Article/details/gtpedcbpyp.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinqigfzy.top/Article/details/gteahjbwlu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ehwqpu.com/Article/details/gtogfoyeot.html

TS:   // Node.js：readline 模块
来源：http://dali.316326.xyz/Article/details/gtdjdqaukj.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.tian-w.cn/Article/details/gtwcyzwxrn.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yongpay.top/Article/details/gtlhnunnsm.html

Ruby: gets.chomp
来源：http://dali.jqgfzy.top/Article/details/gtiswwetcv.html

C#:   Console.ReadLine();
来源：http://dali.zhijiandao.cn/Article/details/gtsufmrvtq.html

[A21] 保留指定小数位输出
来源：http://dali.zdqjudy.top/Article/details/gtaoegthmi.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinqigfzy.top/Article/details/gtpuheggnc.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.smart0.xyz/Article/details/gtxgogenxv.html

JS:   (3.14159).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gtvgbxhsen.html

TS:   (3.14159).toFixed(2)
来源：http://dali.sufxvd.cn/Article/details/gtkkmjymou.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrmyeolx.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorbqcaqw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.meibo888.top/Article/details/gttmmalaii.html

C#:   3.14159.ToString("F2")
来源：http://dali.yj20258.top/Article/details/gtcvnkivnp.html

[A22] 获取字符串长度
来源：http://dali.yueranfly.top/Article/details/gtmljhofrl.html

Py:   len(s)
来源：http://dali.zhengqikj.top/Article/details/gtfrjamgxr.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.guowangkeji.top/Article/details/gtoggvvvuy.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yvedp.cn/Article/details/gtwjsvcplj.html

TS:   s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubemyqku.html

Java: s.length()
来源：http://dali.hnqzz.top/Article/details/gtqfefdblq.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.cheryme.top/Article/details/gtorgmushs.html

Ruby: s.length
来源：http://dali.jiagoushi.top/Article/details/gtcixoijgq.html

C#:   s.Length
来源：http://dali.sufxvd.cn/Article/details/gtvqpmbldu.html

[A23] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtisdoztsi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhiwuduotai.top/Article/details/gtkojwjqqn.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yvedp.cn/Article/details/gtmcirfixy.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangshuangyany.cn/Article/details/gtohxqnomt.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfyqowzv.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.kuanghao11.cn/Article/details/gtldxnzwbg.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ivvv.top/Article/details/gtbddzsgbn.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.chenzaomai.com/Article/details/gtkmcsvtuc.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.nanxinkj.top/Article/details/gtpttxsjtf.html

[A24] 去除首尾空白
来源：http://dali.sweek.top/Article/details/gtuzncijsy.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hongshengwenyu.top/Article/details/gtuhuiqksw.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.guowangkeji.top/Article/details/gtonxfihjj.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.guannengcc.top/Article/details/gtbjjxyrlc.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.316326.xyz/Article/details/gtbrwkmftk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.sweek.top/Article/details/gtjazxdnon.html

Go:   strings.TrimSpace(s)
来源：http://dali.zdqjudy.top/Article/details/gtnhvweshi.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.fzhhl.top/Article/details/gtnqevhhhb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.dashuyun.cn/Article/details/gtlzlpxidv.html

[A25] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtlzviacvc.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhongyouzk.top/Article/details/gtzyvnlugl.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.aizwys.cn/Article/details/gtysbfxkbz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258888.top/Article/details/gtfndkbias.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gzhubu.top/Article/details/gtilzkwbqz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.meibo888.top/Article/details/gtqvhfiulg.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj202588.top/Article/details/gtkardtrnm.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gzhubu.top/Article/details/gtgdttzmlb.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.9152youxi.cn/Article/details/gtcuxmguqy.html

[A26] 类型转换总览
来源：http://dali.fzhhl.top/Article/details/gtlmzuqoby.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hnqzz.top/Article/details/gtaltstxnt.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yonumen.top/Article/details/gtfwiqbvry.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.wangdashe.top/Article/details/gtcnmdlabw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yanxiufei.cn/Article/details/gtdvtuhypk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zdqjudy.top/Article/details/gtpnfcrobs.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj20258.top/Article/details/gtkyyiawmj.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.redwolf501.top/Article/details/gteshyrekq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yanxiufei.cn/Article/details/gtxlejcdeq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtlllymmft.html

B. 流程控制
来源：http://dali.chenjidiqi.icu/Article/details/gtxhhjxfzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtbcvvnevc.html

[B01] 条件判断 if / else
来源：http://dali.hysaishi.cn/Article/details/gtnverwufv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ydzc1.top/Article/details/gtyrwgqezs.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.chenzaomai.com/Article/details/gtxaeqwnnt.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gtcqpdxzel.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gtourczdku.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zycfv.cn/Article/details/gtlzksoteu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.fzhhl.top/Article/details/gtlolnmctb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hywenlv.cn/Article/details/gtoojupvql.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbyyyugy.html

[B02] 多分支 else if / elif
来源：http://dali.havefunace.top/Article/details/gtqniysxmk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.shangyingyoupin.top/Article/details/gtrhuvjkqg.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtesyunm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gtxwljoafd.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gtkdlnssdw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gtswwgsryn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gaohongyu789.top/Article/details/gtlbpmlzxm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhixingplan.top/Article/details/gtwowmoxgj.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gthixmuzlc.html

[B03] switch / match / case
来源：http://dali.nwbrower.top/Article/details/gtkcfymgoh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.9152youxi.cn/Article/details/gtdrredvbr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gtowhvmqpw.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtrosmivwb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gterjcfucq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gtxhavimsx.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtouiygurj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhixingplan.top/Article/details/gthyqoxium.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cqqwz.cn/Article/details/gtsgsajeeb.html

[B04] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gtlqqaxgci.html

Py:   for i in range(10): print(i)
来源：http://dali.redwolf501.top/Article/details/gtyljrhbzv.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinqigfzy.top/Article/details/gtfgxuyvzb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dashuyun.cn/Article/details/gtdzphlcfj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.fzhhl.top/Article/details/gtdivgcohs.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zycfv.cn/Article/details/gtsoxzpckw.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xziqi.cn/Article/details/gtgydmsyia.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinqigfzy.top/Article/details/gthzloyxin.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jiagoushi.top/Article/details/gtefbherpo.html

[B05] 遍历数组 / 列表
来源：http://dali.meibo888.top/Article/details/gtcxrhaqfg.html

Py:   for item in arr: print(item)
来源：http://dali.ydzc1.top/Article/details/gtlkkthmik.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.guannengcc.top/Article/details/gtuznnbhfr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtzugdyafc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.daxiang520.top/Article/details/gtxwhgyjdb.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hnxiangtu.top/Article/details/gthtlbjqlp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jyoumei.cn/Article/details/gtvzmabrup.html

Ruby: arr.each { |item| puts item }
来源：http://dali.tian-w.cn/Article/details/gtgtnirpdz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.haohaochexian.top/Article/details/gtfzpqrece.html

[B06] 遍历字典 / 对象
来源：http://dali.cqqwz.cn/Article/details/gtwfmmzpjj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zycfv.cn/Article/details/gtjutehmbf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jianghu66.top/Article/details/gtjdhfkeem.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvxkamsf.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhiwuduotai.top/Article/details/gtlztylewh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tian-w.cn/Article/details/gtchslvubf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhixingplan.top/Article/details/gtnrotwezd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cqqwz.cn/Article/details/gtrusicjbs.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hysaishi.cn/Article/details/gtpxluyuvp.html

[B07] while 循环
来源：http://dali.ybcxt.top/Article/details/gtqegjhqhb.html

Py:   while i < 10: i += 1
来源：http://dali.ivvv.top/Article/details/gtpuipxaux.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ybcxt.top/Article/details/gtiptmfqne.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvyzueql.html

TS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkpojdgu.html

Java: while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtcztjcdmy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xylfe.cn/Article/details/gtvpoumzmp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.daria6918.cn/Article/details/gteizzrvma.html

C#:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtbhibsaey.html

[B08] do-while（至少执行一次）
来源：http://dali.cashguo.top/Article/details/gtauancrkw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.wangdashe.top/Article/details/gtbowbaufa.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtudugqsgs.html

JS:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtuecszabe.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtcjgyhafd.html

Java: do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtzxuvbryf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yonumen.top/Article/details/gtjihctqyu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nwbrower.top/Article/details/gtklswxpib.html

C#:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtzitigrjd.html

[B09] break 与 continue
来源：http://dali.nwbrower.top/Article/details/gtxvinkspv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.aibaodan.cn/Article/details/gtoeowmaom.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtpvhomttb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtlxyycoio.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtvlruixnc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtwkhwgjrb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.iojbl.cn/Article/details/gtxvttyelv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hfpthk.cn/Article/details/gtgphxmspp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtzbyekhio.html

[B10] 遍历同时拿索引
来源：http://dali.nwbrower.top/Article/details/gtljkacvgm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cqqwz.cn/Article/details/gtciogkqfs.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.smart0.xyz/Article/details/gtksvffgsv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gturgwdabf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pycfn.com/Article/details/gtbjyutsir.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ivvv.top/Article/details/gtydqpmmpy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zycfv.cn/Article/details/gtmilbxwfx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ppjwa.cn/Article/details/gtrtlhifza.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ehwqpu.com/Article/details/gtdeltuypy.html

[B11] 生成数字序列 / 区间
来源：http://dali.gogol.net.cn/Article/details/gtvipgmkin.html

Py:   list(range(0, 10, 2))
来源：http://dali.wangshuangyany.cn/Article/details/gtatuffjlb.html

PHP:  range(0, 10, 2);
来源：http://dali.svipenyu.cn/Article/details/gtemhjaegn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gtqgoqhncr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sxryk.cn/Article/details/gtimurzbwy.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gzhubu.top/Article/details/gtvvnvqwun.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ehwqpu.com/Article/details/gtczvkchbc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jqgufenzy.top/Article/details/gthbgzyadw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtejmlnzfy.html

[B12] 跳出多层循环
来源：http://dali.0kj1m.cn/Article/details/gtjbhcxunj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgufenzy.top/Article/details/gtnpptsoxp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhengqikj.top/Article/details/gtecdvgvjc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gtbtthfzpf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxatxuduh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gtrdtjfxop.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yongpay.top/Article/details/gtyfdymxzg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhixingplan.top/Article/details/gtndtvezfr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.wangshuangyany.cn/Article/details/gttrcxmuwh.html

[B13] 判断是否为数字
来源：http://dali.yj20258888.top/Article/details/gtzhcwqblf.html

Py:   isinstance(x, (int, float))
来源：http://dali.cqqwz.cn/Article/details/gtuvoqpaxo.html

PHP:  is_numeric($x)
来源：http://dali.guowangkeji.top/Article/details/gtffhnpinm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyqgiybt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgufenzy.top/Article/details/gtvcjfuupb.html

Java: x instanceof Number
来源：http://dali.hnxiangtu.top/Article/details/gtbckrpvum.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuetiantiany.cn/Article/details/gtcgzvopxw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yuxming.cn/Article/details/gtcdggahrw.html

C#:   x is int or double or decimal
来源：http://dali.yueranfly.top/Article/details/gtosnxppas.html

[B14] 判断值是否在集合内
来源：http://dali.chenlongwang.top/Article/details/gtpjidcpki.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.andypj.xyz/Article/details/gtgzuzuhzf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shuidangran.top/Article/details/gtmghvotdl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtskpjqjuc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnzfaokg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtnoxmjhsd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgufenzy.top/Article/details/gtmkmngvqe.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.316326.xyz/Article/details/gtnrylyawj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gtknbbiqqa.html

[B15] 布尔运算与取反
来源：http://dali.xziqi.cn/Article/details/gtbyqvyvig.html

Py:   a and b or not c
来源：http://dali.aibaodan.cn/Article/details/gtwfxrcmkl.html

PHP:  $a && $b || !$c
来源：http://dali.andypj.xyz/Article/details/gtsxuojrie.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtkmksuhvr.html

TS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gthzmpcjqb.html

Java: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtsopkensc.html

Go:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtpwvivvlu.html

Ruby: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtnjgdlwnb.html

C#:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtcwfgznkg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xziqi.cn/Article/details/gtxxfhrrnl.html

Py:   if not data: return
来源：http://dali.yueranfly.top/Article/details/gtrmrxfjld.html

PHP:  if (!$data) { return; }
来源：http://dali.fengsongda.top/Article/details/gtkinwjpwa.html

JS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gtjcizxbxh.html

TS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulovloxu.html

Java: if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gtltukzsib.html

Go:   if data == nil { return }
来源：http://dali.shzxlz.cn/Article/details/gtcypoycpm.html

Ruby: return if data.nil?
来源：http://dali.yueranfly.top/Article/details/gtzciekbjk.html

C#:   if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gtsgfbkzof.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtigsomtoj.html

C. 函数与作用域
来源：http://dali.vqdsnc.cn/Article/details/gtupldmumi.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtunmtlnos.html

[C01] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtdwntvjdk.html

Py:   def add(a, b): return a + b
来源：http://dali.pycfn.com/Article/details/gtyjzuuxfh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtvtpmoijz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtowotzkvx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtjhtzhoif.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtlilhtccg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.bjfxy.top/Article/details/gthvamwbcp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yangfankeji.com/Article/details/gtngtwtftx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtvjzgcioh.html

[C02] 默认参数
来源：http://dali.jianghu66.top/Article/details/gtyjqwayjo.html

Py:   def greet(name="World"): return name
来源：http://dali.hnxiangtu.top/Article/details/gtfeofmewt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sweek.top/Article/details/gtmilugnys.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtoozuynoa.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gtmyhqxszn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hammf.cn/Article/details/gtwgirdbet.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pycfn.com/Article/details/gtsgxssyxc.html

Ruby: def greet(name = "World") = name
来源：http://dali.hammf.cn/Article/details/gtohjwtgvr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guannengcc.top/Article/details/gtpsaquvqk.html

[C03] 可变参数
来源：http://dali.jqgfzy.top/Article/details/gtfkhgpavi.html

Py:   def total(*args): return sum(args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkovmkssf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gotoacloud.top/Article/details/gtwrdgefiq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtstcwpdeb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gtsyzdhrjg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guannengcc.top/Article/details/gtxreqjahk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sufxvd.cn/Article/details/gtjvoiocmw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxywyhqm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.guannengcc.top/Article/details/gtvtjohunj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yangfankeji.com/Article/details/gtjfzgqpbo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxinkj.top/Article/details/gtikhrjmvn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gtkmiamamw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtljipfyka.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhengqikj.top/Article/details/gtiycmfijz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.mhx1999.top/Article/details/gtlmadavgd.html

Go:   // 无：用配置结构体参数
来源：http://dali.mhx1999.top/Article/details/gtfymytczc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gtrgyvlexl.html

C#:   f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtinmmoxer.html

[C05] 返回多个值
来源：http://dali.dianchejie.cn/Article/details/gtswkvavot.html

Py:   return a, b
来源：http://dali.wangdashe.top/Article/details/gtgqgmyvgk.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gtsujrsbjp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tianlin.xyz/Article/details/gtfpvitxtg.html

TS:   return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtklukjfuz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinghuilouyu.cn/Article/details/gtredmnhsy.html

Go:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtmerokrhz.html

Ruby: return a, b
来源：http://dali.dashuyun.cn/Article/details/gtklfcunhm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.mhx1999.top/Article/details/gttavixpoh.html

[C06] 匿名函数 / lambda
来源：http://dali.chenzaomai.com/Article/details/gtapabqhuy.html

Py:   square = lambda x: x * x
来源：http://dali.hongshengwenyu.top/Article/details/gtltfnjipq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aibaodan.cn/Article/details/gtgadodvrt.html

JS:   const square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtjytdtazf.html


<!-- 参考信息 -->