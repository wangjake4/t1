代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.chenzaomai.com/Article/details/gtsxeanxcg.html

Ruby: items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtxvuikaak.html

C#:   string.Join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtskpgtdvv.html

[E09] 去除所有空白字符
来源：http://dali.smart0.xyz/Article/details/gtjdguyvds.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigfzy.top/Article/details/gthwjxcigh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yongpay.top/Article/details/gtykgylsqt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtuztvuskb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtjakprnae.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xziqi.cn/Article/details/gtzxixvtvt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cucudq.cn/Article/details/gtzggwodcj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgufenzy.top/Article/details/gtukxiqioq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gtricbgxrm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gtumpbgipc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtegdsfxjj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhoulong.xyz/Article/details/gtxxabgaml.html

JS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtfqlgyujg.html

TS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtlphalpii.html

Java: String.format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtsdemhjle.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgbmkqqy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtnvufmvqa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258.top/Article/details/gtwpmppfww.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gtaetokqfo.html

Py:   s[::-1]
来源：http://dali.fengsongda.top/Article/details/gtweicosey.html

PHP:  strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtyiiyjxbl.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtwlaizasj.html

TS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtkhavaaay.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zdqjudy.top/Article/details/gtzmpsfbgz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gtvocucgji.html

Ruby: s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksfugkhj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtspkhyxts.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtenuntgqc.html

Py:   s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtojufrjok.html

PHP:  substr_count($s, "a");
来源：http://dali.zhiwuduotai.top/Article/details/gtxkfbsuuz.html

JS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gtajbmmgjo.html

TS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gtvsfkazhq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangdashe.top/Article/details/gtteylxdfl.html

Go:   strings.Count(s, "a")
来源：http://dali.yanxiufei.cn/Article/details/gtosehembt.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gtuofolbqs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtptjalfhv.html

[E13] 逐字符遍历
来源：http://dali.tianlin.xyz/Article/details/gtnlltbaod.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gtpgeqteeq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gtsoqemaab.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gtzxmoqkgl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtntmxjjph.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtamyhcjrl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.meibo888.top/Article/details/gtraldoeux.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnxiangtu.top/Article/details/gtzumutcch.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jianghu66.top/Article/details/gtsgbkyais.html

[E14] URL 编码与 Base64
来源：http://dali.zycfv.cn/Article/details/gtznfacphf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gtzzrvsiyk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtleylgvxt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gaohongyu789.top/Article/details/gtrkqgbefd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jlsjyb.cn/Article/details/gteetupked.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtsooioxwy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenzaomai.com/Article/details/gtfxesirmy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shuidangran.top/Article/details/gtjopcbnyp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnqzz.top/Article/details/gtqgdcbvqf.html

[E15] HTML 转义 / 反转义
来源：http://dali.havefunace.top/Article/details/gtvoorigzz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenlongwang.top/Article/details/gtntpojlqc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jiagoushi.top/Article/details/gtxegmtizm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cheryme.top/Article/details/gtjbnuwzkf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gtwynyzcce.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gtiycqxygf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtpsdkhdcj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258888.top/Article/details/gtpkcbmowi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tianlin.xyz/Article/details/gtrwyrkpbc.html

[E16] 数字千分位
来源：http://dali.aizwys.cn/Article/details/gtigvdtqpl.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gtrvftltad.html

PHP:  number_format(1234567);
来源：http://dali.c1oappe.top/Article/details/gtaaljhdvp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtxoeufqce.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gtwhwvmtoa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtldesrmdx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhoulong.xyz/Article/details/gtjegzhkhz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gtpxpavzis.html

C#:   1234567.ToString("N0")
来源：http://dali.ivvv.top/Article/details/gtbsoeytjj.html

[E17] 首字母大写
来源：http://dali.sufxvd.cn/Article/details/gtlrozmtom.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxuanxn.top/Article/details/gtkrkzedrn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yanxiufei.cn/Article/details/gtnfsalsfw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtehplmnsl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtevzoslbk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtktknfbos.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gtseingxkf.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gtlnilvhus.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.iojbl.cn/Article/details/gtoyrcctyf.html

[E18] 模板占位符替换
来源：http://dali.jqgfzy.top/Article/details/gtanroatph.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ydzc1.top/Article/details/gteffusupd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hongshengwenyu.top/Article/details/gtuuelgyvb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtavsemmfe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtqsmskygf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtxqfiidyh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtvjlixqan.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yongpay.top/Article/details/gtigrekxyg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtruwsbewb.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gtoqmdutio.html

Py:   s.splitlines()
来源：http://dali.yvedp.cn/Article/details/gtgkksajfo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gthvbcacho.html

JS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtsbtozcdd.html

TS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gtomtdsdqa.html

