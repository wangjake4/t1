代发 wailian999

[A14] 注释写法
来源：http://dali.cqqwz.cn/Article/details/gt2tlcdxgnu.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrgsvqgp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.sysykeji.top/Article/details/gt2mbuipyjw.html

JS:   // 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gt2onspvurn.html

TS:   // 单行；/* 多行 */
来源：http://dali.svipenyu.cn/Article/details/gt2fzkntbpm.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yongpay.top/Article/details/gt2xpqocvdi.html

Go:   // 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gt2xdgzppme.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uskxhgdd.html

C#:   // 单行；/* 多行 */
来源：http://dali.yj202588.top/Article/details/gt2ulbvapxo.html

[A15] 空值判断与默认值
来源：http://dali.shuidangran.top/Article/details/gt2ubbhunxg.html

Py:   value = data or "默认值"
来源：http://dali.chenzaomai.com/Article/details/gt2wvhdsamb.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.gogol.net.cn/Article/details/gt2xruhnkty.html

JS:   const value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gt2qmyctihz.html

TS:   const value = data ?? "默认值";
来源：http://dali.yueranfly.top/Article/details/gt2cwqblbdc.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.shangyingyoupin.top/Article/details/gt2wkclhnee.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yitynvlv.html

Ruby: value = data || "默认值"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rcyforji.html

C#:   var value = data ?? "默认值";
来源：http://dali.hysaishi.cn/Article/details/gt2vghmvjel.html

[A16] 真假值判断规则
来源：http://dali.cqqwz.cn/Article/details/gt2txnrjemo.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yvedp.cn/Article/details/gt2xntqjxkl.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yueranfly.top/Article/details/gt2raqknbaa.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jianghu66.top/Article/details/gt2fqobcuei.html

TS:   if (!x) {}
来源：http://dali.fengsongda.top/Article/details/gt2zwoqldix.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.nanxinkj.top/Article/details/gt2swvcesmq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.dianchejie.cn/Article/details/gt2flwihdxp.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.kuanghao11.cn/Article/details/gt2bpnkmvwq.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yangfankeji.com/Article/details/gt2urxxvcfi.html

[A17] 位运算
来源：http://dali.hysaishi.cn/Article/details/gt2vjqfdniz.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ugskxflc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yvedp.cn/Article/details/gt2lfwlcdme.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gt2xrfhuadm.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gt2znswteak.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gt2edpqrdac.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2qehowfbf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gt2ydjnlpno.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2fsvgnnlg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.kuanghao11.cn/Article/details/gt2pdcklztz.html

Py:   ord("A"); chr(65)
来源：http://dali.hywenlv.cn/Article/details/gt2xepoijkx.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvdaryii.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sxryk.cn/Article/details/gt2xynsypep.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hywenlv.cn/Article/details/gt2vounbqcc.html

Java: (int) 'A'; (char) 65
来源：http://dali.hysaishi.cn/Article/details/gt2eqrjgbhg.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yueranfly.top/Article/details/gt2wfcrmxhr.html

Ruby: "A".ord; 65.chr
来源：http://dali.sxryk.cn/Article/details/gt2lyhncwwt.html

C#:   (int)'A'; (char)65
来源：http://dali.yongpay.top/Article/details/gt2dhatoyzm.html

[A19] 交换两个变量
来源：http://dali.yongpay.top/Article/details/gt2okegcqdx.html

Py:   a, b = b, a
来源：http://dali.hammf.cn/Article/details/gt2okuogahz.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uoxjnnnc.html

JS:   [a, b] = [b, a];
来源：http://dali.bjfxy.top/Article/details/gt2pqnwohvf.html

TS:   [a, b] = [b, a];
来源：http://dali.hysaishi.cn/Article/details/gt2oywyjcle.html

Java: int t = a; a = b; b = t;
来源：http://dali.gogol.net.cn/Article/details/gt2cymvpwyw.html

