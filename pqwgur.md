代发 wailian999

Java: "第一行\n第二行"
来源：http://dali.iojbl.cn/Article/details/gtwhzmryyd.html

Go:   "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gtetoyprje.html

Ruby: "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gtxkhwwpdc.html

C#:   "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gthnrgjrsi.html

[A14] 注释写法
来源：http://dali.zycfv.cn/Article/details/gtdhqavuvu.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jinqigfzy.top/Article/details/gtaxkrxzxj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.meibo888.top/Article/details/gtqwecthah.html

JS:   // 单行；/* 多行 */
来源：http://dali.pengpengdd.cyou/Article/details/gtblgamdfg.html

TS:   // 单行；/* 多行 */
来源：http://dali.gzhubu.top/Article/details/gtxhbieqdl.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yj20258888.top/Article/details/gtrvphacfz.html

Go:   // 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gthcpenksy.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hnxiangtu.top/Article/details/gtdyrelttp.html

C#:   // 单行；/* 多行 */
来源：http://dali.hongshengwenyu.top/Article/details/gtbzgcsdqv.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gtggbybulb.html

Py:   value = data or "默认值"
来源：http://dali.andypj.xyz/Article/details/gtlsndntoo.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.9152youxi.cn/Article/details/gtwozneprf.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbhkumue.html

TS:   const value = data ?? "默认值";
来源：http://dali.daria6918.cn/Article/details/gtzsnpjmxh.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.redwolf501.top/Article/details/gtysvuzzmd.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.chenjidiqi.icu/Article/details/gtgddduzdm.html

Ruby: value = data || "默认值"
来源：http://dali.zycfv.cn/Article/details/gtrwgrdqsg.html

C#:   var value = data ?? "默认值";
来源：http://dali.pycfn.com/Article/details/gtsbdagkww.html

[A16] 真假值判断规则
来源：http://dali.cqqwz.cn/Article/details/gtyxckcpja.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.nanxinkj.top/Article/details/gtmdqpcslf.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.chenjidiqi.icu/Article/details/gtgwgioamv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.0kj1m.cn/Article/details/gtwzktzhrp.html

TS:   if (!x) {}
来源：http://dali.tian-w.cn/Article/details/gtiisgthlv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.pycfn.com/Article/details/gtaxqwmlcn.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ydzc1.top/Article/details/gtjxmylaty.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shzxlz.cn/Article/details/gtxomktayj.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtebjnzmag.html

[A17] 位运算
来源：http://dali.yonumen.top/Article/details/gtbatszalj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gtuhiynrck.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.nanxinkj.top/Article/details/gtwxrmqxeu.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtowrwlymo.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtxwxvfqai.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtceeipylc.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gtoxvtljgg.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gtnxcikfak.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gtvqkjqmbb.html

[A18] 字符与 ASCII 码互转
来源：http://dali.iojbl.cn/Article/details/gtitophxir.html

Py:   ord("A"); chr(65)
来源：http://dali.mhx1999.top/Article/details/gtpbxhnyxi.html

PHP:  ord("A"); chr(65)
来源：http://dali.birdmap.top/Article/details/gthmvrhgeb.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shuidangran.top/Article/details/gtizvphxmb.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nanxinkj.top/Article/details/gtyppvpbvl.html

Java: (int) 'A'; (char) 65
来源：http://dali.yanxiufei.cn/Article/details/gtvpnszzwl.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.guowangkeji.top/Article/details/gtzublkbwy.html

Ruby: "A".ord; 65.chr
来源：http://dali.316326.xyz/Article/details/gtoenwkczw.html

C#:   (int)'A'; (char)65
来源：http://dali.fengsongda.top/Article/details/gtjdgrvfbr.html

[A19] 交换两个变量
来源：http://dali.jqgfzy.top/Article/details/gthwsrtkgl.html

