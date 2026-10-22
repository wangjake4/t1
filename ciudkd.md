代发 wailian999

Java: "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gtrnnyjysu.html

Go:   "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gtqzkqgavd.html

Ruby: "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmfcchgr.html

C#:   "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbguhqte.html

[A14] 注释写法
来源：http://dali.hywenlv.cn/Article/details/gtdymmhtqo.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqmtxcwz.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gthfuqjzeg.html

JS:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejdfutkm.html

TS:   // 单行；/* 多行 */
来源：http://dali.snrcjt.cn/Article/details/gtblmjdbiu.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhiwuduotai.top/Article/details/gtrzanomxz.html

Go:   // 单行；/* 多行 */
来源：http://dali.dianchejie.cn/Article/details/gtqdnvcikm.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhiwuduotai.top/Article/details/gtbcvkgkiu.html

C#:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gtdekxhskz.html

[A15] 空值判断与默认值
来源：http://dali.nwbrower.top/Article/details/gttcrhusub.html

Py:   value = data or "默认值"
来源：http://dali.kuanghao11.cn/Article/details/gtllxnfxpm.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yuanzhike.top/Article/details/gtjgygdtfv.html

JS:   const value = data ?? "默认值";
来源：http://dali.cashguo.top/Article/details/gtsppdpnnw.html

TS:   const value = data ?? "默认值";
来源：http://dali.cashguo.top/Article/details/gtfsumnqae.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsaywbeux.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.sysykeji.top/Article/details/gtquuziegc.html

Ruby: value = data || "默认值"
来源：http://dali.wangshuangyany.cn/Article/details/gtjahppoiu.html

C#:   var value = data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gtosifadqz.html

[A16] 真假值判断规则
来源：http://dali.sweek.top/Article/details/gttgkoyvzr.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.fzhhl.top/Article/details/gtbywmafkt.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hnxiangtu.top/Article/details/gtrnjijprb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hnqzz.top/Article/details/gtzxcvuxsn.html

TS:   if (!x) {}
来源：http://dali.0kj1m.cn/Article/details/gtbiekwwgq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtjtgkebjn.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.nanxuanxn.top/Article/details/gtrxjptgly.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.nwbrower.top/Article/details/gtozbzbxzn.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.andypj.xyz/Article/details/gtjvhkkmub.html

[A17] 位运算
来源：http://dali.birdmap.top/Article/details/gtmyehxsit.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtmwaposny.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.svipenyu.cn/Article/details/gtyiwgzsaw.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gtkeyzllpm.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmlnxzej.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtcooszilh.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gtuinyhbjn.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gtnnoxdjyd.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtqjodxney.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hammf.cn/Article/details/gtuzmdjajm.html

Py:   ord("A"); chr(65)
来源：http://dali.zhixingplan.top/Article/details/gtmbxgeylp.html

PHP:  ord("A"); chr(65)
来源：http://dali.yuxming.cn/Article/details/gtffemhnjl.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.pycfn.com/Article/details/gtqekvgikx.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.wangshuangyany.cn/Article/details/gtodiwygee.html

Java: (int) 'A'; (char) 65
来源：http://dali.nwbrower.top/Article/details/gtjrymvzyw.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.0kj1m.cn/Article/details/gthgdoehep.html

Ruby: "A".ord; 65.chr
来源：http://dali.cashguo.top/Article/details/gtxntkyiyy.html

C#:   (int)'A'; (char)65
来源：http://dali.tanke756.top/Article/details/gtejquzmij.html

[A19] 交换两个变量
来源：http://dali.dianchejie.cn/Article/details/gtohocvmjr.html

Py:   a, b = b, a
来源：http://dali.zdqjudy.top/Article/details/gtojseratj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.snrcjt.cn/Article/details/gtkuslidxx.html

JS:   [a, b] = [b, a];
来源：http://dali.zhoulong.xyz/Article/details/gtjskodvcg.html