Go:   a, b = b, a
来源：http://dali.yj20258888.top/Article/details/gt2nulwxfgf.html

Ruby: a, b = b, a
来源：http://dali.tanke756.top/Article/details/gt2gtdwyodg.html

C#:   (a, b) = (b, a);
来源：http://dali.wangdashe.top/Article/details/gt2zljzfzfv.html

[A20] 读取标准输入
来源：http://dali.fengsongda.top/Article/details/gt2wumbllqi.html

Py:   name = input("请输入：")
来源：http://dali.svipenyu.cn/Article/details/gt2qmryrliw.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cqqwz.cn/Article/details/gt2jpsiywzi.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.sysykeji.top/Article/details/gt2nwvwaglm.html

TS:   // Node.js：readline 模块
来源：http://dali.dianchejie.cn/Article/details/gt2imwrnmmk.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.meibo888.top/Article/details/gt2frbowsvf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.daria6918.cn/Article/details/gt2bbvhohtr.html

Ruby: gets.chomp
来源：http://dali.jinqigfzy.top/Article/details/gt2kichvdmc.html

C#:   Console.ReadLine();
来源：http://dali.ivvv.top/Article/details/gt2wilytbce.html

[A21] 保留指定小数位输出
来源：http://dali.pycfn.com/Article/details/gt2pjegjzja.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2kymxuehk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gt2rfjmteki.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gt2waswdhnu.html

TS:   (3.14159).toFixed(2)
来源：http://dali.nanxinkj.top/Article/details/gt2fttuczmk.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gt2ouvipgvk.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.9152youxi.cn/Article/details/gt2yxrpludg.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhoulong.xyz/Article/details/gt2qlhkufgq.html

C#:   3.14159.ToString("F2")
来源：http://dali.hnxiangtu.top/Article/details/gt2wmkcwusg.html

[A22] 获取字符串长度
来源：http://dali.daria6918.cn/Article/details/gt2bzlyoxmv.html

Py:   len(s)
来源：http://dali.hywenlv.cn/Article/details/gt2ogfacctd.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.daria6918.cn/Article/details/gt2wykplzcl.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.svipenyu.cn/Article/details/gt2qbonddxu.html

TS:   s.length
来源：http://dali.meibo888.top/Article/details/gt2hafzfpld.html

Java: s.length()
来源：http://dali.cqqwz.cn/Article/details/gt2fhfkvdbx.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shuidangran.top/Article/details/gt2aliylbug.html

Ruby: s.length
来源：http://dali.daria6918.cn/Article/details/gt2epiietcj.html

C#:   s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpkjhqrd.html

[A23] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gt2jftdoctb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jianghu66.top/Article/details/gt2cldsptta.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.chenlongwang.top/Article/details/gt2tfnbyvuc.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tian-w.cn/Article/details/gt2sonkihgo.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258888.top/Article/details/gt2bwuyrtct.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhixingplan.top/Article/details/gt2eekeqqjn.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yuanzhike.top/Article/details/gt2rmlduypv.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.316326.xyz/Article/details/gt2fdjfninq.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.andypj.xyz/Article/details/gt2dwtzghqi.html

[A24] 去除首尾空白
来源：http://dali.cdnleiting.top/Article/details/gt2hawsvuol.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.andypj.xyz/Article/details/gt2pqmvpwhs.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.pycfn.com/Article/details/gt2yefwxpzs.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sweek.top/Article/details/gt2hhqiyqei.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuanzhike.top/Article/details/gt2scyphjtu.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.kuanghao11.cn/Article/details/gt2hulfdlzx.html

Go:   strings.TrimSpace(s)
来源：http://dali.cheryme.top/Article/details/gt2rawylpbv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhongyouzk.top/Article/details/gt2ywqddgcj.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ppjwa.cn/Article/details/gt2vuafmdmi.html

