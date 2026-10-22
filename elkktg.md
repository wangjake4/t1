代发 wailian999

[A14] 注释写法
来源：http://dali.meibo888.top/Article/details/gt2nkpdnksr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hnxiangtu.top/Article/details/gt2jcbdrkpk.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gt2wjeqjsec.html

JS:   // 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gt2zxuxpicm.html

TS:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gt2edsueujf.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jqgufenzy.top/Article/details/gt2ocgvvkgi.html

Go:   // 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gt2reumpyyu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.bjfxy.top/Article/details/gt2wtccuesf.html

C#:   // 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gt2wevpqbde.html

[A15] 空值判断与默认值
来源：http://dali.zdqjudy.top/Article/details/gt2pjabpjgc.html

Py:   value = data or "默认值"
来源：http://dali.ppjwa.cn/Article/details/gt2cuyzwpfd.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.dianchejie.cn/Article/details/gt2jzkjrpbb.html

JS:   const value = data ?? "默认值";
来源：http://dali.nanxinkj.top/Article/details/gt2wyvzxbhk.html

TS:   const value = data ?? "默认值";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vxvzpifl.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shhciigk.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yj202588.top/Article/details/gt2hpetostp.html

Ruby: value = data || "默认值"
来源：http://dali.chenjidiqi.icu/Article/details/gt2omightjh.html

C#:   var value = data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvttitsm.html

[A16] 真假值判断规则
来源：http://dali.zdqjudy.top/Article/details/gt2fzjgkscr.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hnqzz.top/Article/details/gt2whbwbesy.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2jenhfmwm.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhoulong.xyz/Article/details/gt2sxilkgpi.html

TS:   if (!x) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2drosqpkt.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2neajweog.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jyoumei.cn/Article/details/gt2tnzvyzey.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hammf.cn/Article/details/gt2relcagpy.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.daxiang520.top/Article/details/gt2iwxluzic.html

[A17] 位运算
来源：http://dali.cdnleiting.top/Article/details/gt2ozbddqsv.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gt2fbhkejzj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xuanzx.com/Article/details/gt2ypuldrac.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gt2nkcdshwo.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gt2xffkrghl.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gt2apmrbshj.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gt2dnelvptc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gt2wygprodp.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gt2ydyjuslw.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shuidangran.top/Article/details/gt2lbngcxex.html

Py:   ord("A"); chr(65)
来源：http://dali.yj202588.top/Article/details/gt2zjktymyn.html

PHP:  ord("A"); chr(65)
来源：http://dali.snrcjt.cn/Article/details/gt2iowcmrmi.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yongpay.top/Article/details/gt2yddxcaxj.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.snrcjt.cn/Article/details/gt2rtzajouv.html

Java: (int) 'A'; (char) 65
来源：http://dali.tianlin.xyz/Article/details/gt2beqrkuiq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ydzc1.top/Article/details/gt2dkkgtuwe.html

Ruby: "A".ord; 65.chr
来源：http://dali.yangfankeji.com/Article/details/gt2hbwvxjjd.html

C#:   (int)'A'; (char)65
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ghoxupdj.html

[A19] 交换两个变量
来源：http://dali.tianlin.xyz/Article/details/gt2kuwyvkmj.html

Py:   a, b = b, a
来源：http://dali.xuetiantiany.cn/Article/details/gt2kzfxxpjo.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.wangshuangyany.cn/Article/details/gt2mgglyavc.html

JS:   [a, b] = [b, a];
来源：http://dali.jinqigufen.top/Article/details/gt2trewamoo.html

TS:   [a, b] = [b, a];
来源：http://dali.tian-w.cn/Article/details/gt2euuyizte.html

Java: int t = a; a = b; b = t;
来源：http://dali.smart0.xyz/Article/details/gt2pjizkduz.html

Go:   a, b = b, a
来源：http://dali.wangdashe.top/Article/details/gt2jcfvlqgf.html

Ruby: a, b = b, a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yemdskdd.html

C#:   (a, b) = (b, a);
来源：http://dali.hammf.cn/Article/details/gt2yskxyrpu.html

[A20] 读取标准输入
来源：http://dali.tianlin.xyz/Article/details/gt2mrodgnpo.html

Py:   name = input("请输入：")
来源：http://dali.jinqigufen.top/Article/details/gt2wjrjcxmt.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.sufxvd.cn/Article/details/gt2thpvseas.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.pengpengdd.cyou/Article/details/gt2aavblumd.html

TS:   // Node.js：readline 模块
来源：http://dali.tanke756.top/Article/details/gt2plenauxx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.mhx1999.top/Article/details/gt2jkxqkoxl.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jqgufenzy.top/Article/details/gt2uwpndjgo.html

Ruby: gets.chomp
来源：http://dali.gogol.net.cn/Article/details/gt2orukzsyr.html

