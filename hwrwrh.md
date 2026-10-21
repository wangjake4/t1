代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.ivvv.top/Article/details/gtlzodcnod.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ivvv.top/Article/details/gtamoxfwma.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gteypjfran.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.smart0.xyz/Article/details/gtyxftyceh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jianghu66.top/Article/details/gtybphciev.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtmaqpbqju.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hongshengwenyu.top/Article/details/gtdqxkcmdw.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtogszkmze.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtpusefniw.html

Java: String.format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtiypopnza.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtydhzqegu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gthzhljzym.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.redwolf501.top/Article/details/gtawkfuwuz.html

[E11] 反转字符串
来源：http://dali.iojbl.cn/Article/details/gtiftfuuwg.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtqozcntmo.html

PHP:  strrev($s);
来源：http://dali.cucudq.cn/Article/details/gtjnepslyj.html

JS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtmalmsgzd.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gteoglwagp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.havefunace.top/Article/details/gtdqyszqap.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtutwbzrqp.html

Ruby: s.reverse
来源：http://dali.tianlin.xyz/Article/details/gthyisuoxs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtyvzdmgwx.html

[E12] 统计某字符出现次数
来源：http://dali.hnqzz.top/Article/details/gtxdzooltd.html

Py:   s.count("a")
来源：http://dali.gzhubu.top/Article/details/gthacitrmn.html

PHP:  substr_count($s, "a");
来源：http://dali.nwbrower.top/Article/details/gtvctiwhaq.html

JS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtnzoslxpt.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtmfpjbssu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yueranfly.top/Article/details/gtbzsoqrrl.html

Go:   strings.Count(s, "a")
来源：http://dali.sxryk.cn/Article/details/gtkdqqyhnk.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtiqmuowbp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gtzdovlmqn.html

[E13] 逐字符遍历
来源：http://dali.zhongyouzk.top/Article/details/gthnqriwfn.html

Py:   for ch in s: print(ch)
来源：http://dali.zhengqikj.top/Article/details/gthuuacgab.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetqabtok.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtiluqlebp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtpmgjspyj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtahsfkwew.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sweek.top/Article/details/gtuxzvkwpm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnxiangtu.top/Article/details/gtofugiipj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yueranfly.top/Article/details/gtbhnctgfl.html

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gtivxarijy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xylfe.cn/Article/details/gtgcydrvxy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.9152youxi.cn/Article/details/gtjdycrtoj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yangfankeji.com/Article/details/gtepvmwisx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xylfe.cn/Article/details/gttdtzyaev.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gttqwgfqmv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.andypj.xyz/Article/details/gtdfuxyfrp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuanzhike.top/Article/details/gtmtzhsksp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtiotoofet.html

[E15] HTML 转义 / 反转义
来源：http://dali.kuanghao11.cn/Article/details/gtwjtgsslz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gogol.net.cn/Article/details/gtcgryhcds.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hywenlv.cn/Article/details/gtehgdieud.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.bjfxy.top/Article/details/gtpwosdcdy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.0kj1m.cn/Article/details/gtbbhyexmb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gtjrxyqruv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gtpxstpvsz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aibaodan.cn/Article/details/gttrrxajum.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtkljqccui.html

[E16] 数字千分位
来源：http://dali.ybcxt.top/Article/details/gtuyrxuesi.html

Py:   f"{1234567:,}"
来源：http://dali.gogol.net.cn/Article/details/gtdxjyyanj.html

PHP:  number_format(1234567);
来源：http://dali.jiagoushi.top/Article/details/gtwyaudhzb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtmpyruvnc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gtmhogdidw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.mhx1999.top/Article/details/gtvlcnwtcl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ydzc1.top/Article/details/gttkonvmqj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrazkhpx.html

C#:   1234567.ToString("N0")
来源：http://dali.havefunace.top/Article/details/gtkbznaqrf.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gtymxqozlm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzmefmac.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhengqikj.top/Article/details/gtwzmkxzhg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtkwpsoeem.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtdtqccpgt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.0kj1m.cn/Article/details/gtujfmanyp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtnufblhvn.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gtajwgudeu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cashguo.top/Article/details/gtqjsvmjmt.html

[E18] 模板占位符替换
来源：http://dali.jqgufenzy.top/Article/details/gtuixxbskf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gthnuvycoz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gtnrrkmjek.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtcqbidbmi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtexamlutt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtruhokrdw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.meibo888.top/Article/details/gtmkhirkdt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gtjmatcuku.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthznrftzr.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gtvqqhfnvi.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gtxjltzgkn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtgylortnm.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtshvhbcvl.html

TS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gtiliwupwg.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtqgxsigcr.html

Go:   strings.Split(s, "\n")
来源：http://dali.meibo888.top/Article/details/gtatlzliyn.html

