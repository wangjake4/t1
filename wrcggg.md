代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.sweek.top/Article/details/gtikkdculm.html

C#:   var value = data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gtrsycyulx.html

[A16] 真假值判断规则
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyeffyxh.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yvedp.cn/Article/details/gtprotcrex.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.haohaochexian.top/Article/details/gttsywgfnx.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sxryk.cn/Article/details/gtthnwfkse.html

TS:   if (!x) {}
来源：http://dali.tian-w.cn/Article/details/gtebkcwfuq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shzxlz.cn/Article/details/gtviwpjjcx.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ydzc1.top/Article/details/gtsdhjvfck.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yonumen.top/Article/details/gtjixnrdbb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqenyfuyh.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gtafnzlupc.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gtwdpftcgf.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.sweek.top/Article/details/gtqnatrkdp.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtwvzimjni.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.gaohongyu789.top/Article/details/gtpkziqsfh.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtazqklkqu.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gthchxdylv.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gthctdfzil.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gtmombfzxv.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hammf.cn/Article/details/gtrbenoyfj.html

Py:   ord("A"); chr(65)
来源：http://dali.zhiwuduotai.top/Article/details/gtmmoroees.html

PHP:  ord("A"); chr(65)
来源：http://dali.zdqjudy.top/Article/details/gtsczuywxe.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cucudq.cn/Article/details/gtugcplnfk.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.wangdashe.top/Article/details/gtqsyzlwob.html

Java: (int) 'A'; (char) 65
来源：http://dali.jianghu66.top/Article/details/gttsxtzvsc.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yangfankeji.com/Article/details/gtgutfeijf.html

Ruby: "A".ord; 65.chr
来源：http://dali.sysykeji.top/Article/details/gtbqzoitop.html

C#:   (int)'A'; (char)65
来源：http://dali.haohaochexian.top/Article/details/gtautjuktm.html

[A19] 交换两个变量
来源：http://dali.cucudq.cn/Article/details/gtjviokiod.html

Py:   a, b = b, a
来源：http://dali.nwbrower.top/Article/details/gtoumhjdux.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shangyingyoupin.top/Article/details/gtvkviijpy.html

JS:   [a, b] = [b, a];
来源：http://dali.xylfe.cn/Article/details/gtdxgopari.html

TS:   [a, b] = [b, a];
来源：http://dali.yonumen.top/Article/details/gtttdstgfr.html

Java: int t = a; a = b; b = t;
来源：http://dali.ybcxt.top/Article/details/gtbmsqvsjb.html

Go:   a, b = b, a
来源：http://dali.yj202588.top/Article/details/gtdljhupqt.html

Ruby: a, b = b, a
来源：http://dali.meibo888.top/Article/details/gtnllpmfpi.html

C#:   (a, b) = (b, a);
来源：http://dali.ehwqpu.com/Article/details/gtfwcklrsm.html

[A20] 读取标准输入
来源：http://dali.chenjidiqi.icu/Article/details/gtwzdkxyai.html

Py:   name = input("请输入：")
来源：http://dali.aibaodan.cn/Article/details/gtugteisej.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shzxlz.cn/Article/details/gtfvbsrlis.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhixingplan.top/Article/details/gtzomrynrd.html

TS:   // Node.js：readline 模块
来源：http://dali.9152youxi.cn/Article/details/gtduygemlz.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.cdnleiting.top/Article/details/gtoxddpjyi.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumzseydm.html

Ruby: gets.chomp
来源：http://dali.shzxlz.cn/Article/details/gtbqzkbigs.html

C#:   Console.ReadLine();
来源：http://dali.wangdashe.top/Article/details/gtjkaijbbk.html

[A21] 保留指定小数位输出
来源：http://dali.hnxiangtu.top/Article/details/gtiexlpdsq.html

Py:   f"{3.14159:.2f}"
来源：http://dali.9152youxi.cn/Article/details/gtndnhnuxg.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gttzeqzvmt.html

JS:   (3.14159).toFixed(2)
来源：http://dali.nanxinkj.top/Article/details/gtwdbrntnn.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gtoggvdrgx.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhixingplan.top/Article/details/gtzkcqbsiv.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gtzadljhum.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gtbsokqbpo.html

C#:   3.14159.ToString("F2")
来源：http://dali.shangyingyoupin.top/Article/details/gtfwuddenf.html

[A22] 获取字符串长度
来源：http://dali.yongpay.top/Article/details/gtbhlwbfjl.html

Py:   len(s)
来源：http://dali.ehwqpu.com/Article/details/gtgedqlvod.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xuetiantiany.cn/Article/details/gtqgowwlua.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hnqzz.top/Article/details/gtxcecntbd.html

