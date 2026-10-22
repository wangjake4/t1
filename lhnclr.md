代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daria6918.cn/Article/details/gtktzwmxiw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenzaomai.com/Article/details/gtzsygfocg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtmbuanmyk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtjbbxjsnk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sweek.top/Article/details/gtjwabhojc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sweek.top/Article/details/gtyvurkvqi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtlmwxkiyd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gtfisfuqsq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sufxvd.cn/Article/details/gtkvqqbpud.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtavpqgkpc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifelyfid.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtkmgxmvcy.html

TS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtvmokflaz.html

Java: String.format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtcpwetnfd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtacehmfgd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqujlsgz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnmkdcbr.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtcolqkhec.html

Py:   s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtutuyszqg.html

PHP:  strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gtfinwqole.html

JS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gteqiyiiqt.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtifynefrg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.vqdsnc.cn/Article/details/gtvsjwmqts.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtxybiqfwa.html

Ruby: s.reverse
来源：http://dali.sysykeji.top/Article/details/gtyyymncae.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtxogrks.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gtdcczijku.html

Py:   s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gtfpdhvnqq.html

PHP:  substr_count($s, "a");
来源：http://dali.zhiwuduotai.top/Article/details/gtetlqgpcz.html

JS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtbdgfjqvd.html

TS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gtiezlbbnm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gogol.net.cn/Article/details/gtydwwmrnz.html

Go:   strings.Count(s, "a")
来源：http://dali.xylfe.cn/Article/details/gtcgtdpmmh.html

Ruby: s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gtwbhbcvmb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.haohaochexian.top/Article/details/gtchzasvpv.html

[E13] 逐字符遍历
来源：http://dali.sysykeji.top/Article/details/gtyshhwael.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gtkgdxoqdk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gtoraissch.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtidmwoppd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gthhnjgvcs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sxryk.cn/Article/details/gtlhesewjr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenzaomai.com/Article/details/gteowrebvb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gtnmvpndyz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuxming.cn/Article/details/gttkkhqqoq.html

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gtxezqmmxt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gtuouaesyh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtmosudkej.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenzaomai.com/Article/details/gthbdlmgdp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtevcdlwcu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtqnyhqdxd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sweek.top/Article/details/gtybtitzzs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.snrcjt.cn/Article/details/gtonhxxugt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuanzx.com/Article/details/gtbbjcauyl.html

[E15] HTML 转义 / 反转义
来源：http://dali.mhx1999.top/Article/details/gtiqqtmoxc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gzhubu.top/Article/details/gtzepizzmr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuanzhike.top/Article/details/gtaskjrfsu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fengsongda.top/Article/details/gtqopiccye.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtnlbmbeyn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yonumen.top/Article/details/gtrqbrfjbq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cdnleiting.top/Article/details/gtbmffwigi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zycfv.cn/Article/details/gtehxenvaj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gtbjvxxjcu.html

[E16] 数字千分位
来源：http://dali.ybcxt.top/Article/details/gtgazppecg.html

Py:   f"{1234567:,}"
来源：http://dali.ybcxt.top/Article/details/gtpcfyxjjj.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gtetiatfry.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gtstfjyofl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gtlopfpohn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ydzc1.top/Article/details/gturwrgviw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhengqikj.top/Article/details/gtacroplyr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gtbxbixcue.html

C#:   1234567.ToString("N0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsftokgmv.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gtxdgyeugk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtcqlqtcau.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daxiang520.top/Article/details/gtlwcajkic.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtihavfkfy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gtthicfcjv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.haohaochexian.top/Article/details/gtmkexnpad.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gtfolxpwui.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gthoatpgkv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gtyuegjovd.html

[E18] 模板占位符替换
来源：http://dali.mhx1999.top/Article/details/gtwssumvzl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tianlin.xyz/Article/details/gtqpzavjeh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnqzz.top/Article/details/gtiarklrsa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtwsmvexqp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfvugcsx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtpaihdbud.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gthematkox.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.haohaochexian.top/Article/details/gthkuwfbvj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gtuuqxyycp.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gtnjnhwkob.html

Py:   s.splitlines()
来源：http://dali.daria6918.cn/Article/details/gtjuvunqyz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gttdlwsjbo.html

JS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtmrqsyndm.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gtrnqprtzp.html