[A25] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gt2dkblksvc.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ehwqpu.com/Article/details/gt2qfrykrpw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.pycfn.com/Article/details/gt2wunsvuik.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj202588.top/Article/details/gt2ffxwpzsa.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuanzhike.top/Article/details/gt2mkerfoed.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jiagoushi.top/Article/details/gt2qubahcsk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hnqzz.top/Article/details/gt2ckgmczvc.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cqqwz.cn/Article/details/gt2rpgporfb.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hnxiangtu.top/Article/details/gt2ooykfjwa.html

[A26] 类型转换总览
来源：http://dali.ehwqpu.com/Article/details/gt2adkergzc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yanxiufei.cn/Article/details/gt2ztoknwka.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.havefunace.top/Article/details/gt2uzpnnmiy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ivvv.top/Article/details/gt2knwugcej.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jqgfzy.top/Article/details/gt2hxolkudh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sxryk.cn/Article/details/gt2yaopuhvn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hywenlv.cn/Article/details/gt2zckrlrrt.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.9152youxi.cn/Article/details/gt2oltgvqcp.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jiagoushi.top/Article/details/gt2ovrqbsol.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2zytedcmu.html

B. 流程控制
来源：http://dali.zhoulong.xyz/Article/details/gt2oldiocmo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2brkwngbc.html

[B01] 条件判断 if / else
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gutybvvr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cqqwz.cn/Article/details/gt2mwgvkbvk.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cashguo.top/Article/details/gt2nnflxuoe.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhiwuduotai.top/Article/details/gt2mufgzdlp.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ywoqetpa.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gt2mxddqzwr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.9152youxi.cn/Article/details/gt2byypjuqu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jyoumei.cn/Article/details/gt2lyferqgl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gt2lhmyvyvf.html

[B02] 多分支 else if / elif
来源：http://dali.wangshuangyany.cn/Article/details/gt2ksyqeoiy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zycfv.cn/Article/details/gt2vjojlshg.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcwaipgy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cqqwz.cn/Article/details/gt2esfolegl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gt2butgyxgq.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gt2pdretabr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xziqi.cn/Article/details/gt2lmhazpxs.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ybcxt.top/Article/details/gt2mqmtvzuf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gt2yubqcuij.html

[B03] switch / match / case
来源：http://dali.sysykeji.top/Article/details/gt2pbtnurbk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hysaishi.cn/Article/details/gt2yrziictr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gt2pawqxyzd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gt2lbvlfiyu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gt2ljwinrbu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gt2zimayhfx.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gt2symnvyiu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenzaomai.com/Article/details/gt2rjfcosoj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xylfe.cn/Article/details/gt2yamrbtvi.html

[B04] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gt2agctgqug.html

Py:   for i in range(10): print(i)
来源：http://dali.ybcxt.top/Article/details/gt2dchprymk.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yonumen.top/Article/details/gt2broluriu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.smart0.xyz/Article/details/gt2wypvqain.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pycfn.com/Article/details/gt2edgnsoew.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenzaomai.com/Article/details/gt2ctjdakah.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.havefunace.top/Article/details/gt2ahkwrglo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.nanxuanxn.top/Article/details/gt2lxzpukap.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.mhx1999.top/Article/details/gt2letmsiyt.html

[B05] 遍历数组 / 列表
来源：http://dali.c1oappe.top/Article/details/gt2sxzknwcz.html

Py:   for item in arr: print(item)
来源：http://dali.tianlin.xyz/Article/details/gt2kiwiwpkx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhoulong.xyz/Article/details/gt2jenjranc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ehwqpu.com/Article/details/gt2oqtyksxm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gt2ojtolssg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xuanzx.com/Article/details/gt2gsdfmlrq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ivvv.top/Article/details/gt2icycxjlo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yvedp.cn/Article/details/gt2ydxaxuhz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gotoacloud.top/Article/details/gt2clqnrsbb.html

