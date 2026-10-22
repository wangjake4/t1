代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2dkqujjxc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2gkdxljdn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gt2lttqcfqs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2blirfgfg.html

C#:   s.Replace("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2wrcajose.html

[E07] 按分隔符拆分
来源：http://dali.jinqigufen.top/Article/details/gt2jkaqmpju.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yfjjhjwn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2noazjhjc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nwbrower.top/Article/details/gt2zbgfpqci.html

TS:   s.split(",")
来源：http://dali.hnxiangtu.top/Article/details/gt2wpvftdhx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj202588.top/Article/details/gt2shrneerd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.0kj1m.cn/Article/details/gt2cenklocm.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kiuxihgl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yvedp.cn/Article/details/gt2qvqwzvjr.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rbzosotj.html

Py:   ",".join(items)
来源：http://dali.yj20258.top/Article/details/gt2zchvbvln.html

PHP:  implode(",", $items);
来源：http://dali.smart0.xyz/Article/details/gt2yyvzdouh.html

JS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gt2cudcdvrs.html

TS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2ffxxvlyp.html

Java: String.join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gt2wzhymcid.html

Go:   strings.Join(items, ",")
来源：http://dali.shuidangran.top/Article/details/gt2nnjbbjbl.html

Ruby: items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gt2oxsqckex.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwibhvp.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gt2oclrsgap.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.svipenyu.cn/Article/details/gt2slajqtwd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2jmhrebli.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gt2qfjqbykr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gt2budtxafq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gt2wpbsrcgt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daria6918.cn/Article/details/gt2jfywvwbd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hywenlv.cn/Article/details/gt2mhvtwbin.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gt2uzmeffps.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yongpay.top/Article/details/gt2tljvebbm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fzhhl.top/Article/details/gt2kkexygmy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nxqbakoe.html

JS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gt2zvdnhuxg.html

TS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2uumzlmfb.html

Java: String.format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gt2okxukqqk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gt2vqcmmnmz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gt2vwapyykq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.andypj.xyz/Article/details/gt2rtzwkora.html

[E11] 反转字符串
来源：http://dali.yuxming.cn/Article/details/gt2kfkdqivd.html

Py:   s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2spdrihyo.html

PHP:  strrev($s);
来源：http://dali.sweek.top/Article/details/gt2aditjxmn.html

JS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gt2mkcwskiz.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2rhlxlslt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gzhubu.top/Article/details/gt2jtggxwpw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daxiang520.top/Article/details/gt2btcbpdsx.html

Ruby: s.reverse
来源：http://dali.jyoumei.cn/Article/details/gt2bttjkyym.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gt2nsvnkhwi.html

[E12] 统计某字符出现次数
来源：http://dali.zhoulong.xyz/Article/details/gt2alurftfk.html

Py:   s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2thpqztsm.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigufen.top/Article/details/gt2eyxqolhx.html

JS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gt2gncyszxd.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gt2ignxqkla.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cheryme.top/Article/details/gt2uoyeqako.html

Go:   strings.Count(s, "a")
来源：http://dali.yonumen.top/Article/details/gt2gkpgfsny.html

Ruby: s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ccyjggdz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gt2dquzodfx.html

[E13] 逐字符遍历
来源：http://dali.dashuyun.cn/Article/details/gt2schcgtzj.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gt2azrbfwew.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gt2kttylxmn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkjuzewd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2exrzobhy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2pfxqnyhh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gt2aaduuhii.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.daria6918.cn/Article/details/gt2toybqpgn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hammf.cn/Article/details/gt2qxzcyhhy.html

[E14] URL 编码与 Base64
来源：http://dali.zhiwuduotai.top/Article/details/gt2iizoymym.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gt2ncpgbclg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuanzhike.top/Article/details/gt2tpwkorok.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cucudq.cn/Article/details/gt2yglsywii.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aibaodan.cn/Article/details/gt2cdifcgsq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xinyue.icu/Article/details/gt2okacyjat.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gt2pzodvqdf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuxming.cn/Article/details/gt2ccdtlbbk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fengsongda.top/Article/details/gt2mnpapyba.html

[E15] HTML 转义 / 反转义
来源：http://dali.fengsongda.top/Article/details/gt2zqucmixz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.0kj1m.cn/Article/details/gt2xvkvhwqp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yangfankeji.com/Article/details/gt2wniznpfa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nwbrower.top/Article/details/gt2zugpvlrb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zycfv.cn/Article/details/gt2dqziihjw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gt2ranflnpi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gt2brcdsafn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daxiang520.top/Article/details/gt2swldpcvx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gotoacloud.top/Article/details/gt2sjjjtfde.html

[E16] 数字千分位
来源：http://dali.yj202588.top/Article/details/gt2hkwvyiku.html

Py:   f"{1234567:,}"
来源：http://dali.yj202588.top/Article/details/gt2ohzqknpu.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gt2tekzcqwh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gt2plpjzfpy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gt2rtegrhiv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gt2ccluubjb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xziqi.cn/Article/details/gt2bgjccswq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jyoumei.cn/Article/details/gt2yxtieuxb.html

