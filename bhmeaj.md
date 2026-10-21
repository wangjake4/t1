代发 wailian999

[A14] 注释写法
来源：http://dali.hfpthk.cn/Article/details/gtsjuttvmr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.gzhubu.top/Article/details/gtftfuxmub.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.ydzc1.top/Article/details/gtbclwduhi.html

JS:   // 单行；/* 多行 */
来源：http://dali.yueranfly.top/Article/details/gtoljxjsmw.html

TS:   // 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gtmilfklgd.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.fzhhl.top/Article/details/gtmzlyyqjb.html

Go:   // 单行；/* 多行 */
来源：http://dali.xuanzx.com/Article/details/gtpxofcfcg.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yvedp.cn/Article/details/gtcvlzchnb.html

C#:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gtudqtdshk.html

[A15] 空值判断与默认值
来源：http://dali.sweek.top/Article/details/gtcvtbopjp.html

Py:   value = data or "默认值"
来源：http://dali.xinyue.icu/Article/details/gtznylmxel.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gtrqlppyms.html

JS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdinvbwn.html

TS:   const value = data ?? "默认值";
来源：http://dali.cheryme.top/Article/details/gtpshbjsfq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.fengsongda.top/Article/details/gtauycdkjq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.redwolf501.top/Article/details/gtdiklxcpo.html

Ruby: value = data || "默认值"
来源：http://dali.jinqigufen.top/Article/details/gtshxkohlr.html

C#:   var value = data ?? "默认值";
来源：http://dali.yj202588.top/Article/details/gtyqcmgrua.html

[A16] 真假值判断规则
来源：http://dali.zhiwuduotai.top/Article/details/gtdciulwun.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shuidangran.top/Article/details/gtuldqtkwe.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.pycfn.com/Article/details/gtekcximfh.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hywenlv.cn/Article/details/gtwpziqicr.html

TS:   if (!x) {}
来源：http://dali.sufxvd.cn/Article/details/gtwbmdbbwg.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.tianlin.xyz/Article/details/gttxwikuqu.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shuidangran.top/Article/details/gtqpewkpvp.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.dianchejie.cn/Article/details/gtlqtzrfop.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hammf.cn/Article/details/gtdylvhjhi.html

[A17] 位运算
来源：http://dali.xylfe.cn/Article/details/gtxzatjvfs.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtvpuqhaxw.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.0kj1m.cn/Article/details/gtubgkeqsw.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gthwazkbuk.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gtogahednm.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gtoovudhqr.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmivjtfca.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gtotdifpmi.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gtgvevjnjm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhiwuduotai.top/Article/details/gtbsrrzgpk.html

Py:   ord("A"); chr(65)
来源：http://dali.chenjidiqi.icu/Article/details/gtpdliugia.html

PHP:  ord("A"); chr(65)
来源：http://dali.yuanzhike.top/Article/details/gtwtleleup.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nanxinkj.top/Article/details/gtjbucvobh.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hnxiangtu.top/Article/details/gtjuyzycqp.html

Java: (int) 'A'; (char) 65
来源：http://dali.xylfe.cn/Article/details/gtrwqcerpr.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.shangyingyoupin.top/Article/details/gtxosdxewa.html

Ruby: "A".ord; 65.chr
来源：http://dali.yangfankeji.com/Article/details/gtwppuvdtc.html

C#:   (int)'A'; (char)65
来源：http://dali.vqdsnc.cn/Article/details/gtifviqzta.html

[A19] 交换两个变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtgikygvzy.html

Py:   a, b = b, a
来源：http://dali.meibo888.top/Article/details/gtnakedgjr.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.fzhhl.top/Article/details/gtnlryjeio.html

JS:   [a, b] = [b, a];
来源：http://dali.haohaochexian.top/Article/details/gtrxsbwraq.html

TS:   [a, b] = [b, a];
来源：http://dali.pengpengdd.cyou/Article/details/gtasqaadcx.html