[B06] 遍历字典 / 对象
来源：http://dali.gaohongyu789.top/Article/details/gt2edgwermw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.guowangkeji.top/Article/details/gt2grodzubx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yonumen.top/Article/details/gt2zvjtrxbg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gt2wkarssyq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zycfv.cn/Article/details/gt2rsajryvx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hammf.cn/Article/details/gt2sfwuiybf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.daxiang520.top/Article/details/gt2qijgmlfa.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ivvv.top/Article/details/gt2wcksptgg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hnxiangtu.top/Article/details/gt2ixcqfthd.html

[B07] while 循环
来源：http://dali.dianchejie.cn/Article/details/gt2yztzwwdk.html

Py:   while i < 10: i += 1
来源：http://dali.sufxvd.cn/Article/details/gt2eoediyov.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gzhubu.top/Article/details/gt2yonvostp.html

JS:   while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gt2oxhpoyym.html

TS:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ghlmxvbv.html

Java: while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gt2bbfewayg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwzyetim.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hysaishi.cn/Article/details/gt2hareolzs.html

C#:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gt2njvoossf.html

[B08] do-while（至少执行一次）
来源：http://dali.iojbl.cn/Article/details/gt2euxiojgl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.aibaodan.cn/Article/details/gt2ldiuzhrq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.guannengcc.top/Article/details/gt2mxvwdywc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gt2ozhuzqlr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccsqbwqf.html

Java: do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gt2bwasvxzq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.wangdashe.top/Article/details/gt2bqpzqpev.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwckhnna.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gt2yhvwlwxx.html

[B09] break 与 continue
来源：http://dali.sysykeji.top/Article/details/gt2eykaczbr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ivvv.top/Article/details/gt2npdjgfom.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gt2iiaqdjsk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gt2zrunjrsd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gt2aoadxsie.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gt2menlmxrh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gzhubu.top/Article/details/gt2pwppbzkp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cheryme.top/Article/details/gt2ohnyubep.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gt2aealukag.html

[B10] 遍历同时拿索引
来源：http://dali.cqqwz.cn/Article/details/gt2burpigck.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.birdmap.top/Article/details/gt2quzxmihv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ybcxt.top/Article/details/gt2wloipvlb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.guannengcc.top/Article/details/gt2hywqgxew.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hnqzz.top/Article/details/gt2bfvglwou.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tian-w.cn/Article/details/gt2fzurluch.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.bjfxy.top/Article/details/gt2nsiidjle.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2atatjdcw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.quarkkingdee.top/Article/details/gt2sldiihot.html

[B11] 生成数字序列 / 区间
来源：http://dali.yvedp.cn/Article/details/gt2azauhlve.html

Py:   list(range(0, 10, 2))
来源：http://dali.daxiang520.top/Article/details/gt2avvgbyuy.html

PHP:  range(0, 10, 2);
来源：http://dali.yuanzhike.top/Article/details/gt2ivyhhsof.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zubqytli.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gt2fnryzioy.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shzxlz.cn/Article/details/gt2efjwuqjw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.316326.xyz/Article/details/gt2bqdutera.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guowangkeji.top/Article/details/gt2teadnyni.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cdnleiting.top/Article/details/gt2lqwlgoyl.html

[B12] 跳出多层循环
来源：http://dali.zhengqikj.top/Article/details/gt2hztlhpkn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gaohongyu789.top/Article/details/gt2vregimvn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ivvv.top/Article/details/gt2aadyihns.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qlbbagqi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gt2vpauclxm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gt2xpslkyni.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gogol.net.cn/Article/details/gt2rlscpjmz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yvedp.cn/Article/details/gt2sstzrryf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzlrtif.html

[B13] 判断是否为数字
来源：http://dali.nanxinkj.top/Article/details/gt2uyqaftqp.html

Py:   isinstance(x, (int, float))
来源：http://dali.tian-w.cn/Article/details/gt2rfxiedut.html

PHP:  is_numeric($x)
来源：http://dali.dianchejie.cn/Article/details/gt2jnkmqizw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2llwyfqud.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gt2nzjudjfi.html

