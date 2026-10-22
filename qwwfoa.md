代发 wailian999

Java: "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gtvhnqorvq.html

Go:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtbhihjsnq.html

Ruby: "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gtywsmxmhy.html

C#:   "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtanenrijs.html

[A14] 注释写法
来源：http://dali.hongshengwenyu.top/Article/details/gtcjinaggb.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yongpay.top/Article/details/gtganoxekr.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.chenjidiqi.icu/Article/details/gtygpxmxaq.html

JS:   // 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gtslwrihxi.html

TS:   // 单行；/* 多行 */
来源：http://dali.gzhubu.top/Article/details/gtybwjiixe.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.guannengcc.top/Article/details/gtusdegmtp.html

Go:   // 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gttsfsaezy.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.guannengcc.top/Article/details/gtfprtmxyl.html

C#:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gtnyyqwecm.html

[A15] 空值判断与默认值
来源：http://dali.jiagoushi.top/Article/details/gtpkcbvqkt.html

Py:   value = data or "默认值"
来源：http://dali.jqgufenzy.top/Article/details/gtpyufoqxh.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gtpbjxsuhk.html

JS:   const value = data ?? "默认值";
来源：http://dali.yj20258.top/Article/details/gtlkroghmo.html

TS:   const value = data ?? "默认值";
来源：http://dali.gogol.net.cn/Article/details/gtpunvzorw.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksngdjyv.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.feifeiyinyue.top/Article/details/gtjcaefqpm.html

Ruby: value = data || "默认值"
来源：http://dali.hammf.cn/Article/details/gtwplhkrui.html

C#:   var value = data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gtqoztpmxs.html

[A16] 真假值判断规则
来源：http://dali.zhoulong.xyz/Article/details/gtpaaopkwl.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hnxiangtu.top/Article/details/gtrjzxdjqz.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.sweek.top/Article/details/gtlzmlcbys.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hnxiangtu.top/Article/details/gtrridqrih.html

TS:   if (!x) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdzmpsmuj.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zdqjudy.top/Article/details/gtvkaxfnmo.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shzxlz.cn/Article/details/gtiwzxxcdi.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yj202588.top/Article/details/gtuuamozcy.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.nanxuanxn.top/Article/details/gttxwmdnuy.html

[A17] 位运算
来源：http://dali.yanxiufei.cn/Article/details/gtsmtmdtrp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtmquzidvd.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.iojbl.cn/Article/details/gtmebhspux.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gtymonjfyt.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gtkimvbxbr.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gtefbekkbc.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtxuouizvc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtfureiejv.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gtnvborern.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gtbjywdqds.html

Py:   ord("A"); chr(65)
来源：http://dali.kuanghao11.cn/Article/details/gtmfdyfsjr.html

PHP:  ord("A"); chr(65)
来源：http://dali.tian-w.cn/Article/details/gtexyyasdj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gtncfukyoj.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hywenlv.cn/Article/details/gtqofudrda.html

Java: (int) 'A'; (char) 65
来源：http://dali.jianghu66.top/Article/details/gtdjvrejel.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.mhx1999.top/Article/details/gttrtwpjmd.html

Ruby: "A".ord; 65.chr
来源：http://dali.pengpengdd.cyou/Article/details/gtxynsvnqa.html

C#:   (int)'A'; (char)65
来源：http://dali.havefunace.top/Article/details/gtnncktxng.html

[A19] 交换两个变量
来源：http://dali.gotoacloud.top/Article/details/gtfskapmds.html

Py:   a, b = b, a
来源：http://dali.wangdashe.top/Article/details/gtpyzdkabp.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shzxlz.cn/Article/details/gtdnygmklb.html

JS:   [a, b] = [b, a];
来源：http://dali.hongshengwenyu.top/Article/details/gtwmmmzxdc.html

TS:   [a, b] = [b, a];
来源：http://dali.sxryk.cn/Article/details/gtxoubxkxh.html

Java: int t = a; a = b; b = t;
来源：http://dali.wangshuangyany.cn/Article/details/gtqgoktvno.html

Go:   a, b = b, a
来源：http://dali.hfpthk.cn/Article/details/gtyangnrkt.html

Ruby: a, b = b, a
来源：http://dali.iojbl.cn/Article/details/gtgymkloto.html

C#:   (a, b) = (b, a);
来源：http://dali.daxiang520.top/Article/details/gtukhrrnqr.html

[A20] 读取标准输入
来源：http://dali.cqqwz.cn/Article/details/gtfmlexnmn.html

Py:   name = input("请输入：")
来源：http://dali.jqgufenzy.top/Article/details/gttzwcrhkv.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zdqjudy.top/Article/details/gtymhrelmw.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.wangdashe.top/Article/details/gtgyjubghj.html

