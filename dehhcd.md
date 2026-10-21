代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gtzbfjnsif.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.chenjidiqi.icu/Article/details/gthigrzwcy.html

Go:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gtqekunnon.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnhdbhfj.html

C#:   // 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gtvqiteiig.html

[A15] 空值判断与默认值
来源：http://dali.dianchejie.cn/Article/details/gtklvqnknc.html

Py:   value = data or "默认值"
来源：http://dali.vqdsnc.cn/Article/details/gttreflcio.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtjnhqirhf.html

JS:   const value = data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gthmmasnzf.html

TS:   const value = data ?? "默认值";
来源：http://dali.hnqzz.top/Article/details/gtembhpbiw.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.pengpengdd.cyou/Article/details/gtmhkrtnvx.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hnqzz.top/Article/details/gtrbonmtad.html

Ruby: value = data || "默认值"
来源：http://dali.jyoumei.cn/Article/details/gtkgiznvxn.html

C#:   var value = data ?? "默认值";
来源：http://dali.sufxvd.cn/Article/details/gtlnlzwxqg.html

[A16] 真假值判断规则
来源：http://dali.nwbrower.top/Article/details/gttaqbbwgq.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxyuwief.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shangyingyoupin.top/Article/details/gtivxpocyt.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhixingplan.top/Article/details/gturpdifav.html

TS:   if (!x) {}
来源：http://dali.tanke756.top/Article/details/gtbspwgpbn.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ybcxt.top/Article/details/gtuqefgfuu.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.guowangkeji.top/Article/details/gtkwuvmrcm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.smart0.xyz/Article/details/gtagpqxfdy.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcryzgtkv.html

[A17] 位运算
来源：http://dali.cashguo.top/Article/details/gtwkzpinxh.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gtdpifrmtz.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ydzc1.top/Article/details/gtliwmblxg.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gtnihccesw.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gtqifylecr.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gtelscuqoz.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtcmggfevn.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gtwjwzhqff.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gtgjndgvkr.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hammf.cn/Article/details/gtwwgoezqr.html

Py:   ord("A"); chr(65)
来源：http://dali.fengsongda.top/Article/details/gtgdjajkvr.html

PHP:  ord("A"); chr(65)
来源：http://dali.xinyue.icu/Article/details/gtfkmmoxuj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ybcxt.top/Article/details/gtegxithhe.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.daria6918.cn/Article/details/gteajfivxq.html

Java: (int) 'A'; (char) 65
来源：http://dali.vqdsnc.cn/Article/details/gthzvrgadm.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yvedp.cn/Article/details/gtsxitpwqi.html

Ruby: "A".ord; 65.chr
来源：http://dali.ppjwa.cn/Article/details/gtbjwgjknr.html

C#:   (int)'A'; (char)65
来源：http://dali.zhixingplan.top/Article/details/gthbjwirnv.html

[A19] 交换两个变量
来源：http://dali.cqqwz.cn/Article/details/gtabovyrmf.html

Py:   a, b = b, a
来源：http://dali.snrcjt.cn/Article/details/gtjkfniopl.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.iojbl.cn/Article/details/gtvgisdwbv.html

JS:   [a, b] = [b, a];
来源：http://dali.chenjidiqi.icu/Article/details/gtsjnjophr.html

TS:   [a, b] = [b, a];
来源：http://dali.xylfe.cn/Article/details/gtbdisxfka.html

Java: int t = a; a = b; b = t;
来源：http://dali.sysykeji.top/Article/details/gtrumlxeoc.html

Go:   a, b = b, a
来源：http://dali.yangfankeji.com/Article/details/gteryjbfyk.html

Ruby: a, b = b, a
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhclaxih.html

C#:   (a, b) = (b, a);
来源：http://dali.tian-w.cn/Article/details/gtsmwdnize.html

[A20] 读取标准输入
来源：http://dali.haohaochexian.top/Article/details/gtslxsrqlj.html

Py:   name = input("请输入：")
来源：http://dali.mhx1999.top/Article/details/gtxqfncorx.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.gotoacloud.top/Article/details/gtwawgtran.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.chenzaomai.com/Article/details/gtselovmxy.html

TS:   // Node.js：readline 模块
来源：http://dali.316326.xyz/Article/details/gtdfsnksri.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shangyingyoupin.top/Article/details/gtzjsgtixv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.guowangkeji.top/Article/details/gtpxhuqolv.html

Ruby: gets.chomp
来源：http://dali.hywenlv.cn/Article/details/gtjtkiwvpl.html

C#:   Console.ReadLine();
来源：http://dali.c1oappe.top/Article/details/gtiyjhnoab.html

