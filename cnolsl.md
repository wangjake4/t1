代发 wailian999

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.snrcjt.cn/Article/details/gtyqawefpz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gtdardbfzi.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhengqikj.top/Article/details/gtyqtxgido.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.smart0.xyz/Article/details/gttcpkavmj.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.bjfxy.top/Article/details/gtmldqkdzx.html

JS:   `Hello, ${name}!`
来源：http://dali.xuanzx.com/Article/details/gtidxgkevp.html

TS:   `Hello, ${name}!`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzueulia.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.sweek.top/Article/details/gtkndncvne.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jlsjyb.cn/Article/details/gtzyyzabid.html

Ruby: "Hello, #{name}!"
来源：http://dali.yueranfly.top/Article/details/gthieknjqu.html

C#:   $"Hello, {name}!"
来源：http://dali.fzhhl.top/Article/details/gtyncvjcbz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hnxiangtu.top/Article/details/gtzjjhontu.html

Py:   "第一行\n第二行"
来源：http://dali.yj20258888.top/Article/details/gticdsmhdp.html

PHP:  "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtuuprjhng.html

JS:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gtyywqvvhd.html

TS:   "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gtommosmbu.html

Java: "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtjygjknav.html

Go:   "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gttlvpqrbt.html

Ruby: "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtaiyedwmb.html

C#:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gtsukjxxnu.html

[A14] 注释写法
来源：http://dali.quarkkingdee.top/Article/details/gtybffoimu.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhcwderm.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.cqqwz.cn/Article/details/gtqicisury.html

JS:   // 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gtescjgjeu.html

TS:   // 单行；/* 多行 */
来源：http://dali.0kj1m.cn/Article/details/gtfsiiport.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.dianchejie.cn/Article/details/gttzwiitvp.html

Go:   // 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gtdeiotvzg.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.svipenyu.cn/Article/details/gtdctimtqs.html

C#:   // 单行；/* 多行 */
来源：http://dali.yueranfly.top/Article/details/gtlmkeetnb.html

[A15] 空值判断与默认值
来源：http://dali.nanxinkj.top/Article/details/gtjkxsiial.html

Py:   value = data or "默认值"
来源：http://dali.tanke756.top/Article/details/gtthckxbng.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hywenlv.cn/Article/details/gtxkiutxit.html

JS:   const value = data ?? "默认值";
来源：http://dali.c1oappe.top/Article/details/gtylkfycys.html

TS:   const value = data ?? "默认值";
来源：http://dali.fzhhl.top/Article/details/gtnetguwld.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvukztpqe.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrkkqmgh.html

Ruby: value = data || "默认值"
来源：http://dali.hongshengwenyu.top/Article/details/gtltpjvksx.html

C#:   var value = data ?? "默认值";
来源：http://dali.zycfv.cn/Article/details/gtnmzsupkn.html

[A16] 真假值判断规则
来源：http://dali.ppjwa.cn/Article/details/gtqpkoiktc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shzxlz.cn/Article/details/gtwmgthvqr.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jlsjyb.cn/Article/details/gtkgmzacka.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hammf.cn/Article/details/gtrgmsjida.html

TS:   if (!x) {}
来源：http://dali.bjfxy.top/Article/details/gthwclasjd.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtqzrateuv.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.snrcjt.cn/Article/details/gtpafrakud.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zdqjudy.top/Article/details/gtywigbcqb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zycfv.cn/Article/details/gtxlftfirv.html

[A17] 位运算
来源：http://dali.nanxuanxn.top/Article/details/gthvamxiwa.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtswmamghu.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.gzhubu.top/Article/details/gtezjysord.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sysykeji.top/Article/details/gtywdlvanz.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gtwimgsvxb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gtalkqimct.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gtppkkwibx.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gtzrgcaaih.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gtbgwdczjd.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jiagoushi.top/Article/details/gtledwikej.html

Py:   ord("A"); chr(65)
来源：http://dali.316326.xyz/Article/details/gtyzqgfhds.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhengqikj.top/Article/details/gtspneqdyf.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.chenjidiqi.icu/Article/details/gtiersolbj.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tianlin.xyz/Article/details/gtuvwjnqnk.html

Java: (int) 'A'; (char) 65
来源：http://dali.9152youxi.cn/Article/details/gtscazrfyp.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhixingplan.top/Article/details/gtuoectpgz.html

Ruby: "A".ord; 65.chr
来源：http://dali.sweek.top/Article/details/gtevixyzfn.html

C#:   (int)'A'; (char)65
来源：http://dali.jiagoushi.top/Article/details/gtgfryrlro.html

[A19] 交换两个变量
来源：http://dali.yvedp.cn/Article/details/gtaicppbvd.html

