代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.kuanghao11.cn/Article/details/gtqlivntbk.html

[A15] 空值判断与默认值
来源：http://dali.yueranfly.top/Article/details/gtnsmwfzsw.html

Py:   value = data or "默认值"
来源：http://dali.yueranfly.top/Article/details/gtsfcbfier.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.dashuyun.cn/Article/details/gtuavbtjew.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gtbiposgrn.html

TS:   const value = data ?? "默认值";
来源：http://dali.feifeiyinyue.top/Article/details/gtcavdjgxe.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepgnwoqo.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yueranfly.top/Article/details/gtauyufcmv.html

Ruby: value = data || "默认值"
来源：http://dali.wangshuangyany.cn/Article/details/gtbjcraeyl.html

C#:   var value = data ?? "默认值";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhtxzebv.html

[A16] 真假值判断规则
来源：http://dali.gogol.net.cn/Article/details/gtkwrffzfc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zdqjudy.top/Article/details/gtwjfsglxt.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhoulong.xyz/Article/details/gtkzsjbshl.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xylfe.cn/Article/details/gtzjmilyqm.html

TS:   if (!x) {}
来源：http://dali.daxiang520.top/Article/details/gtwbfawduk.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jiagoushi.top/Article/details/gtgsaxemzd.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.iojbl.cn/Article/details/gtgsajdrxq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hammf.cn/Article/details/gtsicyfpup.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptuqrvlv.html

[A17] 位运算
来源：http://dali.shanyushiyangtech.top/Article/details/gtoghxcpme.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvncglvi.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hnqzz.top/Article/details/gtntenhdej.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtshdlotrh.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gtayhthtxc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gtiyrlopnc.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtuqmkfulx.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtlgukvrvr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gtrsezccwy.html

[A18] 字符与 ASCII 码互转
来源：http://dali.havefunace.top/Article/details/gtzimokpww.html

Py:   ord("A"); chr(65)
来源：http://dali.xziqi.cn/Article/details/gtbtqaiwnu.html

PHP:  ord("A"); chr(65)
来源：http://dali.hnxiangtu.top/Article/details/gtkehzmmlw.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjamymgv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cheryme.top/Article/details/gtgsuoitbw.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhengqikj.top/Article/details/gtwrqxevew.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.nanxuanxn.top/Article/details/gtfqmwsrce.html

Ruby: "A".ord; 65.chr
来源：http://dali.cdnleiting.top/Article/details/gtwlmfvyns.html

C#:   (int)'A'; (char)65
来源：http://dali.jyoumei.cn/Article/details/gtcszpitbv.html

[A19] 交换两个变量
来源：http://dali.zhengqikj.top/Article/details/gtygojktxh.html

Py:   a, b = b, a
来源：http://dali.shangyingyoupin.top/Article/details/gtigocwiid.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hnxiangtu.top/Article/details/gtmuxmoump.html

JS:   [a, b] = [b, a];
来源：http://dali.gogol.net.cn/Article/details/gtsodhgqzy.html

TS:   [a, b] = [b, a];
来源：http://dali.xziqi.cn/Article/details/gtvqddjuga.html

Java: int t = a; a = b; b = t;
来源：http://dali.nanxuanxn.top/Article/details/gtxqquswcx.html

Go:   a, b = b, a
来源：http://dali.yj20258888.top/Article/details/gtdkvfwkqv.html

Ruby: a, b = b, a
来源：http://dali.xinyue.icu/Article/details/gtfhymnafj.html

C#:   (a, b) = (b, a);
来源：http://dali.xylfe.cn/Article/details/gtsxtypoxs.html

[A20] 读取标准输入
来源：http://dali.snrcjt.cn/Article/details/gtprakmurs.html

Py:   name = input("请输入：")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxheykkg.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jlsjyb.cn/Article/details/gttjacrnjp.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.tianlin.xyz/Article/details/gtsmbbleee.html

TS:   // Node.js：readline 模块
来源：http://dali.zycfv.cn/Article/details/gthedyngmy.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.gotoacloud.top/Article/details/gtgafhvixp.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.chenzaomai.com/Article/details/gtuhlpaphj.html

Ruby: gets.chomp
来源：http://dali.cdnleiting.top/Article/details/gtosreklds.html

C#:   Console.ReadLine();
来源：http://dali.zhengqikj.top/Article/details/gtjeyxuctm.html

[A21] 保留指定小数位输出
来源：http://dali.hnqzz.top/Article/details/gtwkkrratj.html

Py:   f"{3.14159:.2f}"
来源：http://dali.guowangkeji.top/Article/details/gtnslimzgc.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.tian-w.cn/Article/details/gtqjxombmk.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtodgvayjg.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yangfankeji.com/Article/details/gtixfjroqn.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gtfgmlbnfz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.aibaodan.cn/Article/details/gtvwhhpoih.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yj20258888.top/Article/details/gtetcborlc.html