Py:   a, b = b, a
来源：http://dali.yvedp.cn/Article/details/gtyxcwyxja.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jinghuilouyu.cn/Article/details/gtfveafyxv.html

JS:   [a, b] = [b, a];
来源：http://dali.haohaochexian.top/Article/details/gthgshmune.html

TS:   [a, b] = [b, a];
来源：http://dali.hywenlv.cn/Article/details/gtmbgvdglw.html

Java: int t = a; a = b; b = t;
来源：http://dali.dashuyun.cn/Article/details/gtjucvowvk.html

Go:   a, b = b, a
来源：http://dali.wangshuangyany.cn/Article/details/gtklkbabys.html

Ruby: a, b = b, a
来源：http://dali.hysaishi.cn/Article/details/gtzwlcgtiv.html

C#:   (a, b) = (b, a);
来源：http://dali.guannengcc.top/Article/details/gtghrnaxwl.html

[A20] 读取标准输入
来源：http://dali.pycfn.com/Article/details/gtjizozzcv.html

Py:   name = input("请输入：")
来源：http://dali.daxiang520.top/Article/details/gtwjspdhgp.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yuxming.cn/Article/details/gtxbcunmsi.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yj20258888.top/Article/details/gttvhunwxt.html

TS:   // Node.js：readline 模块
来源：http://dali.hysaishi.cn/Article/details/gtrtpbeyjm.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.tanke756.top/Article/details/gtkybmdsli.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cqqwz.cn/Article/details/gtcyadpwqu.html

Ruby: gets.chomp
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtburjghns.html

C#:   Console.ReadLine();
来源：http://dali.nanxinkj.top/Article/details/gtpblekywo.html

[A21] 保留指定小数位输出
来源：http://dali.zhiwuduotai.top/Article/details/gtgywqswen.html

Py:   f"{3.14159:.2f}"
来源：http://dali.nanxinkj.top/Article/details/gtllwgutmg.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shuidangran.top/Article/details/gtbcwnucjs.html

JS:   (3.14159).toFixed(2)
来源：http://dali.tianlin.xyz/Article/details/gtbomiysgg.html

TS:   (3.14159).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gtqaxltniy.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.redwolf501.top/Article/details/gtcxciorfv.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gtxomsnogj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gtnynoeitp.html

C#:   3.14159.ToString("F2")
来源：http://dali.chenzaomai.com/Article/details/gtwtnmnrkp.html

[A22] 获取字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gtgvampchn.html

Py:   len(s)
来源：http://dali.sweek.top/Article/details/gtprhmpdoj.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ehwqpu.com/Article/details/gtzjsrtcqb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yongpay.top/Article/details/gtqybkwgmc.html

TS:   s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtssihwxmv.html

Java: s.length()
来源：http://dali.cashguo.top/Article/details/gtlqkofbjn.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcavlehyj.html

Ruby: s.length
来源：http://dali.yuanzhike.top/Article/details/gtagjuksyf.html

C#:   s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gthpssbqtx.html

[A23] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtixlrzutf.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shuidangran.top/Article/details/gtxkrslmop.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.havefunace.top/Article/details/gtcgssersl.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangshuangyany.cn/Article/details/gtbldbvvex.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.guowangkeji.top/Article/details/gtvocwvvfk.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.aizwys.cn/Article/details/gtxoucediv.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.smart0.xyz/Article/details/gtgkyvcgxg.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gtauupxrcr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hongshengwenyu.top/Article/details/gtfiplvxsb.html

[A24] 去除首尾空白
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdybxsgln.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zycfv.cn/Article/details/gtulbqxtlj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cucudq.cn/Article/details/gtwjaooxnz.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gogol.net.cn/Article/details/gtxfgegfrv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gaohongyu789.top/Article/details/gtwffdfujc.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.feifeiyinyue.top/Article/details/gtcdcfokjt.html

