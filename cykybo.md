代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtavmgetot.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnfqwnzu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtasheriwj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gtelhwoueq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gtuajitcki.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.quarkkingdee.top/Article/details/gtgslrdhrv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ppjwa.cn/Article/details/gtmuwkinqu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gtpwakjsyu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxuanxn.top/Article/details/gtsgonqsds.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtwhvpuskz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgfzy.top/Article/details/gthrivnbnq.html

JS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtcjguryfu.html

TS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtwbkomiom.html

Java: String.format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gthmcjqzxp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gtnvsvvhtn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtjcenqeqv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nwbrower.top/Article/details/gtngnnwwzp.html

[E11] 反转字符串
来源：http://dali.cashguo.top/Article/details/gtlpppljzq.html

Py:   s[::-1]
来源：http://dali.redwolf501.top/Article/details/gtgpylwpoc.html

PHP:  strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtbrtakfis.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtfinajpkp.html

TS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtsbqrqlok.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aibaodan.cn/Article/details/gtppjfrdjj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ehwqpu.com/Article/details/gtjgwxteuq.html

Ruby: s.reverse
来源：http://dali.tianlin.xyz/Article/details/gtbdukhnmz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gtghjsxvpe.html

[E12] 统计某字符出现次数
来源：http://dali.iojbl.cn/Article/details/gtkjjwpgth.html

Py:   s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gtelgxwakg.html

PHP:  substr_count($s, "a");
来源：http://dali.mhx1999.top/Article/details/gttxnghhxd.html

JS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtxnvtdjhe.html

TS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtfhrkhkyj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pengpengdd.cyou/Article/details/gthqgbmrmb.html

Go:   strings.Count(s, "a")
来源：http://dali.zycfv.cn/Article/details/gtzimljrkl.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gtjxipvmaj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gtkifcjcuu.html

[E13] 逐字符遍历
来源：http://dali.chenlongwang.top/Article/details/gtueustkkh.html

Py:   for ch in s: print(ch)
来源：http://dali.xuetiantiany.cn/Article/details/gtzaolqzdb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gtlxkeyrxk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtnsncqqym.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtzdrkookp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258.top/Article/details/gtbzuegupo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.0kj1m.cn/Article/details/gtuyxkeydt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xziqi.cn/Article/details/gtbpevvtax.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sysykeji.top/Article/details/gtdeerabhq.html

[E14] URL 编码与 Base64
来源：http://dali.chenjidiqi.icu/Article/details/gtwwapjcvc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tanke756.top/Article/details/gtokpxgpzj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtjbigcjns.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgufenzy.top/Article/details/gtsmmfewxo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fengsongda.top/Article/details/gtmpmybwur.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guannengcc.top/Article/details/gtftwisdog.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yangfankeji.com/Article/details/gtkuqyeugh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sxryk.cn/Article/details/gtyekcohjx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtsebjolrw.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gtbspaycof.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ivvv.top/Article/details/gtdoeidfrr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sxryk.cn/Article/details/gtqvxucpzv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hysaishi.cn/Article/details/gtsrwabhst.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigfzy.top/Article/details/gtswkyhrsn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.9152youxi.cn/Article/details/gtfvkxsmck.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnqzz.top/Article/details/gtraxjnxif.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.meibo888.top/Article/details/gtezcxpvbz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxuanxn.top/Article/details/gtirhcmdyr.html

[E16] 数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnlrinyu.html

Py:   f"{1234567:,}"
来源：http://dali.iojbl.cn/Article/details/gtmvftbfop.html

PHP:  number_format(1234567);
来源：http://dali.gogol.net.cn/Article/details/gttllviduf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtimjibeav.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gtpsjbbiif.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gtnzlkzwhx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gtjsfwbexj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gtuxxvvbmu.html

C#:   1234567.ToString("N0")
来源：http://dali.shzxlz.cn/Article/details/gtdefmcpky.html

[E17] 首字母大写
来源：http://dali.nanxinkj.top/Article/details/gtwsucltct.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hfpthk.cn/Article/details/gtaulcsqta.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dianchejie.cn/Article/details/gtzyjqznei.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtwkbkrnyb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtmknepque.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.0kj1m.cn/Article/details/gtiycicngq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtgiqyxkfx.html

Ruby: s.capitalize
来源：http://dali.yj20258.top/Article/details/gtcrozjoqx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daria6918.cn/Article/details/gtrxowzsul.html

