代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.hysaishi.cn/Article/details/gt2ddhhsjuh.html

JS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2ckbghiwe.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gt2adjqqjin.html

Java: String.join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gt2jhjfzhsl.html

Go:   strings.Join(items, ",")
来源：http://dali.fzhhl.top/Article/details/gt2xbduyodj.html

Ruby: items.join(",")
来源：http://dali.cheryme.top/Article/details/gt2ustwlgmw.html

C#:   string.Join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gt2hosrjlqx.html

[E09] 去除所有空白字符
来源：http://dali.iojbl.cn/Article/details/gt2zlzuhseo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gt2tjlgaxcs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2owdrcqqo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gt2vjrvepry.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gt2sdzkvgle.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daxiang520.top/Article/details/gt2njfiiaka.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj202588.top/Article/details/gt2ueygcrkd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yongpay.top/Article/details/gt2xdkknrwp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gt2skddmtfp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jyoumei.cn/Article/details/gt2chldxwka.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gt2vziukmft.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yanxiufei.cn/Article/details/gt2brrdfnuu.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2opxmotbl.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2opyxijbe.html

Java: String.format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2ftklutpj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2muellgtn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gt2dhgyejue.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gt2khydawte.html

[E11] 反转字符串
来源：http://dali.jyoumei.cn/Article/details/gt2cqdsddor.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gt2foktnozq.html

PHP:  strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gt2gldokpbm.html

JS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gt2pfmbzkfn.html

TS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vbutruzl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qndqcuhq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gt2qybjukwf.html

Ruby: s.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2fisjehln.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gt2jwnjzsal.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gt2qyebsbzt.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2uljuqkmg.html

PHP:  substr_count($s, "a");
来源：http://dali.fzhhl.top/Article/details/gt2qgprlqjr.html

JS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gt2fsmdfcku.html

TS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gt2umeogopm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigufen.top/Article/details/gt2rkfepazz.html

