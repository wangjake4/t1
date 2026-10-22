代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.tianlin.xyz/Article/details/gtaccnrgsy.html

Ruby: "Hello, #{name}!"
来源：http://dali.xuetiantiany.cn/Article/details/gttwiofmvj.html

C#:   $"Hello, {name}!"
来源：http://dali.tianlin.xyz/Article/details/gtbdfkwply.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shangyingyoupin.top/Article/details/gtywoyqpah.html

Py:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gtswehaiql.html

PHP:  "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gtngfivflq.html

JS:   "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gtpdrfudom.html

TS:   "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzpyqshn.html

Java: "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gtbtrsggqh.html

Go:   "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gtnvzjcesl.html

Ruby: "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtadrpdgdo.html

C#:   "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gtqubcuhwj.html

[A14] 注释写法
来源：http://dali.0kj1m.cn/Article/details/gthvmakznr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ydzc1.top/Article/details/gtcvhbjpjo.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gtvstibsyv.html

JS:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gtlkrnwetk.html

TS:   // 单行；/* 多行 */
来源：http://dali.jiagoushi.top/Article/details/gtmmrzvejl.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqswhfqs.html

Go:   // 单行；/* 多行 */
来源：http://dali.0kj1m.cn/Article/details/gtppammvpl.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.snrcjt.cn/Article/details/gtuvrmgdbn.html

C#:   // 单行；/* 多行 */
来源：http://dali.jinqigfzy.top/Article/details/gtauopxftv.html

[A15] 空值判断与默认值
来源：http://dali.havefunace.top/Article/details/gtjonupfvs.html

Py:   value = data or "默认值"
来源：http://dali.zdqjudy.top/Article/details/gtfuczbyuu.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gtbbdiutji.html

JS:   const value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gtkvuenhqh.html

TS:   const value = data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gtzjatrhpa.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhoulong.xyz/Article/details/gtgtsxulzc.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ybcxt.top/Article/details/gtmssjgckr.html

Ruby: value = data || "默认值"
来源：http://dali.yuanzhike.top/Article/details/gttbfmohfx.html

C#:   var value = data ?? "默认值";
来源：http://dali.hywenlv.cn/Article/details/gtjwfmxgpp.html

[A16] 真假值判断规则
来源：http://dali.yuanzhike.top/Article/details/gtckisadqn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.c1oappe.top/Article/details/gtdqaimcqf.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yangfankeji.com/Article/details/gtjsaynvnz.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.pycfn.com/Article/details/gtmoghxrky.html

TS:   if (!x) {}
来源：http://dali.yuxming.cn/Article/details/gtwluwfkse.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yangfankeji.com/Article/details/gtjdvahpiz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.gotoacloud.top/Article/details/gtmvdwsngt.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shzxlz.cn/Article/details/gtqkdtnwuq.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hnxiangtu.top/Article/details/gthyepjydq.html

[A17] 位运算
来源：http://dali.yvedp.cn/Article/details/gtqvaofxtg.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gtsrqtbtps.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtdeguxorj.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ivvv.top/Article/details/gthfhvwdis.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gtzudvmupq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtufvadoqn.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtirnvqdbr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gtohqanpqi.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gtygbsrihe.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yuanzhike.top/Article/details/gtdoczgoaa.html

Py:   ord("A"); chr(65)
来源：http://dali.yangfankeji.com/Article/details/gtbtyyatvj.html

PHP:  ord("A"); chr(65)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthewziixg.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ivvv.top/Article/details/gtczheotyl.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.c1oappe.top/Article/details/gtkawtbxkm.html

Java: (int) 'A'; (char) 65
来源：http://dali.daxiang520.top/Article/details/gtyygibqqp.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.cucudq.cn/Article/details/gtmtferrnv.html

Ruby: "A".ord; 65.chr
来源：http://dali.jqgfzy.top/Article/details/gtpoewryyd.html

C#:   (int)'A'; (char)65
来源：http://dali.ydzc1.top/Article/details/gtcyryucoz.html

[A19] 交换两个变量
来源：http://dali.guowangkeji.top/Article/details/gtydmcuonl.html

Py:   a, b = b, a
来源：http://dali.bjfxy.top/Article/details/gtxazpqceu.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.iojbl.cn/Article/details/gtvdfedaqz.html

JS:   [a, b] = [b, a];
来源：http://dali.yueranfly.top/Article/details/gtyjdevokh.html

TS:   [a, b] = [b, a];
来源：http://dali.yvedp.cn/Article/details/gtytlqmfeo.html

Java: int t = a; a = b; b = t;
来源：http://dali.nanxinkj.top/Article/details/gturrmeeak.html

Go:   a, b = b, a
来源：http://dali.chenlongwang.top/Article/details/gteactbhev.html