[A21] 保留指定小数位输出
来源：http://dali.dashuyun.cn/Article/details/gtxichfjkm.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinqigufen.top/Article/details/gtjfzxokks.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gtqkmzavfw.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtzmsavoqm.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gthxuhmhra.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhixingplan.top/Article/details/gtmfwwsldi.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtereneslm.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.gotoacloud.top/Article/details/gtngrqmawu.html

C#:   3.14159.ToString("F2")
来源：http://dali.ybcxt.top/Article/details/gthqwwkagn.html

[A22] 获取字符串长度
来源：http://dali.yonumen.top/Article/details/gtcpdgdywh.html

Py:   len(s)
来源：http://dali.ydzc1.top/Article/details/gtedvngdxp.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.kuanghao11.cn/Article/details/gtgyqizzgj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.tian-w.cn/Article/details/gtttpbscpo.html

TS:   s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcftzlmut.html

Java: s.length()
来源：http://dali.zhijiandao.cn/Article/details/gtsmcosrgf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hnqzz.top/Article/details/gtuvbmdwas.html

Ruby: s.length
来源：http://dali.yanxiufei.cn/Article/details/gtkmygfrqj.html

C#:   s.Length
来源：http://dali.zdqjudy.top/Article/details/gtykarxxzy.html

[A23] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzlhbroh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.mhx1999.top/Article/details/gtxuaesvdx.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.tianlin.xyz/Article/details/gtsonmdtjl.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhoulong.xyz/Article/details/gtmfowxnxw.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gthlkodcpr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhongyouzk.top/Article/details/gtpxykuwid.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.nanxuanxn.top/Article/details/gtcubvxrks.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.sysykeji.top/Article/details/gtxzewnfmv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhengqikj.top/Article/details/gtnsgwqgwb.html

[A24] 去除首尾空白
来源：http://dali.yvedp.cn/Article/details/gtdpdyyuta.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.dianchejie.cn/Article/details/gtpzjjsevm.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jlsjyb.cn/Article/details/gtecqyfwbu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hywenlv.cn/Article/details/gtcgxszrjt.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xuanzx.com/Article/details/gtdnslgqgu.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.tian-w.cn/Article/details/gtddstgwmo.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhijiandao.cn/Article/details/gtuuvcxleh.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yj20258.top/Article/details/gtxwqqbouf.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.birdmap.top/Article/details/gtmqavgklx.html

[A25] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gthcsehlzb.html

Py:   s1 == s2; s1 != s2
来源：http://dali.tianlin.xyz/Article/details/gttvjzfxaf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yj20258888.top/Article/details/gtkjzizjjj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gtiumckhuk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gzhubu.top/Article/details/gtiyrkhvcu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.pycfn.com/Article/details/gthyuacekm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhoulong.xyz/Article/details/gtuufcoeyn.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gogol.net.cn/Article/details/gtllmwgtfu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.daxiang520.top/Article/details/gtbatupdop.html

[A26] 类型转换总览
来源：http://dali.yuanzhike.top/Article/details/gtjeprfgny.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zycfv.cn/Article/details/gtihohixjk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yj20258.top/Article/details/gttbdpuude.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ppjwa.cn/Article/details/gthqcnnrjm.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nanxuanxn.top/Article/details/gtgqofwyws.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.tian-w.cn/Article/details/gtchlovmvk.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cdnleiting.top/Article/details/gtzzrmotzq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shuidangran.top/Article/details/gtrnwuqyrh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xinyue.icu/Article/details/gtbmgwwpoj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtubnhzozi.html

B. 流程控制
来源：http://dali.tanke756.top/Article/details/gtcmzwsuel.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtifyuuruf.html

[B01] 条件判断 if / else
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbivdjiua.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhoulong.xyz/Article/details/gtvobttcdz.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinqigfzy.top/Article/details/gticnucvry.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gtrlsjkizk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gteizoqdno.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xziqi.cn/Article/details/gtalqhasuq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xziqi.cn/Article/details/gtrcajvdoo.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shuidangran.top/Article/details/gtwpenriww.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gthjfzbhix.html

[B02] 多分支 else if / elif
来源：http://dali.yongpay.top/Article/details/gtvwvlwjje.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.smart0.xyz/Article/details/gtcqgvdngc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gogol.net.cn/Article/details/gtcfxbfqgm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenjidiqi.icu/Article/details/gtgheuqjio.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gtbahefqfr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gtxwhilsmg.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.chenjidiqi.icu/Article/details/gtxtlghjaa.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhengqikj.top/Article/details/gtekbtazcd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gtegblgbkh.html

