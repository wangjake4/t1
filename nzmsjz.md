代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.xziqi.cn/Article/details/gtpdhfpcbq.html

JS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtftftmugh.html

TS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gtdkpgykcu.html

Java: String.join(",", items)
来源：http://dali.iojbl.cn/Article/details/gthgaayijt.html

Go:   strings.Join(items, ",")
来源：http://dali.fengsongda.top/Article/details/gtyulsrrpq.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtcigkniht.html

C#:   string.Join(",", items)
来源：http://dali.guannengcc.top/Article/details/gtrmzrhqig.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gtfddcmxbk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtjimlgadb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhixingplan.top/Article/details/gtqpbsjoio.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gthubcmzul.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gtssvmagrq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtxzkzwevi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gtffkwacuh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cheryme.top/Article/details/gtorgpzpxq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtnwljcvry.html

[E10] 左侧补零 / 定长填充
来源：http://dali.haohaochexian.top/Article/details/gteqyeesiw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtnodnqxxq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gotoacloud.top/Article/details/gtbgduafeh.html

JS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtglbqvcyj.html

TS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtqfbijuhv.html

Java: String.format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtczeszcaf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtiewwjfag.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtejcziacd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xylfe.cn/Article/details/gtyelzjbdj.html

[E11] 反转字符串
来源：http://dali.yongpay.top/Article/details/gtlrhdsrhc.html

Py:   s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gtifjfwbpk.html

PHP:  strrev($s);
来源：http://dali.pycfn.com/Article/details/gtwgqmluoq.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtsniqbleq.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtkmsmushd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gtylvhfcqd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gthkmmqtwv.html

Ruby: s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtkhjztqea.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gthwmteqno.html

[E12] 统计某字符出现次数
来源：http://dali.iojbl.cn/Article/details/gthdpkheig.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gtvdggtmry.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwkctwha.html

JS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnlohfrp.html

TS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gtzpzozbqp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.haohaochexian.top/Article/details/gtzpychbhn.html

Go:   strings.Count(s, "a")
来源：http://dali.0kj1m.cn/Article/details/gtpykfqpoo.html

Ruby: s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gtldbaazdl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dianchejie.cn/Article/details/gtxjcdqmjq.html

[E13] 逐字符遍历
来源：http://dali.bjfxy.top/Article/details/gtmyazyhwh.html

Py:   for ch in s: print(ch)
来源：http://dali.fzhhl.top/Article/details/gtcwmilxao.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlllcogc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gthzzdfoxv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtwvgzrzbj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258.top/Article/details/gtpakrtkpl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ydzc1.top/Article/details/gtnwhaqquy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yonumen.top/Article/details/gtkuzedmng.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj20258888.top/Article/details/gtjtddvqax.html

[E14] URL 编码与 Base64
来源：http://dali.aizwys.cn/Article/details/gtzqvisudq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gtlpqnuiif.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gtdpzqydgm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nwbrower.top/Article/details/gtxwkgvsjv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yueranfly.top/Article/details/gtyuddxuze.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtrnlywxxd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gzhubu.top/Article/details/gtgnvxqnjm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gtevaawxhv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ivvv.top/Article/details/gtofjbsbjh.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhoulong.xyz/Article/details/gtcvdhrwos.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gtzyavotte.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258.top/Article/details/gtogrlfhba.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtighijrrg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ivvv.top/Article/details/gtgusqbowg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jlsjyb.cn/Article/details/gtmwgccfli.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.smart0.xyz/Article/details/gtpkfzkfdd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gtsbgxkbbo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgfzy.top/Article/details/gtcsnqensw.html

[E16] 数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gtdiaccuws.html

Py:   f"{1234567:,}"
来源：http://dali.zhoulong.xyz/Article/details/gtxcducosq.html

PHP:  number_format(1234567);
来源：http://dali.wangdashe.top/Article/details/gtszilweth.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtdwrmeyiq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtwleztnrd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jlsjyb.cn/Article/details/gtrcutnmaz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gtycitlqzn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gogol.net.cn/Article/details/gttkxjxfme.html

C#:   1234567.ToString("N0")
来源：http://dali.yongpay.top/Article/details/gthetkddrn.html

[E17] 首字母大写
来源：http://dali.nanxuanxn.top/Article/details/gtzvvgegrp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gotoacloud.top/Article/details/gtxvopltjd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gtdvtcveyx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtfpdkiuer.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gtotlmimmj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangdashe.top/Article/details/gtoutjhmfy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtsgayfgxk.html