Ruby: s.lines
来源：http://dali.sxryk.cn/Article/details/gteskwzbst.html

C#:   s.Split('\n')
来源：http://dali.jyoumei.cn/Article/details/gtvewdtkjn.html

[E20] 判断字符串是否为空
来源：http://dali.dianchejie.cn/Article/details/gttqfqqllw.html

Py:   if not s:
来源：http://dali.feifeiyinyue.top/Article/details/gtdjywbgyl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gogol.net.cn/Article/details/gtzavkqzdv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.feifeiyinyue.top/Article/details/gthcbchijv.html

TS:   if (s === "") {}
来源：http://dali.nwbrower.top/Article/details/gtdztdodbu.html

Java: if (s.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gtnowldvpe.html

Go:   if s == "" {}
来源：http://dali.yj202588.top/Article/details/gtlenfnsig.html

Ruby: if s.empty?
来源：http://dali.guowangkeji.top/Article/details/gtgpikygcv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxmagfes.html

[E21] 超长截断加省略号
来源：http://dali.guannengcc.top/Article/details/gtkrybudec.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hongshengwenyu.top/Article/details/gtghqyzyrb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtbsvwncfu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtgwmagsam.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgvzljqf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtyhifiekh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgufenzy.top/Article/details/gtjrxjoeir.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gtwnhnoztv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtildpfear.html

[E22] 字节长度与字符长度
来源：http://dali.chenlongwang.top/Article/details/gtqvyxsyge.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.birdmap.top/Article/details/gtbojuhcmg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gttjfzcmql.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gtmdxrlzlw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gthoifjqdp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtkntihgtz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pengpengdd.cyou/Article/details/gtwuqqanmj.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gtqmvoyxfs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtblztzfql.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtpdnmmbzj.html

F. 文件与目录
来源：http://dali.yanxiufei.cn/Article/details/gtbzinbnzd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtevrujiyi.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gtnuufvjpe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gtbzwfwnqf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtkszuzkvf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yvedp.cn/Article/details/gtgpfenbbg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohcczugc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxvcmnfr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zycfv.cn/Article/details/gtrxqleyex.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtkzuvfs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtukjnsdnv.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gtoeytevhm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gtczojkciy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yvedp.cn/Article/details/gtwaouavjl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtarmuxfdc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtphkhouyk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gtjsinceun.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hammf.cn/Article/details/gtmkztuirw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.smart0.xyz/Article/details/gtdbqwamfz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.iojbl.cn/Article/details/gtlsycqnot.html

[F03] 写入文件（覆盖）
来源：http://dali.xylfe.cn/Article/details/gtqztnifbs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shzxlz.cn/Article/details/gtwvdeaaou.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gtulonvoov.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjikhnwi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtqnusoaae.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtiynmcwxr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gtmxwieftw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daxiang520.top/Article/details/gtcafqvtgm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtblqjzjaw.html

[F04] 追加写入文件
来源：http://dali.nwbrower.top/Article/details/gtmviadlkj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gttezerqxr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gtunirhbay.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gtoewroead.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtttunqasx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gtripdfagh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258888.top/Article/details/gthifknswe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gtqyfykjpn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gtbhfdslbn.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtixlvomed.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gtqozqtlos.html

PHP:  file_exists("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtdgxemums.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtotjsfnvm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gttmcqpktl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtlqqagaij.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gtshltppfe.html

Ruby: File.exist?("a.txt")
来源：http://dali.316326.xyz/Article/details/gtgdylzwfm.html

C#:   File.Exists("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtqzzvenlw.html

[F06] 删除文件
来源：http://dali.yangfankeji.com/Article/details/gtyajmzgql.html

Py:   os.remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtrbpiitat.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258.top/Article/details/gtmnxpuhft.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtsenooxwg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtjpwuamcf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtozjaezyl.html

Go:   os.Remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gtpgytosee.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtkskkczzx.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtqhpshoqk.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gtjkpqxpce.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.c1oappe.top/Article/details/gtmuykrwsp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtysuqveiy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gtxcixandd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtxaknojpz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxinkj.top/Article/details/gtpmvgkwvb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jyoumei.cn/Article/details/gtctpcuyxj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gtnjwkrmvx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjzalrpn.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gtdrdtepsa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.0kj1m.cn/Article/details/gtauzojigd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cqqwz.cn/Article/details/gtwkjchirb.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtfwonfays.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gtkyoybzhg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gturuwtoqk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yvedp.cn/Article/details/gtkrxjmmku.html

Ruby: Dir.children("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtcfyvjvdn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.316326.xyz/Article/details/gtosppjunp.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gthmvghxbk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtlpocfkxv.html

PHP:  filesize("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtyqhpniyg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtrboohhem.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtpqfwgiig.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtmvkbkmty.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yangfankeji.com/Article/details/gtbatrybip.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtzdyfjfcv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guannengcc.top/Article/details/gtiypbufqs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ydzc1.top/Article/details/gtwppuoaft.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gttswnkccv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gtclxkkfjk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtwqoxshnh.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtplolshad.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yueranfly.top/Article/details/gtffymwcug.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtwlcdujyv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtvpwswivk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtbatypnxj.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gtxttebkht.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtpfaqhvkh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gtjjmkjmea.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtgnzgmkoj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtalwxrjfd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtkbdusxmo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gtrdjhncgc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtpwdqkluc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gtwwizedyw.html

[F12] CSV 读写
来源：http://dali.snrcjt.cn/Article/details/gtqrquzuww.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yanxiufei.cn/Article/details/gtidhovqtk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daria6918.cn/Article/details/gtqdtgbbev.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sxryk.cn/Article/details/gtljeovear.html

TS:   // 同上
来源：http://dali.zycfv.cn/Article/details/gtpjuwjouk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xinyue.icu/Article/details/gtuwfrdkea.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yvedp.cn/Article/details/gtoakjlrjk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pengpengdd.cyou/Article/details/gtnmtmffrl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gtrlsunsdm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdknqgjsv.html

G. 面向对象
来源：http://dali.tanke756.top/Article/details/gtxvmbwrqj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtmtwywbho.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gtbiqwhsus.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gttegonckv.html

PHP:  class User {}
来源：http://dali.c1oappe.top/Article/details/gtgdmuxzto.html

JS:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtuqaitahr.html

TS:   class User { name: string = ""; }
来源：http://dali.cqqwz.cn/Article/details/gtjvftbwvv.html

Java: class User {}
来源：http://dali.daxiang520.top/Article/details/gtxuruksnl.html

Go:   type User struct { Name string }
来源：http://dali.yongpay.top/Article/details/gtpppqngqm.html

Ruby: class User; end
来源：http://dali.jqgufenzy.top/Article/details/gtkajfanqc.html

C#:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtwniakixh.html

[G02] 构造函数
来源：http://dali.havefunace.top/Article/details/gtzehwajnd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.c1oappe.top/Article/details/gttzcluixi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gzhubu.top/Article/details/gtlzpxowzw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtteeenbms.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gttktjzuor.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtinycincb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinghuilouyu.cn/Article/details/gterlyxwvk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cashguo.top/Article/details/gtzdzlxanj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuxming.cn/Article/details/gtxilapspl.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gtcxpjxsix.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gthqhlzlqg.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtbetgipok.html

JS:   this.name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtglpvlfja.html

TS:   name: string = "x";
来源：http://dali.shzxlz.cn/Article/details/gtpbywibfg.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gtuazjvrfy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.snrcjt.cn/Article/details/gtmpqsuftk.html

Ruby: @name = "x"
来源：http://dali.nwbrower.top/Article/details/gtxtudbrzb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmcnznxb.html

[G04] 定义方法
来源：http://dali.iojbl.cn/Article/details/gtoiuyrpji.html

Py:   def greet(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtwpbtoksf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbjajhsis.html

JS:   greet() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtvpfglhtj.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtzjfcdplv.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtndymossz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtjsqogofv.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gtvjpvhqma.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtkrfrnowo.html

[G05] 继承
来源：http://dali.ehwqpu.com/Article/details/gtkxcvoeft.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gtiqksjqys.html

PHP:  class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtrqlgswyv.html

JS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtbijxrpap.html

TS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtqizzzwin.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtusqkvrgr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.c1oappe.top/Article/details/gttuqjckwy.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gtcvvlewbu.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gtgoygexzd.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gtwzrjojke.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxnayhiz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtpfoodijz.html

JS:   greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtydkunozu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtptjnkgcd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtjowshlve.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxinkj.top/Article/details/gtssnkuwcw.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gtesggtdjh.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gtekptxnpq.html

[G07] 调用父类方法
来源：http://dali.gzhubu.top/Article/details/gtnkqkrdxt.html

Py:   super().greet()
来源：http://dali.tianlin.xyz/Article/details/gtjqtlgtso.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gtnloblaih.html

JS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtpxlioivg.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtyrssbuyz.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gtepwzzfvs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cucudq.cn/Article/details/gtswzovzss.html

Ruby: super
来源：http://dali.sxryk.cn/Article/details/gtpmjxfsdl.html

C#:   base.Greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuiyyiidc.html

[G08] 静态方法与属性
来源：http://dali.cucudq.cn/Article/details/gtzzmvcdum.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtkabrozfb.html


<!-- 参考信息 -->