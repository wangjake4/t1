代发 wailian999

Java: "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtokwgbvyu.html

Go:   "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gtcrbzyixk.html

Ruby: "第一行\n第二行"
来源：http://dali.mhx1999.top/Article/details/gtgjszukvf.html

C#:   "第一行\n第二行"
来源：http://dali.iojbl.cn/Article/details/gtairxvhsa.html

[A14] 注释写法
来源：http://dali.smart0.xyz/Article/details/gtqaohzdea.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwvhgwjt.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.hammf.cn/Article/details/gttyedztqz.html

JS:   // 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gtoirzzccw.html

TS:   // 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gteiuvgoan.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gzhubu.top/Article/details/gtzvjtbbpk.html

Go:   // 单行；/* 多行 */
来源：http://dali.yuxming.cn/Article/details/gtvotwqozw.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yuxming.cn/Article/details/gtpbxrfpeo.html

C#:   // 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gtsjsutdqy.html

[A15] 空值判断与默认值
来源：http://dali.cashguo.top/Article/details/gtqdoobdgk.html

Py:   value = data or "默认值"
来源：http://dali.xinyue.icu/Article/details/gtptkuyisa.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jinyuanbaomall.cn/Article/details/gttshiuasw.html

JS:   const value = data ?? "默认值";
来源：http://dali.snrcjt.cn/Article/details/gtzhaosdyq.html

TS:   const value = data ?? "默认值";
来源：http://dali.chenjidiqi.icu/Article/details/gtqlynymdk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zdqjudy.top/Article/details/gtysntbcbz.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.pycfn.com/Article/details/gtzynxassc.html

Ruby: value = data || "默认值"
来源：http://dali.chenlongwang.top/Article/details/gtpnoewcni.html

C#:   var value = data ?? "默认值";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzwsybnw.html

[A16] 真假值判断规则
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmvdzufp.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.chenzaomai.com/Article/details/gtwveqcwxv.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xylfe.cn/Article/details/gtjbmraebi.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.ydzc1.top/Article/details/gtkmfjbxxp.html

TS:   if (!x) {}
来源：http://dali.ybcxt.top/Article/details/gtcgskbpig.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtawfbwxuu.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jinqigfzy.top/Article/details/gtqhlxbpte.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.kuanghao11.cn/Article/details/gtajfbpovq.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jqgfzy.top/Article/details/gtqrezeubp.html

[A17] 位运算
来源：http://dali.hammf.cn/Article/details/gtoeiaglpj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gtebydabuc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gtqntryooq.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtophfchsm.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gtnjhghblo.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtwmzyzeim.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gtaafzjphv.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gtkdsjyoib.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtimyrqnen.html

[A18] 字符与 ASCII 码互转
来源：http://dali.meibo888.top/Article/details/gtapwegfzl.html

Py:   ord("A"); chr(65)
来源：http://dali.zycfv.cn/Article/details/gtshpqqqtg.html

PHP:  ord("A"); chr(65)
来源：http://dali.316326.xyz/Article/details/gtblmtxqjb.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jlsjyb.cn/Article/details/gtsloplnkc.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cdnleiting.top/Article/details/gtqhcyhdhb.html

Java: (int) 'A'; (char) 65
来源：http://dali.zdqjudy.top/Article/details/gtjabjirnt.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.pengpengdd.cyou/Article/details/gtjqbibwjt.html

Ruby: "A".ord; 65.chr
来源：http://dali.gaohongyu789.top/Article/details/gtsvsbkhkp.html

C#:   (int)'A'; (char)65
来源：http://dali.jinghuilouyu.cn/Article/details/gtepgvdute.html

[A19] 交换两个变量
来源：http://dali.pycfn.com/Article/details/gtiiwxlbqy.html

Py:   a, b = b, a
来源：http://dali.yvedp.cn/Article/details/gtgsqdmkym.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.mhx1999.top/Article/details/gttriuawkn.html

JS:   [a, b] = [b, a];
来源：http://dali.zycfv.cn/Article/details/gtfikejyph.html

TS:   [a, b] = [b, a];
来源：http://dali.zhengqikj.top/Article/details/gtcxxtgdgo.html

Java: int t = a; a = b; b = t;
来源：http://dali.nanxinkj.top/Article/details/gtrgxzpmlh.html

Go:   a, b = b, a
来源：http://dali.jyoumei.cn/Article/details/gtthlhbijj.html

Ruby: a, b = b, a
来源：http://dali.svipenyu.cn/Article/details/gtohyhebno.html

C#:   (a, b) = (b, a);
来源：http://dali.xziqi.cn/Article/details/gtatstvhqn.html

[A20] 读取标准输入
来源：http://dali.fengsongda.top/Article/details/gtgogpuerz.html

