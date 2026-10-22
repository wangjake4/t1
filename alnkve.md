代发 wailian999

[A14] 注释写法
来源：http://dali.tanke756.top/Article/details/gttiyqnoze.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jinqigfzy.top/Article/details/gtusnpshnb.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gttavpfbsa.html

JS:   // 单行；/* 多行 */
来源：http://dali.hywenlv.cn/Article/details/gtpedmbdin.html

TS:   // 单行；/* 多行 */
来源：http://dali.meibo888.top/Article/details/gtyjpvhyix.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yj20258888.top/Article/details/gtunagbfqn.html

Go:   // 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gtqajhykgz.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.meibo888.top/Article/details/gtvwqnqzoh.html

C#:   // 单行；/* 多行 */
来源：http://dali.dianchejie.cn/Article/details/gtqnclfsec.html

[A15] 空值判断与默认值
来源：http://dali.cdnleiting.top/Article/details/gtpjibydzp.html

Py:   value = data or "默认值"
来源：http://dali.sysykeji.top/Article/details/gthafqxuhh.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.sufxvd.cn/Article/details/gtiklilcyr.html

JS:   const value = data ?? "默认值";
来源：http://dali.vqdsnc.cn/Article/details/gtkfzwxuiu.html

TS:   const value = data ?? "默认值";
来源：http://dali.tian-w.cn/Article/details/gtdxbksuax.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhixingplan.top/Article/details/gtvtnqqgcn.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.nanxuanxn.top/Article/details/gtwugqqjxs.html

Ruby: value = data || "默认值"
来源：http://dali.hongshengwenyu.top/Article/details/gtvhxluwbh.html

C#:   var value = data ?? "默认值";
来源：http://dali.mhx1999.top/Article/details/gtpvnxjaqy.html

[A16] 真假值判断规则
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuxgmhyw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyyvjfpf.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhengqikj.top/Article/details/gtbjhrwmjz.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.haohaochexian.top/Article/details/gtvwxcclvz.html

TS:   if (!x) {}
来源：http://dali.jqgfzy.top/Article/details/gtobrtcezf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jqgfzy.top/Article/details/gtdsipldme.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.redwolf501.top/Article/details/gtnvyxdvdq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.nanxinkj.top/Article/details/gtmaykoxmj.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jqgfzy.top/Article/details/gtmjbtnlez.html

[A17] 位运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlixugwcw.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gtsnggilbb.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtojpzfapq.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gthjjtmetp.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gtvbfdwehc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtpahnyzzb.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gtzkciwouu.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtyyuqdovz.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtksvfqruz.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gtwqozcabq.html

Py:   ord("A"); chr(65)
来源：http://dali.hammf.cn/Article/details/gtbiyqtvvi.html

PHP:  ord("A"); chr(65)
来源：http://dali.hfpthk.cn/Article/details/gtzgnhrpzw.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqrfzxwf.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nanxinkj.top/Article/details/gtqnpqrulb.html

Java: (int) 'A'; (char) 65
来源：http://dali.yj202588.top/Article/details/gtsbauoswx.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.nanxuanxn.top/Article/details/gteffkojrf.html

Ruby: "A".ord; 65.chr
来源：http://dali.hongshengwenyu.top/Article/details/gtbettqbfy.html

C#:   (int)'A'; (char)65
来源：http://dali.jianghu66.top/Article/details/gtzxpgouzc.html

[A19] 交换两个变量
来源：http://dali.yongpay.top/Article/details/gtirzrbvji.html

Py:   a, b = b, a
来源：http://dali.gaohongyu789.top/Article/details/gttpqetzet.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shangyingyoupin.top/Article/details/gtjeqqiehc.html

JS:   [a, b] = [b, a];
来源：http://dali.dashuyun.cn/Article/details/gtgpfbkrdy.html

TS:   [a, b] = [b, a];
来源：http://dali.andypj.xyz/Article/details/gtizowlcso.html

Java: int t = a; a = b; b = t;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusfbixgw.html