TS:   s.length
来源：http://dali.yvedp.cn/Article/details/gtuyxaijjg.html

Java: s.length()
来源：http://dali.0kj1m.cn/Article/details/gtxqvdrqly.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yj20258888.top/Article/details/gtxscyckcq.html

Ruby: s.length
来源：http://dali.xinyue.icu/Article/details/gtrzxzplfs.html

C#:   s.Length
来源：http://dali.aibaodan.cn/Article/details/gtpkdvzxvv.html

[A23] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtyjfipdti.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.haohaochexian.top/Article/details/gtvmhrwjij.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxbznpfu.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhixingplan.top/Article/details/gtqiexxczs.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nwbrower.top/Article/details/gtlupytmsq.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlnjpuxi.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtricjaorl.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gtnoaugmcq.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xinyue.icu/Article/details/gtwmixxugh.html

[A24] 去除首尾空白
来源：http://dali.yuxming.cn/Article/details/gtojdgrpzc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.vqdsnc.cn/Article/details/gtiddesysl.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ehwqpu.com/Article/details/gtcuflujim.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuxming.cn/Article/details/gtgrbgqclh.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.c1oappe.top/Article/details/gtpcrugtdm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.c1oappe.top/Article/details/gtvifhenqp.html

Go:   strings.TrimSpace(s)
来源：http://dali.yj20258888.top/Article/details/gtndneynnv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.smart0.xyz/Article/details/gtgqdavtzc.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyltewua.html

[A25] 字符串比较
来源：http://dali.birdmap.top/Article/details/gtvmbiftdp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hammf.cn/Article/details/gtpyypolqk.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yongpay.top/Article/details/gtudqyrryj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aizwys.cn/Article/details/gthahfqquk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.316326.xyz/Article/details/gtwlbxvuht.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.guowangkeji.top/Article/details/gtcqbiyfyd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.snrcjt.cn/Article/details/gtvrpjxdir.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hysaishi.cn/Article/details/gtcqxtbafd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.redwolf501.top/Article/details/gtrscjqjgj.html

[A26] 类型转换总览
来源：http://dali.yj20258888.top/Article/details/gtfcysivse.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yuxming.cn/Article/details/gtglapeolj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjhcutuo.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.sufxvd.cn/Article/details/gtwajnydor.html

TS:   Number() String() Boolean() x as number
来源：http://dali.dashuyun.cn/Article/details/gthixzdjlt.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hnqzz.top/Article/details/gtokgyegxr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinqigufen.top/Article/details/gtmgdkfhgq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gthljmzwbj.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ppjwa.cn/Article/details/gtjvlyjrdc.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gthltqigff.html

B. 流程控制
来源：http://dali.tian-w.cn/Article/details/gtxdjjhhof.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtjpvahabc.html

[B01] 条件判断 if / else
来源：http://dali.gzhubu.top/Article/details/gtxpbofuia.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hywenlv.cn/Article/details/gtfaynaqrx.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sysykeji.top/Article/details/gthckmcxii.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gthrnqvrst.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gtcomwmmqw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtbofkrwsk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yvedp.cn/Article/details/gtiwyymvlv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hysaishi.cn/Article/details/gtfakeovuq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gtqtwzulsj.html

[B02] 多分支 else if / elif
来源：http://dali.svipenyu.cn/Article/details/gtlswkixtn.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.tian-w.cn/Article/details/gtsnuvmway.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ivvv.top/Article/details/gtqbeojqtx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sufxvd.cn/Article/details/gtdzyncffq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gttyntjkvh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.0kj1m.cn/Article/details/gtayntjyrz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ybcxt.top/Article/details/gtpgicemri.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yongpay.top/Article/details/gtappweiba.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gtajadjkzw.html

[B03] switch / match / case
来源：http://dali.havefunace.top/Article/details/gttfxofnjf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.tanke756.top/Article/details/gtklmwdujk.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gtxknijhhc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmtlrtwf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gtgmrnbgsj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gtrcmnfosz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.svipenyu.cn/Article/details/gtpeekxnxv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xuanzx.com/Article/details/gtzykqcvbv.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xinyue.icu/Article/details/gtnxagbnej.html

[B04] for 计数循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrirxkkj.html

Py:   for i in range(10): print(i)
来源：http://dali.hysaishi.cn/Article/details/gtykswezxd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.c1oappe.top/Article/details/gtriaapdrt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtikjomael.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gtspqwmhgo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenlongwang.top/Article/details/gtdvqhcmmi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.meibo888.top/Article/details/gtgsllnasc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenzaomai.com/Article/details/gtntpowtnv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yueranfly.top/Article/details/gtcnorskex.html

[B05] 遍历数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqnkmxdn.html