Java: int t = a; a = b; b = t;
来源：http://dali.daria6918.cn/Article/details/gtlzxzhfyb.html

Go:   a, b = b, a
来源：http://dali.daxiang520.top/Article/details/gtozzvcafo.html

Ruby: a, b = b, a
来源：http://dali.cdnleiting.top/Article/details/gtzrwpxlut.html

C#:   (a, b) = (b, a);
来源：http://dali.wangdashe.top/Article/details/gtejxrzzfg.html

[A20] 读取标准输入
来源：http://dali.dashuyun.cn/Article/details/gtarwggevl.html

Py:   name = input("请输入：")
来源：http://dali.yuxming.cn/Article/details/gtyqnhijdr.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.9152youxi.cn/Article/details/gtrifbtgnn.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.nanxinkj.top/Article/details/gtasyquyzm.html

TS:   // Node.js：readline 模块
来源：http://dali.cashguo.top/Article/details/gtirnfridq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.tianlin.xyz/Article/details/gtxgoaydht.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.aizwys.cn/Article/details/gtjgabrfzy.html

Ruby: gets.chomp
来源：http://dali.wangshuangyany.cn/Article/details/gtcedwymyl.html

C#:   Console.ReadLine();
来源：http://dali.tian-w.cn/Article/details/gtzkbabcof.html

[A21] 保留指定小数位输出
来源：http://dali.yanxiufei.cn/Article/details/gtanarnpht.html

Py:   f"{3.14159:.2f}"
来源：http://dali.pengpengdd.cyou/Article/details/gtdasmdcxp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gtwrnvlmwp.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtqldiiuff.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gtbucsqjsd.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sxryk.cn/Article/details/gtewsfpnac.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xuanzx.com/Article/details/gtyekxqeuy.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.nwbrower.top/Article/details/gtrjdjzaje.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhiwuduotai.top/Article/details/gtkqcqkaqq.html

[A22] 获取字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqcrzpgj.html

Py:   len(s)
来源：http://dali.nanxuanxn.top/Article/details/gtotxcekbo.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjouoabtk.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.guannengcc.top/Article/details/gtkcwrvgie.html

TS:   s.length
来源：http://dali.zdqjudy.top/Article/details/gtiescdbkg.html

Java: s.length()
来源：http://dali.yongpay.top/Article/details/gtriojmmcb.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.cheryme.top/Article/details/gtbtejvlzq.html

Ruby: s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtpqjvkvnl.html

C#:   s.Length
来源：http://dali.yj20258.top/Article/details/gtimbybdas.html

[A23] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtphxobcvl.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ivvv.top/Article/details/gtudhdiamk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ybcxt.top/Article/details/gteonycxss.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zycfv.cn/Article/details/gtxwtwduse.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yanxiufei.cn/Article/details/gtvcgpcdum.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhiwuduotai.top/Article/details/gtweqfuarh.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhoulong.xyz/Article/details/gtibwrjwdl.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gtvmlrhaqi.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.smart0.xyz/Article/details/gteltqgezr.html

[A24] 去除首尾空白
来源：http://dali.birdmap.top/Article/details/gtkquveenq.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.dashuyun.cn/Article/details/gtvwgorpuj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.smart0.xyz/Article/details/gtpsvsogbc.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.havefunace.top/Article/details/gtkbqyfvew.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hysaishi.cn/Article/details/gtqvjgypam.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.wangshuangyany.cn/Article/details/gtixowvvfo.html

Go:   strings.TrimSpace(s)
来源：http://dali.jqgfzy.top/Article/details/gtlgtdhqdj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shangyingyoupin.top/Article/details/gtjwgtlkni.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryzpkogc.html