Ruby: s.capitalize
来源：http://dali.chenzaomai.com/Article/details/gtdnwtzois.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sxryk.cn/Article/details/gtopbrcmmj.html

[E18] 模板占位符替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtralcemqn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtqoirwwfb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hammf.cn/Article/details/gtpimwobwl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtpkbjefeg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtcpasltxc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtrmstlben.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtrdhijfgg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtijcvtarj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gtoujsduvr.html

[E19] 多行文本按行拆分
来源：http://dali.fzhhl.top/Article/details/gtroainrqr.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gtqthyakmn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guannengcc.top/Article/details/gtogiddfes.html

JS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gttfyvqlvh.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gthkydzqin.html

Java: s.lines().toList()
来源：http://dali.fengsongda.top/Article/details/gtkebfrsdd.html

Go:   strings.Split(s, "\n")
来源：http://dali.cashguo.top/Article/details/gtcphpxlng.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gtnqcsanpq.html

C#:   s.Split('\n')
来源：http://dali.guowangkeji.top/Article/details/gtbuhurydc.html

[E20] 判断字符串是否为空
来源：http://dali.dianchejie.cn/Article/details/gtlshvivlx.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gtwabszvfc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnqzz.top/Article/details/gtkiizvsfr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hfpthk.cn/Article/details/gtikdijiad.html

TS:   if (s === "") {}
来源：http://dali.iojbl.cn/Article/details/gteeendiyz.html