Py:   for item in arr: print(item)
来源：http://dali.zhiwuduotai.top/Article/details/gtqplngsux.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xuetiantiany.cn/Article/details/gtslysrhyb.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jiagoushi.top/Article/details/gtzddrukkb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gtzktdtqbm.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jqgfzy.top/Article/details/gtcytogrpe.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.sufxvd.cn/Article/details/gtjhfwcocy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.c1oappe.top/Article/details/gtkiquzrrg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenzaomai.com/Article/details/gtcddhrgca.html

[B06] 遍历字典 / 对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrslojsr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.birdmap.top/Article/details/gtjihnhlhc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jyoumei.cn/Article/details/gtdwicvuol.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sweek.top/Article/details/gtwqunmqwe.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aizwys.cn/Article/details/gtpuwyxpml.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhixingplan.top/Article/details/gtyneussmw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj20258.top/Article/details/gtohzwifsr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xuetiantiany.cn/Article/details/gtysifriim.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yuanzhike.top/Article/details/gtpaojwkpc.html

[B07] while 循环
来源：http://dali.hammf.cn/Article/details/gtbvvcogss.html

Py:   while i < 10: i += 1
来源：http://dali.redwolf501.top/Article/details/gtslxfyhfu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zycfv.cn/Article/details/gtsnfsbzlj.html

JS:   while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gtsprnrzjn.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gttmrwiqmf.html

Java: while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtsocnde.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.fengsongda.top/Article/details/gtvzdbrlam.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gaohongyu789.top/Article/details/gtxlfruixp.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtobnolali.html

[B08] do-while（至少执行一次）
来源：http://dali.shuidangran.top/Article/details/gtwgjwjfbw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhongyouzk.top/Article/details/gtoqouwgpy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj20258.top/Article/details/gtdlyscpdz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gthauorcdw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gthsdwiixh.html

Java: do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtxqwkqgjp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchsokdgy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yuxming.cn/Article/details/gttmwlrqfl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtmvqgtccx.html

[B09] break 与 continue
来源：http://dali.iojbl.cn/Article/details/gtebgbpwex.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yanxiufei.cn/Article/details/gtnhgtcqkk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtvnhhcrmr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvcqhukj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtyuelkwrq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtyzavalcj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gtiaiethdl.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenlongwang.top/Article/details/gtfuaseawd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtcoctetgs.html

[B10] 遍历同时拿索引
来源：http://dali.sysykeji.top/Article/details/gtqvrdwcqw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jlsjyb.cn/Article/details/gtsftkewcj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhcdtqfo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gtfiggkntl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gtjjedsjuk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jianghu66.top/Article/details/gtcykcikrw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cdnleiting.top/Article/details/gtzvcnzqhx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xinyue.icu/Article/details/gtnvghrreq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yangfankeji.com/Article/details/gtudkuddqz.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenzaomai.com/Article/details/gtnhlikopq.html

Py:   list(range(0, 10, 2))
来源：http://dali.guannengcc.top/Article/details/gtrtgpzbtk.html

PHP:  range(0, 10, 2);
来源：http://dali.xuanzx.com/Article/details/gtevkbpute.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtltllgfvf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gtmguxbauw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jqgfzy.top/Article/details/gtnwygubij.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yangfankeji.com/Article/details/gteljwfkob.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aibaodan.cn/Article/details/gtxxgypfsg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jianghu66.top/Article/details/gtkakxcmlj.html

[B12] 跳出多层循环
来源：http://dali.zhixingplan.top/Article/details/gtgipzxppb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yongpay.top/Article/details/gtvwvekfwr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zycfv.cn/Article/details/gtumlkwpre.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gtoqeshmep.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtxshqjasl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtmrrudubi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhiwuduotai.top/Article/details/gtyjrxdqkq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dianchejie.cn/Article/details/gtzzlozmjn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hongshengwenyu.top/Article/details/gtdzpansdj.html

[B13] 判断是否为数字
来源：http://dali.wangshuangyany.cn/Article/details/gtooulqppn.html

Py:   isinstance(x, (int, float))
来源：http://dali.jyoumei.cn/Article/details/gthwwgtgxu.html

PHP:  is_numeric($x)
来源：http://dali.xziqi.cn/Article/details/gtnlkpvlzm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtbzerpmnv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gthnoxgmgn.html

Java: x instanceof Number
来源：http://dali.yj202588.top/Article/details/gtkxqfobrr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwckjzkc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hammf.cn/Article/details/gtwkylngtq.html

C#:   x is int or double or decimal
来源：http://dali.xziqi.cn/Article/details/gtejsaffjb.html