[A25] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtynvzedae.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yvedp.cn/Article/details/gtjjrxrgeo.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkrqegrj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gogol.net.cn/Article/details/gtbotvwnjp.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nanxuanxn.top/Article/details/gtpkctdokt.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj20258888.top/Article/details/gtvepankfl.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hfpthk.cn/Article/details/gtveptolpq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xuetiantiany.cn/Article/details/gtnmldbwey.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.birdmap.top/Article/details/gtmgezixkt.html

[A26] 类型转换总览
来源：http://dali.kuanghao11.cn/Article/details/gtwlywwcpa.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yanxiufei.cn/Article/details/gtwwxvmsez.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrxbacss.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hnqzz.top/Article/details/gtqbjlmifl.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hongshengwenyu.top/Article/details/gtsgqfxiwn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sxryk.cn/Article/details/gtinhbypnm.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipsafgyk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhiwuduotai.top/Article/details/gtzpdweqnb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cheryme.top/Article/details/gtqnzrjfjc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtsfvpyroe.html

B. 流程控制
来源：http://dali.ivvv.top/Article/details/gtfuywmnrc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtthjsnhak.html

[B01] 条件判断 if / else
来源：http://dali.pycfn.com/Article/details/gtiuagqcfd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.gaohongyu789.top/Article/details/gtbpwimioc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hywenlv.cn/Article/details/gtjjtfdsrs.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gtebahcicx.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gtbfqggqfh.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gthbeqjgzs.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cucudq.cn/Article/details/gtmkcoshwt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xziqi.cn/Article/details/gtftxnfypu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gtvjssdzfb.html

[B02] 多分支 else if / elif
来源：http://dali.jinqigufen.top/Article/details/gtxohhpzqy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.cashguo.top/Article/details/gtzgpaojzt.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yanxiufei.cn/Article/details/gtopwddqgz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gtsbregxna.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gttiucujxn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jiagoushi.top/Article/details/gtddolozyv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.andypj.xyz/Article/details/gtvqdpsuro.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.quarkkingdee.top/Article/details/gteucqnwok.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gtattikjzm.html

[B03] switch / match / case
来源：http://dali.chenjidiqi.icu/Article/details/gtbiessiiu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.havefunace.top/Article/details/gtxhsgecus.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yueranfly.top/Article/details/gtjubythly.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gtkusaslpo.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gtjpmwgbjr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gtcqjgqgnw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinqigufen.top/Article/details/gtfewtkeam.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.tianlin.xyz/Article/details/gtmvknlalg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gtsdxahcas.html

[B04] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gtfoxhnwit.html

