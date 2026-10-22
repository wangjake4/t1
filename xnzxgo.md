代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.guowangkeji.top/Article/details/gt2znfczrvr.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2nbxhlynl.html

TS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gt2naemlept.html

Java: String.join(",", items)
来源：http://dali.xziqi.cn/Article/details/gt2yfmxwhio.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gt2jufatbjw.html

Ruby: items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2bmdedljj.html

C#:   string.Join(",", items)
来源：http://dali.yvedp.cn/Article/details/gt2glyaszmq.html

[E09] 去除所有空白字符
来源：http://dali.chenzaomai.com/Article/details/gt2enzjduhc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.smart0.xyz/Article/details/gt2esztsytq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jeudufcv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gt2vquvgmgp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gt2fmljduuj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.c1oappe.top/Article/details/gt2garhlkdz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.c1oappe.top/Article/details/gt2xrthdosh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ydzc1.top/Article/details/gt2uhqrguas.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xylfe.cn/Article/details/gt2vdwtoisj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gt2ymiyytlu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gt2ahuddnqd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dianchejie.cn/Article/details/gt2vkvpspao.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gt2cliqfald.html

TS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gt2vuclfjyy.html

Java: String.format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wwccoyec.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gt2azugcddv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gt2ubhnxchu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.316326.xyz/Article/details/gt2bpucfhhy.html

[E11] 反转字符串
来源：http://dali.yangfankeji.com/Article/details/gt2qtvxbtty.html

Py:   s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gt2atfzhlqa.html

PHP:  strrev($s);
来源：http://dali.hammf.cn/Article/details/gt2tastavka.html

JS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2elwemlwm.html

TS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbjliolz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigufen.top/Article/details/gt2vqtzyazn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.svipenyu.cn/Article/details/gt2wstlggsq.html

Ruby: s.reverse
来源：http://dali.316326.xyz/Article/details/gt2bvdlflol.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gt2zapczewr.html

[E12] 统计某字符出现次数
来源：http://dali.ppjwa.cn/Article/details/gt2rcujanup.html

Py:   s.count("a")
来源：http://dali.bjfxy.top/Article/details/gt2rioklwmd.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gt2vnapfkvw.html

JS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hycqmois.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gt2ufjqdvje.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guowangkeji.top/Article/details/gt2aooryczb.html

Go:   strings.Count(s, "a")
来源：http://dali.dashuyun.cn/Article/details/gt2trnaikyw.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qonphvxm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.316326.xyz/Article/details/gt2uxlgrewi.html

[E13] 逐字符遍历
来源：http://dali.tian-w.cn/Article/details/gt2rsaabkur.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xuasckgq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fengsongda.top/Article/details/gt2llipuaeu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gt2amwxmerb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2sriregst.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.meibo888.top/Article/details/gt2opgjqapp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xinyue.icu/Article/details/gt2vyyensyr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258.top/Article/details/gt2yiazuxnc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2snmmkaik.html

[E14] URL 编码与 Base64
来源：http://dali.yongpay.top/Article/details/gt2yoazkttr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.redwolf501.top/Article/details/gt2eydxvfgm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sysykeji.top/Article/details/gt2rhqsojzb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuanzx.com/Article/details/gt2tdsssdgd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gt2cqlllzrk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sufxvd.cn/Article/details/gt2dpheztfu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2icrzzsrc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnqzz.top/Article/details/gt2gncjqgec.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.meibo888.top/Article/details/gt2qgcspimu.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gt2kozswzvo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dianchejie.cn/Article/details/gt2psgljuqu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gt2zwebuwsb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gt2drgqvxhb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gt2mmhootpu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhkakqsq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jianghu66.top/Article/details/gt2ixdbrffh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2rwwbwsng.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gt2ziljjcgg.html

[E16] 数字千分位
来源：http://dali.havefunace.top/Article/details/gt2sclzheok.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gt2fwvrlwde.html

PHP:  number_format(1234567);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lzktneag.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gt2rxpwjgjq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gt2fspfsiqm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gt2jrhqpodr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xziqi.cn/Article/details/gt2aiwstujg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2shdzmojt.html

C#:   1234567.ToString("N0")
来源：http://dali.jlsjyb.cn/Article/details/gt2gupyuplk.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gt2mhuiiwvn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dysgubad.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zycfv.cn/Article/details/gt2pimrwmvi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ziwfxgfn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gt2rfpezaom.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuanzx.com/Article/details/gt2cxpvfkxw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuxming.cn/Article/details/gt2saawhgbd.html

Ruby: s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gt2hvgwpxsp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.haohaochexian.top/Article/details/gt2tscbomak.html

[E18] 模板占位符替换
来源：http://dali.daria6918.cn/Article/details/gt2pucangdx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhongyouzk.top/Article/details/gt2otkdvxat.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yongpay.top/Article/details/gt2sfhgivsm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2eumeiuon.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gt2sydwhjnr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2sskzrqfi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.meibo888.top/Article/details/gt2wfgrmyex.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258888.top/Article/details/gt2sajrboex.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gt2brgepslh.html