Java: s.lines().toList()
来源：http://dali.kuanghao11.cn/Article/details/gtryqkfbra.html

Go:   strings.Split(s, "\n")
来源：http://dali.yangfankeji.com/Article/details/gtduqfgbwj.html

Ruby: s.lines
来源：http://dali.aizwys.cn/Article/details/gtjjwrmtsr.html

C#:   s.Split('\n')
来源：http://dali.zhoulong.xyz/Article/details/gtyrauxlox.html

[E20] 判断字符串是否为空
来源：http://dali.chenjidiqi.icu/Article/details/gtyurhngbr.html

Py:   if not s:
来源：http://dali.sxryk.cn/Article/details/gtqecjxpkq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gotoacloud.top/Article/details/gtvqjsjbrh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhongyouzk.top/Article/details/gtzainrknc.html

TS:   if (s === "") {}
来源：http://dali.guannengcc.top/Article/details/gtxtsaxfvz.html

Java: if (s.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gtavnzyuhx.html

Go:   if s == "" {}
来源：http://dali.cheryme.top/Article/details/gtswutxmsw.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gtfwdumwib.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gtjakqlfjv.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gtrmwjdbgf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gtpxzpkjsk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtvjpgnkjw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtewqyueyi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtxpblnpzv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtipazlmzh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gotoacloud.top/Article/details/gtpnzcpjqj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtgkqhrfua.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gtamrtiuop.html

[E22] 字节长度与字符长度
来源：http://dali.yangfankeji.com/Article/details/gtampycvlj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.havefunace.top/Article/details/gtycwbihsk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtmnnpshhq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtaakuibea.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gtkklbnfuu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gtgvnadohi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbvxepuq.html

Ruby: s.bytesize;  s.length
来源：http://dali.fzhhl.top/Article/details/gtkvcslghm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gttxkzpkyi.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtnvuqtxng.html

F. 文件与目录
来源：http://dali.havefunace.top/Article/details/gtezdvjwrz.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtjvzxsgud.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gtulmyooko.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tanke756.top/Article/details/gtodcwzkki.html

PHP:  file_get_contents("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtsatplfeh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ppjwa.cn/Article/details/gtiwcyxofz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtzgthxjze.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtsjfyyqvs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gtviiakfan.html

Ruby: File.read("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtfycjkhpl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwofjckx.html

[F02] 逐行读取文件
来源：http://dali.yongpay.top/Article/details/gtxhyeerko.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pengpengdd.cyou/Article/details/gtdlckamyr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guannengcc.top/Article/details/gttsfbetsm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gthjrvmhgw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gtlcwnrvug.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtoxftpexj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gtjiyhrreq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daria6918.cn/Article/details/gtcmysizwu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gtyaceezpo.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gtpuvrwtqi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cqqwz.cn/Article/details/gtrgbytdtt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtyehakgfu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtdgkjynvo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtkghuglgb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwadxdkcy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cdnleiting.top/Article/details/gtdxlknpdt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenzaomai.com/Article/details/gthnpyofxa.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gtkorwxvak.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gtvjpocivs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gtqmooobvn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gtwkwzbfos.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtppilqqpi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtlkzinhmb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yvedp.cn/Article/details/gtmblbyzxi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.0kj1m.cn/Article/details/gtlxguamsm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gtxiyeyqlx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhoulong.xyz/Article/details/gtmgusbnsc.html

[F05] 判断文件或目录是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrajpdah.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvevxytz.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtvuohnvsp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtgtepwyls.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtykjlzwrq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtqvjvyqur.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.andypj.xyz/Article/details/gtltqrqbpy.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtskyrhrpv.html

C#:   File.Exists("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtdshesksg.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gteaxlruil.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtndwgapnz.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258.top/Article/details/gtcokdaqme.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtizxrwkuq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtazzjkaik.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtwtxbdmrk.html

Go:   os.Remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtmidbhxsg.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtwgfgvwfh.html

C#:   File.Delete("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtbjwowdfw.html

[F07] 创建目录（含多级）
来源：http://dali.kuanghao11.cn/Article/details/gtadbzixyd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtjvtzcpzt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sufxvd.cn/Article/details/gtqwucvgiu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtwqjszdjd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gtpngafrqp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jianghu66.top/Article/details/gtkmjmvnda.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhongyouzk.top/Article/details/gtmggmpqhb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tianlin.xyz/Article/details/gtiyidhqzk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnqzz.top/Article/details/gthipqspxv.html

[F08] 遍历目录
来源：http://dali.tanke756.top/Article/details/gtuoxlzwvc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ybcxt.top/Article/details/gtyeuowhrs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pengpengdd.cyou/Article/details/gtspblarqn.html

JS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtxckylmqc.html

TS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmntbafgg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrvjxsnq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zdqjudy.top/Article/details/gtybbjnatl.html

Ruby: Dir.children("dir")
来源：http://dali.c1oappe.top/Article/details/gtvwlysohq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ybcxt.top/Article/details/gtrzoxalri.html

[F09] 获取文件大小
来源：http://dali.yj202588.top/Article/details/gtxannhoea.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hammf.cn/Article/details/gtikspthpc.html

PHP:  filesize("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtcwlqvnof.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtlccwiowq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtyhuoxnpn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtxxurzpwg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gaohongyu789.top/Article/details/gtjbkvtyuh.html

Ruby: File.size("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gthfrfpxnw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgfzy.top/Article/details/gtmzirulnm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gthqxwxpmp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gteytehjoy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtnpostdej.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtvrlzpcnl.html

TS:   path.extname("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtomwapann.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gtaodjavpi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gthjhnwpbt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtmrzhgqrf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtbxvfszyk.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gtvelemmek.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtqpmmhqpw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tian-w.cn/Article/details/gtblyslkry.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtqbvecvkv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtfqredhlx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtkbphvsut.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guowangkeji.top/Article/details/gttrethreu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfyjtzwi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gtqbnbzgzw.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gtdzvwbghg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gtsqnthjyr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gtxsrpfydo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gtvddsxtba.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gtrryzhssu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gtlwywasxj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cucudq.cn/Article/details/gtmniurjcn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.birdmap.top/Article/details/gtljhwlkuf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gtllpdfgrn.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtjaejmsap.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gtctphvmxm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthqpetnyl.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gtwutnrovo.html

Py:   class User: pass
来源：http://dali.shzxlz.cn/Article/details/gthsbrjwlb.html

PHP:  class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtrwtairpf.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gthzseolmn.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gtbmokcvrk.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gtcdygelqf.html

Go:   type User struct { Name string }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwxdkxau.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gtnewouwgb.html

C#:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtbikwjzgs.html

[G02] 构造函数
来源：http://dali.ppjwa.cn/Article/details/gtzgiodanw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhixingplan.top/Article/details/gtiwxpzjky.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvrwddss.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtdcwcryaa.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gtaqlvohks.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gttvuostuv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gtsfdtqnyw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gtzvzytgwm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gtwxfhzucr.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gtitfgxpft.html

Py:   self.name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gthxjmunvl.html

PHP:  public string $name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtlwppdooi.html

JS:   this.name = "x";
来源：http://dali.wangdashe.top/Article/details/gtlivgdpzs.html

TS:   name: string = "x";
来源：http://dali.daxiang520.top/Article/details/gtzhbeyytq.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gtpumaaycf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gtjjipmfjm.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtjuzccyhb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gttanibirs.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gtjxltmprg.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtpdynmgbn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtfzogcsmd.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtehalsaqo.html

TS:   greet(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtdcrkncoj.html

Java: String greet() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtueukrweb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvyjrtia.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gttbrvsovr.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtnpmripru.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gtorfoiwnj.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gtzgeoycnk.html

PHP:  class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtlowsddjt.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtzgdocoxi.html

TS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtrjsnhvdu.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gturtryben.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yangfankeji.com/Article/details/gtgecxyqzk.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gtubiirflt.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gtftsrmjqq.html

[G06] 重写方法
来源：http://dali.zhixingplan.top/Article/details/gtvctntvlv.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gtzadpruds.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsctmoylm.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtdjbruuhm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtyvjldhja.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gteknlwffa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gtkoxmeeuq.html

Ruby: def greet; "admin"; end
来源：http://dali.pycfn.com/Article/details/gtmjypmdbl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gtpgelcksi.html

[G07] 调用父类方法
来源：http://dali.jianghu66.top/Article/details/gtzwjbijiq.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gtymvshsvb.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtdrmeoolp.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtnojeulta.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtwjtwdkoi.html

Java: super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtwspxcfjb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gtgtpwnvmz.html


<!-- 参考信息 -->