[B03] switch / match / case
来源：http://dali.jinqigfzy.top/Article/details/gteiehczbn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.fengsongda.top/Article/details/gterehgggd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gtocwigpqv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.vqdsnc.cn/Article/details/gtkboayhdb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.andypj.xyz/Article/details/gtpvwwznmn.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gtmtsqfebh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tanke756.top/Article/details/gtlqekfvhw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sysykeji.top/Article/details/gtpayrwygj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj20258888.top/Article/details/gthmdnfxwd.html

[B04] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gtssgewpra.html

Py:   for i in range(10): print(i)
来源：http://dali.zdqjudy.top/Article/details/gtobzvwiij.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xinyue.icu/Article/details/gtrjbzypdk.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gthbwxrvau.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dianchejie.cn/Article/details/gtbtxxknxa.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jiagoushi.top/Article/details/gtcggohkrg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zycfv.cn/Article/details/gtfndrktfx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yangfankeji.com/Article/details/gtkjlvevpx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.0kj1m.cn/Article/details/gtmwrssajf.html

[B05] 遍历数组 / 列表
来源：http://dali.iojbl.cn/Article/details/gttqtrsgnk.html

Py:   for item in arr: print(item)
来源：http://dali.yuanzhike.top/Article/details/gtrvglbogl.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.c1oappe.top/Article/details/gtfvcjytvf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xinyue.icu/Article/details/gtqgjynngu.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.haohaochexian.top/Article/details/gthzbojfha.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.smart0.xyz/Article/details/gtzxowitdj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgfzy.top/Article/details/gtxcixubmc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.nwbrower.top/Article/details/gtmuxptcwu.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hammf.cn/Article/details/gtrkhyqxox.html

[B06] 遍历字典 / 对象
来源：http://dali.yj202588.top/Article/details/gtqtrkglho.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nanxinkj.top/Article/details/gtioxswjfk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ydzc1.top/Article/details/gtegmmzrps.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ybcxt.top/Article/details/gtzymljnlt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sweek.top/Article/details/gtmtatbxnp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.pycfn.com/Article/details/gtnrheqkky.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.birdmap.top/Article/details/gtfcxswqmz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sweek.top/Article/details/gtegjbkain.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jlsjyb.cn/Article/details/gtfguigsux.html

[B07] while 循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gthziomatj.html

Py:   while i < 10: i += 1
来源：http://dali.kuanghao11.cn/Article/details/gtycjndywo.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yonumen.top/Article/details/gtalnsrgoh.html

JS:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gtpxkixwwm.html

TS:   while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gtbeprudbd.html

Java: while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gtdmbktspr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.daria6918.cn/Article/details/gtxwhfdezo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgzhyrvb.html

C#:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtcobzypmx.html

[B08] do-while（至少执行一次）
来源：http://dali.shzxlz.cn/Article/details/gtufvznhkg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tianlin.xyz/Article/details/gtuopdntsw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.andypj.xyz/Article/details/gtsveavjhn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gthnyxfsba.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gttfkqnfxh.html

Java: do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtylfapugs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gzhubu.top/Article/details/gtuabkpjlp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj20258.top/Article/details/gtpefbubrr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtriryrdoj.html

[B09] break 与 continue
来源：http://dali.zhengqikj.top/Article/details/gtgzttofbs.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.vqdsnc.cn/Article/details/gtxnxxzxjk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtjtaidjvp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtlnztcvgu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtvxrciwmr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtgsxfaxmu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ivvv.top/Article/details/gtlymcceox.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.aibaodan.cn/Article/details/gtrexmqvst.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtcbjeozai.html

[B10] 遍历同时拿索引
来源：http://dali.zhongyouzk.top/Article/details/gtqnuyxaql.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.havefunace.top/Article/details/gtxqgvcvcm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yuxming.cn/Article/details/gtpodysvnn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gtnikqmxuo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.guowangkeji.top/Article/details/gtedowncjq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenzaomai.com/Article/details/gtieymxsgp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ydzc1.top/Article/details/gtsewoqkbr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.andypj.xyz/Article/details/gtbayvdalg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sxryk.cn/Article/details/gtnowbohkk.html

[B11] 生成数字序列 / 区间
来源：http://dali.jyoumei.cn/Article/details/gtimuxtsyc.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinqigufen.top/Article/details/gtqnxwlfkq.html

PHP:  range(0, 10, 2);
来源：http://dali.ehwqpu.com/Article/details/gtzimdysdq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gtvelzkumz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnqzz.top/Article/details/gtrwnsvkoi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yvedp.cn/Article/details/gtfusqaujl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhongyouzk.top/Article/details/gtmcglmykg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhongyouzk.top/Article/details/gtrvgwzrvk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xziqi.cn/Article/details/gtgotdzrjy.html

