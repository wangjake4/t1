代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gtyortzmga.html

[A15] 空值判断与默认值
来源：http://dali.chenzaomai.com/Article/details/gtwrdismxi.html

Py:   value = data or "默认值"
来源：http://dali.gzhubu.top/Article/details/gtzsxdijyt.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gtchocyyvr.html

JS:   const value = data ?? "默认值";
来源：http://dali.jyoumei.cn/Article/details/gtripmzvjo.html

TS:   const value = data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gtjfwueghk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.pengpengdd.cyou/Article/details/gtwlnuprdr.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmhonygy.html

Ruby: value = data || "默认值"
来源：http://dali.fzhhl.top/Article/details/gtwsqqmdij.html

C#:   var value = data ?? "默认值";
来源：http://dali.yvedp.cn/Article/details/gtldepyvdh.html

[A16] 真假值判断规则
来源：http://dali.jlsjyb.cn/Article/details/gtoantqoeu.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvzaaeez.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.sysykeji.top/Article/details/gtedrbhhdp.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.pengpengdd.cyou/Article/details/gtytkjxqap.html

TS:   if (!x) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtttnclmgv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjkhbvhiw.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.birdmap.top/Article/details/gtthaskced.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.chenzaomai.com/Article/details/gtruhxmpis.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.pycfn.com/Article/details/gtiauvnoah.html

[A17] 位运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgotvcdir.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gthicyccgl.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.meibo888.top/Article/details/gtsuxodwnu.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gtljzdufaz.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtdwbmpfgc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzxbakmx.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtkgkfmplo.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gtgeldeaol.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gtkqizsiuz.html

[A18] 字符与 ASCII 码互转
来源：http://dali.pengpengdd.cyou/Article/details/gtarkdpaiv.html

Py:   ord("A"); chr(65)
来源：http://dali.yongpay.top/Article/details/gtqgazzavz.html

PHP:  ord("A"); chr(65)
来源：http://dali.yj20258.top/Article/details/gttgljhoao.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.fengsongda.top/Article/details/gtgdxgupgr.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gzhubu.top/Article/details/gtgfejrzgn.html

Java: (int) 'A'; (char) 65
来源：http://dali.cqqwz.cn/Article/details/gtnxhldjzk.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hongshengwenyu.top/Article/details/gtdkfskvdj.html

Ruby: "A".ord; 65.chr
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcvraybz.html

C#:   (int)'A'; (char)65
来源：http://dali.jyoumei.cn/Article/details/gtttkfmano.html

[A19] 交换两个变量
来源：http://dali.ybcxt.top/Article/details/gtgfalvcla.html

Py:   a, b = b, a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfnjwvgh.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zycfv.cn/Article/details/gtwnqxbmvg.html

JS:   [a, b] = [b, a];
来源：http://dali.jinqigfzy.top/Article/details/gttjwipabw.html

TS:   [a, b] = [b, a];
来源：http://dali.yj202588.top/Article/details/gtjbhfetjy.html

Java: int t = a; a = b; b = t;
来源：http://dali.ybcxt.top/Article/details/gtnfozenni.html

Go:   a, b = b, a
来源：http://dali.ybcxt.top/Article/details/gttvxrxzyl.html

Ruby: a, b = b, a
来源：http://dali.snrcjt.cn/Article/details/gtmurssywq.html

C#:   (a, b) = (b, a);
来源：http://dali.smart0.xyz/Article/details/gtjnxouzzz.html

[A20] 读取标准输入
来源：http://dali.jinqigfzy.top/Article/details/gtzucqjbpx.html

Py:   name = input("请输入：")
来源：http://dali.ehwqpu.com/Article/details/gtgjtpnalj.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinqigufen.top/Article/details/gtarzavbem.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.daria6918.cn/Article/details/gtrxylosbr.html

TS:   // Node.js：readline 模块
来源：http://dali.smart0.xyz/Article/details/gtgfsrcmqv.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.quarkkingdee.top/Article/details/gtdzbkyzax.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tian-w.cn/Article/details/gtoibxnpmw.html

Ruby: gets.chomp
来源：http://dali.jianghu66.top/Article/details/gtptpjpflk.html

C#:   Console.ReadLine();
来源：http://dali.cqqwz.cn/Article/details/gtkjdsfana.html

[A21] 保留指定小数位输出
来源：http://dali.jlsjyb.cn/Article/details/gtrtyqbilz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jqgufenzy.top/Article/details/gtqtupnxvw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.birdmap.top/Article/details/gtvppsjupi.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yj20258888.top/Article/details/gtpsryjxdt.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ivvv.top/Article/details/gtlmvmypii.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.snrcjt.cn/Article/details/gtwyvpimua.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.vqdsnc.cn/Article/details/gtifgvewvc.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gtkpvjjqjr.html