C#:   1234567.ToString("N0")
来源：http://dali.andypj.xyz/Article/details/gt2rtvmgllt.html

[E17] 首字母大写
来源：http://dali.ehwqpu.com/Article/details/gt2msabrrre.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gt2ipkphgkv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258.top/Article/details/gt2tizrfbqc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gt2pjxoyfem.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gt2ugapdiez.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.havefunace.top/Article/details/gt2aymqmikq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.mhx1999.top/Article/details/gt2gfzsfaty.html

Ruby: s.capitalize
来源：http://dali.snrcjt.cn/Article/details/gt2mqwomrsx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.316326.xyz/Article/details/gt2bcqtumqp.html

[E18] 模板占位符替换
来源：http://dali.c1oappe.top/Article/details/gt2bajglvhs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hfpthk.cn/Article/details/gt2plrtgcki.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gt2yfwbgffy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gt2lywzffin.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gt2jloxllwj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2mzrszecw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrsdllrt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gaohongyu789.top/Article/details/gt2lktbmsgb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gt2ekmkeppj.html

[E19] 多行文本按行拆分
来源：http://dali.iojbl.cn/Article/details/gt2xtxeelgh.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gt2elzhacri.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2dvdxvihn.html

JS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gt2tlvkfjpq.html

TS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zcyheuoz.html

Java: s.lines().toList()
来源：http://dali.chenzaomai.com/Article/details/gt2niiduhwb.html

Go:   strings.Split(s, "\n")
来源：http://dali.c1oappe.top/Article/details/gt2fswwrnwa.html

Ruby: s.lines
来源：http://dali.yanxiufei.cn/Article/details/gt2puwfqhpz.html

C#:   s.Split('\n')
来源：http://dali.tian-w.cn/Article/details/gt2oiqayjho.html

[E20] 判断字符串是否为空
来源：http://dali.hnqzz.top/Article/details/gt2qnvvhcpu.html

Py:   if not s:
来源：http://dali.yonumen.top/Article/details/gt2lnggakqc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258.top/Article/details/gt2zwswhqic.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dashuyun.cn/Article/details/gt2yqjmcecj.html