TS:   [a, b] = [b, a];
来源：http://dali.yj20258888.top/Article/details/gtsxnmhnyd.html

Java: int t = a; a = b; b = t;
来源：http://dali.jiagoushi.top/Article/details/gtxiajzzow.html

Go:   a, b = b, a
来源：http://dali.ehwqpu.com/Article/details/gtimykhckf.html

Ruby: a, b = b, a
来源：http://dali.sweek.top/Article/details/gttptifmvf.html

C#:   (a, b) = (b, a);
来源：http://dali.zdqjudy.top/Article/details/gtjpkwtlgo.html

[A20] 读取标准输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzmajxnw.html

Py:   name = input("请输入：")
来源：http://dali.yuanzhike.top/Article/details/gtyzwmkzjs.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuuyjxyp.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.sxryk.cn/Article/details/gtwvgkissh.html

TS:   // Node.js：readline 模块
来源：http://dali.aibaodan.cn/Article/details/gttxavjwxx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.chenzaomai.com/Article/details/gtcjvgmywm.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.guowangkeji.top/Article/details/gtkeiwytzd.html

Ruby: gets.chomp
来源：http://dali.c1oappe.top/Article/details/gtaxltzqpq.html

C#:   Console.ReadLine();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkavpzuuf.html

[A21] 保留指定小数位输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtbhdugd.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cashguo.top/Article/details/gtstgllmyi.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gtkhjejkgp.html

JS:   (3.14159).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gtytwrebsy.html

TS:   (3.14159).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gtsfdiysqw.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpiinvacf.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.gaohongyu789.top/Article/details/gtgecfchch.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gtpvyhvqmp.html

C#:   3.14159.ToString("F2")
来源：http://dali.yongpay.top/Article/details/gtrfuytxvh.html

[A22] 获取字符串长度
来源：http://dali.iojbl.cn/Article/details/gtegswliuh.html

Py:   len(s)
来源：http://dali.yuanzhike.top/Article/details/gtdzsedftf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.tian-w.cn/Article/details/gtvfckppew.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.fengsongda.top/Article/details/gtbokzmafz.html

TS:   s.length
来源：http://dali.hywenlv.cn/Article/details/gteswryxfm.html

Java: s.length()
来源：http://dali.xuanzx.com/Article/details/gtkpcnkvci.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ppjwa.cn/Article/details/gtopgsjpel.html

Ruby: s.length
来源：http://dali.cheryme.top/Article/details/gtiunxjufp.html

C#:   s.Length
来源：http://dali.jqgfzy.top/Article/details/gtrxuiyrpr.html

[A23] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gtpptaozdm.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.tianlin.xyz/Article/details/gtxngnkngo.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.wangshuangyany.cn/Article/details/gtyutiqcnn.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.svipenyu.cn/Article/details/gtchokfrax.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ivvv.top/Article/details/gtromxjekl.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxinkj.top/Article/details/gtwokmzoit.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonhaqqis.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gtymhqxcye.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.gotoacloud.top/Article/details/gttbsunwss.html

[A24] 去除首尾空白
来源：http://dali.jqgfzy.top/Article/details/gtbxuoiwxo.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sxryk.cn/Article/details/gtttltobus.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.pycfn.com/Article/details/gtbozfxkdg.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hysaishi.cn/Article/details/gtbwydrbiu.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj202588.top/Article/details/gtxqinonkc.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hnqzz.top/Article/details/gthmdepxcr.html

Go:   strings.TrimSpace(s)
来源：http://dali.dashuyun.cn/Article/details/gtxgskfzxc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yvedp.cn/Article/details/gtflhdfljh.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ppjwa.cn/Article/details/gtbebfanhd.html