Ruby: a, b = b, a
来源：http://dali.zycfv.cn/Article/details/gtfysicoqu.html

C#:   (a, b) = (b, a);
来源：http://dali.guannengcc.top/Article/details/gttryixdtr.html

[A20] 读取标准输入
来源：http://dali.jqgufenzy.top/Article/details/gtlmmbwucg.html

Py:   name = input("请输入：")
来源：http://dali.nanxinkj.top/Article/details/gtpqzpitpf.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.dashuyun.cn/Article/details/gtfcrxdrvc.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hnqzz.top/Article/details/gttgsqjemp.html

TS:   // Node.js：readline 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtfxcduwom.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hfpthk.cn/Article/details/gtklevaiar.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yongpay.top/Article/details/gtdhtbattt.html

Ruby: gets.chomp
来源：http://dali.fzhhl.top/Article/details/gtcvoqakvh.html

C#:   Console.ReadLine();
来源：http://dali.birdmap.top/Article/details/gtcebrzkij.html

[A21] 保留指定小数位输出
来源：http://dali.birdmap.top/Article/details/gtgsyzrxzv.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspxuwrcf.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gtxynzzdjn.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gtktevrgfk.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gtgjouyavy.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gtjlhvkxyo.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.wangdashe.top/Article/details/gtmwlqwwtt.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.andypj.xyz/Article/details/gtkqziqfja.html

C#:   3.14159.ToString("F2")
来源：http://dali.jianghu66.top/Article/details/gtnmjsnufd.html

[A22] 获取字符串长度
来源：http://dali.sweek.top/Article/details/gtzjkiwlaw.html

Py:   len(s)
来源：http://dali.yueranfly.top/Article/details/gtpmiceqek.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cheryme.top/Article/details/gtizdpzdvu.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhongyouzk.top/Article/details/gthommzhua.html

TS:   s.length
来源：http://dali.cashguo.top/Article/details/gtpywgkzrg.html

Java: s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtbkznanwd.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.birdmap.top/Article/details/gtmpyxdmpe.html

Ruby: s.length
来源：http://dali.kuanghao11.cn/Article/details/gtadmkxsby.html

C#:   s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtsvoszonz.html

[A23] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gtjxhxejmb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.chenjidiqi.icu/Article/details/gtzehbtzmd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.gotoacloud.top/Article/details/gtrugggpbn.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shangyingyoupin.top/Article/details/gtrtxhihpp.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gtmtbonwdz.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.tianlin.xyz/Article/details/gtajzjhcmf.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.dianchejie.cn/Article/details/gtpwpfvxng.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hnqzz.top/Article/details/gtiwbawrqz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.nanxinkj.top/Article/details/gtfybulbxb.html

[A24] 去除首尾空白
来源：http://dali.zhijiandao.cn/Article/details/gtfzcgaezu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.0kj1m.cn/Article/details/gtzdwxyskr.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cdnleiting.top/Article/details/gtruxqawyd.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jyoumei.cn/Article/details/gtlqhjgfxy.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sysykeji.top/Article/details/gtwgineock.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jlsjyb.cn/Article/details/gtiruywqmp.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtrcsasrbm.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.haohaochexian.top/Article/details/gtoilqdxuh.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.daria6918.cn/Article/details/gtdymjsxje.html

[A25] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhbqlciq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.meibo888.top/Article/details/gtskillvuy.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.guowangkeji.top/Article/details/gtdlxdaplg.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cheryme.top/Article/details/gtlrnubcjc.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ehwqpu.com/Article/details/gtadvxfmtz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkatvyedt.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.daxiang520.top/Article/details/gthqcqzeux.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ehwqpu.com/Article/details/gtvrownmkb.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.dianchejie.cn/Article/details/gtfvflkkdc.html

[A26] 类型转换总览
来源：http://dali.ydzc1.top/Article/details/gtweairubr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.fzhhl.top/Article/details/gtnalxhfxk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sxryk.cn/Article/details/gtnhnpseoi.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zdqjudy.top/Article/details/gtcouxronf.html

TS:   Number() String() Boolean() x as number
来源：http://dali.kuanghao11.cn/Article/details/gtjpptfdcu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.fengsongda.top/Article/details/gtbfnkhdfe.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hongshengwenyu.top/Article/details/gtwhbwrkge.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yj202588.top/Article/details/gtrhaeelov.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jyoumei.cn/Article/details/gtjociumxu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtzakaeeln.html

B. 流程控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuohudtmd.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtdshlqsrz.html

[B01] 条件判断 if / else
来源：http://dali.feifeiyinyue.top/Article/details/gtpiyksqcl.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.dashuyun.cn/Article/details/gtzerryabz.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xziqi.cn/Article/details/gtfwhpcemp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gtzvukvzha.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gthqcwsgip.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gtnjwqkzub.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tian-w.cn/Article/details/gtmiixyfkq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yangfankeji.com/Article/details/gtghwlhbrt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gtjalineaf.html