[E19] 多行文本按行拆分
来源：http://dali.jiagoushi.top/Article/details/gt2keoxlzae.html

Py:   s.splitlines()
来源：http://dali.hongshengwenyu.top/Article/details/gt2xpramrby.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2fzcdhxnq.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gt2fnlbavky.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cehaiosk.html

Java: s.lines().toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2aokkqcvd.html

Go:   strings.Split(s, "\n")
来源：http://dali.hammf.cn/Article/details/gt2anwzfywx.html

Ruby: s.lines
来源：http://dali.svipenyu.cn/Article/details/gt2rzohmtuq.html

C#:   s.Split('\n')
来源：http://dali.hysaishi.cn/Article/details/gt2xfyhgtdx.html

[E20] 判断字符串是否为空
来源：http://dali.hysaishi.cn/Article/details/gt2yfnvyobd.html

Py:   if not s:
来源：http://dali.tianlin.xyz/Article/details/gt2yzrpprye.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hysaishi.cn/Article/details/gt2agycrsrt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijwkkzji.html

TS:   if (s === "") {}
来源：http://dali.daria6918.cn/Article/details/gt2gtbbopby.html

Java: if (s.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gt2mxijrflq.html

Go:   if s == "" {}
来源：http://dali.birdmap.top/Article/details/gt2hdgvtzvf.html

Ruby: if s.empty?
来源：http://dali.zhixingplan.top/Article/details/gt2kvkxvkwf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuxming.cn/Article/details/gt2iimhacbi.html

[E21] 超长截断加省略号
来源：http://dali.pengpengdd.cyou/Article/details/gt2lajnuwpj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gt2eokhcbwf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2zvffixnn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2cnjnmsfa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbllswbl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gt2pphqqmka.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yonumen.top/Article/details/gt2hxzzitgz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2rlvwwczp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2xrlclmyg.html

[E22] 字节长度与字符长度
来源：http://dali.jqgfzy.top/Article/details/gt2jonmijrl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nwbrower.top/Article/details/gt2ulkcfrrj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2buzcmrbd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2wnkgvxfa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gt2rujqhqyq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yqbozyjl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ppjwa.cn/Article/details/gt2ofqeupid.html

Ruby: s.bytesize;  s.length
来源：http://dali.guowangkeji.top/Article/details/gt2mcsaaywf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gt2keyyankr.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ulmoatkj.html

F. 文件与目录
来源：http://dali.svipenyu.cn/Article/details/gt2ojgjewgm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2hoeldxul.html

[F01] 读取整个文件
来源：http://dali.yuxming.cn/Article/details/gt2fpsfnrxo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.mhx1999.top/Article/details/gt2utmsdhax.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2piuiottj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxinkj.top/Article/details/gt2wcmmoobi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gt2hncyrhri.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2boazgcxl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhengqikj.top/Article/details/gt2lyutgecr.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fwsgqtpc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2jqttjqci.html

[F02] 逐行读取文件
来源：http://dali.sysykeji.top/Article/details/gt2locskdsq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gt2syvbemws.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2sqwpqydv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gt2hrjxzdov.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gt2meilcdjs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gt2hbivrdmg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.bjfxy.top/Article/details/gt2ntrumlbo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sufxvd.cn/Article/details/gt2xdhtjiql.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gt2bwvmctsj.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gt2fokbrkao.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gt2kmxdcwld.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gt2vosfpvba.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gt2tsjmgocj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gt2phculzid.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gt2fetimlah.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgfzy.top/Article/details/gt2yjxtsptt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gt2fpwoxzph.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gt2klxmhtya.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gt2lyjxmqjm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2pwzywjoq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sxryk.cn/Article/details/gt2ipasxyjo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kobzzbon.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gt2vjcvgcob.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cljntlpd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2izqxespn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gt2sbrhvtom.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kwixgmsr.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2odtnsfor.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pycfn.com/Article/details/gt2awiqpgvl.html

PHP:  file_exists("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2hntykvev.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2nlnjzsqy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2dywagctp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2uexovpqq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gt2ndcapwcg.html

Ruby: File.exist?("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2bbvpawmq.html

C#:   File.Exists("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2canwjxdq.html

[F06] 删除文件
来源：http://dali.yj20258.top/Article/details/gt2iplvvaxr.html

Py:   os.remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2nstnyxnv.html

PHP:  unlink("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2sqjlyrxv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2mzwcrkwo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2ccfrrphy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2siagurir.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2uduxhkal.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2tepgpbka.html

C#:   File.Delete("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2oxsckjfi.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gt2jodlbntr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gt2cccbrnao.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gt2vmyncpzo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gt2ktoxsbiw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gt2gesdkqqw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gt2bwaxcdtq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mehfingw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rkqortho.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cheryme.top/Article/details/gt2dussazks.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qteunegv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gt2cynmmpwa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yangfankeji.com/Article/details/gt2shxgkvbl.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nxgvxarz.html

TS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gt2yenpzvef.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gt2vqswxtts.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2dbunqjau.html

Ruby: Dir.children("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2zptuuqmg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daxiang520.top/Article/details/gt2xymqwlzq.html

[F09] 获取文件大小
来源：http://dali.iojbl.cn/Article/details/gt2cklinzlp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2bnadvxgy.html

PHP:  filesize("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2aebaqnfx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gt2xingaceh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gt2zaxkqvnz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2gkhsuryo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.andypj.xyz/Article/details/gt2omncsbfp.html

Ruby: File.size("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2qhmvzvvz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gt2gottywlm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gt2zgdvqtef.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2mkabmryx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2tzgyyvjf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2cnepazkt.html

TS:   path.extname("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2wcfgsbtj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gt2bwwabzxm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2wfrdepbx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2jfgunpta.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2etyeegpo.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gt2imcvjece.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gt2ouxqpvxw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2xcbwiall.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gt2ubqvrgma.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2yazqulcc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guowangkeji.top/Article/details/gt2klngbgbt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gt2oltnkufw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2aeudrpgy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gt2kvcmxifz.html

[F12] CSV 读写
来源：http://dali.xuanzx.com/Article/details/gt2dwuoeyhf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxinkj.top/Article/details/gt2tcuswhos.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gt2uoxlozjg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.0kj1m.cn/Article/details/gt2zgvvodsv.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gt2hkeqkcyl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gt2vhxwmyoa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gt2libzkcul.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gt2ctawwxbg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gt2jzksbohk.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2bsfklcoe.html

G. 面向对象
来源：http://dali.zhoulong.xyz/Article/details/gt2fkldwhye.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2zswhkcgh.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gt2isyderxw.html

Py:   class User: pass
来源：http://dali.birdmap.top/Article/details/gt2agfbenpr.html

PHP:  class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2hglqegfi.html

JS:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2umbnhfmq.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ydvigacy.html

Java: class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2mroixoos.html

Go:   type User struct { Name string }
来源：http://dali.gzhubu.top/Article/details/gt2bmkoqdsn.html

Ruby: class User; end
来源：http://dali.zycfv.cn/Article/details/gt2ssiapulw.html

C#:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2bfrtlcjl.html

[G02] 构造函数
来源：http://dali.hnxiangtu.top/Article/details/gt2qpagdaxz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhongyouzk.top/Article/details/gt2xbllsgwx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhixingplan.top/Article/details/gt2pyzjwntm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gt2rlaarqbl.html

TS:   constructor(public name: string) {}
来源：http://dali.yonumen.top/Article/details/gt2hjjggzlg.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nnyklxtx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hysaishi.cn/Article/details/gt2ikmubkhf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cheryme.top/Article/details/gt2xbhnxmkm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2jfxiactl.html

[G03] 实例属性
来源：http://dali.zdqjudy.top/Article/details/gt2myamqtqo.html

Py:   self.name = "x"
来源：http://dali.xylfe.cn/Article/details/gt2ibbegrrb.html

PHP:  public string $name = "x";
来源：http://dali.redwolf501.top/Article/details/gt2ousuhoxh.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2yraoesog.html

TS:   name: string = "x";
来源：http://dali.shuidangran.top/Article/details/gt2zekujqge.html

Java: private String name;
来源：http://dali.gaohongyu789.top/Article/details/gt2qkzastuv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhiwuduotai.top/Article/details/gt2sliflrhx.html

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gt2oqpjnnzo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.birdmap.top/Article/details/gt2yoflgdkr.html

[G04] 定义方法
来源：http://dali.jlsjyb.cn/Article/details/gt2tddtogkp.html

Py:   def greet(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gt2znlterrb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2grvlxhwc.html

JS:   greet() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2xqvopoxh.html

TS:   greet(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2ayrmkkny.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuegzjis.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2nhemucyu.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gt2onxlmdua.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gt2hxcolanh.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2tmigftvj.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pombogvc.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2hthdwtuq.html

JS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2uddgyzph.html

TS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gt2tfwfpkcf.html

Java: class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2gqeeqdsn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tanke756.top/Article/details/gt2baiitrsw.html

Ruby: class Admin < User; end
来源：http://dali.gzhubu.top/Article/details/gt2rtnqsymk.html

C#:   class Admin : User {}
来源：http://dali.shzxlz.cn/Article/details/gt2zyoyfndy.html

[G06] 重写方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2noysyvcl.html

Py:   def greet(self): return "admin"
来源：http://dali.fzhhl.top/Article/details/gt2wdvxnxkg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2odvqudwi.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2eqlwncoj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2ynmjnhrr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2bfehxydq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gt2emkfpstb.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gt2xowgwikj.html


<!-- 参考信息 -->