[A25] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtdnxxxpmz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.aizwys.cn/Article/details/gtgrnnjlrd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cdnleiting.top/Article/details/gthaqmiavn.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhengqikj.top/Article/details/gtsuyzhmnx.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigfzy.top/Article/details/gtjwbzkjox.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gotoacloud.top/Article/details/gtjrkkkwcl.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.andypj.xyz/Article/details/gtojgfljbw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yuxming.cn/Article/details/gtadrsyvce.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jlsjyb.cn/Article/details/gtpvfsuapr.html

[A26] 类型转换总览
来源：http://dali.quarkkingdee.top/Article/details/gtrjfphujt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cucudq.cn/Article/details/gtmbbeswqo.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cucudq.cn/Article/details/gtgpleurrw.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.meibo888.top/Article/details/gteqspybgg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yj20258888.top/Article/details/gtyzqohjib.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.svipenyu.cn/Article/details/gtnxogstqx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.kuanghao11.cn/Article/details/gtbeilokfh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.0kj1m.cn/Article/details/gtrzspdepz.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zycfv.cn/Article/details/gtdmmmlcdc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtngxvpphe.html

B. 流程控制
来源：http://dali.andypj.xyz/Article/details/gtoepsjgmt.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtzsoqljrn.html

[B01] 条件判断 if / else
来源：http://dali.fzhhl.top/Article/details/gtvoaewijp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sysykeji.top/Article/details/gtdltfeqwy.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yj202588.top/Article/details/gttslzduaw.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gtqgrvdinu.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nanxinkj.top/Article/details/gtuofeujrz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjldczil.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zdqjudy.top/Article/details/gtovozvzvp.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.cashguo.top/Article/details/gttlwvicrf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sxryk.cn/Article/details/gtbtvgghwm.html

[B02] 多分支 else if / elif
来源：http://dali.xinyue.icu/Article/details/gtesfinsut.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.aibaodan.cn/Article/details/gtvjzoacmx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shuidangran.top/Article/details/gtcjzmyput.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gtgfkglufk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangtech.top/Article/details/gttrnplebo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cucudq.cn/Article/details/gtssdftnue.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hnqzz.top/Article/details/gtihtmtvfs.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jianghu66.top/Article/details/gtspjdilxi.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.kuanghao11.cn/Article/details/gtmbqwelcn.html

[B03] switch / match / case
来源：http://dali.wangshuangyany.cn/Article/details/gtpnpbpgsj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yongpay.top/Article/details/gtfoweiavl.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gtlpsoebec.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gtltrbbwla.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gtxgwohbdn.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gtclmnufxo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtphenjzuv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ybcxt.top/Article/details/gtcdcxteub.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.kuanghao11.cn/Article/details/gtgygftcat.html

[B04] for 计数循环
来源：http://dali.hongshengwenyu.top/Article/details/gttszbsipr.html

Py:   for i in range(10): print(i)
来源：http://dali.xuanzx.com/Article/details/gtddqvxcbe.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gzhubu.top/Article/details/gthvpwarij.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gtnspraatx.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yanxiufei.cn/Article/details/gteabnkuwm.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shzxlz.cn/Article/details/gtyoohfxuo.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyblejtqo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.pycfn.com/Article/details/gtbithcxdb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.fengsongda.top/Article/details/gtzccesxef.html

[B05] 遍历数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gtdupivght.html

Py:   for item in arr: print(item)
来源：http://dali.tianlin.xyz/Article/details/gtmbbipvje.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhongyouzk.top/Article/details/gthbbzfgbp.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.quarkkingdee.top/Article/details/gtelnopjrj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.guowangkeji.top/Article/details/gtrtzqazei.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cheryme.top/Article/details/gtmptsrylg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tianlin.xyz/Article/details/gtqyhyvocj.html

Ruby: arr.each { |item| puts item }
来源：http://dali.bjfxy.top/Article/details/gtxchvqigw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtjoxmicdb.html