TS:   // Node.js：readline 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnnjwtho.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhijiandao.cn/Article/details/gtfstkyril.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.vqdsnc.cn/Article/details/gtrduklspb.html

Ruby: gets.chomp
来源：http://dali.yuanzhike.top/Article/details/gtfbtcnwuk.html

C#:   Console.ReadLine();
来源：http://dali.zhijiandao.cn/Article/details/gtrvqywyse.html

[A21] 保留指定小数位输出
来源：http://dali.jianghu66.top/Article/details/gtfnedehfm.html

Py:   f"{3.14159:.2f}"
来源：http://dali.guannengcc.top/Article/details/gtnrdndtzp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gtuxzjqyyw.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtcbtbkcgw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gtqxdqeiam.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yj20258888.top/Article/details/gtmqbydriq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gthyvxcnuo.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yj20258888.top/Article/details/gtyfpgnqpx.html

C#:   3.14159.ToString("F2")
来源：http://dali.daria6918.cn/Article/details/gtciamabpz.html

[A22] 获取字符串长度
来源：http://dali.ydzc1.top/Article/details/gtnmefxfwj.html

Py:   len(s)
来源：http://dali.fengsongda.top/Article/details/gtntwscmlg.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.havefunace.top/Article/details/gtbyyspuqr.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.316326.xyz/Article/details/gtlojybgxv.html

TS:   s.length
来源：http://dali.0kj1m.cn/Article/details/gtdeflrend.html

Java: s.length()
来源：http://dali.pycfn.com/Article/details/gtcdinsafg.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtlpiztlpo.html

Ruby: s.length
来源：http://dali.hysaishi.cn/Article/details/gtvgphowwu.html

C#:   s.Length
来源：http://dali.snrcjt.cn/Article/details/gtxjbooeut.html

[A23] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtxjrjhcrk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhoulong.xyz/Article/details/gttxdrvcou.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yanxiufei.cn/Article/details/gtjpbceupp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.iojbl.cn/Article/details/gtihsgvcab.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jlsjyb.cn/Article/details/gtsnwmccsp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.kuanghao11.cn/Article/details/gtzbcqsrrp.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yonumen.top/Article/details/gtscjpjapc.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.daxiang520.top/Article/details/gtlfgydald.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.dianchejie.cn/Article/details/gtwazbeqdf.html

[A24] 去除首尾空白
来源：http://dali.quarkkingdee.top/Article/details/gttznfijtl.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhijiandao.cn/Article/details/gtjspxyvvx.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.0kj1m.cn/Article/details/gtwfinalhf.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj20258.top/Article/details/gtwonktnar.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenzaomai.com/Article/details/gtjsvzzaub.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.birdmap.top/Article/details/gtgjnkycdg.html

Go:   strings.TrimSpace(s)
来源：http://dali.gaohongyu789.top/Article/details/gtyzcecurv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhongyouzk.top/Article/details/gtcjaeftww.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.pengpengdd.cyou/Article/details/gttmrrnocc.html

[A25] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtozgiiftw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbaojuojs.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtxhsucnjg.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.guannengcc.top/Article/details/gtiuybfohb.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.mhx1999.top/Article/details/gthaliwsrd.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.pycfn.com/Article/details/gtcdmkkndt.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hnxiangtu.top/Article/details/gtvblguveq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.c1oappe.top/Article/details/gtzklfsouu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrdaobik.html

[A26] 类型转换总览
来源：http://dali.ehwqpu.com/Article/details/gtxtmpycjo.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sysykeji.top/Article/details/gtvzwhsagd.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.daria6918.cn/Article/details/gtdayivubv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.redwolf501.top/Article/details/gtgpbdxujt.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yueranfly.top/Article/details/gtdmlufmxu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.daxiang520.top/Article/details/gtegovkpxz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.aizwys.cn/Article/details/gtdqczazmk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.svipenyu.cn/Article/details/gtmzfmxzdl.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjouswsv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtrieginin.html

B. 流程控制
来源：http://dali.yonumen.top/Article/details/gtmdtigeyt.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtdoftcsva.html

[B01] 条件判断 if / else
来源：http://dali.cucudq.cn/Article/details/gtnownpxqx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.redwolf501.top/Article/details/gtodqkphfw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.aizwys.cn/Article/details/gtjynrhzkm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gtdxrsxawg.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ehwqpu.com/Article/details/gtycwrswrw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gtkbprhvzy.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhongyouzk.top/Article/details/gthfxruyuc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sweek.top/Article/details/gtxtcazweq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gttavjjvpd.html