C#:   3.14159.ToString("F2")
来源：http://dali.shangyingyoupin.top/Article/details/gtnjpylghd.html

[A22] 获取字符串长度
来源：http://dali.yuxming.cn/Article/details/gtsjhetvto.html

Py:   len(s)
来源：http://dali.zhoulong.xyz/Article/details/gtzgopdjdq.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.quarkkingdee.top/Article/details/gtyyubffyg.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xziqi.cn/Article/details/gtnqlehfke.html

TS:   s.length
来源：http://dali.yonumen.top/Article/details/gtgspcadpc.html

Java: s.length()
来源：http://dali.bjfxy.top/Article/details/gtdeyuczsl.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtaaqrxhsj.html

Ruby: s.length
来源：http://dali.zhixingplan.top/Article/details/gtgohfslxr.html

C#:   s.Length
来源：http://dali.jiagoushi.top/Article/details/gtegpfmola.html

[A23] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtqokbgwod.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.kuanghao11.cn/Article/details/gtuxsvwtlk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yuxming.cn/Article/details/gtfufozpzu.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinobnmfy.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jlsjyb.cn/Article/details/gtfwxeltlg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gtyqsgsukr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jianghu66.top/Article/details/gtelgvwrph.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.sxryk.cn/Article/details/gtkxpjlgmi.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.svipenyu.cn/Article/details/gtjzporgyk.html

[A24] 去除首尾空白
来源：http://dali.iojbl.cn/Article/details/gtarnguxcv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.birdmap.top/Article/details/gtqwccgaes.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpffvapfq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shangyingyoupin.top/Article/details/gtbjaqvrnx.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuanzhike.top/Article/details/gtgxmushat.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jinqigufen.top/Article/details/gtcnfmorzg.html