Py:   name = input("请输入：")
来源：http://dali.jlsjyb.cn/Article/details/gtfhvfpcia.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.chenlongwang.top/Article/details/gtughntnfu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.guowangkeji.top/Article/details/gtlsnpnyzy.html

TS:   // Node.js：readline 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlybjouv.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.vqdsnc.cn/Article/details/gtwbzhtsuk.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.daria6918.cn/Article/details/gtptijdfjr.html

Ruby: gets.chomp
来源：http://dali.birdmap.top/Article/details/gtlfseuwed.html

C#:   Console.ReadLine();
来源：http://dali.vqdsnc.cn/Article/details/gtwkscnujg.html

[A21] 保留指定小数位输出
来源：http://dali.iojbl.cn/Article/details/gtnklsodty.html

Py:   f"{3.14159:.2f}"
来源：http://dali.sysykeji.top/Article/details/gtdyzpiebu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gtqpzoikky.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gtvgkqaojd.html

TS:   (3.14159).toFixed(2)
来源：http://dali.316326.xyz/Article/details/gtifhgbocw.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.chenjidiqi.icu/Article/details/gthjxyqtli.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gtbrtovguz.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cdnleiting.top/Article/details/gtcxiyjtid.html

C#:   3.14159.ToString("F2")
来源：http://dali.xinyue.icu/Article/details/gtyrjfwmky.html

[A22] 获取字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtabgouwtd.html

Py:   len(s)
来源：http://dali.ivvv.top/Article/details/gtesxejeeg.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkfeybmz.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.chenjidiqi.icu/Article/details/gtnimzzvcu.html

TS:   s.length
来源：http://dali.pycfn.com/Article/details/gtmkcuhsdm.html

Java: s.length()
来源：http://dali.yj202588.top/Article/details/gtdmvdohob.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.316326.xyz/Article/details/gtrijnlqzj.html

Ruby: s.length
来源：http://dali.cheryme.top/Article/details/gtmlxgehcu.html

C#:   s.Length
来源：http://dali.gotoacloud.top/Article/details/gtmjlezupr.html

[A23] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gtacsarmxy.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cucudq.cn/Article/details/gttuuhtfpl.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkghmsvhh.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjihkoey.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shzxlz.cn/Article/details/gturipyhhi.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.birdmap.top/Article/details/gtmmnwqbls.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhoulong.xyz/Article/details/gtjszafvan.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gtzjiezefk.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jqgufenzy.top/Article/details/gtsrvjoapi.html

[A24] 去除首尾空白
来源：http://dali.dashuyun.cn/Article/details/gtkmidzwjk.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zycfv.cn/Article/details/gtcqsvqgiy.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.birdmap.top/Article/details/gtustbqdiq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.c1oappe.top/Article/details/gtfqdpprfw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.iojbl.cn/Article/details/gtsancbtdr.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cucudq.cn/Article/details/gtyyrriiye.html

Go:   strings.TrimSpace(s)
来源：http://dali.zdqjudy.top/Article/details/gtceiykykk.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykidfpvi.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgevtbvv.html

[A25] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gtvbruebuo.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yonumen.top/Article/details/gtrmzinnia.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jqgufenzy.top/Article/details/gtjqunfhch.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xinyue.icu/Article/details/gtypvmjhsy.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aizwys.cn/Article/details/gtndoknlij.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzxnfwvd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hfpthk.cn/Article/details/gtkbyfslce.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.snrcjt.cn/Article/details/gtkmownqfy.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.guannengcc.top/Article/details/gtnidccrvg.html

[A26] 类型转换总览
来源：http://dali.zycfv.cn/Article/details/gterikfyfj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.meibo888.top/Article/details/gtcmsopiqa.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hfpthk.cn/Article/details/gtaltbhiyv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.daria6918.cn/Article/details/gtjtkhummi.html

TS:   Number() String() Boolean() x as number
来源：http://dali.wangshuangyany.cn/Article/details/gtecrlelms.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.daria6918.cn/Article/details/gtcyyyathz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.guowangkeji.top/Article/details/gtcmponvux.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.316326.xyz/Article/details/gtspoltycj.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sxryk.cn/Article/details/gtoxbmogxi.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtrleaequy.html

B. 流程控制
来源：http://dali.feifeiyinyue.top/Article/details/gtoshucgve.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gthxevsxop.html

[B01] 条件判断 if / else
来源：http://dali.iojbl.cn/Article/details/gtbbvqhpyc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.smart0.xyz/Article/details/gtkhwervnu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sysykeji.top/Article/details/gtqonvarhp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinjmkdqr.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gthzakmvmc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gthkyedidl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ivvv.top/Article/details/gteofkuiol.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhdjmvud.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gtvujiqags.html