[B02] 多分支 else if / elif
来源：http://dali.cucudq.cn/Article/details/gtfqakufvu.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhoulong.xyz/Article/details/gtisjgymvy.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.tanke756.top/Article/details/gtfiyjolvj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtydpkkhna.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gteaynmcgi.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cucudq.cn/Article/details/gtxapricgx.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ydzc1.top/Article/details/gtbejlbdsw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrnxaqlb.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtgddtnkzg.html

[B03] switch / match / case
来源：http://dali.gaohongyu789.top/Article/details/gtglzsbrfd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj20258.top/Article/details/gtzhkxfjot.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.pycfn.com/Article/details/gtpsrcgkgg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtsvpxmmcc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtpjpnaoow.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gtdqixxubv.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.sysykeji.top/Article/details/gtfrhdrdnk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hnxiangtu.top/Article/details/gtsspjhudw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gtakopagwf.html

[B04] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gtnfpyxyqo.html

Py:   for i in range(10): print(i)
来源：http://dali.gotoacloud.top/Article/details/gtaljvbqjx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xylfe.cn/Article/details/gtfridqzdo.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.haohaochexian.top/Article/details/gtzmfhcwmt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xinyue.icu/Article/details/gtsodowphp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.aibaodan.cn/Article/details/gtxummeluc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.316326.xyz/Article/details/gtlhqjuqiy.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cheryme.top/Article/details/gtuawnossb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifqvujwd.html

[B05] 遍历数组 / 列表
来源：http://dali.havefunace.top/Article/details/gtbtyaihwl.html

Py:   for item in arr: print(item)
来源：http://dali.havefunace.top/Article/details/gtymyvddlg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hywenlv.cn/Article/details/gtreegkhrb.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gtgxlrsfvt.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxuanxn.top/Article/details/gteelbzzyo.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hysaishi.cn/Article/details/gtxfyrbkhv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cdnleiting.top/Article/details/gtpscnesly.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xylfe.cn/Article/details/gtyztgyqve.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hywenlv.cn/Article/details/gtnnydhuee.html

[B06] 遍历字典 / 对象
来源：http://dali.zhijiandao.cn/Article/details/gtptaexucf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xziqi.cn/Article/details/gtozwtidiy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtrdessgym.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenzaomai.com/Article/details/gtschwykfy.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtluddprin.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.aizwys.cn/Article/details/gttxsclxyo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.aibaodan.cn/Article/details/gtyjljnviy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvtbbsvm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.redwolf501.top/Article/details/gtzkjoipjn.html

[B07] while 循环
来源：http://dali.fzhhl.top/Article/details/gtusshhljk.html

Py:   while i < 10: i += 1
来源：http://dali.ivvv.top/Article/details/gthxuynpzr.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.iojbl.cn/Article/details/gtneerkjva.html

JS:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtnvevfsdg.html

TS:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gtjhtwmztr.html

Java: while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtdlcpyrlr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gaohongyu789.top/Article/details/gtwphcamry.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cashguo.top/Article/details/gtmgtfravd.html

C#:   while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gtbaiizxog.html

[B08] do-while（至少执行一次）
来源：http://dali.hfpthk.cn/Article/details/gtydpjdysv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sxryk.cn/Article/details/gtlaxgtplh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.mhx1999.top/Article/details/gthlhpqssd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gtzdscmifu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gthfojvmrt.html

Java: do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtebaiwtcs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj202588.top/Article/details/gtfrsqggta.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yanxiufei.cn/Article/details/gttyapxkyi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtqgzfzsxv.html

[B09] break 与 continue
来源：http://dali.zhiwuduotai.top/Article/details/gtrybfteki.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.iojbl.cn/Article/details/gtogagtsoh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtojxluwye.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtbfvhkenk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtyermkwqo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtbszfhsqo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sufxvd.cn/Article/details/gtmmpjffiu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhengqikj.top/Article/details/gtzbxdfrig.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtnaifftix.html

[B10] 遍历同时拿索引
来源：http://dali.chenlongwang.top/Article/details/gtcdqzvlyi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cheryme.top/Article/details/gtttlhhxsb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangdashe.top/Article/details/gtavmsabqo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuanzx.com/Article/details/gtjwwctwwh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.aizwys.cn/Article/details/gthmaabcvt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hfpthk.cn/Article/details/gtatqorewq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsmojzop.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrktgrgv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nanxuanxn.top/Article/details/gtkdajvqva.html

[B11] 生成数字序列 / 区间
来源：http://dali.meibo888.top/Article/details/gthwylmvjl.html