Go:   strings.TrimSpace(s)
来源：http://dali.ydzc1.top/Article/details/gtmmplpblm.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yuxming.cn/Article/details/gtwuwewdlx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.shzxlz.cn/Article/details/gtfghyovze.html

[A25] 字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gtximmguas.html

Py:   s1 == s2; s1 != s2
来源：http://dali.nwbrower.top/Article/details/gtbhmdrcjf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtuipookby.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnqzz.top/Article/details/gtgcgdphtl.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258.top/Article/details/gtxjcmhozk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jiagoushi.top/Article/details/gtpsoggrhb.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.bjfxy.top/Article/details/gtaivmrifb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.c1oappe.top/Article/details/gtqiyweayw.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.redwolf501.top/Article/details/gtkaetaftp.html

[A26] 类型转换总览
来源：http://dali.daxiang520.top/Article/details/gtlgoqlkgy.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.haohaochexian.top/Article/details/gtdawlikia.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hfpthk.cn/Article/details/gtingwiwhy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yvedp.cn/Article/details/gtrmhkhclg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gzhubu.top/Article/details/gtglanumiy.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.chenzaomai.com/Article/details/gttutsqkhl.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhiwuduotai.top/Article/details/gtcycvdvpo.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yueranfly.top/Article/details/gtmldweqjy.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.andypj.xyz/Article/details/gtwxjbzfzx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtkgiyavia.html

B. 流程控制
来源：http://dali.jiagoushi.top/Article/details/gtnqelqeox.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthdctkmof.html

[B01] 条件判断 if / else
来源：http://dali.hnqzz.top/Article/details/gtogimwfdv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.pycfn.com/Article/details/gtlltsrbyk.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jiagoushi.top/Article/details/gtchliuxwj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gtbzetctge.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwznfmkv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gtejnhwfkn.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.chenzaomai.com/Article/details/gtjcyywhrr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ydzc1.top/Article/details/gtbtthsusl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gtiacbrvdx.html

[B02] 多分支 else if / elif
来源：http://dali.pengpengdd.cyou/Article/details/gtzpbgwmrd.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuetiantiany.cn/Article/details/gtueaseyoh.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yj202588.top/Article/details/gtibjifcjt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gtxnkeilrk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guannengcc.top/Article/details/gttsekxhuc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gtqmbaavdw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jianghu66.top/Article/details/gtqzhqswyi.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xinyue.icu/Article/details/gtvbzsoqso.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtwnvazjyx.html

[B03] switch / match / case
来源：http://dali.iojbl.cn/Article/details/gtchvsctlg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhijiandao.cn/Article/details/gtsktoltut.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gtbicufhdq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yanxiufei.cn/Article/details/gttserwrxt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gtsdaxspqg.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gtylcimekj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xylfe.cn/Article/details/gtxycxdeze.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zycfv.cn/Article/details/gtdfvfkgkt.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.pycfn.com/Article/details/gtmwxlelgn.html

[B04] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gttlrlwlfa.html

Py:   for i in range(10): print(i)
来源：http://dali.sweek.top/Article/details/gtukplkenu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpdonzhut.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnhvturh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ivvv.top/Article/details/gtnfhwvnnl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yuxming.cn/Article/details/gtoyadenpa.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.haohaochexian.top/Article/details/gtsjrdwinu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqxjrjtb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.quarkkingdee.top/Article/details/gtlnubgdqs.html

[B05] 遍历数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gtzvgzoxbx.html

Py:   for item in arr: print(item)
来源：http://dali.gaohongyu789.top/Article/details/gtnpuxhbro.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.daxiang520.top/Article/details/gtkquuawml.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258888.top/Article/details/gteuppkiip.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cucudq.cn/Article/details/gtzmfeikgx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.iojbl.cn/Article/details/gtveqqjuhg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.meibo888.top/Article/details/gtzxveubml.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jlsjyb.cn/Article/details/gtpezlydye.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sufxvd.cn/Article/details/gtneenfxsw.html