Go:   a, b = b, a
来源：http://dali.hnqzz.top/Article/details/gttmkyemtl.html

Ruby: a, b = b, a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuksrsgoo.html

C#:   (a, b) = (b, a);
来源：http://dali.0kj1m.cn/Article/details/gtgvxqtqll.html

[A20] 读取标准输入
来源：http://dali.ivvv.top/Article/details/gtgwpjetjr.html

Py:   name = input("请输入：")
来源：http://dali.gogol.net.cn/Article/details/gtvcnwvhkf.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhengqikj.top/Article/details/gtotctppdw.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.316326.xyz/Article/details/gtrrminnxh.html

TS:   // Node.js：readline 模块
来源：http://dali.ehwqpu.com/Article/details/gtgwlyrybu.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhoulong.xyz/Article/details/gtqwhuszek.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.nanxinkj.top/Article/details/gtupvumeci.html

Ruby: gets.chomp
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqaamfcnl.html

C#:   Console.ReadLine();
来源：http://dali.redwolf501.top/Article/details/gtatdteoqi.html

[A21] 保留指定小数位输出
来源：http://dali.xuetiantiany.cn/Article/details/gtzvfwatyc.html

Py:   f"{3.14159:.2f}"
来源：http://dali.daxiang520.top/Article/details/gtyaklvztv.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.svipenyu.cn/Article/details/gtslcpobqi.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gttekkmvuo.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ybcxt.top/Article/details/gtwnvlhcgd.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.smart0.xyz/Article/details/gtktozlsqy.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gtypurdpne.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hywenlv.cn/Article/details/gtrssshfol.html

C#:   3.14159.ToString("F2")
来源：http://dali.iojbl.cn/Article/details/gtlmelabwg.html

[A22] 获取字符串长度
来源：http://dali.yonumen.top/Article/details/gtuiusibdx.html

Py:   len(s)
来源：http://dali.yonumen.top/Article/details/gthsirlwtc.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yonumen.top/Article/details/gtmrrvyrgl.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yj20258888.top/Article/details/gthqqmcjzf.html

TS:   s.length
来源：http://dali.0kj1m.cn/Article/details/gtstjprqio.html

Java: s.length()
来源：http://dali.zhijiandao.cn/Article/details/gtbavviflc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xuanzx.com/Article/details/gtrammbhgq.html

Ruby: s.length
来源：http://dali.yanxiufei.cn/Article/details/gtdslkpbmr.html

C#:   s.Length
来源：http://dali.yj202588.top/Article/details/gtjqwiadyq.html

[A23] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtllmsdfyo.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gzhubu.top/Article/details/gtsimfclly.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.haohaochexian.top/Article/details/gtxdedtsqf.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlhmgtea.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenjidiqi.icu/Article/details/gtiyjesqgu.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.feifeiyinyue.top/Article/details/gtbtvewjul.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jlsjyb.cn/Article/details/gtypuyqrwh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.pengpengdd.cyou/Article/details/gtoiiedccd.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.tianlin.xyz/Article/details/gttsgugqbb.html

[A24] 去除首尾空白
来源：http://dali.c1oappe.top/Article/details/gtqknrwjwp.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yuanzhike.top/Article/details/gtqccsbavb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jinqigfzy.top/Article/details/gtymwtlnyg.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nanxinkj.top/Article/details/gtrwzpxszm.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnqzz.top/Article/details/gtuhqhqcjh.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.0kj1m.cn/Article/details/gtfogwmmph.html

Go:   strings.TrimSpace(s)
来源：http://dali.vqdsnc.cn/Article/details/gtynerpzug.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzribrdp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj20258888.top/Article/details/gtvvpdirca.html

[A25] 字符串比较
来源：http://dali.tanke756.top/Article/details/gtogtfkfpf.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yangfankeji.com/Article/details/gtrksmnpmu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.aibaodan.cn/Article/details/gthtuzspmb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwblcmpes.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jiagoushi.top/Article/details/gtzsndukra.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinqigufen.top/Article/details/gtksrmrakf.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hywenlv.cn/Article/details/gtenpboijv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jiagoushi.top/Article/details/gtankawrsa.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.aizwys.cn/Article/details/gtkwufjeca.html