[B02] 多分支 else if / elif
来源：http://dali.bjfxy.top/Article/details/gtkzyzoxsh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocptosvx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yj20258888.top/Article/details/gtbniwphcp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnsvjcik.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gogol.net.cn/Article/details/gtkegvqpfv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gtqnvtfect.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jqgfzy.top/Article/details/gtfenqtbuh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yanxiufei.cn/Article/details/gtackpdoea.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gtylivxldf.html

[B03] switch / match / case
来源：http://dali.pengpengdd.cyou/Article/details/gtivvvryjh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sysykeji.top/Article/details/gtxgrlquwk.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gtqekkvtbt.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gtfydbcnic.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtggmnxlxr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtueeakbks.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cdnleiting.top/Article/details/gtqzzafcii.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzittjpc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tianlin.xyz/Article/details/gtzqdrgjyv.html

[B04] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gtodhawgsl.html

Py:   for i in range(10): print(i)
来源：http://dali.mhx1999.top/Article/details/gthaoqtfxp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.dianchejie.cn/Article/details/gtwflvisyl.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jlsjyb.cn/Article/details/gtvfemtouw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gogol.net.cn/Article/details/gtmollwhlx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.fzhhl.top/Article/details/gtirmvzpyf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.wangshuangyany.cn/Article/details/gtbxrkfeyv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.havefunace.top/Article/details/gteewwqzhs.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.dashuyun.cn/Article/details/gtsvvrwlqp.html

[B05] 遍历数组 / 列表
来源：http://dali.nanxuanxn.top/Article/details/gtegozedgo.html

Py:   for item in arr: print(item)
来源：http://dali.shuidangran.top/Article/details/gtwrrrikqw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yvedp.cn/Article/details/gtzuutpgmy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigufen.top/Article/details/gtttfpsvjn.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gtgkzxmyef.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.daxiang520.top/Article/details/gtawsunpho.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yangfankeji.com/Article/details/gtehijdtsf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.aibaodan.cn/Article/details/gtyepuxbyg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.haohaochexian.top/Article/details/gtkppayhxe.html

[B06] 遍历字典 / 对象
来源：http://dali.0kj1m.cn/Article/details/gticbqdvco.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nanxinkj.top/Article/details/gtoeuvexel.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yangfankeji.com/Article/details/gteuccivbj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hfpthk.cn/Article/details/gtjrdgieov.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gzhubu.top/Article/details/gtudjjgmrk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.snrcjt.cn/Article/details/gttxtarauy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.bjfxy.top/Article/details/gtrsiobzrl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yvedp.cn/Article/details/gtxjrdpbfj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.daria6918.cn/Article/details/gtlqwtabzi.html

[B07] while 循环
来源：http://dali.zhongyouzk.top/Article/details/gtbngkgxrp.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiolfersk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tanke756.top/Article/details/gtufrnyawn.html

JS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauptvmix.html

TS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gttkewpqtz.html

Java: while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvhoysfqn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ivvv.top/Article/details/gteegemujg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlgaxjcw.html

C#:   while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gtsesahxez.html

[B08] do-while（至少执行一次）
来源：http://dali.smart0.xyz/Article/details/gtegvasaqy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.aibaodan.cn/Article/details/gtxqbtrchn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtuoramxbm.html

JS:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtoyayzgnb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtoqhsqbnc.html

Java: do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtcbeheplh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.9152youxi.cn/Article/details/gtbraatkjm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtfayegnrq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtfeijrlcs.html

[B09] break 与 continue
来源：http://dali.havefunace.top/Article/details/gtiykxqwdq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shzxlz.cn/Article/details/gttlnhcgbh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklvrbpsb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtelirpwmm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtpzucbbsq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlpvvbgkj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cqqwz.cn/Article/details/gtpvegdses.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cdnleiting.top/Article/details/gthgveszmy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtxbctpdjt.html

[B10] 遍历同时拿索引
来源：http://dali.daria6918.cn/Article/details/gtprthagkx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guowangkeji.top/Article/details/gtvzlitzqs.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.pycfn.com/Article/details/gtnnkyykck.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gtjsnfdyul.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hnqzz.top/Article/details/gtyevmjocr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shuidangran.top/Article/details/gtcwobsfeb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pengpengdd.cyou/Article/details/gttcpwctid.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daria6918.cn/Article/details/gtqiaqufjd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.mhx1999.top/Article/details/gtljgxduna.html

[B11] 生成数字序列 / 区间
来源：http://dali.nwbrower.top/Article/details/gthvrsnuwp.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuanzx.com/Article/details/gtszcuyxnb.html

PHP:  range(0, 10, 2);
来源：http://dali.andypj.xyz/Article/details/gtxefdawfs.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpwtvpmv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgfzy.top/Article/details/gthrlbnnue.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtndcckxbv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxuanxn.top/Article/details/gtjltjmdue.html