Go:   strings.Count(s, "a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhjqojpz.html

Ruby: s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2oblrtskf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.c1oappe.top/Article/details/gt2waunxwnq.html

[E13] 逐字符遍历
来源：http://dali.dashuyun.cn/Article/details/gt2kutrslrb.html

Py:   for ch in s: print(ch)
来源：http://dali.yangfankeji.com/Article/details/gt2jdwbgbmv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.mhx1999.top/Article/details/gt2gfaakafs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2apktgnge.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2zqvqmxwy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gt2cjfbxwiz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yvedp.cn/Article/details/gt2qnmyvjvf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.c1oappe.top/Article/details/gt2wnavckmi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gt2tpadwegw.html

[E14] URL 编码与 Base64
来源：http://dali.jlsjyb.cn/Article/details/gt2nvfdjawg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ahkkijcw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2ddfsmsnw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fengsongda.top/Article/details/gt2rvikcekd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ytamkjyq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gt2deaftfvk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gt2chezdtos.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gzhubu.top/Article/details/gt2xwzlbhrs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gt2fldrhlvo.html

[E15] HTML 转义 / 反转义
来源：http://dali.316326.xyz/Article/details/gt2aidceikk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xylfe.cn/Article/details/gt2iciapxsw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2haqjnayw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gt2gijniqko.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yangfankeji.com/Article/details/gt2nhqihgsk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yueranfly.top/Article/details/gt2iifezswy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.iojbl.cn/Article/details/gt2lniwepnr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gt2hldqcrtf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gt2izgvwmnm.html

[E16] 数字千分位
来源：http://dali.316326.xyz/Article/details/gt2dupkcjzq.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gt2vwhazrap.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gt2mdzcrlje.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gt2wcbqkpup.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gt2ntlgqfqv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gt2rzrzyzsr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daria6918.cn/Article/details/gt2hqvdvbpr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.snrcjt.cn/Article/details/gt2lticpmlr.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gt2wpycppim.html

[E17] 首字母大写
来源：http://dali.dashuyun.cn/Article/details/gt2cqjpujow.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hywenlv.cn/Article/details/gt2fovmmvqn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cheryme.top/Article/details/gt2quguvjts.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpluvhiy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gt2cczopokk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.0kj1m.cn/Article/details/gt2tnvxaqrl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zdqjudy.top/Article/details/gt2avqnpjav.html

Ruby: s.capitalize
来源：http://dali.fzhhl.top/Article/details/gt2xmixqwub.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gt2fusslmfn.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gt2obzdbkxh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xziqi.cn/Article/details/gt2vydnzanz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigfzy.top/Article/details/gt2avjzlpgs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqmohgp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2aicrrqra.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gt2iptxevrx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2fqkqxvjq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gt2lyinympr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.9152youxi.cn/Article/details/gt2sxcfvbfy.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gt2lgifyyvv.html

Py:   s.splitlines()
来源：http://dali.hnqzz.top/Article/details/gt2klwjxzgj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2ejeduief.html

JS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gt2nkekshed.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gt2fbfyedxc.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svsxqfwx.html

Go:   strings.Split(s, "\n")
来源：http://dali.gogol.net.cn/Article/details/gt2ltwsugmm.html

Ruby: s.lines
来源：http://dali.haohaochexian.top/Article/details/gt2ahuxkleq.html

C#:   s.Split('\n')
来源：http://dali.havefunace.top/Article/details/gt2wcflcqru.html

[E20] 判断字符串是否为空
来源：http://dali.jqgfzy.top/Article/details/gt2oqtbulcw.html

Py:   if not s:
来源：http://dali.nwbrower.top/Article/details/gt2rxgpazgu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.meibo888.top/Article/details/gt2jzlzsltd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2rleolcbw.html

TS:   if (s === "") {}
来源：http://dali.mhx1999.top/Article/details/gt2hkwlrjxl.html

Java: if (s.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gt2yziwszfe.html

Go:   if s == "" {}
来源：http://dali.cqqwz.cn/Article/details/gt2agrpmvcu.html

Ruby: if s.empty?
来源：http://dali.gzhubu.top/Article/details/gt2ixaypuhy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuanzhike.top/Article/details/gt2mfjhbcav.html

[E21] 超长截断加省略号
来源：http://dali.chenjidiqi.icu/Article/details/gt2kraeszvh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gt2mcnauurz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gt2vzfwhkvq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gt2ccmhffmb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2zmrexifk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2zisspsir.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.c1oappe.top/Article/details/gt2rxefbdza.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2wdqxkbep.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2kcrylywp.html

[E22] 字节长度与字符长度
来源：http://dali.tian-w.cn/Article/details/gt2fpdxjstp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwldiqoh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2ttmuildh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2npmffuob.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gt2ymcihnan.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gt2bygqamhi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shangyingyoupin.top/Article/details/gt2fpizmust.html

Ruby: s.bytesize;  s.length
来源：http://dali.iojbl.cn/Article/details/gt2tygjqllq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.snrcjt.cn/Article/details/gt2urncskic.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2kxcqdeus.html

F. 文件与目录
来源：http://dali.zhengqikj.top/Article/details/gt2tdaudwso.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2xebrzrtl.html

[F01] 读取整个文件
来源：http://dali.9152youxi.cn/Article/details/gt2fbjelxyn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.9152youxi.cn/Article/details/gt2bhalxxct.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2epwbbgxe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenzaomai.com/Article/details/gt2dysqjvux.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gt2wgnkkfek.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sfvohfvg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jyoumei.cn/Article/details/gt2wuunrqcv.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2nisflsie.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2wmlgjrdu.html

[F02] 逐行读取文件
来源：http://dali.daria6918.cn/Article/details/gt2maqripsy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daxiang520.top/Article/details/gt2xlyaaqsi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.bjfxy.top/Article/details/gt2fijnanat.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gt2gberjgkt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gt2vpvkjenf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gt2hpsqhofm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ejktkfmk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daxiang520.top/Article/details/gt2ggacsxlj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jianghu66.top/Article/details/gt2vbykkpgc.html

[F03] 写入文件（覆盖）
来源：http://dali.guannengcc.top/Article/details/gt2pvbpgowf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guowangkeji.top/Article/details/gt2hqadzebn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gt2laqymtow.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtbqigxk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gt2weencbnu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgufenzy.top/Article/details/gt2nvlqsrlc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gt2dlovafzx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.vqdsnc.cn/Article/details/gt2ptybqatu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2jwkqxxop.html

[F04] 追加写入文件
来源：http://dali.guowangkeji.top/Article/details/gt2vvbbzxie.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2fzwfcnmj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yangfankeji.com/Article/details/gt2nxitobgw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gt2clxetnqv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gt2mxzfxbin.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigufen.top/Article/details/gt2eknzowvl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ynvejejq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gt2jmunpaxx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xziqi.cn/Article/details/gt2onlksmjs.html

[F05] 判断文件或目录是否存在
来源：http://dali.daxiang520.top/Article/details/gt2tsyhwqlp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gt2acjesyiy.html

PHP:  file_exists("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2xoynxppv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2ieggbxwv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2gzqqqfys.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2enzgzhhm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gt2mootcmrl.html

Ruby: File.exist?("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2eknrhyzd.html

C#:   File.Exists("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2zqyjyntw.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gt2lwzpeppx.html

Py:   os.remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2vfmjgydl.html

PHP:  unlink("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2agcazrhb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2qpqfvygv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2rqttksvh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2pjfyzakl.html

Go:   os.Remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2gsjjqyhl.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2ebrkeyei.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2lodhmmwo.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rflvoias.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gt2zjzjrbis.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gogol.net.cn/Article/details/gt2lrcskcky.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gt2shixnmsq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gt2pgzsfooi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2shzoxjiu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.snrcjt.cn/Article/details/gt2xuglnmup.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gt2bwkbgyga.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gt2yfgftsmx.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gt2gffycmxp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gt2ssgrxlmn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.redwolf501.top/Article/details/gt2qnvqcuua.html

JS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2jefmgogc.html

TS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gt2gqsovker.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qfilxlsz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2uyltcgso.html

Ruby: Dir.children("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2exmfzcxt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2szwlmshc.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gt2vqusozqs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2dyfszhnb.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2xjrylclj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gt2kbeyopik.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gt2hayafkqs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2utrmawyj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gt2rnhpjsbp.html

Ruby: File.size("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2yhamffil.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gt2fjaqmyeq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gt2tzyflgrp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eexcbsjj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2idrzsqwt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2rbqkvhao.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2gpfnkymu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tian-w.cn/Article/details/gt2noakoyem.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2ugmootnv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2sbcxmupo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2ewftzbvt.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gt2gadpzber.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2seipsifi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iqyegyxh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2wyspasce.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gt2dmpbzunj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gt2fmgrbsos.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gt2ktmsgztq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2umydlpxf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gt2dcfjhpng.html

[F12] CSV 读写
来源：http://dali.0kj1m.cn/Article/details/gt2ebowyodu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gt2mwemynwj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tanke756.top/Article/details/gt2rilixcws.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ehwqpu.com/Article/details/gt2phrkzecg.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gt2ajpcbrkb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gt2nyvecpex.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gt2lkuoenxa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yangfankeji.com/Article/details/gt2hookjdim.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuanzx.com/Article/details/gt2tvboxrog.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snemgzjw.html

G. 面向对象
来源：http://dali.sufxvd.cn/Article/details/gt2guwuprcn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2yxwxrugw.html

[G01] 定义类
来源：http://dali.ivvv.top/Article/details/gt2gvnsymbe.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gt2tdmcewhs.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2cbnbzhlv.html

JS:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2ausfnhvx.html

TS:   class User { name: string = ""; }
来源：http://dali.dashuyun.cn/Article/details/gt2nrvepbvk.html

Java: class User {}
来源：http://dali.cashguo.top/Article/details/gt2kjuhwdcn.html

Go:   type User struct { Name string }
来源：http://dali.cheryme.top/Article/details/gt2xmxffygj.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gt2gzklaawz.html

C#:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2vhvovgwl.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gt2vsyjrrud.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zycfv.cn/Article/details/gt2ikxlnirx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gt2jktqanir.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2ugsyhqtc.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gt2jafybxam.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gt2efuoehdu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gt2hgnzrgrm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gt2thmiatld.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2mmcsduox.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gt2zqelntcm.html

Py:   self.name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gt2lrbrkzwa.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2dxyxopem.html

JS:   this.name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eajlcrpx.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2qidvkdev.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gt2fkclhqug.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gt2waxnmpyu.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gt2fdfmxzon.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2wlktpbfo.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gt2yvyrxkgg.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gt2csaxwazf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gt2cbtorqdq.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2zrbuvsdz.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2szfdmkri.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2upsjeyfn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gt2uhjelduo.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2tgbcroxd.html

C#:   public string Greet() => Name;
来源：http://dali.havefunace.top/Article/details/gt2gcdhyysu.html

[G05] 继承
来源：http://dali.dianchejie.cn/Article/details/gt2zybqrdfb.html

Py:   class Admin(User): pass
来源：http://dali.gaohongyu789.top/Article/details/gt2lgywscyt.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2pbamfmmo.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2wallicoa.html

TS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qbaeeeum.html

Java: class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2cmdwmley.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gt2rmgoimkt.html

Ruby: class Admin < User; end
来源：http://dali.hysaishi.cn/Article/details/gt2hmjxgkik.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbsrxxpq.html

[G06] 重写方法
来源：http://dali.vqdsnc.cn/Article/details/gt2cgyifkgd.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gt2ezavykbw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2sornjbqz.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2uewsygme.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2vcbmrpmb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2cmjcpyku.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daria6918.cn/Article/details/gt2fthkqezs.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gt2mrpsaedf.html


<!-- 参考信息 -->