Java: s.lines().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtbtbamcig.html

Go:   strings.Split(s, "\n")
来源：http://dali.sufxvd.cn/Article/details/gtytclogyl.html

Ruby: s.lines
来源：http://dali.hammf.cn/Article/details/gtnxusowyg.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gtksrmcqxl.html

[E20] 判断字符串是否为空
来源：http://dali.xuetiantiany.cn/Article/details/gtgoidtabe.html

Py:   if not s:
来源：http://dali.andypj.xyz/Article/details/gtxoinufvn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangshuangyany.cn/Article/details/gtqbpyxxmr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hammf.cn/Article/details/gtredsqrqu.html

TS:   if (s === "") {}
来源：http://dali.smart0.xyz/Article/details/gtgpbaagpy.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxelaioxs.html

Go:   if s == "" {}
来源：http://dali.gaohongyu789.top/Article/details/gtgbqyztde.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtxacxplsj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtorsxwpdd.html

[E21] 超长截断加省略号
来源：http://dali.hongshengwenyu.top/Article/details/gtshwedtjc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zycfv.cn/Article/details/gtcxniemvj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtwcixlqoy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtfdtgnhux.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtpacuewbm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzlbmnbn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrxcmydw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtlmvnnetq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtkxlletsp.html

[E22] 字节长度与字符长度
来源：http://dali.zhoulong.xyz/Article/details/gtbidphhgp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.mhx1999.top/Article/details/gtgufmhymp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtfprlejbw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtjxvufqle.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtqtckvjby.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gtyrzrzszl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gttyazbyhp.html

Ruby: s.bytesize;  s.length
来源：http://dali.andypj.xyz/Article/details/gtpbldqmrm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gtznitleeg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtxnbyxrcd.html

F. 文件与目录
来源：http://dali.gaohongyu789.top/Article/details/gtzayhyykq.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gteaixolaj.html

[F01] 读取整个文件
来源：http://dali.jyoumei.cn/Article/details/gtnftmliew.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sxryk.cn/Article/details/gtudeyokgx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gteaulygdq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnqzz.top/Article/details/gtpwrsgebw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzirirdv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtmddufueg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daria6918.cn/Article/details/gtpgutkcvr.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtyzmbudqy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtebtuwapq.html

[F02] 逐行读取文件
来源：http://dali.bjfxy.top/Article/details/gtqheytsxl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gzhubu.top/Article/details/gtjdmsldas.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigufen.top/Article/details/gtwpnhftgb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gtkwewaagi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakcpjdds.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gtzktnojha.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.mhx1999.top/Article/details/gtluqrlimm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.vqdsnc.cn/Article/details/gtkhjsgggq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shuidangran.top/Article/details/gtmmtmqflf.html

[F03] 写入文件（覆盖）
来源：http://dali.hammf.cn/Article/details/gtevbcobnc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gtdgegdikd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gtoouyezvs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtyuupxncw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtwcvbgesw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shuidangran.top/Article/details/gtzkbaiaxn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangshuangyany.cn/Article/details/gtbckpguag.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dianchejie.cn/Article/details/gtyuzgyrjd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtidqovooe.html

[F04] 追加写入文件
来源：http://dali.havefunace.top/Article/details/gtsusucrja.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtnxqayizo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gtrdecnlqz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gtlgrjeuev.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtsqyehlzg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yangfankeji.com/Article/details/gtepbqlwee.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtxbauulsh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sufxvd.cn/Article/details/gtbyhyyovd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhixingplan.top/Article/details/gtxfvxmnza.html

[F05] 判断文件或目录是否存在
来源：http://dali.ybcxt.top/Article/details/gtkjgmdxwc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guowangkeji.top/Article/details/gthxteiuck.html