[A26] 类型转换总览
来源：http://dali.jiagoushi.top/Article/details/gtuntaywsp.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cucudq.cn/Article/details/gtjzdjknms.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tian-w.cn/Article/details/gtxivaklgl.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.9152youxi.cn/Article/details/gtsmvnjgkz.html

TS:   Number() String() Boolean() x as number
来源：http://dali.chenzaomai.com/Article/details/gtrtidybnm.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.9152youxi.cn/Article/details/gtljlkgvok.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.quarkkingdee.top/Article/details/gtdhutubzq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.iojbl.cn/Article/details/gtlmwdivxk.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ehwqpu.com/Article/details/gtoiirvrdi.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbtjgmnkg.html

B. 流程控制
来源：http://dali.hnxiangtu.top/Article/details/gteqoulows.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtxsagqzxv.html

[B01] 条件判断 if / else
来源：http://dali.yueranfly.top/Article/details/gttehfxuzy.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhiwuduotai.top/Article/details/gtvrkgpgbq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sxryk.cn/Article/details/gtvzvmivtr.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cucudq.cn/Article/details/gtdccgazpz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gtfvyfoxsw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gtjuvdvqfi.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yuanzhike.top/Article/details/gtyzzqgrnh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.cqqwz.cn/Article/details/gtaohnzczx.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gtxjpvnucv.html

[B02] 多分支 else if / elif
来源：http://dali.zhixingplan.top/Article/details/gtgzfdbxqx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinghuilouyu.cn/Article/details/gtztorkdzz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.aibaodan.cn/Article/details/gtfmrhbqxh.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gtyhhupubb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gtusuyhzpw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgqsnohq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.smart0.xyz/Article/details/gtpocxwafe.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cheryme.top/Article/details/gttpbzemdt.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gtqlletjmo.html

[B03] switch / match / case
来源：http://dali.gotoacloud.top/Article/details/gtjnssubpe.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sufxvd.cn/Article/details/gtsucukbrp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gturaywarm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gticxdnqdz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtclwvhucx.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gtvmnvbzzs.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jianghu66.top/Article/details/gtgyjnevcl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cqqwz.cn/Article/details/gtcxpoxwgk.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gtijhjsqkw.html

[B04] for 计数循环
来源：http://dali.iojbl.cn/Article/details/gtashzunfz.html

Py:   for i in range(10): print(i)
来源：http://dali.shuidangran.top/Article/details/gtetvxyuco.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sweek.top/Article/details/gtezqfitxv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxuanxn.top/Article/details/gtmyyuqrzn.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shzxlz.cn/Article/details/gtxbymnvgp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hfpthk.cn/Article/details/gtbgkzuhzb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.9152youxi.cn/Article/details/gtkxksqbpf.html

Ruby: 10.times { |i| puts i }
来源：http://dali.andypj.xyz/Article/details/gtirrfdlrb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gzhubu.top/Article/details/gtkoqkhmpl.html

[B05] 遍历数组 / 列表
来源：http://dali.hnxiangtu.top/Article/details/gtswutovut.html

Py:   for item in arr: print(item)
来源：http://dali.jinghuilouyu.cn/Article/details/gtftizmovn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhongyouzk.top/Article/details/gttfithbte.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.svipenyu.cn/Article/details/gtboogasrh.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.dashuyun.cn/Article/details/gtwfhqvlca.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifqbsssf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.vqdsnc.cn/Article/details/gtojcohdlw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.feifeiyinyue.top/Article/details/gtcrcbkrml.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sysykeji.top/Article/details/gtdnhkubyb.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258888.top/Article/details/gtdgtchviv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ydzc1.top/Article/details/gtttxmsjed.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sxryk.cn/Article/details/gtbotylnly.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gthjdicjdf.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ppjwa.cn/Article/details/gtwyatvaxy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ybcxt.top/Article/details/gtotygrvel.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zycfv.cn/Article/details/gtobtfpeuk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj20258888.top/Article/details/gtnndkehpi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenlongwang.top/Article/details/gtmiknqxcv.html