[E18] 模板占位符替换
来源：http://dali.yuxming.cn/Article/details/gtwudfdpkc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gtpbffabee.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.0kj1m.cn/Article/details/gtxrnkhzkv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtvpxorhyj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtmmszgurs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtfljzxjoc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtizvttasa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.andypj.xyz/Article/details/gthitgzxuo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtytiirono.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gthsokgbdl.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gtolfwirlc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtsdhskapb.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtbxjczjxw.html

TS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtzrcyibzj.html

Java: s.lines().toList()
来源：http://dali.cdnleiting.top/Article/details/gtaghdpzxy.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gtbpslntfp.html

Ruby: s.lines
来源：http://dali.birdmap.top/Article/details/gttmiwrwnj.html

C#:   s.Split('\n')
来源：http://dali.meibo888.top/Article/details/gtoglvdloq.html

[E20] 判断字符串是否为空
来源：http://dali.vqdsnc.cn/Article/details/gttpinmlor.html

Py:   if not s:
来源：http://dali.dianchejie.cn/Article/details/gtyakphgee.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yongpay.top/Article/details/gtqceifvdj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gtpydqkhrx.html

TS:   if (s === "") {}
来源：http://dali.xinyue.icu/Article/details/gtzrwrxrpp.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gtrfvidnsm.html

Go:   if s == "" {}
来源：http://dali.xinyue.icu/Article/details/gtmlmckwxj.html

Ruby: if s.empty?
来源：http://dali.guowangkeji.top/Article/details/gtkuvdblzd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gtbmtyjvjp.html

[E21] 超长截断加省略号
来源：http://dali.tianlin.xyz/Article/details/gturbagtjw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuanzhike.top/Article/details/gtjfvdpatw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtwvnxzzjh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtkzzlpiul.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtvbanglms.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtcmlpkstq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ivvv.top/Article/details/gteupfvtkz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtaiggcpff.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhpvdteq.html

[E22] 字节长度与字符长度
来源：http://dali.iojbl.cn/Article/details/gtjltsazyt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuxming.cn/Article/details/gtojjhrvuv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtfhfwpuao.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtbczkqqef.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gtgwdvmcpa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gtyqkgtaax.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenlongwang.top/Article/details/gthicxwsxr.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gtjqcmyfmo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gtnlxusdcb.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtlmvnjsdq.html

F. 文件与目录
来源：http://dali.zhongyouzk.top/Article/details/gtmontrtps.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtykvecxfv.html

[F01] 读取整个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtkujeazfg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangdashe.top/Article/details/gtcqtomjpi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.havefunace.top/Article/details/gtgsanbwni.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jianghu66.top/Article/details/gtclxaupnm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqstjdrhf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtdjqrgnfa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xziqi.cn/Article/details/gtjnjhjsbn.html

