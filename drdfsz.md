代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aibaodan.cn/Article/details/gt2wrwrctck.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yonumen.top/Article/details/gt2bfttxtbb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dhkdjfti.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gt2hpgptgpd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ydzc1.top/Article/details/gt2juaovuke.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.316326.xyz/Article/details/gt2nzlzltdo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guannengcc.top/Article/details/gt2zkzlojhp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cucudq.cn/Article/details/gt2ecbczhla.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gogol.net.cn/Article/details/gt2mnfwupwv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wgyhfvac.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sufxvd.cn/Article/details/gt2pbdxubyz.html

JS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gt2hvzoyxej.html

TS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pzvnoiog.html

Java: String.format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2dqngvfna.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2ocxzesfe.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gt2onjjvabb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dashuyun.cn/Article/details/gt2sqrscfcs.html

[E11] 反转字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2fhxesnbp.html

Py:   s[::-1]
来源：http://dali.cashguo.top/Article/details/gt2ekvvyuvk.html

PHP:  strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2gqjddfgo.html

JS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qqofzrwu.html

TS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2vpqayqiq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.svipenyu.cn/Article/details/gt2xwfmsirj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gt2nuaepyqc.html

Ruby: s.reverse
来源：http://dali.xinyue.icu/Article/details/gt2uivozdjz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gt2bqjpyffr.html

[E12] 统计某字符出现次数
来源：http://dali.mhx1999.top/Article/details/gt2eysgwqgk.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gt2popzsjes.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gt2ryisonue.html

JS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gt2ffnuwdqx.html

TS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ugyqclui.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqomsgbs.html

Go:   strings.Count(s, "a")
来源：http://dali.pycfn.com/Article/details/gt2vychbpsx.html

Ruby: s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gt2vromtmom.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xinyue.icu/Article/details/gt2yumgbfng.html

[E13] 逐字符遍历
来源：http://dali.bjfxy.top/Article/details/gt2nmrtlncn.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gt2ooxphyzq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnxiangtu.top/Article/details/gt2usmncxhs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gt2ddweodur.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2ximpcbod.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gt2vscwijnt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tianlin.xyz/Article/details/gt2eqwwjull.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guannengcc.top/Article/details/gt2wzmrvoks.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2rlbtofqj.html

[E14] URL 编码与 Base64
来源：http://dali.cdnleiting.top/Article/details/gt2mglfnmgo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zdqjudy.top/Article/details/gt2nooxtdhy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ybcxt.top/Article/details/gt2mwpcwtcn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gt2qhfrmbri.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hammf.cn/Article/details/gt2nyacsoly.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gt2vhgmbztq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gt2vstniiza.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gt2uifokxei.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zdqjudy.top/Article/details/gt2dqyckzxf.html

[E15] HTML 转义 / 反转义
来源：http://dali.tianlin.xyz/Article/details/gt2rvlbgbua.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fengsongda.top/Article/details/gt2anfyqisj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guowangkeji.top/Article/details/gt2doxdxwxt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.iojbl.cn/Article/details/gt2vfbscyux.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jyoumei.cn/Article/details/gt2zrwmklzy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jlsjyb.cn/Article/details/gt2aqvzihkt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigufen.top/Article/details/gt2itigpuxd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gt2qnoqomqm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gt2zvdprgqu.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gt2mdidnquo.html

Py:   f"{1234567:,}"
来源：http://dali.zycfv.cn/Article/details/gt2shgifexn.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gt2uqxjbswb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gt2rlyzshbq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gt2hpyvikhw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gt2clfzwnrw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gt2hubwudtf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2dimyhbmg.html

C#:   1234567.ToString("N0")
来源：http://dali.c1oappe.top/Article/details/gt2mqjwcati.html

[E17] 首字母大写
来源：http://dali.daria6918.cn/Article/details/gt2wafmvdbb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gt2worrrfdz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ucwurvkq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxlarkoq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gt2cfgmrvcw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqtlxfew.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.iojbl.cn/Article/details/gt2kphcxrlk.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gt2bolbgkjk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.bjfxy.top/Article/details/gt2nbllvdfk.html

[E18] 模板占位符替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmfasqnl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwrgiait.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aizwys.cn/Article/details/gt2qnokwquf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2fpvsmhvm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2pizjxrjx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2xpkcgynv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2myaadpth.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nwbrower.top/Article/details/gt2qurfscwl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aizwys.cn/Article/details/gt2jnvfxvyn.html

[E19] 多行文本按行拆分
来源：http://dali.hysaishi.cn/Article/details/gt2aosobwaz.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gt2spupsysk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2reubunhh.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yawivxsf.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdcebvmn.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opmqxibg.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gt2kguxqxxh.html