[B12] 跳出多层循环
来源：http://dali.haohaochexian.top/Article/details/gtanohnlex.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aibaodan.cn/Article/details/gtdfsvdtox.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.mhx1999.top/Article/details/gtgqqreevs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtokofryxf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtxfjwyfbj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gtzwtwejtl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tianlin.xyz/Article/details/gtruxjznux.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.0kj1m.cn/Article/details/gtnipqsnsy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.wangdashe.top/Article/details/gtvumvnebm.html

[B13] 判断是否为数字
来源：http://dali.fengsongda.top/Article/details/gtwvwsbxck.html

Py:   isinstance(x, (int, float))
来源：http://dali.shzxlz.cn/Article/details/gtqtnohobq.html

PHP:  is_numeric($x)
来源：http://dali.gotoacloud.top/Article/details/gtguiydgrc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gtucwmjasm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gtwrovikvb.html

Java: x instanceof Number
来源：http://dali.nwbrower.top/Article/details/gtjitqapao.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.iojbl.cn/Article/details/gtcourubpb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sweek.top/Article/details/gtsllmptsl.html

C#:   x is int or double or decimal
来源：http://dali.pycfn.com/Article/details/gtwrvfieaz.html

[B14] 判断值是否在集合内
来源：http://dali.bjfxy.top/Article/details/gtmwfrhhxw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnxiangtu.top/Article/details/gtayinxuad.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shangyingyoupin.top/Article/details/gtwvabosef.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtsgfbasya.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gtitpcqaai.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtjclahfnv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.havefunace.top/Article/details/gtqiywvjdc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtzpyrhcsk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sxryk.cn/Article/details/gtbnmahbkh.html

[B15] 布尔运算与取反
来源：http://dali.quarkkingdee.top/Article/details/gtvosnzlud.html

Py:   a and b or not c
来源：http://dali.yj20258.top/Article/details/gtgkgasugc.html

PHP:  $a && $b || !$c
来源：http://dali.jinqigfzy.top/Article/details/gtkapjhmhx.html

JS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gthfmdfpzj.html

TS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwajpfomk.html

Java: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtqfedeckq.html

Go:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtvrfqsqyp.html

Ruby: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtquwzimil.html

C#:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtcofwcwhq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cucudq.cn/Article/details/gtebczrjqh.html

Py:   if not data: return
来源：http://dali.pengpengdd.cyou/Article/details/gtsbiikpty.html

PHP:  if (!$data) { return; }
来源：http://dali.jlsjyb.cn/Article/details/gttdxawfmt.html

JS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gtppjvramv.html

TS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtqlpuxcee.html

Java: if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gtwaeyuhnx.html

Go:   if data == nil { return }
来源：http://dali.mhx1999.top/Article/details/gtuftzqmok.html

Ruby: return if data.nil?
来源：http://dali.chenjidiqi.icu/Article/details/gtsobhywru.html

C#:   if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gthhubbrhc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjbyzruet.html

C. 函数与作用域
来源：http://dali.xinyue.icu/Article/details/gtnhmtmwpz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtpgjzykzq.html

[C01] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtjfmaxgva.html

Py:   def add(a, b): return a + b
来源：http://dali.ivvv.top/Article/details/gtlepawiqr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtdcvxxaxe.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtgloeqozj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtrikipfed.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtcohffbln.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tianlin.xyz/Article/details/gtpqnjrmyj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cdnleiting.top/Article/details/gtzmmhjggk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtdvmpzrbv.html

[C02] 默认参数
来源：http://dali.havefunace.top/Article/details/gttwknngua.html

Py:   def greet(name="World"): return name
来源：http://dali.ybcxt.top/Article/details/gtiptezktz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yonumen.top/Article/details/gtfuqrtemv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtlhmiitpn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtwelvjrvk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gtuioqfkln.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ybcxt.top/Article/details/gtjwqrjewf.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmkeiaye.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.aibaodan.cn/Article/details/gtsbppdbym.html

[C03] 可变参数
来源：http://dali.chenzaomai.com/Article/details/gtoroujmre.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfnnrdzq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258.top/Article/details/gtzqnyqcvk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gttrduelqw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gtajlvgxjd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yanxiufei.cn/Article/details/gtmtdnohzy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuanzx.com/Article/details/gtqebqkfvx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yueranfly.top/Article/details/gtlpjxrmap.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuxming.cn/Article/details/gtislgfhib.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hammf.cn/Article/details/gthrrtpcvg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yanxiufei.cn/Article/details/gtvtcfbohg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj202588.top/Article/details/gtadakogiw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gtambnmois.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fengsongda.top/Article/details/gtbbgrivld.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hammf.cn/Article/details/gtvqyapglj.html

Go:   // 无：用配置结构体参数
来源：http://dali.sxryk.cn/Article/details/gtgthmwvia.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gtkloloqud.html

C#:   f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtvdgxnulp.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gtouficfeo.html


<!-- 参考信息 -->