TS:   if (s === "") {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjnzvyjs.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gt2awzltvcx.html

Go:   if s == "" {}
来源：http://dali.tanke756.top/Article/details/gt2ccszjynj.html

Ruby: if s.empty?
来源：http://dali.zdqjudy.top/Article/details/gt2dkexyroh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gt2mghmoaug.html

[E21] 超长截断加省略号
来源：http://dali.hongshengwenyu.top/Article/details/gt2olvyabwf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.316326.xyz/Article/details/gt2uwvgcumw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gt2hjricghv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2mzicxtyl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2folxqaav.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2npqdbdlx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenjidiqi.icu/Article/details/gt2wbefifjz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2qlaimlsx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2rrfsgnpi.html

[E22] 字节长度与字符长度
来源：http://dali.gogol.net.cn/Article/details/gt2oezotnew.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jiagoushi.top/Article/details/gt2xfkkfcvx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2mpfogeue.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2emgodkeu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2lvkxlvex.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gt2htxkbpda.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cqqwz.cn/Article/details/gt2tdyzmhte.html

Ruby: s.bytesize;  s.length
来源：http://dali.nwbrower.top/Article/details/gt2ekojvjsd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxinkj.top/Article/details/gt2scfrecxd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2jxdtckbi.html

F. 文件与目录
来源：http://dali.xinyue.icu/Article/details/gt2uysyjwkb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2fkrpyeyb.html

[F01] 读取整个文件
来源：http://dali.hnqzz.top/Article/details/gt2fdatasoa.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.c1oappe.top/Article/details/gt2xekcapur.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ptribcpn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gt2hodjehwb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gt2pskjgqmv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2aannpqor.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jyoumei.cn/Article/details/gt2xkcdcrzx.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2toroehcv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2uogwqzva.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gt2hqwtwuzd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dashuyun.cn/Article/details/gt2jsmslkjg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xjstqxtx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gt2lzyicrjc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2txjmubuw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxuptvsn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gt2hlqljdch.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umrcdpms.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cashguo.top/Article/details/gt2vbqraiat.html

[F03] 写入文件（覆盖）
来源：http://dali.xuanzx.com/Article/details/gt2xfepwcwx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gt2gdbddgzb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gt2ebhmbllg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gt2yuaxtpui.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ihkqrapo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tanke756.top/Article/details/gt2qkilfkwy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hqggvsnl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fasevfjk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gt2dxxotwzj.html

[F04] 追加写入文件
来源：http://dali.xuanzx.com/Article/details/gt2kquvcqqj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gt2iowymide.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gt2azngdruy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2ovcksgkb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2vqzgcjnn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dashuyun.cn/Article/details/gt2bgjnmvcs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2wfzjkgxt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sweek.top/Article/details/gt2zonnoaiu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zdqjudy.top/Article/details/gt2jzwpkzqf.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gt2ppikcctv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhrxxyxx.html

PHP:  file_exists("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2ibvzwghr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2rbjxpzvv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2hhgleeab.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2ttgrtrja.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cashguo.top/Article/details/gt2gaaxxomt.html

Ruby: File.exist?("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2vuqysvxw.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2peonzzre.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gt2pcedaoet.html

Py:   os.remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2yzmyypju.html

PHP:  unlink("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2ciwydfms.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2umzlnhij.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2tsckdhid.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2pntssilh.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2pxjckbud.html

Ruby: File.delete("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2idylravt.html

C#:   File.Delete("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2mxunccrw.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gt2qygebejl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gt2jpfctzgz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gt2tpmhextx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gt2hlgxovhk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2tjgwzkqw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yanxiufei.cn/Article/details/gt2rmyyvgoq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhengqikj.top/Article/details/gt2gqopcjue.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fengsongda.top/Article/details/gt2qhqqpyeg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuanzhike.top/Article/details/gt2tbjikviv.html

[F08] 遍历目录
来源：http://dali.sysykeji.top/Article/details/gt2usyitfan.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gt2fxzhbkyh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yanxiufei.cn/Article/details/gt2fxbsoodi.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rcjbfniu.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2uqybxuku.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzwozhod.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ygicsgyn.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258.top/Article/details/gt2jzncixiy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2pmnlfyed.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gt2nmuqvtqc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2xbuamnlv.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2xcgzmqmn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gt2eeszamwk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gt2seugqbuz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2fdjvujls.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sysykeji.top/Article/details/gt2lqmmswoa.html

Ruby: File.size("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2khhahlov.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ppjwa.cn/Article/details/gt2pixmucyv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gt2rfxpjslb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2gyxxllao.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2nzdyuksc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2rzoatree.html

TS:   path.extname("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2elrvdtom.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tanke756.top/Article/details/gt2vaiaflhb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2vevjhbxb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2kohbfspg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2edpedrvz.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gt2onaakeqf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2hmsebrfr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gt2yuehbnow.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2bzsxvjyg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gt2mtplnxrq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gt2ymgsxdaj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gt2tqnvgkcy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2chtbktou.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gt2mjzstjmt.html

[F12] CSV 读写
来源：http://dali.yuxming.cn/Article/details/gt2foxnlkks.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xinyue.icu/Article/details/gt2dmradgjp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qynhznet.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigfzy.top/Article/details/gt2doezedbg.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gt2wjzjxpfu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.mhx1999.top/Article/details/gt2zgecsfgc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangshuangyany.cn/Article/details/gt2pssiubln.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.0kj1m.cn/Article/details/gt2oqdjycdv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2djxdrnha.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2bgojzmfr.html

G. 面向对象
来源：http://dali.tianlin.xyz/Article/details/gt2ubdfmgni.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2nwprjvad.html

[G01] 定义类
来源：http://dali.chenjidiqi.icu/Article/details/gt2xbehouea.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gt2dswegcnh.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2glqiczrk.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gt2wjywjull.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigufen.top/Article/details/gt2cfepbcbf.html

Java: class User {}
来源：http://dali.aizwys.cn/Article/details/gt2uiuzksvn.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xfacaxrn.html

Ruby: class User; end
来源：http://dali.redwolf501.top/Article/details/gt2tmitihzq.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2kfqjucmu.html

[G02] 构造函数
来源：http://dali.sysykeji.top/Article/details/gt2mgovgfbm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daxiang520.top/Article/details/gt2lgxowser.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tianlin.xyz/Article/details/gt2acqzfwhz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ckaokmgw.html

TS:   constructor(public name: string) {}
来源：http://dali.daxiang520.top/Article/details/gt2sjrvdkol.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gt2lrobaipo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kgmeplje.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vscqjvzr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gt2lhjrdzfb.html

[G03] 实例属性
来源：http://dali.quarkkingdee.top/Article/details/gt2ydcejfmg.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gt2notqjlna.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2gwnpolps.html

JS:   this.name = "x";
来源：http://dali.sweek.top/Article/details/gt2fhouojla.html

TS:   name: string = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2nlasbwbv.html

Java: private String name;
来源：http://dali.dashuyun.cn/Article/details/gt2tgdydtfv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.feifeiyinyue.top/Article/details/gt2xupawzdu.html

Ruby: @name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gt2mkjejups.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.birdmap.top/Article/details/gt2sequkzsf.html

[G04] 定义方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2gbmvcvza.html

Py:   def greet(self): return self.name
来源：http://dali.tanke756.top/Article/details/gt2gheenyqf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2wvezjlsu.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lirtiklh.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2djevjwqb.html

Java: String greet() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2vguututz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gt2vxwvwmoi.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gt2oaejctkf.html

C#:   public string Greet() => Name;
来源：http://dali.gogol.net.cn/Article/details/gt2guxpgsxw.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gt2hmjkjcfb.html


<!-- 参考信息 -->