[B06] 遍历字典 / 对象
来源：http://dali.ivvv.top/Article/details/gtesuukwov.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cqqwz.cn/Article/details/gthccnnitf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jqgufenzy.top/Article/details/gtwxzdumcj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.andypj.xyz/Article/details/gteluqyrgb.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.0kj1m.cn/Article/details/gtwyyddhmv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.guannengcc.top/Article/details/gtwnzjzdxl.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtepqaczsc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xuanzx.com/Article/details/gterqlilxt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhongyouzk.top/Article/details/gtuwtmnbxm.html

[B07] while 循环
来源：http://dali.316326.xyz/Article/details/gtuywpjxlh.html

Py:   while i < 10: i += 1
来源：http://dali.wangshuangyany.cn/Article/details/gtqxghzzws.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwvwcxzuo.html

JS:   while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gtjhujabrl.html

TS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gthfzzmvdr.html

Java: while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gtpmxrspdw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jianghu66.top/Article/details/gtelakvbyz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.0kj1m.cn/Article/details/gthtctewdj.html

C#:   while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gtmoynshuz.html

[B08] do-while（至少执行一次）
来源：http://dali.ivvv.top/Article/details/gtmortgcna.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.wangdashe.top/Article/details/gtqhnghfug.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.fzhhl.top/Article/details/gtvcpbcktt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtqrxccfpo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsmengqp.html

Java: do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtuyiaemni.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pycfn.com/Article/details/gtucfythdj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cdnleiting.top/Article/details/gtrufbpelj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtiynasxbk.html

[B09] break 与 continue
来源：http://dali.yvedp.cn/Article/details/gtddnbdoij.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.svipenyu.cn/Article/details/gtpmtytdts.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrskvroaw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtbtouukui.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtswdiuzoj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtrlgfgwtd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yvedp.cn/Article/details/gtwltloxeo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258.top/Article/details/gthpihkqpm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtvuzijkvo.html

[B10] 遍历同时拿索引
来源：http://dali.sxryk.cn/Article/details/gtqhtqiweh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.316326.xyz/Article/details/gtzpeepike.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.aizwys.cn/Article/details/gtgglytsxc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xziqi.cn/Article/details/gtsnleuulf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tanke756.top/Article/details/gtfyakxlms.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmkqfhgeb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hywenlv.cn/Article/details/gtjgffyxgd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.havefunace.top/Article/details/gtahnwhkny.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.feifeiyinyue.top/Article/details/gthehzuxze.html

[B11] 生成数字序列 / 区间
来源：http://dali.gaohongyu789.top/Article/details/gtyccaqbhx.html

Py:   list(range(0, 10, 2))
来源：http://dali.sysykeji.top/Article/details/gtrutvqovj.html

PHP:  range(0, 10, 2);
来源：http://dali.xinyue.icu/Article/details/gtsxrzsdjt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtfmpuqyhp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj202588.top/Article/details/gtmpfdtdjp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtgvdgodjc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.c1oappe.top/Article/details/gtcroasmma.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gzhubu.top/Article/details/gtcpynvlkm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhengqikj.top/Article/details/gtmxmepwcy.html

[B12] 跳出多层循环
来源：http://dali.sxryk.cn/Article/details/gtmlkjakvq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nwbrower.top/Article/details/gtjkhwzhqt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.316326.xyz/Article/details/gtctrkejhy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gtjqengbru.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gtypldjksc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gtteitrcxm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.9152youxi.cn/Article/details/gtmanqnblg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fzhhl.top/Article/details/gtqatslbqj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhengqikj.top/Article/details/gtjwynvdkr.html

[B13] 判断是否为数字
来源：http://dali.ehwqpu.com/Article/details/gtcqdpjutr.html

Py:   isinstance(x, (int, float))
来源：http://dali.hammf.cn/Article/details/gtrbcdbpoz.html

PHP:  is_numeric($x)
来源：http://dali.yongpay.top/Article/details/gtknvikhpt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gtpmtortab.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gtfxlxyckw.html