[B07] while 循环
来源：http://dali.cqqwz.cn/Article/details/gtccezcioz.html

Py:   while i < 10: i += 1
来源：http://dali.cashguo.top/Article/details/gtttfocpci.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gogol.net.cn/Article/details/gtqmbxracw.html

JS:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtjtzdolyu.html

TS:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtoxtorflr.html

Java: while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gtgdeeahqa.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.guannengcc.top/Article/details/gtaguuzwfg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gaohongyu789.top/Article/details/gtymdvsgad.html

C#:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtczyutqsp.html

[B08] do-while（至少执行一次）
来源：http://dali.nanxuanxn.top/Article/details/gtueoxtytx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sysykeji.top/Article/details/gtvwajxysu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtlmmwlxum.html

JS:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtammtgalv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtlvmucncc.html

Java: do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtaqmlbquw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gtzjtjhudr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnqzz.top/Article/details/gtyduiitxp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtafmxcyhd.html

[B09] break 与 continue
来源：http://dali.316326.xyz/Article/details/gthdwsdagu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.snrcjt.cn/Article/details/gtzfagbxtn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtllvcigao.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtcuoqsner.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtafzzdplu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtoqadvskg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjprrvzoo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jlsjyb.cn/Article/details/gtcnsoidyf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtbfuxwhbn.html

[B10] 遍历同时拿索引
来源：http://dali.pycfn.com/Article/details/gtdhirtcrf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.bjfxy.top/Article/details/gtuppnkexl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ivvv.top/Article/details/gtrzcnlbhb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.daria6918.cn/Article/details/gtslxxhsmq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jyoumei.cn/Article/details/gtzkuhwfiw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gaohongyu789.top/Article/details/gtdkqfkeat.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.guannengcc.top/Article/details/gtsywutsoz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shuidangran.top/Article/details/gtpkpwqrcc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yueranfly.top/Article/details/gtpfhoxtgw.html

[B11] 生成数字序列 / 区间
来源：http://dali.fengsongda.top/Article/details/gtcwfxxgbx.html

Py:   list(range(0, 10, 2))
来源：http://dali.wangdashe.top/Article/details/gtxlbszgks.html

PHP:  range(0, 10, 2);
来源：http://dali.haohaochexian.top/Article/details/gtopjunwja.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hysaishi.cn/Article/details/gtflqtxujx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtbxtjmbcn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.daria6918.cn/Article/details/gttwmvnmon.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guannengcc.top/Article/details/gtsbjplojm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.pengpengdd.cyou/Article/details/gtvgiibpyt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yueranfly.top/Article/details/gtbdwcwier.html

[B12] 跳出多层循环
来源：http://dali.ppjwa.cn/Article/details/gtzhnyczfu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xylfe.cn/Article/details/gtfrpwrgab.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.svipenyu.cn/Article/details/gtluotgfws.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtkqddavvm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtarzodmhp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gtduihuytv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgufenzy.top/Article/details/gttktqswce.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.aizwys.cn/Article/details/gtxclwbeqd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.meibo888.top/Article/details/gtgofmcekn.html

[B13] 判断是否为数字
来源：http://dali.xuetiantiany.cn/Article/details/gtdlixawqq.html

Py:   isinstance(x, (int, float))
来源：http://dali.c1oappe.top/Article/details/gtnrppcrom.html

PHP:  is_numeric($x)
来源：http://dali.cucudq.cn/Article/details/gthlamvrpb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cqqwz.cn/Article/details/gtcfopaoaz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtwlykyowa.html

Java: x instanceof Number
来源：http://dali.sweek.top/Article/details/gtbumrfafh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigufen.top/Article/details/gtwsqbekyr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jlsjyb.cn/Article/details/gtotxmgsic.html