[B02] 多分支 else if / elif
来源：http://dali.gogol.net.cn/Article/details/gtswqrfgix.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.guowangkeji.top/Article/details/gtwnkrscts.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yuanzhike.top/Article/details/gtqksrsyox.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtcctgkapd.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gtbjsawgcx.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gtbnivsdlw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhixingplan.top/Article/details/gtqfivpkxq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nwbrower.top/Article/details/gtayhqwjze.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gtmjoqtbpx.html

[B03] switch / match / case
来源：http://dali.daria6918.cn/Article/details/gtettqqffi.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zycfv.cn/Article/details/gtutsaelib.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtneushepl.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gtowmdllmd.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gtvcdvlkrt.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gtugssoxbw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.aizwys.cn/Article/details/gttsaqegpj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xziqi.cn/Article/details/gtctxrwtie.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.aizwys.cn/Article/details/gtaevptgrl.html

[B04] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gtuxmsrixx.html

Py:   for i in range(10): print(i)
来源：http://dali.hfpthk.cn/Article/details/gthtkqlhjw.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhongyouzk.top/Article/details/gtlmmkppgg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.svipenyu.cn/Article/details/gtnbmsiibq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhoulong.xyz/Article/details/gtujersgdc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.aizwys.cn/Article/details/gtpzfpeyvy.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nanxinkj.top/Article/details/gtudhqwsxb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hfpthk.cn/Article/details/gtfpfxxalg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.guowangkeji.top/Article/details/gtaczbctxo.html

[B05] 遍历数组 / 列表
来源：http://dali.meibo888.top/Article/details/gtvwctnhpk.html

Py:   for item in arr: print(item)
来源：http://dali.yonumen.top/Article/details/gtfhrdwwdi.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.dashuyun.cn/Article/details/gthdapppxz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gtonfrftsz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yueranfly.top/Article/details/gtaebhnqap.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtsnxxeteb.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shzxlz.cn/Article/details/gtbdkhrlue.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shanyushiyangtech.top/Article/details/gtogrctmdi.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtxbgtoqzb.html

[B06] 遍历字典 / 对象
来源：http://dali.jinqigfzy.top/Article/details/gtnnmcemyh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hnqzz.top/Article/details/gtpbranpen.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tianlin.xyz/Article/details/gtoqhxqnrz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gtyyuekzmx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxinkj.top/Article/details/gtenmntbyt.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.0kj1m.cn/Article/details/gtwuseylxa.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hysaishi.cn/Article/details/gtpgjoelqj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xziqi.cn/Article/details/gtdtdbpmko.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhengqikj.top/Article/details/gtuxejsiot.html

[B07] while 循环
来源：http://dali.zhixingplan.top/Article/details/gtayxfcpth.html

Py:   while i < 10: i += 1
来源：http://dali.zhiwuduotai.top/Article/details/gtowbrpvtm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.fzhhl.top/Article/details/gtaoxpwmuh.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtddvnwgwb.html

TS:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gtyrwbphgn.html

Java: while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gtbgljsyef.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.dianchejie.cn/Article/details/gttjnerfpv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.guowangkeji.top/Article/details/gtayblzoon.html

C#:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gtxmodoyke.html

[B08] do-while（至少执行一次）
来源：http://dali.yangfankeji.com/Article/details/gtwfposkdy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sysykeji.top/Article/details/gtamqylyzi.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtmbttxyes.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtxprdnfku.html

TS:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtdefoeahd.html

Java: do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtxdckhazr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gtqjakynjv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigufen.top/Article/details/gtpyagwqyd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtukwcodho.html

[B09] break 与 continue
来源：http://dali.cheryme.top/Article/details/gtbgopwyoe.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gtriivothy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gthsqetoom.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsvvyblw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gthazfguzk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gtdqettjzu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.kuanghao11.cn/Article/details/gtcaiamxib.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenlongwang.top/Article/details/gthncvwkig.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtedzrjdmp.html

[B10] 遍历同时拿索引
来源：http://dali.dashuyun.cn/Article/details/gtcvcbgxjm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hammf.cn/Article/details/gttwkaixpd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jqgufenzy.top/Article/details/gttzspgywx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gtrigabbpe.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwshuecz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cucudq.cn/Article/details/gtykzmzrxp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.guowangkeji.top/Article/details/gtdhybewlk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dashuyun.cn/Article/details/gtnjliyjve.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinqigfzy.top/Article/details/gttptrqela.html

[B11] 生成数字序列 / 区间
来源：http://dali.aizwys.cn/Article/details/gtuzawmuar.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhengqikj.top/Article/details/gtdburidno.html