C#:   3.14159.ToString("F2")
来源：http://dali.yangfankeji.com/Article/details/gttqgagrec.html

[A22] 获取字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gtcxgbkrbd.html

Py:   len(s)
来源：http://dali.yuanzhike.top/Article/details/gtobxjwody.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.nanxuanxn.top/Article/details/gtpyhdmitf.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zycfv.cn/Article/details/gtvspqvifw.html

TS:   s.length
来源：http://dali.ivvv.top/Article/details/gtnzoecllc.html

Java: s.length()
来源：http://dali.yangfankeji.com/Article/details/gtfgksjfcv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.daria6918.cn/Article/details/gtcpbvmigf.html

Ruby: s.length
来源：http://dali.chenzaomai.com/Article/details/gtmehedosm.html

C#:   s.Length
来源：http://dali.xuanzx.com/Article/details/gtnpvqslay.html

[A23] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gtigemrsrp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yangfankeji.com/Article/details/gtlwwtclvh.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jqgufenzy.top/Article/details/gtsmbqfldz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.aibaodan.cn/Article/details/gtebhzmpoz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.meibo888.top/Article/details/gtekqkwlgo.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gtbiinddfi.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yuanzhike.top/Article/details/gtapntsdaa.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhixingplan.top/Article/details/gtwalvxgar.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayxboivq.html

[A24] 去除首尾空白
来源：http://dali.daxiang520.top/Article/details/gtrhhsihww.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shangyingyoupin.top/Article/details/gtxcouohwq.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.sufxvd.cn/Article/details/gtjjaagkqt.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.iojbl.cn/Article/details/gtplbyokdr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xinyue.icu/Article/details/gtdyicnmrj.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zycfv.cn/Article/details/gtrtibklfm.html

Go:   strings.TrimSpace(s)
来源：http://dali.jyoumei.cn/Article/details/gtuyracrfo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.tian-w.cn/Article/details/gtqtmfymcg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.birdmap.top/Article/details/gtifxnwtme.html

[A25] 字符串比较
来源：http://dali.ppjwa.cn/Article/details/gtcdzarxrh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.vqdsnc.cn/Article/details/gtzwsiyjxu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zycfv.cn/Article/details/gtwwyqeuwr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yvedp.cn/Article/details/gtotsveiyc.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.meibo888.top/Article/details/gtopmephel.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.tianlin.xyz/Article/details/gtwzwqknle.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.vqdsnc.cn/Article/details/gttkkmdamg.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xuetiantiany.cn/Article/details/gtqxvyncob.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jqgufenzy.top/Article/details/gttabwpzoz.html

[A26] 类型转换总览
来源：http://dali.mhx1999.top/Article/details/gtdmfdfqtp.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.tian-w.cn/Article/details/gtjobnyixd.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zdqjudy.top/Article/details/gtmecdamni.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cashguo.top/Article/details/gtzenuimtn.html

TS:   Number() String() Boolean() x as number
来源：http://dali.bjfxy.top/Article/details/gtosnuxnwu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.aizwys.cn/Article/details/gtkaxavysp.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.c1oappe.top/Article/details/gtuvpbnbua.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cheryme.top/Article/details/gtqqiedjfm.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sweek.top/Article/details/gtdlovrbxn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gthqfleojz.html

B. 流程控制
来源：http://dali.nanxinkj.top/Article/details/gtkjympqkn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtvmtnovkz.html

[B01] 条件判断 if / else
来源：http://dali.xuetiantiany.cn/Article/details/gtnvzyfreo.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.fengsongda.top/Article/details/gtntvquoqk.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.iojbl.cn/Article/details/gtvbtuopdz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gttuehkuao.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gtmktwyeby.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gthetvqbqo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shzxlz.cn/Article/details/gtvindmzew.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.daxiang520.top/Article/details/gtgwwanwrl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.9152youxi.cn/Article/details/gthsvjwpjo.html

[B02] 多分支 else if / elif
来源：http://dali.vqdsnc.cn/Article/details/gtvquqwumr.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ppjwa.cn/Article/details/gtvfsknvnb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.0kj1m.cn/Article/details/gteeuefirh.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtvsllhvop.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.mhx1999.top/Article/details/gtpevhfosv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gtmljqwgyi.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yonumen.top/Article/details/gttirevtmz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yueranfly.top/Article/details/gtwoexkzpz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gtvoymahzi.html

[B03] switch / match / case
来源：http://dali.guannengcc.top/Article/details/gtjcehjtbg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.pycfn.com/Article/details/gtkccilnqz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gtxvdaqqnf.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gtxmleacqy.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfwkqayy.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtcknwywqs.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.dianchejie.cn/Article/details/gtbmmuwamf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ppjwa.cn/Article/details/gtlmnxegsl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tanke756.top/Article/details/gtipubjyxa.html