Ruby: File.read("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtmkvvcjgp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtyayiioki.html

[F02] 逐行读取文件
来源：http://dali.yj202588.top/Article/details/gtshohflnt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jlsjyb.cn/Article/details/gtwryvpsqx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jiagoushi.top/Article/details/gtqxefjwui.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gtnhcagkma.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtirjkwhug.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtjjkuxgni.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jianghu66.top/Article/details/gtebyxebqx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigufen.top/Article/details/gtjclguume.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gaohongyu789.top/Article/details/gtyqxyrijo.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gtqmctpctp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gtqhpbhqdg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gtclvomfbx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtkefzmxrg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtsgttrwmj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gzhubu.top/Article/details/gtfxuyqjxk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ivvv.top/Article/details/gtmtulprtp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gtevaqcytj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtxhhudzum.html

[F04] 追加写入文件
来源：http://dali.chenjidiqi.icu/Article/details/gtbnxrrbcs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258.top/Article/details/gtpqvodcwm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gotoacloud.top/Article/details/gtmqiccord.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtpuxwgyer.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtxfrgkyrs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hammf.cn/Article/details/gtctxwjpbb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daria6918.cn/Article/details/gtjtgbdrha.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhixingplan.top/Article/details/gtzrdsrgvi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aizwys.cn/Article/details/gteqvdlzeg.html

[F05] 判断文件或目录是否存在
来源：http://dali.hfpthk.cn/Article/details/gtuzlfqvtt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yvedp.cn/Article/details/gtrhhoajgx.html

PHP:  file_exists("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfvbqcek.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtxkzvfdwk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtjttluuol.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtifmxwglc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yongpay.top/Article/details/gtqfnekazn.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtelynhbmc.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtkxifxbqz.html

[F06] 删除文件
来源：http://dali.0kj1m.cn/Article/details/gtwpelxsem.html

Py:   os.remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtncelruhc.html

PHP:  unlink("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtguaxrluh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gthyzygcvn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtkmogihpl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtbhccbqir.html

Go:   os.Remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtnrarsavb.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtqoinumgm.html

C#:   File.Delete("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtcbbckujv.html

[F07] 创建目录（含多级）
来源：http://dali.guowangkeji.top/Article/details/gtaiyshmki.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cucudq.cn/Article/details/gtikwpnziy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gtdwedrquf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtfjycdiqi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfulpkxag.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gtauujbdey.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gtklzncxqz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jiagoushi.top/Article/details/gtdnzsuhlp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gtefvbfeka.html

[F08] 遍历目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzxulgur.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.316326.xyz/Article/details/gtjzhwrfxz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gtdwpeyixo.html

JS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtcbyawbgl.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gthdbpfdon.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtzgdltvpz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfvvmsas.html

Ruby: Dir.children("dir")
来源：http://dali.yvedp.cn/Article/details/gttcypbbpd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guannengcc.top/Article/details/gthdhztmkv.html

[F09] 获取文件大小
来源：http://dali.zhongyouzk.top/Article/details/gtdgcmucns.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtqhwwuoeb.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gttitrzpkq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtymzpmsdb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gthgejlrut.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtkafucsqe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gtchynkdtb.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtjwtymcxu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gtcssuwgul.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gtmoejosal.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtwuprazac.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtrdvacxpe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtwgbmrksd.html

TS:   path.extname("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gthrwitbkl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gtxqepelxj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtkidkxanp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gthsjoroww.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtnarcsorz.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gtbvxwqihb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtwlolvzrg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jyoumei.cn/Article/details/gtcdbyxwhx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtzwuddcpv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtvlqytymv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtyqyagmpo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gaohongyu789.top/Article/details/gteeuedsuv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtlrggkmdd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.svipenyu.cn/Article/details/gtxzcjcdcp.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gthohvqmnv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gthclsvycu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hysaishi.cn/Article/details/gtilkmivtf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cqqwz.cn/Article/details/gtackccmmy.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gtxrqonfzu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gtkrnlxafq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gtilhxoecn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhixingplan.top/Article/details/gtsmyprttt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gtrrgovzdh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtffveiavy.html

G. 面向对象
来源：http://dali.jinqigfzy.top/Article/details/gtjoqsbcll.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtvwviyrye.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gtjntzeshv.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gtsvgpkqno.html

PHP:  class User {}
来源：http://dali.hammf.cn/Article/details/gtcilsticv.html

JS:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gttavytkpj.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtbrozeqei.html

Java: class User {}
来源：http://dali.chenzaomai.com/Article/details/gtsgseaolb.html

Go:   type User struct { Name string }
来源：http://dali.mhx1999.top/Article/details/gtsszgyblm.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gtqlvqlwsl.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gtwjcezpyw.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gtohgpoowo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gtkyhjqzwu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gtqhtfnpsf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gturxxxpww.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gtqgvkatvs.html

Java: User(String name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtxogxqjnf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcuupdbtn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gthclhehfy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtjbcvqsfp.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gtjaryolpt.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtsqcldhrp.html

PHP:  public string $name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtdqfddylg.html

JS:   this.name = "x";
来源：http://dali.daria6918.cn/Article/details/gtfcpqwojy.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtvuvntwha.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gtevlakuin.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gtluyjnwyo.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtjbhzcqpw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gtytclyjjo.html

[G04] 定义方法
来源：http://dali.yuanzhike.top/Article/details/gttlgurrxq.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtlmgzduxg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gttvbbjlnu.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtzupynkzk.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gthlmpkqlq.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtpnzfsdye.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtnqrpfrlx.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtqsrsksem.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gteggfoevg.html

[G05] 继承
来源：http://dali.redwolf501.top/Article/details/gtlrwzuzor.html

Py:   class Admin(User): pass
来源：http://dali.zhongyouzk.top/Article/details/gtgkasxmbc.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtzlmiccuq.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtnxjjaljb.html

TS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtbnxfnzmn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtqonddrtn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.kuanghao11.cn/Article/details/gtlcpryiqh.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gtngocevrv.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gtvblosgxy.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gtivubknqs.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gtybmqhngj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtvyekthzi.html

JS:   greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtgnarxhur.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtyjvzkpvd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtfajrhnpn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gttlxncdzn.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gtkwjemmse.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gtnncjlhgc.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gtsakxiajn.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gtujiiffjq.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspsoydmc.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtxdsvptqp.html

TS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gtfpflkjxh.html

Java: super.greet();
来源：http://dali.pycfn.com/Article/details/gtenujxgqo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtvfqutgzc.html


<!-- 参考信息 -->