Py:   list(range(0, 10, 2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsezlvaev.html

PHP:  range(0, 10, 2);
来源：http://dali.pycfn.com/Article/details/gtmhlmjjqs.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sweek.top/Article/details/gtvfbwfrpo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gthzwzoewk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtjpfavstl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cucudq.cn/Article/details/gtdwicpkqr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.feifeiyinyue.top/Article/details/gtbiffsxws.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.fzhhl.top/Article/details/gteykrrvsp.html

[B12] 跳出多层循环
来源：http://dali.hysaishi.cn/Article/details/gthobmgbsg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hongshengwenyu.top/Article/details/gtodjnekax.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.svipenyu.cn/Article/details/gtrkskkhrl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtobkpvwpl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtoxpbsgdx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gtjnlvwjlk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrcxzfsh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tian-w.cn/Article/details/gtkwtmueed.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuxming.cn/Article/details/gtjtdmgrnw.html

[B13] 判断是否为数字
来源：http://dali.fzhhl.top/Article/details/gtcwxcnqll.html

Py:   isinstance(x, (int, float))
来源：http://dali.havefunace.top/Article/details/gtnapodtsv.html

PHP:  is_numeric($x)
来源：http://dali.yonumen.top/Article/details/gtnkdqfimu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxrectza.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gtzqadmdis.html

Java: x instanceof Number
来源：http://dali.wangshuangyany.cn/Article/details/gttnmybjqq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.0kj1m.cn/Article/details/gteapubhmy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shuidangran.top/Article/details/gtkvajnuyp.html

C#:   x is int or double or decimal
来源：http://dali.zhixingplan.top/Article/details/gtvvmgstjf.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gtqeghbywo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ppjwa.cn/Article/details/gtnnkvgvva.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.svipenyu.cn/Article/details/gtuntagspk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtwrppnjqz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtllepdevh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswaffkci.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gaohongyu789.top/Article/details/gttcyioxpg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sweek.top/Article/details/gtmfkjcxxs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gtezqkacfk.html

[B15] 布尔运算与取反
来源：http://dali.jiagoushi.top/Article/details/gtsipwspap.html

Py:   a and b or not c
来源：http://dali.jlsjyb.cn/Article/details/gtulngsbmi.html

PHP:  $a && $b || !$c
来源：http://dali.tianlin.xyz/Article/details/gtcjtwztor.html

JS:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtaxbulkqw.html

TS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtwckbwcso.html

Java: a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtdtvdxbkf.html

Go:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtsvqpexcb.html

Ruby: a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtrnflrpkg.html

C#:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtgzampakh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ivvv.top/Article/details/gtmeaulzef.html

Py:   if not data: return
来源：http://dali.quarkkingdee.top/Article/details/gtaityqodi.html

PHP:  if (!$data) { return; }
来源：http://dali.shzxlz.cn/Article/details/gtannmjqcz.html

JS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gtzvemrtyy.html

TS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gthrugakaa.html

Java: if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gtpaynnmmk.html

Go:   if data == nil { return }
来源：http://dali.jqgufenzy.top/Article/details/gtyunaxmor.html

Ruby: return if data.nil?
来源：http://dali.jqgfzy.top/Article/details/gtswxpfear.html

C#:   if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gtlsrwspbj.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gteedbyefm.html

C. 函数与作用域
来源：http://dali.fzhhl.top/Article/details/gtvnbelfpf.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwrpiwxqk.html

[C01] 定义函数
来源：http://dali.tian-w.cn/Article/details/gtagvtdesd.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzaqzsrd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtvtqabpts.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtmbiajbxt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtsqmxjqha.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtkmbyiygq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.haohaochexian.top/Article/details/gtiblgrprm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sxryk.cn/Article/details/gtcsdclpha.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtslrhpauq.html

[C02] 默认参数
来源：http://dali.cashguo.top/Article/details/gthbewuwyv.html

Py:   def greet(name="World"): return name
来源：http://dali.yvedp.cn/Article/details/gtmryxtvjl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.kuanghao11.cn/Article/details/gtpcerkkbs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlvskioc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtjkkbbfct.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.kuanghao11.cn/Article/details/gtrsfotqrz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sufxvd.cn/Article/details/gtsdfkbwrc.html

Ruby: def greet(name = "World") = name
来源：http://dali.sysykeji.top/Article/details/gtknuczgpd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yonumen.top/Article/details/gtdjkanvna.html

[C03] 可变参数
来源：http://dali.hywenlv.cn/Article/details/gtcdfxguon.html

Py:   def total(*args): return sum(args)
来源：http://dali.cqqwz.cn/Article/details/gtlkimgfmw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgfzy.top/Article/details/gtbimozmri.html


<!-- 参考信息 -->