[B04] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtekacwwvr.html

Py:   for i in range(10): print(i)
来源：http://dali.chenzaomai.com/Article/details/gtvhskqfvn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxpqcvim.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.kuanghao11.cn/Article/details/gtoyqfldkf.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqodwqdr.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.mhx1999.top/Article/details/gtjthbalij.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.andypj.xyz/Article/details/gtsqlstnii.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zdqjudy.top/Article/details/gtxurhvefq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.nwbrower.top/Article/details/gtpsveozrt.html

[B05] 遍历数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gttbyorrel.html

Py:   for item in arr: print(item)
来源：http://dali.tian-w.cn/Article/details/gtqpuxysuj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinqigfzy.top/Article/details/gtabnaaxih.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.316326.xyz/Article/details/gtafgkyaym.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gtiudukfoq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnbnzcyn.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.dianchejie.cn/Article/details/gtstmxavdz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xinyue.icu/Article/details/gtzfuwrioz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgfzy.top/Article/details/gtedslictu.html

[B06] 遍历字典 / 对象
来源：http://dali.bjfxy.top/Article/details/gtmdzwgpoo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yvedp.cn/Article/details/gtkawibcgi.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.aibaodan.cn/Article/details/gtngzjffbm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gtnjuvaeah.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.snrcjt.cn/Article/details/gtnfpdsssi.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtulbdvesv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.iojbl.cn/Article/details/gtglsedqxs.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.birdmap.top/Article/details/gtvbbryyui.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ydzc1.top/Article/details/gtxtcrnbbs.html

[B07] while 循环
来源：http://dali.nanxinkj.top/Article/details/gtbfgagyea.html

Py:   while i < 10: i += 1
来源：http://dali.chenzaomai.com/Article/details/gthqjelvlw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yueranfly.top/Article/details/gtlglqbwag.html

JS:   while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gtuitvtjgc.html

TS:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gtvelwpnxl.html

Java: while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gtsicysnff.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hywenlv.cn/Article/details/gtwgdxdcpz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxinkj.top/Article/details/gtpjkjjngr.html

C#:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gtpdqosdis.html

[B08] do-while（至少执行一次）
来源：http://dali.sweek.top/Article/details/gtvpbggikx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cheryme.top/Article/details/gtfozdeely.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtciusayhe.html

JS:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtcqkrrbtl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtzhzvhaje.html

Java: do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtefmvuhbp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jqgfzy.top/Article/details/gtysgavrdy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhixingplan.top/Article/details/gtbzsxdmyi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gtikajunpn.html

[B09] break 与 continue
来源：http://dali.cheryme.top/Article/details/gtfyghhntl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jiagoushi.top/Article/details/gtqpzhvhhr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtmrnnbudn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtlplkyzui.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtazcvfmdg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtwdduzdue.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xylfe.cn/Article/details/gtgzdpattb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhoulong.xyz/Article/details/gtcpejkzdx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuejrchdl.html

[B10] 遍历同时拿索引
来源：http://dali.yvedp.cn/Article/details/gtgvmgspho.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yj202588.top/Article/details/gthwhmrfrm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj202588.top/Article/details/gtukcfnihp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hfpthk.cn/Article/details/gtuhrtakom.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hywenlv.cn/Article/details/gtaxociejc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hysaishi.cn/Article/details/gtuxdxrrbc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zdqjudy.top/Article/details/gtopmyvrwt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmejgmbn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvoqwvubr.html

[B11] 生成数字序列 / 区间
来源：http://dali.ydzc1.top/Article/details/gtjptqnoln.html

Py:   list(range(0, 10, 2))
来源：http://dali.shuidangran.top/Article/details/gtiqpxkicg.html

PHP:  range(0, 10, 2);
来源：http://dali.zhengqikj.top/Article/details/gtstihxxtj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotvtnduw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gtpwqyzkwh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.mhx1999.top/Article/details/gtsgymxizh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqtkhskz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenlongwang.top/Article/details/gtgukonahe.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.smart0.xyz/Article/details/gtcbmfsrpr.html

[B12] 跳出多层循环
来源：http://dali.chenjidiqi.icu/Article/details/gtdmcxteza.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.andypj.xyz/Article/details/gtjopweryl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.dianchejie.cn/Article/details/gtsafgffcf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtbqwlwogf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtznftdala.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gtrbozmsgo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxuanxn.top/Article/details/gtpiwhrqva.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hywenlv.cn/Article/details/gtmwbqybch.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.meibo888.top/Article/details/gtyuntjpif.html

[B13] 判断是否为数字
来源：http://dali.tianlin.xyz/Article/details/gthvfhlhlj.html

Py:   isinstance(x, (int, float))
来源：http://dali.sysykeji.top/Article/details/gtsnzedfpv.html