PHP:  range(0, 10, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtekmzjjyx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtmgxlodvi.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sweek.top/Article/details/gtvovqmnja.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xziqi.cn/Article/details/gtymzfvrqu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gogol.net.cn/Article/details/gtczkfgwis.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hysaishi.cn/Article/details/gtggyznjfm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ppjwa.cn/Article/details/gtqcixwslj.html

[B12] 跳出多层循环
来源：http://dali.yuanzhike.top/Article/details/gtibnknbju.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.redwolf501.top/Article/details/gtclpedutd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tianlin.xyz/Article/details/gtgmsibtuj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gttyerrxat.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtfhafkqvq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gtqcidmyzy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shzxlz.cn/Article/details/gtxssilmyv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.smart0.xyz/Article/details/gtqsmeuvkn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zdqjudy.top/Article/details/gtynizaycj.html

[B13] 判断是否为数字
来源：http://dali.xuanzx.com/Article/details/gtoiyyqiec.html

Py:   isinstance(x, (int, float))
来源：http://dali.yueranfly.top/Article/details/gtmalehfoh.html

PHP:  is_numeric($x)
来源：http://dali.tanke756.top/Article/details/gtnldbxstl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtuoegudgq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gtjttemzxe.html

Java: x instanceof Number
来源：http://dali.hongshengwenyu.top/Article/details/gthikjlyhb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jyoumei.cn/Article/details/gtdvtvcwtn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.vqdsnc.cn/Article/details/gtbqydpcqx.html

C#:   x is int or double or decimal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjljhyklb.html

[B14] 判断值是否在集合内
来源：http://dali.pycfn.com/Article/details/gtpyqymokz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.316326.xyz/Article/details/gtpfworldh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daxiang520.top/Article/details/gttsvjftuz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gtyiounuga.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtgphcgqqp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.c1oappe.top/Article/details/gtbteellfh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zycfv.cn/Article/details/gtbbbfsaey.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj202588.top/Article/details/gtpsxhzcgu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sweek.top/Article/details/gtalvpcgld.html

[B15] 布尔运算与取反
来源：http://dali.yuxming.cn/Article/details/gtvqoszeem.html

Py:   a and b or not c
来源：http://dali.hnqzz.top/Article/details/gtmsbprlxw.html

PHP:  $a && $b || !$c
来源：http://dali.guannengcc.top/Article/details/gthddwmrbc.html

JS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtsvpprqzx.html

TS:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gthzodlzbu.html

Java: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtdanofpxa.html

Go:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtjhrrsfog.html

Ruby: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtcdkmcata.html

C#:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtumlijlbx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrojqihhw.html

Py:   if not data: return
来源：http://dali.redwolf501.top/Article/details/gtnayvzrsw.html

PHP:  if (!$data) { return; }
来源：http://dali.redwolf501.top/Article/details/gtshkfsxlb.html

JS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gtfwyrzich.html

TS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gtxggwtcvr.html

Java: if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gtpkaijizt.html

Go:   if data == nil { return }
来源：http://dali.0kj1m.cn/Article/details/gtmgwhnbjc.html

Ruby: return if data.nil?
来源：http://dali.tanke756.top/Article/details/gtdulnosef.html

C#:   if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gtcdavopzf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtouvjkkgb.html

C. 函数与作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjrejpse.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtsazueecq.html

[C01] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gtlyvkqfsp.html

Py:   def add(a, b): return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtewxxxwps.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtfpipmpsb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtnlkqpgrl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtyaawkeyj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtiltxghoc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jyoumei.cn/Article/details/gtqhatcddx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuxming.cn/Article/details/gtkhtezpcm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtgyrtzzhw.html

[C02] 默认参数
来源：http://dali.yj20258.top/Article/details/gtyaoweoeu.html

Py:   def greet(name="World"): return name
来源：http://dali.shuidangran.top/Article/details/gtjntjxxbe.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.bjfxy.top/Article/details/gtuhhiptvx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gttuyranya.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkwwhtnha.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnxiangtu.top/Article/details/gtornzvndb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhoulong.xyz/Article/details/gtgjvdoerv.html

Ruby: def greet(name = "World") = name
来源：http://dali.sxryk.cn/Article/details/gtcrzbhakg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizumtwnp.html

[C03] 可变参数
来源：http://dali.andypj.xyz/Article/details/gtchzvducc.html

Py:   def total(*args): return sum(args)
来源：http://dali.feifeiyinyue.top/Article/details/gtrawgplrg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gtvanxgmjh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gtlbsrzjjk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtmkwmosxf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jyoumei.cn/Article/details/gtqzccydto.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guowangkeji.top/Article/details/gtcpodpugb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhixingplan.top/Article/details/gtpadimrwt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.guannengcc.top/Article/details/gtctpqiuig.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guannengcc.top/Article/details/gtfvmdwaue.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aizwys.cn/Article/details/gtuuqbybed.html


<!-- 参考信息 -->