Java: if (s.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtpomxcekr.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gtdkvwelci.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gtkcsvccwt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guannengcc.top/Article/details/gtdxebrynr.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gtrfvitueq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gttnuojsym.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxbenzcu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtcxenmhzj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gttqqxutir.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtvenqlckm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jlsjyb.cn/Article/details/gttbiwmgla.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtpwacosty.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtcndubhrz.html

[E22] 字节长度与字符长度
来源：http://dali.xuanzx.com/Article/details/gtugtypdjf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ydzc1.top/Article/details/gtozvrlhiw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtliikdpbe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtojzdgsqj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gthvbtwwba.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtltmfkfuu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sxryk.cn/Article/details/gtrjoaqmdr.html

Ruby: s.bytesize;  s.length
来源：http://dali.andypj.xyz/Article/details/gtwsdjdhuv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.smart0.xyz/Article/details/gtagtpuhis.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtmjjtvwyl.html

F. 文件与目录
来源：http://dali.xuetiantiany.cn/Article/details/gtzblaqzsu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtrkbljmnp.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gtqmlxmjkh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gtztzjnput.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gthuxtnfcr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gtdqbcdcwa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyxnnzgg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtydckjnzw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gtcpzpioal.html

Ruby: File.read("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtlyvfxsdr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtnqaxulla.html

[F02] 逐行读取文件
来源：http://dali.zhiwuduotai.top/Article/details/gtengitdth.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gtzxysvzrz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gotoacloud.top/Article/details/gtxmvyeian.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtrqragezj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtxlqmqixm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtmswqodqh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ppjwa.cn/Article/details/gtnkewjacj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tian-w.cn/Article/details/gtvqycvafy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gthnfrxecs.html

[F03] 写入文件（覆盖）
来源：http://dali.yuxming.cn/Article/details/gtpywavjto.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hfpthk.cn/Article/details/gtpdiawtfe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtwimyhkiv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtowjhvrje.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtwfhzhyfv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtgthzzlvl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.redwolf501.top/Article/details/gteivkgpqe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dianchejie.cn/Article/details/gtfuiqhtqo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtsmwbuxgm.html

[F04] 追加写入文件
来源：http://dali.sxryk.cn/Article/details/gtdxtntvzd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhxfvikn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cqqwz.cn/Article/details/gtedknbufk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtoycufusc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtujvzjbzb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cheryme.top/Article/details/gtrrasqcrq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtjllsnrpl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jlsjyb.cn/Article/details/gtmfdxjgok.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yongpay.top/Article/details/gtwbqdynyd.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj202588.top/Article/details/gtwatazzas.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxuanxn.top/Article/details/gtfkplmtbu.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtqriiythu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtzdexxjyx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtgnsetzbk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtrudarcky.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhoulong.xyz/Article/details/gtfdljkoiv.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtdiogxqlt.html

C#:   File.Exists("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtaxzrbzlk.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gtgxjmjbzl.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtvvchtmnl.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtfqnepzwc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gthwsefbqe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtyvvckvxe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtvdrbscwl.html

Go:   os.Remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtomnvxhuk.html

Ruby: File.delete("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtlxzcvckz.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtwfpxnzsb.html

[F07] 创建目录（含多级）
来源：http://dali.andypj.xyz/Article/details/gtbaczgzuk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtxqovmrvt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj202588.top/Article/details/gtdiinjfqw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtdzlcpubz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gteimmwdzc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gtsalkrups.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuanzx.com/Article/details/gtptdrmsks.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gtojlkojxz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gzhubu.top/Article/details/gtzotngzfo.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gtxsrxohwy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gtjoeqvnmc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnqzz.top/Article/details/gtvlunyxel.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gthclkugrn.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtlnrirdji.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtsxojciar.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.meibo888.top/Article/details/gtvtxifpyk.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gtlauzsrdr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gtahrhkzuy.html

[F09] 获取文件大小
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafvksaik.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtxxddxqfs.html

PHP:  filesize("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtmvprwxba.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtjynteqre.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtdnudrfpm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtvdjnsljz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gogol.net.cn/Article/details/gtfkigggei.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtasndtfgw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gaohongyu789.top/Article/details/gtbmtrtklh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gtmpvmnhik.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtcvbhjjdh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtrapwslzd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtwmftgjyd.html

TS:   path.extname("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtotoskbip.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gtptzvdyjo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtatusrmgu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtjzxvygvj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtfrjfvmay.html

[F11] 复制与移动文件
来源：http://dali.zhixingplan.top/Article/details/gtglyiqdgm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtverkglcz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gtvoxcgfzo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtdpzugclh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtepgfoseu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtfywadfyq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pengpengdd.cyou/Article/details/gtppxlqoyl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtzvwqadkj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gtyuppxgbw.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gtlsxbaahj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daxiang520.top/Article/details/gtmfakcnym.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.bjfxy.top/Article/details/gtsywbnhgb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gtyfmhxxrs.html

TS:   // 同上
来源：http://dali.sweek.top/Article/details/gtcrdpucps.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gtrvrvctzb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gtzjfsolfc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guowangkeji.top/Article/details/gtgeclfant.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.andypj.xyz/Article/details/gtfmtusuox.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosttfqad.html

G. 面向对象
来源：http://dali.feifeiyinyue.top/Article/details/gtkbmejrvg.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtnphbflwd.html

[G01] 定义类
来源：http://dali.ivvv.top/Article/details/gtlzvgnjmj.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gtektqiagi.html

PHP:  class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmxqalsey.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gtciwockbb.html

TS:   class User { name: string = ""; }
来源：http://dali.yvedp.cn/Article/details/gtayaxvioh.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gtjvetbdmi.html

Go:   type User struct { Name string }
来源：http://dali.jinqigfzy.top/Article/details/gttkloixta.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gtksrkncnt.html

C#:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gthmmyqrlw.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gtvrkgsvfh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.c1oappe.top/Article/details/gtcqunesyz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ybcxt.top/Article/details/gtakqkwlvn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvldwmdna.html

TS:   constructor(public name: string) {}
来源：http://dali.hnqzz.top/Article/details/gtbkxwoblm.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtmaigghbk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gtxkmloztu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjeqjukp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gttkbifrre.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gtciofkhdh.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtnulzqjgp.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtjykxewjv.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcglkjeh.html

TS:   name: string = "x";
来源：http://dali.pycfn.com/Article/details/gtofiyondn.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gtekrghppr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gtwrlkidwh.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gtqxslrdit.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtquhbcvqw.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gtklfoeirp.html

Py:   def greet(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbzeqmhl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtjmfftrsx.html

JS:   greet() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gthbrulmwm.html

TS:   greet(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtjolpxjcw.html

Java: String greet() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtmexdrfxs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtlrylbvvs.html

Ruby: def greet; @name; end
来源：http://dali.yuxming.cn/Article/details/gtgsnabnpr.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtfsdpialj.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtebshfify.html

Py:   class Admin(User): pass
来源：http://dali.fzhhl.top/Article/details/gtgefroxbi.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gthgixkwhg.html

JS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzdxyoytz.html

TS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtktnsgfqd.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtejjxzsnn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gtefahnshv.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gtwjtpvoqq.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gtaygmqwqv.html

[G06] 重写方法
来源：http://dali.meibo888.top/Article/details/gtxlautovz.html

Py:   def greet(self): return "admin"
来源：http://dali.gotoacloud.top/Article/details/gtcgoihqpx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtfgxgnvve.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtztlkjgqo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtlrocdmmo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtnmlrjehy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.havefunace.top/Article/details/gtkccfmqfs.html

Ruby: def greet; "admin"; end
来源：http://dali.bjfxy.top/Article/details/gthhkmjwtn.html


<!-- 参考信息 -->