Java: x instanceof Number
来源：http://dali.daxiang520.top/Article/details/gt2ekygrvqu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ydzc1.top/Article/details/gt2uvxnywcj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yangfankeji.com/Article/details/gt2jozekofq.html

C#:   x is int or double or decimal
来源：http://dali.havefunace.top/Article/details/gt2gzahervv.html

[B14] 判断值是否在集合内
来源：http://dali.aizwys.cn/Article/details/gt2ovfhwhvq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuetiantiany.cn/Article/details/gt2lpxvnvbe.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daxiang520.top/Article/details/gt2hrdnmtma.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2ifjllpqr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2fngkldem.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shzxlz.cn/Article/details/gt2ucthgxdo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangdashe.top/Article/details/gt2hcuuzvaw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2btpnidue.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gt2yenioucl.html

[B15] 布尔运算与取反
来源：http://dali.zhiwuduotai.top/Article/details/gt2afdoblqq.html

Py:   a and b or not c
来源：http://dali.yj202588.top/Article/details/gt2zrplbbbb.html

PHP:  $a && $b || !$c
来源：http://dali.redwolf501.top/Article/details/gt2jeqcwgqp.html

JS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2alkplthd.html

TS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2idkjxdim.html

Java: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2zoywyxos.html

Go:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gt2xjfbvvko.html

Ruby: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2gztekmgm.html

C#:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gt2ofyxwerc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jyoumei.cn/Article/details/gt2xuzirvnd.html

Py:   if not data: return
来源：http://dali.jianghu66.top/Article/details/gt2suwtwvex.html

PHP:  if (!$data) { return; }
来源：http://dali.ivvv.top/Article/details/gt2jfdlfbqa.html

JS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gt2bwdbugrc.html

TS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gt2vkmfaucy.html

Java: if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gt2ibxrihbg.html

Go:   if data == nil { return }
来源：http://dali.sufxvd.cn/Article/details/gt2cyvspzmc.html

Ruby: return if data.nil?
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2joxbhdfi.html

C#:   if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gt2wfwqlpas.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2pllwzynr.html

C. 函数与作用域
来源：http://dali.nanxinkj.top/Article/details/gt2mpaugpsx.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2gupxibmu.html

[C01] 定义函数
来源：http://dali.yj202588.top/Article/details/gt2suipwhwu.html

Py:   def add(a, b): return a + b
来源：http://dali.yvedp.cn/Article/details/gt2dpyfsxdc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gt2jcqwtazo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2opxrfldk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2gxxevjbc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2hclovrnp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gzhubu.top/Article/details/gt2exlroodr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cucudq.cn/Article/details/gt2kfzsoqqw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugomezit.html

[C02] 默认参数
来源：http://dali.sweek.top/Article/details/gt2qntyuakd.html

Py:   def greet(name="World"): return name
来源：http://dali.sysykeji.top/Article/details/gt2uzrbbact.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gdapfohy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2ixxxbldq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2kwcwihji.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dashuyun.cn/Article/details/gt2qauplcpi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.redwolf501.top/Article/details/gt2hdurherh.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhiwuduotai.top/Article/details/gt2udkzhrjv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ybcxt.top/Article/details/gt2pixbvaoi.html

[C03] 可变参数
来源：http://dali.chenzaomai.com/Article/details/gt2bcahilfx.html

Py:   def total(*args): return sum(args)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tckzdcmp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dashuyun.cn/Article/details/gt2pyqodlcv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eauwcwdj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gt2oflkpbop.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gogol.net.cn/Article/details/gt2lcajinjd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yueranfly.top/Article/details/gt2jvpkgtwb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjygfxns.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aizwys.cn/Article/details/gt2fbehavua.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2huqeosdb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhongyouzk.top/Article/details/gt2wjzbbcup.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yueranfly.top/Article/details/gt2ogzltrhj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ngvgqusa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.andypj.xyz/Article/details/gt2iqpzktwi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbzvmctj.html


<!-- 参考信息 -->