C#:   x is int or double or decimal
来源：http://dali.cqqwz.cn/Article/details/gtazbudbrj.html

[B14] 判断值是否在集合内
来源：http://dali.cqqwz.cn/Article/details/gtzbrblacx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zdqjudy.top/Article/details/gtgocrietd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.redwolf501.top/Article/details/gtgfhnycfv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtwxkidqlh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtoeyempwn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.smart0.xyz/Article/details/gtoorxrgmh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cdnleiting.top/Article/details/gtwjsfwocr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtamknpxdk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj202588.top/Article/details/gtmuiobuof.html

[B15] 布尔运算与取反
来源：http://dali.gzhubu.top/Article/details/gtctppedtk.html

Py:   a and b or not c
来源：http://dali.yueranfly.top/Article/details/gtggnnuhig.html

PHP:  $a && $b || !$c
来源：http://dali.zhongyouzk.top/Article/details/gtcqkefkfc.html

JS:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gttfcpxmly.html

TS:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtrrzdotyx.html

Java: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtozachjds.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtpzigbljo.html

Ruby: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtqwosmcov.html

C#:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtidniquyy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxuanxn.top/Article/details/gtfvjsymak.html

Py:   if not data: return
来源：http://dali.nwbrower.top/Article/details/gtulfdqeid.html

PHP:  if (!$data) { return; }
来源：http://dali.dashuyun.cn/Article/details/gtkyaucpcf.html

JS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgucgsdee.html

TS:   if (!data) return;
来源：http://dali.tanke756.top/Article/details/gtbjbdwcpw.html

Java: if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gtvxzouhxx.html

Go:   if data == nil { return }
来源：http://dali.dashuyun.cn/Article/details/gtdbevtqyl.html

Ruby: return if data.nil?
来源：http://dali.daria6918.cn/Article/details/gtxobrcetq.html

C#:   if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gtqnrjfezy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtzdfeegkp.html

C. 函数与作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqedxxbv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqblfpdxw.html

[C01] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtfeoaywdj.html

Py:   def add(a, b): return a + b
来源：http://dali.ydzc1.top/Article/details/gtxjjrzhzj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtvoecyifd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzkyllbue.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtobxcqhfj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtnttukfov.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.redwolf501.top/Article/details/gtzzywledv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.vqdsnc.cn/Article/details/gtsqhzngae.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtyfrpwoys.html

[C02] 默认参数
来源：http://dali.andypj.xyz/Article/details/gtjyekkpwg.html

Py:   def greet(name="World"): return name
来源：http://dali.yj202588.top/Article/details/gtoxykyypa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.fzhhl.top/Article/details/gtmescjmit.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gttclmzigi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gtwyqcfrvs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenjidiqi.icu/Article/details/gtkncazhsu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gtwcgkdlff.html

Ruby: def greet(name = "World") = name
来源：http://dali.vqdsnc.cn/Article/details/gtnanxzpjq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.redwolf501.top/Article/details/gtwmntizow.html

[C03] 可变参数
来源：http://dali.feifeiyinyue.top/Article/details/gtdlotywhr.html

Py:   def total(*args): return sum(args)
来源：http://dali.sweek.top/Article/details/gtrtesoapp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hongshengwenyu.top/Article/details/gtoqpzbshu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gtctqfefdg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.havefunace.top/Article/details/gtsvfqymgh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbstqxupo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hongshengwenyu.top/Article/details/gtlabzoqwe.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ehwqpu.com/Article/details/gtqgatxlvn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jianghu66.top/Article/details/gtxvivkjdg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxinkj.top/Article/details/gtcpvtyndg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ybcxt.top/Article/details/gtgnnxkgpd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yangfankeji.com/Article/details/gtjzvuzpti.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.aizwys.cn/Article/details/gtduwgnrha.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgufenzy.top/Article/details/gttaotqubs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuxming.cn/Article/details/gtrpbdkkzt.html


<!-- 参考信息 -->