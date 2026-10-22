代发 wailian999

[A06] 字符串转数字
来源：http://dali.zycfv.cn/Article/details/gtzxlqwotb.html

Py:   int("42"); float("3.14")
来源：http://dali.xylfe.cn/Article/details/gtquujjxmg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.fengsongda.top/Article/details/gttwglgpll.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yj20258.top/Article/details/gtymoqdizx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.gzhubu.top/Article/details/gtjbpxijnl.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.mhx1999.top/Article/details/gtngpklxni.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hnxiangtu.top/Article/details/gtbnfioetx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yj20258.top/Article/details/gtnshrvuuj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.cdnleiting.top/Article/details/gtemrcaact.html

[A07] 数字转字符串
来源：http://dali.yueranfly.top/Article/details/gtqrohwuwx.html

Py:   str(42)
来源：http://dali.jianghu66.top/Article/details/gtxrgcwoyg.html

PHP:  (string) 42; strval(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjdjosvi.html

JS:   String(42); (42).toString()
来源：http://dali.yanxiufei.cn/Article/details/gtcqgmufrn.html

TS:   String(42)
来源：http://dali.jqgfzy.top/Article/details/gtbjsgvmuc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.fengsongda.top/Article/details/gtpqjtcxqq.html

Go:   strconv.Itoa(42)
来源：http://dali.meibo888.top/Article/details/gtyvpwslnr.html

Ruby: 42.to_s
来源：http://dali.cashguo.top/Article/details/gtwvgbmhgw.html

C#:   42.ToString()
来源：http://dali.dashuyun.cn/Article/details/gtrtrozohb.html

[A08] 取整与四舍五入
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvbknkrk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzrnehmo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.chenzaomai.com/Article/details/gtcjrthzqs.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.smart0.xyz/Article/details/gtmigyvizf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hnxiangtu.top/Article/details/gtrllrnkfs.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tanke756.top/Article/details/gtfynnsbou.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gtjixsqnnl.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.chenlongwang.top/Article/details/gtbnufjgla.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gtmyzgybyz.html

[A09] 绝对值与最大最小值
来源：http://dali.sufxvd.cn/Article/details/gtjgxzqkdi.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtaccydypg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtxckhbbvs.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtsvqckxgl.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.birdmap.top/Article/details/gtxmjohxag.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfhufjge.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hnxiangtu.top/Article/details/gtgxjrmkbf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yvedp.cn/Article/details/gtgxecclyp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtiefegqwp.html

[A10] 生成随机数
来源：http://dali.jiagoushi.top/Article/details/gtjuebkkqn.html

Py:   import random; random.randint(1, 100)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflygimca.html

PHP:  random_int(1, 100);
来源：http://dali.xziqi.cn/Article/details/gthcdplgkf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.mhx1999.top/Article/details/gtmfwummpz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.daria6918.cn/Article/details/gtwwoagvyh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xuetiantiany.cn/Article/details/gtctjjtigx.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.vqdsnc.cn/Article/details/gtovmhduko.html

Ruby: rand(1..100)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkupzuvhc.html

C#:   new Random().Next(1, 101)
来源：http://dali.iojbl.cn/Article/details/gtxutimtup.html

[A11] 条件表达式（三元）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszwtvhig.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.guannengcc.top/Article/details/gtytbvldii.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gtinmqrord.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gtjyagjfyb.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gtdzrzjdmo.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gtyvofrckb.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.hammf.cn/Article/details/gtsnatpepq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gtmgzliabo.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gthfqrjiwl.html

[A12] 字符串插值 / 格式化
来源：http://dali.sxryk.cn/Article/details/gtboprwjbg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.ybcxt.top/Article/details/gtpbyebukq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.quarkkingdee.top/Article/details/gtuioufawr.html

JS:   `Hello, ${name}!`
来源：http://dali.cdnleiting.top/Article/details/gtxidnmume.html

TS:   `Hello, ${name}!`
来源：http://dali.ppjwa.cn/Article/details/gtcgabvhwq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.feifeiyinyue.top/Article/details/gthqxpamgv.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrhzygii.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhoulong.xyz/Article/details/gtpuncjofy.html

C#:   $"Hello, {name}!"
来源：http://dali.sysykeji.top/Article/details/gtpawralsp.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sweek.top/Article/details/gteqnlyndh.html

Py:   "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gthwtcgkts.html

PHP:  "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscikfggn.html

JS:   "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxoymhluq.html

TS:   "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtuctzvnoz.html

Java: "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtgwbenpuw.html

Go:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gtptfjllbw.html

Ruby: "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gtsfpdmseu.html

C#:   "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gtbnmumebh.html

[A14] 注释写法
来源：http://dali.yj20258888.top/Article/details/gtwbqqlaxl.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.pengpengdd.cyou/Article/details/gtraxbxpfs.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.cucudq.cn/Article/details/gtloolfjwn.html

JS:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gthloocukl.html

TS:   // 单行；/* 多行 */
来源：http://dali.hnxiangtu.top/Article/details/gtoeffysja.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.cashguo.top/Article/details/gtsmtdafub.html

Go:   // 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkjezdpv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.birdmap.top/Article/details/gtihtmyfly.html

C#:   // 单行；/* 多行 */
来源：http://dali.dianchejie.cn/Article/details/gtwxqbzhcq.html

[A15] 空值判断与默认值
来源：http://dali.shuidangran.top/Article/details/gtitplvcol.html

Py:   value = data or "默认值"
来源：http://dali.hfpthk.cn/Article/details/gtjvzspfml.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.nwbrower.top/Article/details/gtefffrjou.html

JS:   const value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gtkqcnbgeh.html

TS:   const value = data ?? "默认值";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgfvhgzd.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yj20258.top/Article/details/gtbpdluypo.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ybcxt.top/Article/details/gtvrnxyidq.html

Ruby: value = data || "默认值"
来源：http://dali.jqgfzy.top/Article/details/gthdcfnrpg.html

C#:   var value = data ?? "默认值";
来源：http://dali.shzxlz.cn/Article/details/gtwenewhqu.html

[A16] 真假值判断规则
来源：http://dali.snrcjt.cn/Article/details/gtagfzdvod.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jqgufenzy.top/Article/details/gtmcbcyctt.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.wangshuangyany.cn/Article/details/gtdyifurdl.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvejkwrr.html

TS:   if (!x) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtarhmozsq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ybcxt.top/Article/details/gtaoowcruc.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.meibo888.top/Article/details/gtlmewhalg.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzvggerp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.daxiang520.top/Article/details/gtremkqkvf.html

[A17] 位运算
来源：http://dali.jyoumei.cn/Article/details/gteicrrach.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gtvxslphpn.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yvedp.cn/Article/details/gtyivtoukt.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtxnvlszpm.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gtfurovhyf.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtzagqsixy.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtilbtgonm.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgapxmmkk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gttptmirdu.html

[A18] 字符与 ASCII 码互转
来源：http://dali.316326.xyz/Article/details/gtqybzraem.html

Py:   ord("A"); chr(65)
来源：http://dali.nanxuanxn.top/Article/details/gtfmpjwbki.html

PHP:  ord("A"); chr(65)
来源：http://dali.zdqjudy.top/Article/details/gtsyxfnhkb.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.snrcjt.cn/Article/details/gtathnqddk.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkigtplk.html

Java: (int) 'A'; (char) 65
来源：http://dali.ybcxt.top/Article/details/gtjnwreiqu.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xylfe.cn/Article/details/gtllrdoduo.html

Ruby: "A".ord; 65.chr
来源：http://dali.shuidangran.top/Article/details/gtlecalfzd.html

C#:   (int)'A'; (char)65
来源：http://dali.yuanzhike.top/Article/details/gteebhoeav.html

[A19] 交换两个变量
来源：http://dali.fengsongda.top/Article/details/gtqtqmnfne.html

Py:   a, b = b, a
来源：http://dali.pycfn.com/Article/details/gtmidbnksn.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.wangdashe.top/Article/details/gtqndooyzu.html

JS:   [a, b] = [b, a];
来源：http://dali.hammf.cn/Article/details/gtozlrzkrb.html

TS:   [a, b] = [b, a];
来源：http://dali.jinghuilouyu.cn/Article/details/gtwosdlfmg.html

Java: int t = a; a = b; b = t;
来源：http://dali.guannengcc.top/Article/details/gtplcrnrgz.html

Go:   a, b = b, a
来源：http://dali.chenjidiqi.icu/Article/details/gtfbaxvcqk.html

Ruby: a, b = b, a
来源：http://dali.shzxlz.cn/Article/details/gtlwewwqdg.html

C#:   (a, b) = (b, a);
来源：http://dali.kuanghao11.cn/Article/details/gtwayajdgt.html

[A20] 读取标准输入
来源：http://dali.cdnleiting.top/Article/details/gtsgerxnpr.html

Py:   name = input("请输入：")
来源：http://dali.hongshengwenyu.top/Article/details/gtajovkfpn.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hammf.cn/Article/details/gtlatghkfa.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.0kj1m.cn/Article/details/gtfkzffzhu.html

TS:   // Node.js：readline 模块
来源：http://dali.cucudq.cn/Article/details/gtfyvpnfzd.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hammf.cn/Article/details/gtenkwbarn.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hnqzz.top/Article/details/gtyyftgdpq.html

Ruby: gets.chomp
来源：http://dali.gogol.net.cn/Article/details/gteqaolrmk.html

C#:   Console.ReadLine();
来源：http://dali.tian-w.cn/Article/details/gthhgdxprd.html

[A21] 保留指定小数位输出
来源：http://dali.yj202588.top/Article/details/gtpslynvyq.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutmpbnnu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gtmfndzbak.html

JS:   (3.14159).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gtrrqdmyth.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gtwmgvxuep.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gtnxmdfqnk.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gtqgvjobkk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jlsjyb.cn/Article/details/gtyoofehmb.html

C#:   3.14159.ToString("F2")
来源：http://dali.xziqi.cn/Article/details/gtqyydujcd.html

[A22] 获取字符串长度
来源：http://dali.pycfn.com/Article/details/gtrxneindm.html

Py:   len(s)
来源：http://dali.sxryk.cn/Article/details/gthwsduflt.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhaomingkeji.xyz/Article/details/gtergtwbkh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hnqzz.top/Article/details/gtupuzagli.html

TS:   s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcykywghy.html

Java: s.length()
来源：http://dali.fengsongda.top/Article/details/gtjnefihhf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.nanxinkj.top/Article/details/gtutjegxye.html

Ruby: s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymeudesh.html

C#:   s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtnuavgkph.html

[A23] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtuahknmny.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegvljxca.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.daxiang520.top/Article/details/gtxltromqj.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258.top/Article/details/gthlujtwuw.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.guowangkeji.top/Article/details/gteyxonvje.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gtjftvhdky.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhijiandao.cn/Article/details/gttiymldvv.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhengqikj.top/Article/details/gtekvrckwm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.mhx1999.top/Article/details/gtusjzhmfo.html

[A24] 去除首尾空白
来源：http://dali.mhx1999.top/Article/details/gtbyfrqppc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sxryk.cn/Article/details/gtwmiudrou.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.kuanghao11.cn/Article/details/gtwmtjebdi.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gtzqbxwwps.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.quarkkingdee.top/Article/details/gtsmwdyhbm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.andypj.xyz/Article/details/gtztltsmym.html

Go:   strings.TrimSpace(s)
来源：http://dali.daria6918.cn/Article/details/gtaikhnzrt.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.0kj1m.cn/Article/details/gtjrfxhzdz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ybcxt.top/Article/details/gtckdzrcvm.html

[A25] 字符串比较
来源：http://dali.guowangkeji.top/Article/details/gtsfyrmeos.html

Py:   s1 == s2; s1 != s2
来源：http://dali.316326.xyz/Article/details/gtaqugsakf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.meibo888.top/Article/details/gtjggwthvi.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuxming.cn/Article/details/gtlsszeyrp.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jlsjyb.cn/Article/details/gtrjqiusre.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cqqwz.cn/Article/details/gtadtfndmk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.aizwys.cn/Article/details/gthsjzioii.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.nanxinkj.top/Article/details/gtpvniqvgl.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xuanzx.com/Article/details/gtlibtudnx.html

[A26] 类型转换总览
来源：http://dali.nanxinkj.top/Article/details/gtnipcskan.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yangfankeji.com/Article/details/gtwltamuks.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gotoacloud.top/Article/details/gtconzhzio.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hongshengwenyu.top/Article/details/gtluoemjpv.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yongpay.top/Article/details/gtksrvlhdt.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hywenlv.cn/Article/details/gtovuwhodc.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.haohaochexian.top/Article/details/gtojqnqbch.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ivvv.top/Article/details/gtnwapfcqp.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.guowangkeji.top/Article/details/gtvezlqxvd.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxlbxrovi.html

B. 流程控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtqlikip.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtdvcwmunr.html

[B01] 条件判断 if / else
来源：http://dali.cashguo.top/Article/details/gtiruuhfvi.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ivvv.top/Article/details/gtqhzzekhb.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.gaohongyu789.top/Article/details/gtlwmnczhq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gtjmmalroy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gtmmbupfmr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gthurbmklk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xuanzx.com/Article/details/gtmoreidbt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhixingplan.top/Article/details/gtvjjwyzvo.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gtqdcmpbxx.html

[B02] 多分支 else if / elif
来源：http://dali.gogol.net.cn/Article/details/gtcflekpnv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yvedp.cn/Article/details/gtfyzkpihe.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gticuzdfds.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gtogaavfrn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gaohongyu789.top/Article/details/gtashqpvzc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gthswhpfnm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ybcxt.top/Article/details/gtfmxbuije.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jiagoushi.top/Article/details/gtjpsptqyq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gtmmshbstx.html

[B03] switch / match / case
来源：http://dali.yuanzhike.top/Article/details/gtgmscwrxq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.9152youxi.cn/Article/details/gtzpqhmitl.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gthsgtisrw.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtfrcchydp.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gtlvzohhhe.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gtbugzkvel.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmdacylm.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.feifeiyinyue.top/Article/details/gtoyesdvas.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.guannengcc.top/Article/details/gtlylcxtzo.html

[B04] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gtbnpgnzfq.html

Py:   for i in range(10): print(i)
来源：http://dali.dianchejie.cn/Article/details/gtkpqxggzt.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhixingplan.top/Article/details/gtwljcexjn.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guowangkeji.top/Article/details/gtfgsinofa.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhongyouzk.top/Article/details/gtasxzxzpl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.9152youxi.cn/Article/details/gtmfttrbvk.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.0kj1m.cn/Article/details/gtuqvscqhf.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yvedp.cn/Article/details/gtoctvpwvl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.chenlongwang.top/Article/details/gtujcprsxb.html

[B05] 遍历数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gtpgiebgwk.html

Py:   for item in arr: print(item)
来源：http://dali.316326.xyz/Article/details/gtgbynmwdu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.daria6918.cn/Article/details/gtkulwiuhe.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuxming.cn/Article/details/gtgpnkinga.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.smart0.xyz/Article/details/gtwdguytxw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhixingplan.top/Article/details/gtnnxnzfqs.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yueranfly.top/Article/details/gtzawczzql.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigfzy.top/Article/details/gteoxwnpnn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtxnonrmvo.html

[B06] 遍历字典 / 对象
来源：http://dali.svipenyu.cn/Article/details/gtfksqmaps.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.fzhhl.top/Article/details/gtyndorckd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hnqzz.top/Article/details/gtkcbcbfku.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhongyouzk.top/Article/details/gtbdzvzqwf.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.c1oappe.top/Article/details/gtkzyutvlt.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhoulong.xyz/Article/details/gtdexbvctt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jyoumei.cn/Article/details/gtifktwvtt.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxtswvsr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.nanxuanxn.top/Article/details/gtsjafoagk.html

[B07] while 循环
来源：http://dali.snrcjt.cn/Article/details/gthwvzywnd.html

Py:   while i < 10: i += 1
来源：http://dali.ppjwa.cn/Article/details/gtobuacdxm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenlongwang.top/Article/details/gtkqdxvxej.html

JS:   while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gtndeulvob.html

TS:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtxfhqrdzo.html

Java: while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtffjqdjtq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sxryk.cn/Article/details/gtrmkwphed.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tanke756.top/Article/details/gtjvnypcmj.html

C#:   while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gtpfxtxnpj.html

[B08] do-while（至少执行一次）
来源：http://dali.yvedp.cn/Article/details/gtdvfkzkxz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczqhdsam.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hnqzz.top/Article/details/gttqvtqyyq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtbwrptvcl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtobhjniwl.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtahmjtdzp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gtaolpvgtv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yonumen.top/Article/details/gtlrmgmzjq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtvyihyvyd.html

[B09] break 与 continue
来源：http://dali.pengpengdd.cyou/Article/details/gtnyuczvuw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqacslkhc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtsegmgiol.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtgzjuxkuy.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtuofeluqt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtrfjsdtol.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gtfkmzuawj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.nanxinkj.top/Article/details/gtebfjzjnx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtoojuaygd.html

[B10] 遍历同时拿索引
来源：http://dali.shuidangran.top/Article/details/gthwgtnavs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.birdmap.top/Article/details/gtmnhpcpou.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.316326.xyz/Article/details/gtfotlztwj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gtlhpnvvcq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yuanzhike.top/Article/details/gtdkvlezqx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.316326.xyz/Article/details/gtntodkdpq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sufxvd.cn/Article/details/gtukyjyaau.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gtpxvligmf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkidcnzi.html

[B11] 生成数字序列 / 区间
来源：http://dali.yonumen.top/Article/details/gtgrehnvqs.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gtgwxmbocg.html

PHP:  range(0, 10, 2);
来源：http://dali.dianchejie.cn/Article/details/gtgcgiivdq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gtthaktpfg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlygqthud.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ydzc1.top/Article/details/gtullmjjlk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangtech.top/Article/details/gttslecfcm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aizwys.cn/Article/details/gtqwwxrnvk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.pycfn.com/Article/details/gtaxdahthq.html

[B12] 跳出多层循环
来源：http://dali.dashuyun.cn/Article/details/gtmwhttmjj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhongyouzk.top/Article/details/gtveyifriz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ybcxt.top/Article/details/gtjtlyozhu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gtiyjholen.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtqbczeqgu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtppokpkbc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hywenlv.cn/Article/details/gtkptzakkz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cheryme.top/Article/details/gtcycjrlgn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcldustm.html


<!-- 参考信息 -->