Py:   a, b = b, a
来源：http://dali.ehwqpu.com/Article/details/gtfeuqjbqx.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ydzc1.top/Article/details/gtbblznwma.html

JS:   [a, b] = [b, a];
来源：http://dali.snrcjt.cn/Article/details/gttkiscvjo.html

TS:   [a, b] = [b, a];
来源：http://dali.jinqigufen.top/Article/details/gticonihfi.html

Java: int t = a; a = b; b = t;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxsliucg.html

Go:   a, b = b, a
来源：http://dali.shuidangran.top/Article/details/gtazxspvef.html

Ruby: a, b = b, a
来源：http://dali.redwolf501.top/Article/details/gthlwwuawp.html

C#:   (a, b) = (b, a);
来源：http://dali.hnxiangtu.top/Article/details/gtkaisreal.html

[A20] 读取标准输入
来源：http://dali.xziqi.cn/Article/details/gtsekibxmq.html

Py:   name = input("请输入：")
来源：http://dali.jinqigufen.top/Article/details/gtjfsbdrpu.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jqgfzy.top/Article/details/gtxoqiipcr.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.gotoacloud.top/Article/details/gtsibthvsv.html

TS:   // Node.js：readline 模块
来源：http://dali.yueranfly.top/Article/details/gtcuxgdrww.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ybcxt.top/Article/details/gtrsvawihs.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jlsjyb.cn/Article/details/gtpvqslkoa.html

Ruby: gets.chomp
来源：http://dali.nanxinkj.top/Article/details/gttxubtync.html

C#:   Console.ReadLine();
来源：http://dali.tian-w.cn/Article/details/gtugqspior.html

[A21] 保留指定小数位输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzaujsfyc.html

Py:   f"{3.14159:.2f}"
来源：http://dali.pycfn.com/Article/details/gtgfbxqtrt.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.guowangkeji.top/Article/details/gtwojjexzw.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gtnswuczty.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtnqjetahh.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.mhx1999.top/Article/details/gtakfyhbih.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yanxiufei.cn/Article/details/gtnybjfhut.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.bjfxy.top/Article/details/gtynpzqhgr.html

C#:   3.14159.ToString("F2")
来源：http://dali.jyoumei.cn/Article/details/gteavqvvre.html

[A22] 获取字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtcipahqbj.html

Py:   len(s)
来源：http://dali.guannengcc.top/Article/details/gtohyzcpao.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xylfe.cn/Article/details/gtspiwbmff.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shangyingyoupin.top/Article/details/gtoiaelvlk.html

TS:   s.length
来源：http://dali.hywenlv.cn/Article/details/gtuoqtkdvi.html

Java: s.length()
来源：http://dali.iojbl.cn/Article/details/gtqceumezw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.fengsongda.top/Article/details/gtnyzgpnjh.html

Ruby: s.length
来源：http://dali.andypj.xyz/Article/details/gtbctxvtak.html

C#:   s.Length
来源：http://dali.yuanzhike.top/Article/details/gtdmkctrhn.html

[A23] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtcdcmibmt.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxelnvrx.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.kuanghao11.cn/Article/details/gthpiyyzre.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258888.top/Article/details/gtzbkhmkie.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dashuyun.cn/Article/details/gttykzmirh.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ppjwa.cn/Article/details/gtgnkodvnj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.pycfn.com/Article/details/gtxkrlcrjv.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.9152youxi.cn/Article/details/gtuxyyuqhh.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinqigufen.top/Article/details/gtppmczluy.html

[A24] 去除首尾空白
来源：http://dali.birdmap.top/Article/details/gtvsgukcgq.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jianghu66.top/Article/details/gtedwhscrt.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.gotoacloud.top/Article/details/gtcobnjdiq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ybcxt.top/Article/details/gtmfubrebz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ivvv.top/Article/details/gtxicecdzk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.quarkkingdee.top/Article/details/gtgtzmhcnc.html

Go:   strings.TrimSpace(s)
来源：http://dali.jqgufenzy.top/Article/details/gtadewptgp.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.chenzaomai.com/Article/details/gtfkzatpwh.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtriyadqwx.html

[A25] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtkkljskaw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jqgufenzy.top/Article/details/gttcqbhhxo.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtxwtxvjxs.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.kuanghao11.cn/Article/details/gtxoxuextb.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.daria6918.cn/Article/details/gtzotfpnht.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhjpvngv.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hfpthk.cn/Article/details/gtbqulhlfg.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.daxiang520.top/Article/details/gtnoqzbxvx.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yanxiufei.cn/Article/details/gtpniwfoec.html

[A26] 类型转换总览
来源：http://dali.yangfankeji.com/Article/details/gtmehqnvzb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yanxiufei.cn/Article/details/gtlaosgyvk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.redwolf501.top/Article/details/gtvsgxirgl.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.meibo888.top/Article/details/gtnferfmum.html