[B06] 遍历字典 / 对象
来源：http://dali.ybcxt.top/Article/details/gthtplldcl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.dianchejie.cn/Article/details/gtulzfpfxr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.haohaochexian.top/Article/details/gtsdjjpcfe.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aibaodan.cn/Article/details/gtxbzvixjn.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sufxvd.cn/Article/details/gtrmazhvql.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hysaishi.cn/Article/details/gtrovbjwmi.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenlongwang.top/Article/details/gtnjhbxros.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zdqjudy.top/Article/details/gtckcphekr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangshuangyany.cn/Article/details/gtnnxqngls.html

[B07] while 循环
来源：http://dali.aibaodan.cn/Article/details/gtgvgkfjnv.html

Py:   while i < 10: i += 1
来源：http://dali.cashguo.top/Article/details/gtvnrzbyps.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.iojbl.cn/Article/details/gtfsgcnrzd.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gtorfnrnxw.html

TS:   while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gtfsmgtyib.html

Java: while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtigtsyezx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gaohongyu789.top/Article/details/gtjbapcpvh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.daxiang520.top/Article/details/gtksqkahuc.html

C#:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtvjqlzhuv.html

[B08] do-while（至少执行一次）
来源：http://dali.ivvv.top/Article/details/gtxkztqgrl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.9152youxi.cn/Article/details/gtumjsbsoe.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtsahqdhbz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtvtekcbqt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtxfsibzee.html

Java: do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtsbtyjnfk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.wangshuangyany.cn/Article/details/gtgrblxycf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.chenlongwang.top/Article/details/gtsfrghcyn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gthvhsvczn.html

[B09] break 与 continue
来源：http://dali.xuetiantiany.cn/Article/details/gtwsrqozdz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.svipenyu.cn/Article/details/gtdecsphix.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtejbqycqa.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gturkepyoc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtiubxuzsz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtldurstrd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.316326.xyz/Article/details/gtbxhphvyg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.iojbl.cn/Article/details/gtcbtyurns.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtmnbliopz.html

[B10] 遍历同时拿索引
来源：http://dali.nanxinkj.top/Article/details/gtemdvuooh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sxryk.cn/Article/details/gtiohcctzq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.nanxuanxn.top/Article/details/gtfgdrbtpf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nwbrower.top/Article/details/gttykitnpc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yuanzhike.top/Article/details/gtbaokahyg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.c1oappe.top/Article/details/gtozgabamu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ppjwa.cn/Article/details/gtdqrkvrzb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tian-w.cn/Article/details/gtjnpycdnv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jlsjyb.cn/Article/details/gtxjksmcds.html

[B11] 生成数字序列 / 区间
来源：http://dali.yvedp.cn/Article/details/gttuvesfck.html

Py:   list(range(0, 10, 2))
来源：http://dali.smart0.xyz/Article/details/gtsfhqardb.html

PHP:  range(0, 10, 2);
来源：http://dali.havefunace.top/Article/details/gtazskeycj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gtrcjbyfrr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gtiotiejzj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenzaomai.com/Article/details/gteuopptwp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ehwqpu.com/Article/details/gtjrxjgzzw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dianchejie.cn/Article/details/gteyqqfttf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.birdmap.top/Article/details/gtozybshzf.html

[B12] 跳出多层循环
来源：http://dali.ydzc1.top/Article/details/gtbbrfkbih.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258888.top/Article/details/gtasgiauwb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuxming.cn/Article/details/gtmksrjakn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtsksizlra.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gtblfsuzdp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtvczmalqn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hfpthk.cn/Article/details/gtntztbrms.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.smart0.xyz/Article/details/gtuwnkjerk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tanke756.top/Article/details/gtgtlgphtc.html

[B13] 判断是否为数字
来源：http://dali.sysykeji.top/Article/details/gtfoykkkxn.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinqigfzy.top/Article/details/gthrbzqrru.html