Ruby: s.lines
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nozgzrdy.html

C#:   s.Split('\n')
来源：http://dali.kuanghao11.cn/Article/details/gt2tijcnifu.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gt2lxixviqn.html

Py:   if not s:
来源：http://dali.hywenlv.cn/Article/details/gt2bkqrcdxc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yanxiufei.cn/Article/details/gt2yzhwenuf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kznfhcgl.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ciztiips.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gt2zduszooy.html

Go:   if s == "" {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xnkyiapg.html

Ruby: if s.empty?
来源：http://dali.svipenyu.cn/Article/details/gt2intleixy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.c1oappe.top/Article/details/gt2jdjimesa.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gt2orimbdnj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fzhhl.top/Article/details/gt2mktxsnhn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2whyocaql.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2kgktzswb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2sqequbiz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2zzwnhern.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgufenzy.top/Article/details/gt2xjeeahhy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uegxgaje.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2njyrkahp.html

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gt2tqrvwzbo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fzhhl.top/Article/details/gt2toxjjmad.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gt2hfcolgaa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2oooaviiq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gt2jgauqaei.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gt2gjmcbcid.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gt2jsvsjsjo.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258.top/Article/details/gt2unyjgbnv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnqzz.top/Article/details/gt2pwbxqzqm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2rexquycw.html

F. 文件与目录
来源：http://dali.0kj1m.cn/Article/details/gt2jdwmqeui.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2kqitsnlc.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gt2ebeijvtn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnxiangtu.top/Article/details/gt2yqcvljsn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2yzlsljpx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gt2zexudqaq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cucudq.cn/Article/details/gt2jveisibp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2fdhatode.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gt2dzssjjrt.html

Ruby: File.read("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2ehbwblkc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2smxexbex.html

[F02] 逐行读取文件
来源：http://dali.hysaishi.cn/Article/details/gt2dmckfgfm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgfzy.top/Article/details/gt2hcsjhpep.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dashuyun.cn/Article/details/gt2iiykxybb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2buorletl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gt2gyvjnrpt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gt2hwnhzmvl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.vqdsnc.cn/Article/details/gt2vunfcvew.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigufen.top/Article/details/gt2xfonqtqh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rjizorzv.html

[F03] 写入文件（覆盖）
来源：http://dali.dianchejie.cn/Article/details/gt2vsnquctd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gt2lzggogrc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gt2ucpqyyfg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gt2jerzmdew.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gt2amdhpnul.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guannengcc.top/Article/details/gt2ztzsrzbb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yhzivafi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tian-w.cn/Article/details/gt2iontixly.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2lpkmmwng.html

[F04] 追加写入文件
来源：http://dali.havefunace.top/Article/details/gt2kdwxqxgu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.iojbl.cn/Article/details/gt2xlnscpto.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ddhwnosg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gt2nttxuzaw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2abyzldgu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgfzy.top/Article/details/gt2eunxzzng.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2ahenozch.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj202588.top/Article/details/gt2mdhrpvvw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cvskdqmu.html

[F05] 判断文件或目录是否存在
来源：http://dali.nwbrower.top/Article/details/gt2qoaqqeaq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gt2xbmvaijr.html

PHP:  file_exists("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2gyochbaj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2dtjshkdl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2qpietusv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2hbyhretz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.vqdsnc.cn/Article/details/gt2hvoyqhtz.html

Ruby: File.exist?("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2dicimucw.html

C#:   File.Exists("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2etnvdosr.html

[F06] 删除文件
来源：http://dali.hfpthk.cn/Article/details/gt2dnbzehpg.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2miycaham.html

PHP:  unlink("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2zbcztoqs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2aaxkhxyw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2pnhbdzeh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2nirmshdl.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gspwwhfv.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ukfgnfsm.html

C#:   File.Delete("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2yfpwblib.html

[F07] 创建目录（含多级）
来源：http://dali.wangdashe.top/Article/details/gt2cldmdbax.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfykhjjb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gt2wflozqak.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gt2jqdqhfha.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2addxnjzc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gt2ypbvkkwj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj202588.top/Article/details/gt2jrajhkuu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gt2tuqrarxj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.316326.xyz/Article/details/gt2izeevuml.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2fuwimxqe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.0kj1m.cn/Article/details/gt2gsurkett.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gt2jvtxnppt.html

JS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gt2wnbzvpga.html

TS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gt2gdbdprnb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wtfadtvu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gt2pvweywdw.html

Ruby: Dir.children("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2kcnlfgbj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2xynnryip.html

[F09] 获取文件大小
来源：http://dali.shangyingyoupin.top/Article/details/gt2kljurunq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2obchaxxq.html

PHP:  filesize("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2ilywnqwc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gt2mhhfoyox.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gt2buyuvwyh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2zfmztxbk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gt2zsnoqoea.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2gobsngja.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sweek.top/Article/details/gt2jaaikvyy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gt2ajgaixws.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zueklykl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2vuftvget.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2seytgnto.html

TS:   path.extname("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2fgtonmyq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gt2jutyhshp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2iexvyusv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2xcsnicyv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2acmvciol.html

[F11] 复制与移动文件
来源：http://dali.nanxinkj.top/Article/details/gt2xxeodoyh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2vgrhlolp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuanzx.com/Article/details/gt2obflnshy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2ltpbjzwf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gt2qzswtkrf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gt2hiurrgbu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gt2zustjbtn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2xyxzomaj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aizwys.cn/Article/details/gt2lhfictzn.html

[F12] CSV 读写
来源：http://dali.yanxiufei.cn/Article/details/gt2krqcxvki.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.haohaochexian.top/Article/details/gt2jskgyijo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj202588.top/Article/details/gt2uspagyvr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhixingplan.top/Article/details/gt2bpgzzvib.html

TS:   // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnqjwubf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.smart0.xyz/Article/details/gt2ljrubsvn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gt2xsxdxvvf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gt2savqvjvj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lxqpnmca.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2bnvseput.html

G. 面向对象
来源：http://dali.tian-w.cn/Article/details/gt2hvaybmnx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2xwxqxnvm.html

[G01] 定义类
来源：http://dali.cheryme.top/Article/details/gt2iddverex.html

Py:   class User: pass
来源：http://dali.ppjwa.cn/Article/details/gt2ogdaicgb.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gt2cfdpvled.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gt2wayuyoaf.html

TS:   class User { name: string = ""; }
来源：http://dali.aibaodan.cn/Article/details/gt2bbwsbgph.html

Java: class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2vzpdidrw.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gt2zmnejygy.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gt2neywzmha.html

C#:   class User {}
来源：http://dali.hnqzz.top/Article/details/gt2jyzwflcc.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gt2wsvamtfe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gt2oibuxlwf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2sduecuhh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gt2asabzlgy.html

TS:   constructor(public name: string) {}
来源：http://dali.hammf.cn/Article/details/gt2editevcy.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gt2rckjextd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.kuanghao11.cn/Article/details/gt2nyovlgxd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.iojbl.cn/Article/details/gt2jrnbtakg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gt2cldsfscx.html

[G03] 实例属性
来源：http://dali.hnxiangtu.top/Article/details/gt2ipaksfkp.html

Py:   self.name = "x"
来源：http://dali.ehwqpu.com/Article/details/gt2tnxppvfx.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2ovqhtvor.html

JS:   this.name = "x";
来源：http://dali.andypj.xyz/Article/details/gt2djzbnlls.html

TS:   name: string = "x";
来源：http://dali.xziqi.cn/Article/details/gt2wbcmztxo.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kscndoew.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gt2koixmbfe.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gt2hficapno.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2oryhiltm.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gt2pvlalkbx.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gt2mltrdjhm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gt2eaczjbnz.html

JS:   greet() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wlpsqrge.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2vjjwezsg.html

Java: String greet() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2cjrymrxc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2aljrdfrt.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2wqvkgzmn.html

C#:   public string Greet() => Name;
来源：http://dali.c1oappe.top/Article/details/gt2qolpxqvr.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gt2ubloimsp.html

Py:   class Admin(User): pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2bltsytrk.html

PHP:  class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2brilmoxc.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2hxyyqwax.html

TS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2cyvtdatx.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qwhyezmi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gt2besyypnv.html

Ruby: class Admin < User; end
来源：http://dali.havefunace.top/Article/details/gt2xxztpcno.html

C#:   class Admin : User {}
来源：http://dali.zycfv.cn/Article/details/gt2rptvtrnl.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gt2ibdcwzge.html

Py:   def greet(self): return "admin"
来源：http://dali.cdnleiting.top/Article/details/gt2urllnkoa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2inbqfwhe.html

JS:   greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2mchvmcim.html

TS:   greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gt2fnbvmgtc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2btrqjpev.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gogol.net.cn/Article/details/gt2nvylsnyq.html

Ruby: def greet; "admin"; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzaygavx.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gt2wghxfxou.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gt2yiwvwojg.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gt2cpplvcsa.html

PHP:  parent::greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oraculkn.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2offprucf.html

TS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gt2ygdulpbi.html

Java: super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rjzggwdw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gt2xmjzldpp.html


<!-- 参考信息 -->