Java: x instanceof Number
来源：http://dali.wangshuangyany.cn/Article/details/gtqjjxmmus.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj20258.top/Article/details/gtfvcojewu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cdnleiting.top/Article/details/gtstebgpug.html

C#:   x is int or double or decimal
来源：http://dali.jianghu66.top/Article/details/gtzoefpvkd.html

[B14] 判断值是否在集合内
来源：http://dali.chenzaomai.com/Article/details/gtbfmyqiao.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aizwys.cn/Article/details/gttjqobfbc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hnqzz.top/Article/details/gtptixlhvf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.birdmap.top/Article/details/gtzftqphjd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gttccwojwc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtzrnewbdw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daxiang520.top/Article/details/gtrvnbpmrc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgfzy.top/Article/details/gtwacvmuex.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.meibo888.top/Article/details/gtxxcbcybm.html

[B15] 布尔运算与取反
来源：http://dali.redwolf501.top/Article/details/gtahstadtl.html

Py:   a and b or not c
来源：http://dali.yueranfly.top/Article/details/gtjloyivor.html

PHP:  $a && $b || !$c
来源：http://dali.quarkkingdee.top/Article/details/gtpkexaiyp.html

JS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtqwhwwozy.html

TS:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtrrgcjjqb.html

Java: a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gttmisgvpd.html

Go:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtrcsdpfxe.html

Ruby: a && b || !c
来源：http://dali.cashguo.top/Article/details/gtvpxarkam.html

C#:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtzkjfzkeo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.redwolf501.top/Article/details/gtmktuawmi.html

Py:   if not data: return
来源：http://dali.c1oappe.top/Article/details/gtvvnjdtvk.html

PHP:  if (!$data) { return; }
来源：http://dali.dianchejie.cn/Article/details/gtgvbtvbtx.html

JS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gtdyylxfmg.html

TS:   if (!data) return;
来源：http://dali.9152youxi.cn/Article/details/gtqdqbheia.html

Java: if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gtppyhofbw.html

Go:   if data == nil { return }
来源：http://dali.yj20258.top/Article/details/gtwgzlyfnr.html

Ruby: return if data.nil?
来源：http://dali.sxryk.cn/Article/details/gtlidyomqt.html

C#:   if (data == null) return;
来源：http://dali.gogol.net.cn/Article/details/gtacdkrsai.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtpmkducoo.html

C. 函数与作用域
来源：http://dali.cdnleiting.top/Article/details/gtarxzqwvg.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtywurfeet.html

[C01] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtmhvwvzzd.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gtlomeqksv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gthktqbymc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqseooun.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtdxmopzie.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtjkxjmgat.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jyoumei.cn/Article/details/gtsejaopha.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuetiantiany.cn/Article/details/gtqucpdght.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtvdakesak.html

[C02] 默认参数
来源：http://dali.tanke756.top/Article/details/gtbdunnwmg.html

Py:   def greet(name="World"): return name
来源：http://dali.svipenyu.cn/Article/details/gtkxpygjhm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hammf.cn/Article/details/gtvuuzjnoa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtnzefksbl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtrqyulgik.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnxiangtu.top/Article/details/gtcoamjeef.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.316326.xyz/Article/details/gthmipquat.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxinkj.top/Article/details/gtnzegjbgf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqoyarnz.html

[C03] 可变参数
来源：http://dali.cucudq.cn/Article/details/gttkuewxrb.html

Py:   def total(*args): return sum(args)
来源：http://dali.cqqwz.cn/Article/details/gthanqrrhb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.feifeiyinyue.top/Article/details/gthmomctuk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gtiwpjwhyz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtfjbijmaw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttskeimag.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhongyouzk.top/Article/details/gtadvadfdc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhiwuduotai.top/Article/details/gtvvzawusu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cdnleiting.top/Article/details/gtfltosngq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guannengcc.top/Article/details/gtiynqrrgc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.dianchejie.cn/Article/details/gtgwivuqlz.html


<!-- 参考信息 -->