Go:   strings.TrimSpace(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtczbukxfw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.fzhhl.top/Article/details/gtcphnhhsn.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.smart0.xyz/Article/details/gticqzyptu.html

[A25] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtoepoonfw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.wangdashe.top/Article/details/gtimtqmcrw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ybcxt.top/Article/details/gtugkmgqcq.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aibaodan.cn/Article/details/gtupdxynho.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhongyouzk.top/Article/details/gtnahhexzk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj202588.top/Article/details/gtvspaztdi.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shzxlz.cn/Article/details/gtyekvhvrs.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.haohaochexian.top/Article/details/gtblryxxvh.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.kuanghao11.cn/Article/details/gtdluutfqo.html

[A26] 类型转换总览
来源：http://dali.0kj1m.cn/Article/details/gtxwwqhghb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cqqwz.cn/Article/details/gtmnnpwydk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xuetiantiany.cn/Article/details/gtpiaxslrv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqztpbsl.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cdnleiting.top/Article/details/gtlmjzkbjv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jiagoushi.top/Article/details/gthdhxzvky.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.quarkkingdee.top/Article/details/gtltzfiofo.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqymqfujo.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hongshengwenyu.top/Article/details/gtmotwfdqd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtrfalgtfr.html

B. 流程控制
来源：http://dali.xuetiantiany.cn/Article/details/gtaialdifr.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtlejnihik.html

[B01] 条件判断 if / else
来源：http://dali.meibo888.top/Article/details/gtbwefplrl.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ppjwa.cn/Article/details/gtdhksywog.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfgvjjlkq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gtwtejquiu.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gtxlfeetyz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtxyckmzzn.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jinqigfzy.top/Article/details/gtifvloyfb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtndigvvsi.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gtmdlwjsny.html

[B02] 多分支 else if / elif
来源：http://dali.tanke756.top/Article/details/gtdsmongba.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhijiandao.cn/Article/details/gtunsnktdi.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdjalfrt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gtlbsgchns.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gtaldvxdkp.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ybcxt.top/Article/details/gtvikpuxmo.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhiwuduotai.top/Article/details/gtdlwifxih.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.c1oappe.top/Article/details/gtxvrtmolt.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gtgvzivxtx.html

[B03] switch / match / case
来源：http://dali.yj20258888.top/Article/details/gtzywriuvk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shzxlz.cn/Article/details/gtjwsnwegj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gtaqkofgws.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gtqyenjzey.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gtaldvgzve.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gtbisrffff.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.chenjidiqi.icu/Article/details/gtzkeusfws.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.iojbl.cn/Article/details/gtxlukakfe.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvzqaywf.html

[B04] for 计数循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetzlfiqb.html

Py:   for i in range(10): print(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmyhtwhi.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ppjwa.cn/Article/details/gtpmhtbygo.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aibaodan.cn/Article/details/gtxrnwflqg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.mhx1999.top/Article/details/gtigzfdiux.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgpxhlnb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hfpthk.cn/Article/details/gtbsiinkwp.html

Ruby: 10.times { |i| puts i }
来源：http://dali.fzhhl.top/Article/details/gtppmjefgu.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cashguo.top/Article/details/gtzdfsnlgy.html

[B05] 遍历数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gthaeskjoo.html

Py:   for item in arr: print(item)
来源：http://dali.jqgfzy.top/Article/details/gteiiwqvei.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pycfn.com/Article/details/gtmtmjbjzw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gtjvymigav.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.meibo888.top/Article/details/gtiwuodayt.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdchdetqi.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.pycfn.com/Article/details/gtfowlqxtz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cqqwz.cn/Article/details/gtafnjzfoz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gzhubu.top/Article/details/gtraoibiuo.html

[B06] 遍历字典 / 对象
来源：http://dali.zhengqikj.top/Article/details/gtadjheqlo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.havefunace.top/Article/details/gtgjixbbzr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.snrcjt.cn/Article/details/gtrxazjuhz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhixingplan.top/Article/details/gtmvakixrk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gtltcxgvca.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.meibo888.top/Article/details/gthpemrtol.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cucudq.cn/Article/details/gtvvbpvyca.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jiagoushi.top/Article/details/gtcskncxaj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgufenzy.top/Article/details/gtidpftegk.html

[B07] while 循环
来源：http://dali.gzhubu.top/Article/details/gtltkwknry.html

Py:   while i < 10: i += 1
来源：http://dali.yanxiufei.cn/Article/details/gtesehgerc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cdnleiting.top/Article/details/gtwejejerr.html

JS:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gtkfucqmti.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcupmsewf.html

Java: while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gthapddwei.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jlsjyb.cn/Article/details/gtuvlvrlmi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.kuanghao11.cn/Article/details/gtgpdoegmk.html

C#:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtagothuju.html

[B08] do-while（至少执行一次）
来源：http://dali.jianghu66.top/Article/details/gtvyfqmlan.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jqgufenzy.top/Article/details/gtcroyceyf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtaophsequ.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtkgqoubem.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtaryaqdyc.html

Java: do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtuzynigzd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.andypj.xyz/Article/details/gtnlgxdlrq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.c1oappe.top/Article/details/gtrfoljiuk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtcojcdglz.html

[B09] break 与 continue
来源：http://dali.smart0.xyz/Article/details/gttjmvbqat.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cdnleiting.top/Article/details/gtdrbkygoc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmbfxusfx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtcrnyehpb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtunjumkgv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtdmiwacxs.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.bjfxy.top/Article/details/gtextiaijv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hnqzz.top/Article/details/gtjfoskoiq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtipftbtkn.html

[B10] 遍历同时拿索引
来源：http://dali.tian-w.cn/Article/details/gtuirymbdd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hnxiangtu.top/Article/details/gtynpqhduy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zdqjudy.top/Article/details/gtigpefsdc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gtzuxktwjp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj20258.top/Article/details/gthpctvlfa.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gotoacloud.top/Article/details/gtlxkhsuzs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ppjwa.cn/Article/details/gtgxzhgkfh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenlongwang.top/Article/details/gtwyltxrxm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorhbkkvq.html

[B11] 生成数字序列 / 区间
来源：http://dali.nanxinkj.top/Article/details/gtthmzonfg.html

Py:   list(range(0, 10, 2))
来源：http://dali.svipenyu.cn/Article/details/gtwmioshqz.html

PHP:  range(0, 10, 2);
来源：http://dali.jlsjyb.cn/Article/details/gtqateugmf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gthxdfdfbr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gtstjrjnfl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jyoumei.cn/Article/details/gtbnwkijvb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shzxlz.cn/Article/details/gtanqtqduu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yangfankeji.com/Article/details/gttmuvxuzr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nanxinkj.top/Article/details/gtpymvqydx.html

[B12] 跳出多层循环
来源：http://dali.gotoacloud.top/Article/details/gtphxmmogm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tian-w.cn/Article/details/gtcruwrfmk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jqgufenzy.top/Article/details/gtxjrodsaa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtashdiklo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gtykygmeau.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gtjmpyxdsj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinqigfzy.top/Article/details/gtovaocjrc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.meibo888.top/Article/details/gtuufxqtyf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yj20258888.top/Article/details/gtpgsydwmk.html

[B13] 判断是否为数字
来源：http://dali.zycfv.cn/Article/details/gtelxaurgv.html

Py:   isinstance(x, (int, float))
来源：http://dali.ydzc1.top/Article/details/gtpwmqigiq.html

PHP:  is_numeric($x)
来源：http://dali.cdnleiting.top/Article/details/gtgexdlvum.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gtfookrhsh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gtcvzeordv.html

Java: x instanceof Number
来源：http://dali.chenlongwang.top/Article/details/gtyuonsbzz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hammf.cn/Article/details/gtqyujaipx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.haohaochexian.top/Article/details/gtkwpspzox.html

C#:   x is int or double or decimal
来源：http://dali.0kj1m.cn/Article/details/gtpxldshce.html

[B14] 判断值是否在集合内
来源：http://dali.pycfn.com/Article/details/gtudzfwhgz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenjidiqi.icu/Article/details/gtlkimvmtn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj202588.top/Article/details/gtevxccgtx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cheryme.top/Article/details/gtyksgmwzd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtnckimhwx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtghzidufj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.svipenyu.cn/Article/details/gtizaqdzlz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gtyflojejx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtbxcvxtjl.html

[B15] 布尔运算与取反
来源：http://dali.c1oappe.top/Article/details/gtdqecopqa.html

Py:   a and b or not c
来源：http://dali.cqqwz.cn/Article/details/gtebcuvqzl.html

PHP:  $a && $b || !$c
来源：http://dali.ppjwa.cn/Article/details/gtirciaaje.html

JS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gteztjwhnc.html

TS:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtarethsow.html

Java: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlrmfdwk.html

Go:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtzpryyzag.html

Ruby: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtuynakayu.html

C#:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtndtfpckl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhengqikj.top/Article/details/gtiatiapwi.html

Py:   if not data: return
来源：http://dali.xuetiantiany.cn/Article/details/gtjcpqifgt.html

PHP:  if (!$data) { return; }
来源：http://dali.xziqi.cn/Article/details/gtjsmzjqpn.html

JS:   if (!data) return;
来源：http://dali.sxryk.cn/Article/details/gthoqudwmr.html

TS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtdrrjljfs.html

Java: if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtdwlnzhyp.html

Go:   if data == nil { return }
来源：http://dali.yj202588.top/Article/details/gtrdzcokfu.html

Ruby: return if data.nil?
来源：http://dali.cdnleiting.top/Article/details/gtvuqnpgvh.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gtxsbxnnkw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwjzgrafo.html

C. 函数与作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtuvaxscjp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbychmmxr.html

[C01] 定义函数
来源：http://dali.c1oappe.top/Article/details/gtzxplwpmf.html

Py:   def add(a, b): return a + b
来源：http://dali.yanxiufei.cn/Article/details/gtnwtehmut.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gtxfwnryaz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtjofrssep.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtuuwuxehc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtflwkthmf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyguymvt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydryvrhm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtqnbuftkw.html

[C02] 默认参数
来源：http://dali.aibaodan.cn/Article/details/gtaekpdfcn.html

Py:   def greet(name="World"): return name
来源：http://dali.xziqi.cn/Article/details/gtroznxrol.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pycfn.com/Article/details/gtzbinnlje.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtvcdhbjoy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gtjnljyyid.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuanzx.com/Article/details/gtwcyplkfp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dashuyun.cn/Article/details/gtwedkugpb.html

Ruby: def greet(name = "World") = name
来源：http://dali.yvedp.cn/Article/details/gtosxdmbec.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hongshengwenyu.top/Article/details/gtycoqlgws.html

[C03] 可变参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnmpfrnf.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxinkj.top/Article/details/gttwnkkjkp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.kuanghao11.cn/Article/details/gtdadncppq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtnickfeln.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtnuujwjyb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlanmfihl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.vqdsnc.cn/Article/details/gttxmjofit.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sysykeji.top/Article/details/gtrclbuliv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.andypj.xyz/Article/details/gtcwgfixip.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibbqepci.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sysykeji.top/Article/details/gtalzpsnjv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pycfn.com/Article/details/gtafxasozs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gtvnyzmfnp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.haohaochexian.top/Article/details/gtsoagerks.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sxryk.cn/Article/details/gtkaqoudgs.html

Go:   // 无：用配置结构体参数
来源：http://dali.9152youxi.cn/Article/details/gtqrhiskuq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gthxxwcenn.html

C#:   f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gthrfqymzv.html

[C05] 返回多个值
来源：http://dali.smart0.xyz/Article/details/gttvmmrbwv.html

Py:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtxitqkyfr.html

PHP:  return [$a, $b];
来源：http://dali.pycfn.com/Article/details/gthntxdgnz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gtfvyssrwt.html

TS:   return { a, b };
来源：http://dali.chenlongwang.top/Article/details/gtzvgkrryt.html


<!-- 参考信息 -->