PHP:  is_numeric($x)
来源：http://dali.pengpengdd.cyou/Article/details/gtqbenccke.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yueranfly.top/Article/details/gtlfpqterb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gtezhlapee.html

Java: x instanceof Number
来源：http://dali.yueranfly.top/Article/details/gtwsbfjzzy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.havefunace.top/Article/details/gthvpsoefb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zycfv.cn/Article/details/gtdlujlfrh.html

C#:   x is int or double or decimal
来源：http://dali.haohaochexian.top/Article/details/gtimfkukil.html

[B14] 判断值是否在集合内
来源：http://dali.xinyue.icu/Article/details/gtqpjiwguk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnxiangtu.top/Article/details/gtcnakclfn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gotoacloud.top/Article/details/gtakdjzglv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gtwwxkmalj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gtoaowusfp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtyeemsxiu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ppjwa.cn/Article/details/gtqvhkenea.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gtfosazpcm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtindlownp.html

[B15] 布尔运算与取反
来源：http://dali.aibaodan.cn/Article/details/gtgmpwyioe.html

Py:   a and b or not c
来源：http://dali.chenjidiqi.icu/Article/details/gtvzskizlf.html

PHP:  $a && $b || !$c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptgayufa.html

JS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtiiodqwfq.html

TS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtpibfrrvh.html

Java: a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtvoqngdlq.html

Go:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtgegetjei.html

Ruby: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtzerskypo.html

C#:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtioxdipjd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhdmsavl.html

Py:   if not data: return
来源：http://dali.yongpay.top/Article/details/gtplutynyp.html

PHP:  if (!$data) { return; }
来源：http://dali.sufxvd.cn/Article/details/gtazeqhxgn.html

JS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gtvnlqhbpj.html

TS:   if (!data) return;
来源：http://dali.hnqzz.top/Article/details/gtytrmdhpj.html

Java: if (data == null) return;
来源：http://dali.nanxuanxn.top/Article/details/gtwzocllcs.html

Go:   if data == nil { return }
来源：http://dali.cashguo.top/Article/details/gtencazayl.html

Ruby: return if data.nil?
来源：http://dali.shuidangran.top/Article/details/gtlnoyeljb.html

C#:   if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gtziqguzel.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtvkveonpo.html

C. 函数与作用域
来源：http://dali.gzhubu.top/Article/details/gtxveekglf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtpnlzbulv.html

[C01] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gtfnbjrssm.html

Py:   def add(a, b): return a + b
来源：http://dali.xylfe.cn/Article/details/gtssigldul.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvaducete.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtqffkxhdo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtalhrpled.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtjbruyini.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgufenzy.top/Article/details/gtjwomhbez.html

Ruby: def add(a, b); a + b; end
来源：http://dali.c1oappe.top/Article/details/gtbbavyfds.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtjnvwarqm.html

[C02] 默认参数
来源：http://dali.zdqjudy.top/Article/details/gtjbpyrobe.html

Py:   def greet(name="World"): return name
来源：http://dali.pengpengdd.cyou/Article/details/gtpfacjmqa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjincwjhg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtbcoaiedl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtbjknbxgf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jlsjyb.cn/Article/details/gtrpfbbdgb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhixingplan.top/Article/details/gtisapypii.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxuanxn.top/Article/details/gtzmnnjnrm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nanxuanxn.top/Article/details/gthhgrxcby.html

[C03] 可变参数
来源：http://dali.0kj1m.cn/Article/details/gtpohgmykm.html

Py:   def total(*args): return sum(args)
来源：http://dali.pengpengdd.cyou/Article/details/gtvrypjccv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.quarkkingdee.top/Article/details/gtlwycgqdx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtcjwquvak.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gtnvxffmmn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yongpay.top/Article/details/gtpwndkzxt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gtfagdowxa.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nanxinkj.top/Article/details/gtedcpfjgj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gotoacloud.top/Article/details/gtxvxzyuvn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daxiang520.top/Article/details/gtmmeyczlz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.dianchejie.cn/Article/details/gtbrtrzqqn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhengqikj.top/Article/details/gtzekiguum.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtnkyvthau.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhoulong.xyz/Article/details/gtvfczsepd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigfzy.top/Article/details/gtwknvqvtk.html

Go:   // 无：用配置结构体参数
来源：http://dali.shzxlz.cn/Article/details/gturbhilav.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gtcbneoedq.html

C#:   f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gtwsilxdzl.html

[C05] 返回多个值
来源：http://dali.chenjidiqi.icu/Article/details/gtnymrxwbq.html

Py:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gtrbhiqnxl.html

PHP:  return [$a, $b];
来源：http://dali.birdmap.top/Article/details/gtodhqnthn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gtmdlqebkc.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gthfhajpii.html


<!-- 参考信息 -->