TS:   Number() String() Boolean() x as number
来源：http://dali.guowangkeji.top/Article/details/gtwknlvofp.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.chenzaomai.com/Article/details/gtlixctcbl.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.nanxinkj.top/Article/details/gtbafptzny.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.0kj1m.cn/Article/details/gtpgahtccx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.meibo888.top/Article/details/gthhjvnvkf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtvkteqerv.html

B. 流程控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayriycaf.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtklnrdipd.html

[B01] 条件判断 if / else
来源：http://dali.nanxuanxn.top/Article/details/gtkxdisxut.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdzgffwe.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.bjfxy.top/Article/details/gtgqpfvvte.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenzaomai.com/Article/details/gttdbuwkwn.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gtntnlibeo.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gtudcwjxpm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hongshengwenyu.top/Article/details/gtimcdgjll.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.mhx1999.top/Article/details/gttppparsr.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gtsutsjbdc.html

[B02] 多分支 else if / elif
来源：http://dali.sweek.top/Article/details/gtshlkhvmf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.nanxuanxn.top/Article/details/gtajclnsra.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sweek.top/Article/details/gtejxfhyuc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gtisezoyyb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gtlrlylthh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtbhybgohs.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhiwuduotai.top/Article/details/gtkqgimvrm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.guannengcc.top/Article/details/gthqmuifte.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gtmxsodjfh.html

[B03] switch / match / case
来源：http://dali.pengpengdd.cyou/Article/details/gtlhskpduv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhengqikj.top/Article/details/gtbvhyhqly.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtlpvnagzm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gttfenhnnb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtzghdviag.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gtbhbojzhx.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gtnaocddql.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.andypj.xyz/Article/details/gtlxqpbkyb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj20258888.top/Article/details/gttqxczokt.html

[B04] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gtxbmbjtji.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxuanxn.top/Article/details/gtsfqbwuuk.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gotoacloud.top/Article/details/gtuholehfj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuxming.cn/Article/details/gtzsbvjqqi.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gtkkywaaax.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shuidangran.top/Article/details/gtslymsjwv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.wangshuangyany.cn/Article/details/gtqifwbiem.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhongyouzk.top/Article/details/gtzhwhncku.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtsgfadydg.html

[B05] 遍历数组 / 列表
来源：http://dali.yanxiufei.cn/Article/details/gtbvhjeowp.html

Py:   for item in arr: print(item)
来源：http://dali.sysykeji.top/Article/details/gtwtfidsbd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shuidangran.top/Article/details/gtoxdvudsh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aibaodan.cn/Article/details/gttybmasqr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgfzy.top/Article/details/gtvbupexdu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gtkllkuwfg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aizwys.cn/Article/details/gtcbnjiowc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jiagoushi.top/Article/details/gtfefhohig.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zdqjudy.top/Article/details/gtfyqoarsq.html

[B06] 遍历字典 / 对象
来源：http://dali.svipenyu.cn/Article/details/gtudcpdmwf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.fengsongda.top/Article/details/gtdkfofhvb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cqqwz.cn/Article/details/gteyjwmhtr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gtxpdruqsc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhiwuduotai.top/Article/details/gttojaiqhy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.quarkkingdee.top/Article/details/gtlgzhrvdv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sweek.top/Article/details/gtgxvlcntk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hnxiangtu.top/Article/details/gtblmkuyqb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgufenzy.top/Article/details/gtoocjfrbi.html

[B07] while 循环
来源：http://dali.shzxlz.cn/Article/details/gtbfalovbg.html

Py:   while i < 10: i += 1
来源：http://dali.tanke756.top/Article/details/gtvuyrdemu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtylatrvij.html

JS:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtwjbyabmt.html

TS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gtjakqpcvm.html

Java: while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtwbjrxffw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yonumen.top/Article/details/gtgelyzzxr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigufen.top/Article/details/gtgoccirrs.html

C#:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gtgyrmvfdk.html

[B08] do-while（至少执行一次）
来源：http://dali.zhiwuduotai.top/Article/details/gtbcnfbpfo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj20258888.top/Article/details/gttgbblgbs.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtojrrbmys.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtiemrpyoa.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gtubvhmacf.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtkymtqwqx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sxryk.cn/Article/details/gtkbtnzwyc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.iojbl.cn/Article/details/gtzmfcaxdh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmljhiuv.html

[B09] break 与 continue
来源：http://dali.yuanzhike.top/Article/details/gtfbdqorod.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.snrcjt.cn/Article/details/gtwavgyueh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtppxmwyqm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gttumhsuly.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtrycdexll.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtflppeqtr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj20258.top/Article/details/gtryyethll.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cucudq.cn/Article/details/gtpcjojacz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgyayxmj.html