[B14] 判断值是否在集合内
来源：http://dali.9152youxi.cn/Article/details/gtobqwevme.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcglnosb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tianlin.xyz/Article/details/gtzrlksjdc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtpcgagjtt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtjqsqjfht.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.redwolf501.top/Article/details/gtkvrwjxwb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.mhx1999.top/Article/details/gtzxgmbrki.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sysykeji.top/Article/details/gtnpjdiwyk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gtziddhcju.html

[B15] 布尔运算与取反
来源：http://dali.svipenyu.cn/Article/details/gthlvfgrhs.html

Py:   a and b or not c
来源：http://dali.fengsongda.top/Article/details/gtfkiuxdrw.html

PHP:  $a && $b || !$c
来源：http://dali.316326.xyz/Article/details/gtiogmjqac.html

JS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtgbjoirpt.html

TS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtlalujoml.html

Java: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtgbogogag.html

Go:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtiuqtetrr.html

Ruby: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtxpxvuvdn.html

C#:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtoegxvtfi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.birdmap.top/Article/details/gthmuxondw.html

Py:   if not data: return
来源：http://dali.shangyingyoupin.top/Article/details/gthdtxkmwz.html

PHP:  if (!$data) { return; }
来源：http://dali.xuanzx.com/Article/details/gtpaxyogkd.html

JS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtemzcmlmb.html

TS:   if (!data) return;
来源：http://dali.xziqi.cn/Article/details/gtrwltyjcv.html

Java: if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gtjuvrycpl.html

Go:   if data == nil { return }
来源：http://dali.shuidangran.top/Article/details/gtdzlpkxmp.html

Ruby: return if data.nil?
来源：http://dali.shangyingyoupin.top/Article/details/gtjxgxohsf.html

C#:   if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gtqucaoara.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtckdnjioi.html

C. 函数与作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtvelwiqen.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtlhwindhs.html

[C01] 定义函数
来源：http://dali.xziqi.cn/Article/details/gtgvhlclcp.html

Py:   def add(a, b): return a + b
来源：http://dali.redwolf501.top/Article/details/gtdgbzitmj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtimoojajs.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtwimsourh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahpskwfv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtrkireeqh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangdashe.top/Article/details/gtwsukwxfv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zdqjudy.top/Article/details/gtstdsmfll.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtmcdqtdjo.html

[C02] 默认参数
来源：http://dali.hfpthk.cn/Article/details/gtdfctpjwj.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpxujorc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtecnkkimj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gtypijrwqp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gtcjfoqcce.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxuanxn.top/Article/details/gtxzuacwwc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnqzz.top/Article/details/gtehualewy.html

Ruby: def greet(name = "World") = name
来源：http://dali.xylfe.cn/Article/details/gtqrchyhyb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258888.top/Article/details/gtjoyscrle.html

[C03] 可变参数
来源：http://dali.dashuyun.cn/Article/details/gtjskfblxt.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhixingplan.top/Article/details/gtpcxuaken.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fengsongda.top/Article/details/gtnhuynszt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gtusqtbfpv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gtefwqvlns.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hywenlv.cn/Article/details/gteniojlae.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gtdkmkrrac.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xziqi.cn/Article/details/gtlnbqjqzw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dianchejie.cn/Article/details/gtxrajhndw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.316326.xyz/Article/details/gtdbjwtecq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.birdmap.top/Article/details/gtvlhqkkjv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gaohongyu789.top/Article/details/gtsxzmtodx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gtxommtaag.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtutkxtwvb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shangyingyoupin.top/Article/details/gttnddrwiv.html

Go:   // 无：用配置结构体参数
来源：http://dali.hongshengwenyu.top/Article/details/gtrvpeuaeh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtgcixlxvy.html

C#:   f(a: 1, b: 2)
来源：http://dali.sweek.top/Article/details/gtroirymhy.html

[C05] 返回多个值
来源：http://dali.pycfn.com/Article/details/gtfyynfduk.html

Py:   return a, b
来源：http://dali.bjfxy.top/Article/details/gtaoeoyfmc.html

PHP:  return [$a, $b];
来源：http://dali.zhixingplan.top/Article/details/gtafjrfyle.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.redwolf501.top/Article/details/gtfxijgbit.html

TS:   return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gtosnaxzpj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrxtivka.html

Go:   return a, b
来源：http://dali.zycfv.cn/Article/details/gtjopitfpw.html

Ruby: return a, b
来源：http://dali.shuidangran.top/Article/details/gtddizflzg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ybcxt.top/Article/details/gtxgqmcwbu.html

[C06] 匿名函数 / lambda
来源：http://dali.ydzc1.top/Article/details/gtnwteuuwl.html

Py:   square = lambda x: x * x
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzwfvrda.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuanzhike.top/Article/details/gtmqschruj.html

JS:   const square = x => x * x;
来源：http://dali.sweek.top/Article/details/gtcytuxrbr.html


<!-- 参考信息 -->