C#:   Console.ReadLine();
来源：http://dali.cashguo.top/Article/details/gt2aghbutdg.html

[A21] 保留指定小数位输出
来源：http://dali.guowangkeji.top/Article/details/gt2dcfkaord.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jqgufenzy.top/Article/details/gt2fsbbmeef.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinqigufen.top/Article/details/gt2dxsqvlka.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gt2yyfcejoe.html

TS:   (3.14159).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gt2pfmqzlhk.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gt2rxynfyev.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gt2vwygasay.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2srtbruuk.html

C#:   3.14159.ToString("F2")
来源：http://dali.ppjwa.cn/Article/details/gt2nwbtnxcg.html

[A22] 获取字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwkyjcos.html

Py:   len(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2biescqpn.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.316326.xyz/Article/details/gt2spqpmcym.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.wangshuangyany.cn/Article/details/gt2bydefpcs.html

TS:   s.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2qynafqbg.html

Java: s.length()
来源：http://dali.sxryk.cn/Article/details/gt2opobtcpu.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2gjtlhxyb.html

Ruby: s.length
来源：http://dali.bjfxy.top/Article/details/gt2xpqyliju.html

C#:   s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2wlrrtyil.html

[A23] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gt2pzkvhnfc.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dtkqhnuo.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.redwolf501.top/Article/details/gt2uppvnezj.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.316326.xyz/Article/details/gt2zpumcjsz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.aibaodan.cn/Article/details/gt2nemkwcle.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmevxjmx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cdnleiting.top/Article/details/gt2olpzyrwm.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hnqzz.top/Article/details/gt2guguudhy.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.nanxinkj.top/Article/details/gt2ooyitaey.html

[A24] 去除首尾空白
来源：http://dali.zdqjudy.top/Article/details/gt2zrwnveje.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shuidangran.top/Article/details/gt2xycolhbs.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jinqigfzy.top/Article/details/gt2rnzqpxxn.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yueranfly.top/Article/details/gt2vbvnbspf.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ydzc1.top/Article/details/gt2yizkdidi.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hammf.cn/Article/details/gt2venfskzt.html

Go:   strings.TrimSpace(s)
来源：http://dali.yonumen.top/Article/details/gt2qnpkrulj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jianghu66.top/Article/details/gt2ubfzfsqv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.pycfn.com/Article/details/gt2yrhgvxjd.html

[A25] 字符串比较
来源：http://dali.yj202588.top/Article/details/gt2peyfjqsh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.nwbrower.top/Article/details/gt2zbigykwn.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jqgfzy.top/Article/details/gt2fhfbuoxt.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aibaodan.cn/Article/details/gt2zxwgbisg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.snrcjt.cn/Article/details/gt2ntixdgzu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yongpay.top/Article/details/gt2hhqtxwsc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.quarkkingdee.top/Article/details/gt2wcixotft.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jyoumei.cn/Article/details/gt2ppabiphe.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.tian-w.cn/Article/details/gt2igybrrzt.html

[A26] 类型转换总览
来源：http://dali.birdmap.top/Article/details/gt2qiyocedp.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhoulong.xyz/Article/details/gt2nwrqpbwh.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.guowangkeji.top/Article/details/gt2vynackif.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vkgshcae.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zycfv.cn/Article/details/gt2pqpyqzbw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.quarkkingdee.top/Article/details/gt2egfewvbn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hnqzz.top/Article/details/gt2tpottjah.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.dashuyun.cn/Article/details/gt2hivgxzju.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.nanxuanxn.top/Article/details/gt2iiknjwgy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pnlajana.html

B. 流程控制
来源：http://dali.yueranfly.top/Article/details/gt2xmyhrjlo.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2igftasbm.html

[B01] 条件判断 if / else
来源：http://dali.hnqzz.top/Article/details/gt2wstnydqc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ehwqpu.com/Article/details/gt2fvomdgke.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yonumen.top/Article/details/gt2ojmghyai.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gt2dwwyvjxa.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxhlmbdw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gt2yojnayxq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sweek.top/Article/details/gt2pbuqknam.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.birdmap.top/Article/details/gt2sndphbfa.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gt2qpccwcun.html

[B02] 多分支 else if / elif
来源：http://dali.cucudq.cn/Article/details/gt2koljhcqu.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jodsupbj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tdqmjbea.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gt2gkyalqol.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gt2nzoeqjbh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2mhalfrjn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhengqikj.top/Article/details/gt2rxkbxstt.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhengqikj.top/Article/details/gt2cvyrtacl.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yzlnxbem.html

[B03] switch / match / case
来源：http://dali.birdmap.top/Article/details/gt2hhcbtmqt.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xuetiantiany.cn/Article/details/gt2khhuetda.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gt2xjixmkhv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ubrjqbxt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gt2gjrcqpsu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gt2ikjnhbts.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.haohaochexian.top/Article/details/gt2jpchapzv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hnxiangtu.top/Article/details/gt2gyqeuwoq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zycfv.cn/Article/details/gt2zuiktdpg.html

[B04] for 计数循环
来源：http://dali.dianchejie.cn/Article/details/gt2cvsgkcdn.html

Py:   for i in range(10): print(i)
来源：http://dali.pycfn.com/Article/details/gt2kwalmxiw.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.pycfn.com/Article/details/gt2comvalya.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jiagoushi.top/Article/details/gt2gluylbhs.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.birdmap.top/Article/details/gt2shcvocis.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.havefunace.top/Article/details/gt2rrkxapbz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxidzman.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jiagoushi.top/Article/details/gt2jbfgldjn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shzxlz.cn/Article/details/gt2coejjxuu.html

[B05] 遍历数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gt2clteplsb.html

Py:   for item in arr: print(item)
来源：http://dali.zhengqikj.top/Article/details/gt2wogdkwya.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yuxming.cn/Article/details/gt2fpzjqaoh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xylfe.cn/Article/details/gt2dtzwxkqt.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gt2muumhtxj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cdnleiting.top/Article/details/gt2uewpgcdu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.snrcjt.cn/Article/details/gt2mndajkzg.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ybcxt.top/Article/details/gt2grewoybv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daxiang520.top/Article/details/gt2onkrrfox.html

[B06] 遍历字典 / 对象
来源：http://dali.cucudq.cn/Article/details/gt2tqqamehk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.andypj.xyz/Article/details/gt2qcnudhpy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jyoumei.cn/Article/details/gt2tuqugabo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vgcwkmri.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.316326.xyz/Article/details/gt2jgtzrttv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.aibaodan.cn/Article/details/gt2xlrfkuaq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2oftvkjlg.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.haohaochexian.top/Article/details/gt2cuflhonq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.andypj.xyz/Article/details/gt2awevhafi.html

[B07] while 循环
来源：http://dali.cdnleiting.top/Article/details/gt2bomdyssc.html

Py:   while i < 10: i += 1
来源：http://dali.fzhhl.top/Article/details/gt2qkjucrvk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.aibaodan.cn/Article/details/gt2twjlldhy.html

JS:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gt2pasqwdfs.html

TS:   while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gt2jckchzgx.html

Java: while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gt2cpjjwyan.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.smart0.xyz/Article/details/gt2igwdbrml.html

Ruby: while i < 10; i += 1; end
来源：http://dali.9152youxi.cn/Article/details/gt2qdnpdofv.html

C#:   while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gt2zpizzqfs.html

[B08] do-while（至少执行一次）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aafbbqip.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hysaishi.cn/Article/details/gt2ivxzuljw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.andypj.xyz/Article/details/gt2bkawvtwk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gt2jaxntkze.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmnzfgot.html

Java: do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gt2cnohofbb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.fzhhl.top/Article/details/gt2jwlwkbaw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yongpay.top/Article/details/gt2mgukkfmf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gt2jofmsyih.html

[B09] break 与 continue
来源：http://dali.vqdsnc.cn/Article/details/gt2bjbblsqo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ssssoman.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gt2hbljglfr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gt2pxulqsxg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gt2ijnbsyom.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gt2ldqohykv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yvedp.cn/Article/details/gt2vcblsasn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ybcxt.top/Article/details/gt2wkjfbuhx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txmsxuua.html

[B10] 遍历同时拿索引
来源：http://dali.chenjidiqi.icu/Article/details/gt2rwsomvia.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.birdmap.top/Article/details/gt2oclkkdrq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.meibo888.top/Article/details/gt2fvrehzey.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jyoumei.cn/Article/details/gt2lfuliqmt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gt2qyjkgqyh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.havefunace.top/Article/details/gt2efulcpzv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.quarkkingdee.top/Article/details/gt2vrpxooxc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dianchejie.cn/Article/details/gt2gtywznwk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jiagoushi.top/Article/details/gt2ssgxhbqf.html

[B11] 生成数字序列 / 区间
来源：http://dali.gogol.net.cn/Article/details/gt2sytbrxyt.html

Py:   list(range(0, 10, 2))
来源：http://dali.iojbl.cn/Article/details/gt2lewlmnnc.html

PHP:  range(0, 10, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oitoolcl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.snrcjt.cn/Article/details/gt2eehnoaah.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gt2wfibwsvi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.9152youxi.cn/Article/details/gt2osausakk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj202588.top/Article/details/gt2xpyexbob.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2mplhqkwy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nwbrower.top/Article/details/gt2nksqjjsy.html

[B12] 跳出多层循环
来源：http://dali.yj202588.top/Article/details/gt2qzvfvvou.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvpkmtft.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuetiantiany.cn/Article/details/gt2wgmateqe.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shsicsnu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gt2uhqbvahm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2feiqtiys.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.0kj1m.cn/Article/details/gt2begfvxxx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shuidangran.top/Article/details/gt2rpgkukcf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yonumen.top/Article/details/gt2qrejydds.html

[B13] 判断是否为数字
来源：http://dali.gzhubu.top/Article/details/gt2lkjgdshe.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuanzx.com/Article/details/gt2uuggqnxs.html

PHP:  is_numeric($x)
来源：http://dali.yuxming.cn/Article/details/gt2mjopetvf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2eqsjwaut.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gt2rflatpjo.html

Java: x instanceof Number
来源：http://dali.nwbrower.top/Article/details/gt2kvsqmsrx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sxryk.cn/Article/details/gt2luyrvvgh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tian-w.cn/Article/details/gt2hdlyqihe.html

C#:   x is int or double or decimal
来源：http://dali.hfpthk.cn/Article/details/gt2facxfzgj.html

[B14] 判断值是否在集合内
来源：http://dali.zhongyouzk.top/Article/details/gt2drwrddso.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zdqjudy.top/Article/details/gt2tcjiyjss.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jyoumei.cn/Article/details/gt2gxqefwgq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2apnzmovt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yangfankeji.com/Article/details/gt2coxuhfug.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2pjsuersl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2unvdfnqa.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sysykeji.top/Article/details/gt2jqcrekpl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gt2sehsimgc.html

[B15] 布尔运算与取反
来源：http://dali.feifeiyinyue.top/Article/details/gt2ztqkhean.html

Py:   a and b or not c
来源：http://dali.yueranfly.top/Article/details/gt2auyrmika.html

PHP:  $a && $b || !$c
来源：http://dali.hysaishi.cn/Article/details/gt2stwafwuv.html

JS:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2pcglaxta.html

TS:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gt2unxvcrkz.html

Java: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2myqanjtv.html

Go:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2glehyobp.html

Ruby: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2msjeucqq.html

C#:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2czgtduds.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hysaishi.cn/Article/details/gt2oyxgynzz.html

Py:   if not data: return
来源：http://dali.bjfxy.top/Article/details/gt2xvynutrz.html

PHP:  if (!$data) { return; }
来源：http://dali.haohaochexian.top/Article/details/gt2aummmjdl.html

JS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gt2mtihlobf.html

TS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gt2kdsxyjal.html

Java: if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zjpbimin.html

Go:   if data == nil { return }
来源：http://dali.hysaishi.cn/Article/details/gt2osmojmrs.html

Ruby: return if data.nil?
来源：http://dali.gotoacloud.top/Article/details/gt2bglhkhqf.html

C#:   if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gt2emztnsyn.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2oaulhvkw.html

C. 函数与作用域
来源：http://dali.yueranfly.top/Article/details/gt2znzhgvkj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2qyyhkqjm.html

[C01] 定义函数
来源：http://dali.smart0.xyz/Article/details/gt2zrazmerd.html

Py:   def add(a, b): return a + b
来源：http://dali.jyoumei.cn/Article/details/gt2myhihhgm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gt2pjlyxiuk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2ktqcaaqe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2axbopsgt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2mjrseuzl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhongyouzk.top/Article/details/gt2lqeirxcg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cucudq.cn/Article/details/gt2rkbguppo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fhpnxijw.html

[C02] 默认参数
来源：http://dali.wangdashe.top/Article/details/gt2zxpwnjrg.html

Py:   def greet(name="World"): return name
来源：http://dali.sysykeji.top/Article/details/gt2bmewviol.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ivvv.top/Article/details/gt2uztldtos.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2tieliuya.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2jalpgzpv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fengsongda.top/Article/details/gt2tgwzbppc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhengqikj.top/Article/details/gt2eydbqxno.html

Ruby: def greet(name = "World") = name
来源：http://dali.andypj.xyz/Article/details/gt2otmukcuu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yvedp.cn/Article/details/gt2qsuvwaam.html

[C03] 可变参数
来源：http://dali.ivvv.top/Article/details/gt2xnzhtipq.html

Py:   def total(*args): return sum(args)
来源：http://dali.birdmap.top/Article/details/gt2pdshlpno.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.iojbl.cn/Article/details/gt2fycxtnym.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gt2qbwqruun.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gt2zokkyybw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2wyafvsno.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sufxvd.cn/Article/details/gt2icwfwmjm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dianchejie.cn/Article/details/gt2entpsphu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hysaishi.cn/Article/details/gt2hehsczag.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yangfankeji.com/Article/details/gt2qkkqbeke.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ybcxt.top/Article/details/gt2lbsohthr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fduhzhsi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gt2vrwetefb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkfadjuv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gzhubu.top/Article/details/gt2qionjjec.html


<!-- 参考信息 -->