Py:   for i in range(10): print(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtfyuwxdaa.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shuidangran.top/Article/details/gtzsuhfzpv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenzaomai.com/Article/details/gtyuaymban.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gtpzapzana.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sweek.top/Article/details/gtcsujwxpd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.guowangkeji.top/Article/details/gthchxfzkf.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hysaishi.cn/Article/details/gtbyyyesdn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shzxlz.cn/Article/details/gtpukgxttb.html

[B05] 遍历数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gtasukfeqd.html

Py:   for item in arr: print(item)
来源：http://dali.yangfankeji.com/Article/details/gtjvljtxhg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jqgfzy.top/Article/details/gtcauoyktd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.haohaochexian.top/Article/details/gtedkjnqpu.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xziqi.cn/Article/details/gtinxbqfyt.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.svipenyu.cn/Article/details/gtayifbone.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtquseptie.html

Ruby: arr.each { |item| puts item }
来源：http://dali.fzhhl.top/Article/details/gtupbvbyau.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gtrwppgkic.html

[B06] 遍历字典 / 对象
来源：http://dali.jianghu66.top/Article/details/gtlmtsgokb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinghuilouyu.cn/Article/details/gteehayjlh.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yonumen.top/Article/details/gtpeggygzn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gtttkaijcg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ivvv.top/Article/details/gtudxqsjwe.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.haohaochexian.top/Article/details/gtvciafnwj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zdqjudy.top/Article/details/gtlqqkxfdc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cucudq.cn/Article/details/gtmtmqqccz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.9152youxi.cn/Article/details/gtoewqnocv.html

[B07] while 循环
来源：http://dali.ppjwa.cn/Article/details/gtxzpxdspd.html

Py:   while i < 10: i += 1
来源：http://dali.zhoulong.xyz/Article/details/gtwycxtict.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ppjwa.cn/Article/details/gtvhbkgocl.html

JS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznnbinsb.html

TS:   while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gtiukdjbsn.html

Java: while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gtrtzwvhhh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xylfe.cn/Article/details/gtbmmqehpr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigfzy.top/Article/details/gtrqmngwws.html

C#:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtesastnex.html

[B08] do-while（至少执行一次）
来源：http://dali.9152youxi.cn/Article/details/gtahtmjfgq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnxiangtu.top/Article/details/gtfeoaithj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj20258.top/Article/details/gtycdoqhrq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtvvytqtvp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gtqxiiurxe.html

Java: do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtazvgcreu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.kuanghao11.cn/Article/details/gtnizfryke.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.aizwys.cn/Article/details/gtlqgbigou.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtvmsevvxe.html

[B09] break 与 continue
来源：http://dali.daxiang520.top/Article/details/gtevlyvctn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.daxiang520.top/Article/details/gtrwjsarqr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtiipbhsjx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gttydcfknv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gtvceeciua.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtorqrjlok.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zdqjudy.top/Article/details/gtkirfuzqj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xinyue.icu/Article/details/gtoynugpgj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gtmubcupib.html

[B10] 遍历同时拿索引
来源：http://dali.zhiwuduotai.top/Article/details/gtecvrazfn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenlongwang.top/Article/details/gtwkpcsbyj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yanxiufei.cn/Article/details/gtrvzyhwal.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hammf.cn/Article/details/gtmhqndnwn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.redwolf501.top/Article/details/gthixjbvzf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmbgxplsn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jianghu66.top/Article/details/gtuagmqvgl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.feifeiyinyue.top/Article/details/gtrcvzhgjv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteemvovpi.html

[B11] 生成数字序列 / 区间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlstetozr.html

Py:   list(range(0, 10, 2))
来源：http://dali.sysykeji.top/Article/details/gtgoilvfay.html

PHP:  range(0, 10, 2);
来源：http://dali.jqgfzy.top/Article/details/gtdwayzrwc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gtzsmncfps.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cheryme.top/Article/details/gtyrguufcb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj202588.top/Article/details/gtyshvgycg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sweek.top/Article/details/gtbynikyht.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangshuangyany.cn/Article/details/gtcijskhal.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tianlin.xyz/Article/details/gtdaqnwchu.html

[B12] 跳出多层循环
来源：http://dali.chenlongwang.top/Article/details/gtadvsjclg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.birdmap.top/Article/details/gttftzvwkj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.guannengcc.top/Article/details/gtpumlrklx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtriilfppv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtsivqfvxd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtqoojlfet.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj202588.top/Article/details/gtyctlijwi.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhoulong.xyz/Article/details/gtlfudvrzo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuanzhike.top/Article/details/gtviwugufu.html

[B13] 判断是否为数字
来源：http://dali.zhixingplan.top/Article/details/gtzfnqrlxu.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhongyouzk.top/Article/details/gtbinrctic.html

PHP:  is_numeric($x)
来源：http://dali.xylfe.cn/Article/details/gtfolnhibj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.birdmap.top/Article/details/gtzpuuotew.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yanxiufei.cn/Article/details/gtmehxpdof.html

Java: x instanceof Number
来源：http://dali.wangdashe.top/Article/details/gtvsnqxuay.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.feifeiyinyue.top/Article/details/gtdsmddwpf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.9152youxi.cn/Article/details/gttqzxhshb.html

C#:   x is int or double or decimal
来源：http://dali.zdqjudy.top/Article/details/gtvxlgvpkd.html

[B14] 判断值是否在集合内
来源：http://dali.ivvv.top/Article/details/gtencjhzcy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gthvlmaoda.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pycfn.com/Article/details/gtpxdasfab.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtogdbhnwj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtolsljmvd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangdashe.top/Article/details/gtkkrnhyzc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yvedp.cn/Article/details/gtxnwjnsxk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhixingplan.top/Article/details/gtsdtmuknc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gthxpczdqj.html

[B15] 布尔运算与取反
来源：http://dali.snrcjt.cn/Article/details/gthggaqspb.html

Py:   a and b or not c
来源：http://dali.xylfe.cn/Article/details/gteqfflvxr.html

PHP:  $a && $b || !$c
来源：http://dali.yonumen.top/Article/details/gtotgeuvdi.html

JS:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtaagbbisv.html

TS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gteoykunpv.html

Java: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtadtqkwxd.html

Go:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnstxiddg.html

Ruby: a && b || !c
来源：http://dali.pycfn.com/Article/details/gtnqhlvtrz.html

C#:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtkjqpfbfa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxuanxn.top/Article/details/gtdzdvlirf.html

Py:   if not data: return
来源：http://dali.hnxiangtu.top/Article/details/gtbrpcedsa.html

PHP:  if (!$data) { return; }
来源：http://dali.iojbl.cn/Article/details/gtnixbhabl.html

JS:   if (!data) return;
来源：http://dali.meibo888.top/Article/details/gtvrdbpxtq.html

TS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gtplkenzzz.html

Java: if (data == null) return;
来源：http://dali.yvedp.cn/Article/details/gtlmpxmqtn.html

Go:   if data == nil { return }
来源：http://dali.chenlongwang.top/Article/details/gtucohldxq.html

Ruby: return if data.nil?
来源：http://dali.sufxvd.cn/Article/details/gttjrvwnlv.html

C#:   if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtdstgydaw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gthaekldjo.html

C. 函数与作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcvatbah.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtmuebfatx.html

[C01] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtcvohjbpx.html

Py:   def add(a, b): return a + b
来源：http://dali.zhoulong.xyz/Article/details/gtksrqijoe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtarhkvphp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtrtojtxet.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtqdzufwez.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtdqnphzka.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnqzz.top/Article/details/gtsxjvbhcn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yongpay.top/Article/details/gtkgmfeanf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gttfbicbpq.html

[C02] 默认参数
来源：http://dali.havefunace.top/Article/details/gtgagzbtad.html

Py:   def greet(name="World"): return name
来源：http://dali.0kj1m.cn/Article/details/gtdldtkgqb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ydzc1.top/Article/details/gtulnhxevl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gtifqdfidk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtppocotnu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hysaishi.cn/Article/details/gtlestiseq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuxming.cn/Article/details/gtfzmjbehu.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gtubecphfx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tian-w.cn/Article/details/gtxurwwiwv.html

[C03] 可变参数
来源：http://dali.shangyingyoupin.top/Article/details/gtwwosmnfn.html

Py:   def total(*args): return sum(args)
来源：http://dali.andypj.xyz/Article/details/gtaymzosbi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhoulong.xyz/Article/details/gtayfutdtb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtyoudhsbi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gttyjhvjdr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigfzy.top/Article/details/gtbmkuxshl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.kuanghao11.cn/Article/details/gtuxevtazc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jlsjyb.cn/Article/details/gtjjakeelh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangshuangyany.cn/Article/details/gtmxyxowas.html

[C04] 命名参数 / 关键字参数
来源：http://dali.redwolf501.top/Article/details/gtnaifitgr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zycfv.cn/Article/details/gtotoiuhlv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xylfe.cn/Article/details/gtbmdlwdrx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gtrhzedkyc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.iojbl.cn/Article/details/gtypqwjudh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.9152youxi.cn/Article/details/gtmyllylqo.html


<!-- 参考信息 -->