Ruby: (0...10).step(2).to_a
来源：http://dali.c1oappe.top/Article/details/gtoiuaxjiq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ehwqpu.com/Article/details/gtmitjkpxk.html

[B12] 跳出多层循环
来源：http://dali.dashuyun.cn/Article/details/gtglldaojq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgufenzy.top/Article/details/gtmymdelja.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.0kj1m.cn/Article/details/gtpwtrxqow.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gtnhevbaqc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gteqoljpvu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gthtzvdusa.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jiagoushi.top/Article/details/gtizpmnlbx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yanxiufei.cn/Article/details/gtumzzyhoe.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.daxiang520.top/Article/details/gtvrtinhgr.html

[B13] 判断是否为数字
来源：http://dali.hywenlv.cn/Article/details/gtnpodewza.html

Py:   isinstance(x, (int, float))
来源：http://dali.yuanzhike.top/Article/details/gtufdbmtxv.html

PHP:  is_numeric($x)
来源：http://dali.iojbl.cn/Article/details/gtrcaiblha.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gtnfokfdgk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gtwfsupoka.html

Java: x instanceof Number
来源：http://dali.redwolf501.top/Article/details/gtizwmakya.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gogol.net.cn/Article/details/gtawftprvb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnqzz.top/Article/details/gthpullyuq.html

C#:   x is int or double or decimal
来源：http://dali.pengpengdd.cyou/Article/details/gtquodohbh.html

[B14] 判断值是否在集合内
来源：http://dali.iojbl.cn/Article/details/gtedfkfdgi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzipswfo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jlsjyb.cn/Article/details/gtfrvbeeaw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtacsdvlzr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtmptsmjgc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yonumen.top/Article/details/gtftubcgjk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nanxinkj.top/Article/details/gtqxzslanm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yuanzhike.top/Article/details/gtmcjnuvqk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gthvgdxkas.html

[B15] 布尔运算与取反
来源：http://dali.aibaodan.cn/Article/details/gtzfzwdgyv.html

Py:   a and b or not c
来源：http://dali.wangdashe.top/Article/details/gtwzvasrgm.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangtech.top/Article/details/gtxexseaom.html

JS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtmeomfobs.html

TS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtabbizpgp.html

Java: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtgactbsbi.html

Go:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtngybwiyy.html

Ruby: a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtakvzmmrq.html

C#:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtnnimdimq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuanzhike.top/Article/details/gtrlpcwuck.html

Py:   if not data: return
来源：http://dali.9152youxi.cn/Article/details/gtxmtyvhpg.html

PHP:  if (!$data) { return; }
来源：http://dali.aibaodan.cn/Article/details/gtbfrtxzcn.html

JS:   if (!data) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtojjuhnxh.html

TS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gtihnfamdm.html

Java: if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gtwrecznpi.html

Go:   if data == nil { return }
来源：http://dali.snrcjt.cn/Article/details/gtrzhfordc.html

Ruby: return if data.nil?
来源：http://dali.mhx1999.top/Article/details/gtxkwtowex.html

C#:   if (data == null) return;
来源：http://dali.cqqwz.cn/Article/details/gtsijkozfq.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtdhmblnkh.html

C. 函数与作用域
来源：http://dali.guannengcc.top/Article/details/gtmdipujfj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkqpzvguv.html

[C01] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gtaoenwcbm.html

Py:   def add(a, b): return a + b
来源：http://dali.9152youxi.cn/Article/details/gtowqkwgbs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtlctjqoyh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtytmhssbl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtdekamapb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtufffavyn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.snrcjt.cn/Article/details/gtyyfmyycq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yueranfly.top/Article/details/gtqqtwohnq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtvjhrlaxs.html

[C02] 默认参数
来源：http://dali.redwolf501.top/Article/details/gtdwwnfmzm.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgufenzy.top/Article/details/gtsnxcbift.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gogol.net.cn/Article/details/gttozqivbu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gtpjwthrxg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtfithhfuz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhoulong.xyz/Article/details/gtovzaylnj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zycfv.cn/Article/details/gtpkxzoats.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszjwogyp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.aibaodan.cn/Article/details/gtjdyxjsas.html

[C03] 可变参数
来源：http://dali.jqgfzy.top/Article/details/gtedwfzftr.html

Py:   def total(*args): return sum(args)
来源：http://dali.pengpengdd.cyou/Article/details/gtboefdtea.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgufenzy.top/Article/details/gtntlhrtik.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gtzmjrphik.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gtwsttqsis.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtukexvncx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guowangkeji.top/Article/details/gtswckucfe.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgufenzy.top/Article/details/gthijbesnr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yangfankeji.com/Article/details/gtpxcjvmlt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cdnleiting.top/Article/details/gtkjbxebsf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ybcxt.top/Article/details/gtmcvrripv.html


<!-- 参考信息 -->