PHP:  file_exists("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtnctvypwm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtzheceagm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtjojtftsp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtcmpobtog.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cheryme.top/Article/details/gtdmfbwhrn.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtsiqtrtjw.html

C#:   File.Exists("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtsbsvakvh.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gtwfoamwzm.html

Py:   os.remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtufmhmebc.html

PHP:  unlink("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtqthswvob.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtkvkcazro.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gttraneunn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtqrivgkri.html

Go:   os.Remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtximnebdx.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnxyeosb.html

C#:   File.Delete("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtkhshrkay.html

[F07] 创建目录（含多级）
来源：http://dali.guannengcc.top/Article/details/gtboovmyqx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtsciykeck.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gtyjjagfin.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtssjinwdr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtkbscsuwi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.svipenyu.cn/Article/details/gtmiywgwot.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gtqkiybwyb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gtouqszytm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xziqi.cn/Article/details/gtmvoidlhx.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gtrtavkcuf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnxiangtu.top/Article/details/gtbuhztcyi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gtknuogdkk.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gtcfylbrjd.html

TS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gthwssoqdj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtehpjmdca.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gthikafnbg.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gtxqctyydy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gzhubu.top/Article/details/gtmzcoihyw.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gtsilukwog.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gtdiupfojn.html

PHP:  filesize("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtmvcjjspp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtuoxecgyb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtrdpfjqyx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtaodwaeqt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jiagoushi.top/Article/details/gtkfmczpxv.html

Ruby: File.size("a.txt")
来源：http://dali.yj202588.top/Article/details/gtzokrwaqa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gtujgphrpb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gtbpxjxkan.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtmflpasnl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yonumen.top/Article/details/gtlnocfwff.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtyeciowwr.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gttfzhsvli.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.316326.xyz/Article/details/gtbbfvoekt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtowoiddqt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gthgibwvwh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtgcsmqmlh.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gtkhgksckd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtborokpvz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtqqgqrcjg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtwbwfmoxn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtsmrlafsh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtedcbleyt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gzhubu.top/Article/details/gtykmwxyga.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtmljefioo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gtjrrbomvq.html

[F12] CSV 读写
来源：http://dali.meibo888.top/Article/details/gtonvpcqfg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258888.top/Article/details/gtogrgoxjt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xziqi.cn/Article/details/gtyodquprk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gtfxardqol.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gtjejyccib.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusjbrjzp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cucudq.cn/Article/details/gtnjvfptgp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gtvirhzayo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.birdmap.top/Article/details/gtstuvknku.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtitinewke.html

G. 面向对象
来源：http://dali.yj20258.top/Article/details/gtnltxlqth.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtdchsijdg.html

[G01] 定义类
来源：http://dali.snrcjt.cn/Article/details/gthyasiofh.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gtqimrhoyn.html

PHP:  class User {}
来源：http://dali.hammf.cn/Article/details/gtbvcafrgb.html

JS:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqwmivdud.html

TS:   class User { name: string = ""; }
来源：http://dali.shuidangran.top/Article/details/gtduhtlwym.html

Java: class User {}
来源：http://dali.yj20258888.top/Article/details/gtscokaytm.html

Go:   type User struct { Name string }
来源：http://dali.hywenlv.cn/Article/details/gtjziyenlc.html

Ruby: class User; end
来源：http://dali.andypj.xyz/Article/details/gttasclaxl.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdzvoetl.html

[G02] 构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtmskytqnx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daria6918.cn/Article/details/gtnxmgudfj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guannengcc.top/Article/details/gtesgwngqs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtdqdsqpzp.html

TS:   constructor(public name: string) {}
来源：http://dali.havefunace.top/Article/details/gtutunvxey.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjdcqvrz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gtfpkqgaqa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.mhx1999.top/Article/details/gtyjuscjnh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gttyhwfnuo.html

[G03] 实例属性
来源：http://dali.ppjwa.cn/Article/details/gtgkxozbzt.html

Py:   self.name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtrbamykkv.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtszfdfbwt.html

JS:   this.name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtdhgrkmfe.html

TS:   name: string = "x";
来源：http://dali.fzhhl.top/Article/details/gtsuiufjsk.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfghoqjkw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.meibo888.top/Article/details/gtnxicloam.html

Ruby: @name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtgwrbvdnw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shzxlz.cn/Article/details/gtxguqpmvu.html

[G04] 定义方法
来源：http://dali.yuanzhike.top/Article/details/gtoorwzmoa.html

Py:   def greet(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtxdeidoos.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtkkxseqoy.html

JS:   greet() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtakzhbteo.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtpuhkkqxa.html

Java: String greet() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtwotgwoko.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtwedtdmgs.html

Ruby: def greet; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gttnywrogr.html

C#:   public string Greet() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtynlwydgu.html

[G05] 继承
来源：http://dali.hnxiangtu.top/Article/details/gtssqielwq.html

Py:   class Admin(User): pass
来源：http://dali.316326.xyz/Article/details/gthcvaevij.html

PHP:  class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtkwmfkwea.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtjlbmejle.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gthevfalfv.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtpkhensga.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtojfgjlfy.html

Ruby: class Admin < User; end
来源：http://dali.dashuyun.cn/Article/details/gtenawlaqe.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gtygjtzqdi.html

[G06] 重写方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjgmttzu.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gtmsbqqnog.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtuvxfnnfu.html

JS:   greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtmxhwqhtu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtmykwbfse.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtjihdbthf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gtasozfqhw.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqdoaknp.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrldglyc.html

[G07] 调用父类方法
来源：http://dali.shzxlz.cn/Article/details/gtnmramhom.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gtfrnxsdpf.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gtgqqtuhar.html


<!-- 参考信息 -->