PHP:  is_numeric($x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtibxzoqrg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gtrzwefyri.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jyoumei.cn/Article/details/gtmmunkivn.html

Java: x instanceof Number
来源：http://dali.feifeiyinyue.top/Article/details/gtiinrxrrm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hysaishi.cn/Article/details/gtqzjkluqi.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shangyingyoupin.top/Article/details/gtitjrryey.html

C#:   x is int or double or decimal
来源：http://dali.yonumen.top/Article/details/gtdvmrsoil.html

[B14] 判断值是否在集合内
来源：http://dali.nanxuanxn.top/Article/details/gtnnomlhkg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnqzz.top/Article/details/gthjzlwwtm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.c1oappe.top/Article/details/gtrhbksjdq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gtmwwxyskz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cashguo.top/Article/details/gteqceuwrg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtihvbmuuf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxmiaxas.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj20258.top/Article/details/gteccyymkz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gtjzsdldfh.html

[B15] 布尔运算与取反
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsboywdi.html

Py:   a and b or not c
来源：http://dali.cucudq.cn/Article/details/gthyanrcke.html

PHP:  $a && $b || !$c
来源：http://dali.wangshuangyany.cn/Article/details/gtxieclyfy.html

JS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtrokpsntb.html

TS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gthhvroavx.html

Java: a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtvkumserg.html

Go:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtdshvsgbx.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gthydjorvv.html

C#:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtrdonkcwb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gtducxejbs.html

Py:   if not data: return
来源：http://dali.nanxinkj.top/Article/details/gtakjquwhs.html

PHP:  if (!$data) { return; }
来源：http://dali.kuanghao11.cn/Article/details/gtwztdhial.html

JS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gtlzjfqhki.html

TS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gtrjcvdxpq.html

Java: if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gtmulotkko.html

Go:   if data == nil { return }
来源：http://dali.sufxvd.cn/Article/details/gtkimcadnd.html

Ruby: return if data.nil?
来源：http://dali.316326.xyz/Article/details/gtanyptbxj.html

C#:   if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gtfqufldpd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtocsxzpve.html

C. 函数与作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbulxgoad.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbhhmmxgy.html

[C01] 定义函数
来源：http://dali.ybcxt.top/Article/details/gttbhcwnkx.html

Py:   def add(a, b): return a + b
来源：http://dali.haohaochexian.top/Article/details/gtwrgizqth.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtcwrxbrzt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtoxhkzqhj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtizvolzdu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtjecjzxra.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xylfe.cn/Article/details/gtlkgoeewy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuanzhike.top/Article/details/gtdmfnsogq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtffrinhxw.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtaxrxqtuv.html

Py:   def greet(name="World"): return name
来源：http://dali.zhoulong.xyz/Article/details/gtbvyvnqnq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxuanxn.top/Article/details/gtqtcxyflz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtxiflinzr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtstobmvpe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yangfankeji.com/Article/details/gtcocqmbbz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xziqi.cn/Article/details/gthgcrcadb.html

Ruby: def greet(name = "World") = name
来源：http://dali.daria6918.cn/Article/details/gtrhwvnnpp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fengsongda.top/Article/details/gtillhxbae.html

[C03] 可变参数
来源：http://dali.jinqigfzy.top/Article/details/gtniblpkrx.html

Py:   def total(*args): return sum(args)
来源：http://dali.dianchejie.cn/Article/details/gtzruzqhmo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gtrphmyxpb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gtrolcuojw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gthozeuath.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpspxthy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zdqjudy.top/Article/details/gtchfrlfbv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.svipenyu.cn/Article/details/gtjvbwnlcg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhengqikj.top/Article/details/gtdwrmiowx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cucudq.cn/Article/details/gthfzkhnhs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daxiang520.top/Article/details/gtktfoaotv.html


<!-- 参考信息 -->