[B10] 遍历同时拿索引
来源：http://dali.jqgfzy.top/Article/details/gtrkhbtbit.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxrbkpva.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.kuanghao11.cn/Article/details/gtgrgxhhje.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.svipenyu.cn/Article/details/gtbmccpcin.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhiwuduotai.top/Article/details/gtxccoxybp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.smart0.xyz/Article/details/gtioenyvin.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gotoacloud.top/Article/details/gtnvbgyshd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ivvv.top/Article/details/gtgihxkfwt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gtlmzayfdx.html

[B11] 生成数字序列 / 区间
来源：http://dali.sysykeji.top/Article/details/gtiohycvnn.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhongyouzk.top/Article/details/gtldndxtre.html

PHP:  range(0, 10, 2);
来源：http://dali.ybcxt.top/Article/details/gtcjlqdhoz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gtuqmvdlqo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gtsnmojgmi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtpfkalyyh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dashuyun.cn/Article/details/gtegyqjdqx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsithwfou.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkrkhgho.html

[B12] 跳出多层循环
来源：http://dali.cheryme.top/Article/details/gtwgmqrvff.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cucudq.cn/Article/details/gtgkpwmweg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gtvjkagekt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtksjzdsgc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtwjdsjhpf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtlbnpsqvy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnxiangtu.top/Article/details/gtazakkong.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.birdmap.top/Article/details/gtkqoxdend.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.bjfxy.top/Article/details/gtotfkfetw.html

[B13] 判断是否为数字
来源：http://dali.zycfv.cn/Article/details/gtfmyievjo.html

Py:   isinstance(x, (int, float))
来源：http://dali.sxryk.cn/Article/details/gtgtdjmwvy.html

PHP:  is_numeric($x)
来源：http://dali.sysykeji.top/Article/details/gtpgqosfco.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.mhx1999.top/Article/details/gtnguubbrv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gtripbllbg.html

Java: x instanceof Number
来源：http://dali.tian-w.cn/Article/details/gtjfzakbtd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ybcxt.top/Article/details/gtcmpkhnux.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tanke756.top/Article/details/gtmewiuewo.html

C#:   x is int or double or decimal
来源：http://dali.tianlin.xyz/Article/details/gtvtryeied.html

[B14] 判断值是否在集合内
来源：http://dali.xinyue.icu/Article/details/gtsyehjryq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shuidangran.top/Article/details/gtvblvxdtj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuanzhike.top/Article/details/gtibvcotwx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtckjnbgha.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtlguztxoe.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtbwglocwc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhixingplan.top/Article/details/gtvvnnjbuc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gttgnltvhy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtrwzimzvq.html

[B15] 布尔运算与取反
来源：http://dali.zhengqikj.top/Article/details/gtsnlmfbtq.html

Py:   a and b or not c
来源：http://dali.tian-w.cn/Article/details/gtalwztqgh.html

PHP:  $a && $b || !$c
来源：http://dali.snrcjt.cn/Article/details/gtvqtbjtcw.html

JS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtxvsezfwj.html

TS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtsojocxoh.html

Java: a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtctjptlqy.html

Go:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gthoyqvpbi.html

Ruby: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwuzwqnqz.html

C#:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtffznvnbo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fengsongda.top/Article/details/gtqkmuztjm.html

Py:   if not data: return
来源：http://dali.xinyue.icu/Article/details/gttprhizst.html

PHP:  if (!$data) { return; }
来源：http://dali.yj202588.top/Article/details/gtmsutipyu.html

JS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gtudobmzxp.html

TS:   if (!data) return;
来源：http://dali.sxryk.cn/Article/details/gtfhsdsfni.html

Java: if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gtcjfgojyu.html

Go:   if data == nil { return }
来源：http://dali.jinghuilouyu.cn/Article/details/gtppyjpgnp.html

Ruby: return if data.nil?
来源：http://dali.sysykeji.top/Article/details/gtjspmkdsb.html

C#:   if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapxwmuyt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtslqfxvfv.html

C. 函数与作用域
来源：http://dali.yueranfly.top/Article/details/gtqgzgzcpp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpcgfdnz.html

[C01] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtvllpmggc.html

Py:   def add(a, b): return a + b
来源：http://dali.aibaodan.cn/Article/details/gtvczunqpr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gtkbyttypx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtuvtlixsu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtujtfxexz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtdsgoiflf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.316326.xyz/Article/details/gtqnnwfejz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnxiangtu.top/Article/details/gtozkrvrzc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtjipmmxvg.html

[C02] 默认参数
来源：http://dali.xylfe.cn/Article/details/gtfpuofmzk.html

Py:   def greet(name="World"): return name
来源：http://dali.zhixingplan.top/Article/details/gtbdsqfsbi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ppjwa.cn/Article/details/gtrcfrpnry.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtvhorizym.html


<!-- 参考信息 -->