代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtrvsaudms.html

[E07] 按分隔符拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuphmxvul.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hongshengwenyu.top/Article/details/gtxzmuvkyd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtcsbqkpqk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenlongwang.top/Article/details/gteylmuuwg.html

TS:   s.split(",")
来源：http://dali.daria6918.cn/Article/details/gtdfoygtsz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gtkrjsyary.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gzhubu.top/Article/details/gtjkyzbhav.html

Ruby: s.split(",");  s.split
来源：http://dali.xziqi.cn/Article/details/gtcyrdevyk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ehwqpu.com/Article/details/gtwazyzsov.html

[E08] 数组按分隔符合并
来源：http://dali.xziqi.cn/Article/details/gtutljojoq.html

Py:   ",".join(items)
来源：http://dali.andypj.xyz/Article/details/gtsqikeavd.html

PHP:  implode(",", $items);
来源：http://dali.fzhhl.top/Article/details/gtlssjzdtf.html

JS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtvlfxglmr.html

TS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtfxagmkcr.html

Java: String.join(",", items)
来源：http://dali.jianghu66.top/Article/details/gtgsvdkqlq.html

Go:   strings.Join(items, ",")
来源：http://dali.jianghu66.top/Article/details/gtkmmxpsbm.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gturlljiuk.html

C#:   string.Join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gtrupyguta.html

[E09] 去除所有空白字符
来源：http://dali.cheryme.top/Article/details/gtmeuviqwv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.kuanghao11.cn/Article/details/gtqozggccq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.birdmap.top/Article/details/gtwgzkniqi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtwlhscnmh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gtlkhllyri.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpkyrxcq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jlsjyb.cn/Article/details/gtiezwqlis.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daxiang520.top/Article/details/gtybugwwbe.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gthkxgplaf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.birdmap.top/Article/details/gtefbmkvsg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtmquypemc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvtxnyrn.html

JS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gteijxwhiv.html

TS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtdiejspij.html

Java: String.format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtsmzixykf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqraryhq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtqazclujm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gtostvuxoc.html

[E11] 反转字符串
来源：http://dali.ybcxt.top/Article/details/gthiqpqvar.html

Py:   s[::-1]
来源：http://dali.cucudq.cn/Article/details/gtojlqgemm.html

PHP:  strrev($s);
来源：http://dali.yj202588.top/Article/details/gtfgbrkpgf.html

JS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtpmpwjzzn.html

TS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtnqovsite.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sufxvd.cn/Article/details/gtilzboaio.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xinyue.icu/Article/details/gtclkxlkyl.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gtltbbgizc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gtoqazxrfh.html

[E12] 统计某字符出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gtievajfbd.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnokflymk.html

PHP:  substr_count($s, "a");
来源：http://dali.feifeiyinyue.top/Article/details/gtfjbhzbts.html

JS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtkoywjamw.html

TS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtzhsdzkez.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenjidiqi.icu/Article/details/gtnvwgjnoa.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gtjyunquic.html

Ruby: s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gtlooovzyb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.svipenyu.cn/Article/details/gtoxvhbaug.html

[E13] 逐字符遍历
来源：http://dali.vqdsnc.cn/Article/details/gtggznauhr.html

Py:   for ch in s: print(ch)
来源：http://dali.redwolf501.top/Article/details/gtsrxxdybu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqlkhhzwy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbozkxvgo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gttgdqtxkt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtcwqttnkp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258888.top/Article/details/gtwcczfukz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shuidangran.top/Article/details/gtlttbzhhu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gtfsnxkxbc.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfixngox.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnxiangtu.top/Article/details/gtmxrawows.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gtswjzitzb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdfvbzrw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenzaomai.com/Article/details/gtiewnjvch.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tanke756.top/Article/details/gtsdktxcrt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aizwys.cn/Article/details/gtbjsalhze.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxinkj.top/Article/details/gtjejatieh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sysykeji.top/Article/details/gtiypcvkmd.html

[E15] HTML 转义 / 反转义
来源：http://dali.shzxlz.cn/Article/details/gtupsrmpno.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnxiangtu.top/Article/details/gtuqpibhfe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guowangkeji.top/Article/details/gtsyuckpnw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtypptysta.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehedmtfv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daria6918.cn/Article/details/gtuukggwlr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.havefunace.top/Article/details/gtwmmgzayb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtwlxdoylm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cdnleiting.top/Article/details/gtiefslnbz.html

[E16] 数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gtdofodcsq.html

Py:   f"{1234567:,}"
来源：http://dali.yuxming.cn/Article/details/gtjxctsbmf.html

PHP:  number_format(1234567);
来源：http://dali.nwbrower.top/Article/details/gtpzxmwxlz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtjhdxueap.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtuimxswlg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xylfe.cn/Article/details/gtteokwtxb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cucudq.cn/Article/details/gtajqohxvg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnqzz.top/Article/details/gtqvisqqaj.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgufenzy.top/Article/details/gtqkfxdefp.html

[E17] 首字母大写
来源：http://dali.aibaodan.cn/Article/details/gtmqevtnov.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.316326.xyz/Article/details/gtlubdcjwv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gaohongyu789.top/Article/details/gtzmekgcih.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtmsypmfpb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gtbllcjzbl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmencfcav.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gtindttxpv.html

Ruby: s.capitalize
来源：http://dali.hammf.cn/Article/details/gtndydjzpa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqubbptpw.html

[E18] 模板占位符替换
来源：http://dali.zhiwuduotai.top/Article/details/gtbzoowkdh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnxiangtu.top/Article/details/gthdpvkgel.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.quarkkingdee.top/Article/details/gtmccqdvfo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtmwwnswmr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtakdzizlk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtvglbnief.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtlhoeqhky.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ybcxt.top/Article/details/gtjrjzqksf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhengqikj.top/Article/details/gtrylegqxu.html

[E19] 多行文本按行拆分
来源：http://dali.ehwqpu.com/Article/details/gtzglmqezc.html

Py:   s.splitlines()
来源：http://dali.hammf.cn/Article/details/gtjpbotswh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ydzc1.top/Article/details/gttskunxqg.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtbsxgbavz.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtkievvurx.html

Java: s.lines().toList()
来源：http://dali.pycfn.com/Article/details/gtauqyngux.html

Go:   strings.Split(s, "\n")
来源：http://dali.cqqwz.cn/Article/details/gtotoofqvz.html

Ruby: s.lines
来源：http://dali.guannengcc.top/Article/details/gtadkhsnoe.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gtnwfymshn.html

[E20] 判断字符串是否为空
来源：http://dali.xinyue.icu/Article/details/gtvjhrnowi.html

Py:   if not s:
来源：http://dali.zhongyouzk.top/Article/details/gtuzqrpoxn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gtdrkjddzf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gtptdklmuj.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gtdyxwatbg.html

Java: if (s.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtkhbjpeds.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevoxrpbi.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gthegjdvme.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtwcrnnahu.html

[E21] 超长截断加省略号
来源：http://dali.gotoacloud.top/Article/details/gtkwcwhjla.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenjidiqi.icu/Article/details/gtzbqngfwf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtqjbprbjd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtufqarwnx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtymwolhdh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtgjjyyvnn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.haohaochexian.top/Article/details/gtoqukrtsg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtkekgemcq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtlshqxqcy.html

[E22] 字节长度与字符长度
来源：http://dali.svipenyu.cn/Article/details/gtioejkbdo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenzaomai.com/Article/details/gtovklyjcs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtmpbybfoc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtfprbvyri.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtkhmxvjgb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtambsgkku.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gaohongyu789.top/Article/details/gtpasadjci.html

Ruby: s.bytesize;  s.length
来源：http://dali.nwbrower.top/Article/details/gtiutxpqrg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtliahupnd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtjhrnspaj.html

F. 文件与目录
来源：http://dali.zhiwuduotai.top/Article/details/gthohkzcep.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtouajnvkj.html

[F01] 读取整个文件
来源：http://dali.jinqigfzy.top/Article/details/gttwwwbcyq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pengpengdd.cyou/Article/details/gtkwggfizk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.birdmap.top/Article/details/gtxicngueo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gtybuweidi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtuzcezori.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtbuhfdarw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.bjfxy.top/Article/details/gtrpxtdklt.html

Ruby: File.read("a.txt")
来源：http://dali.pycfn.com/Article/details/gttfidtmba.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtjgcxnwgf.html

[F02] 逐行读取文件
来源：http://dali.bjfxy.top/Article/details/gtxmljktch.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aizwys.cn/Article/details/gtxestwqvy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtszcfpqbs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gtomuxngxb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtecathzzn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtdkjdwanz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.bjfxy.top/Article/details/gtrjdsewnk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aibaodan.cn/Article/details/gtcajpopmb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pengpengdd.cyou/Article/details/gtfesfyaoa.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gtavdxulby.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gtqcylyftc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtzchummcv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtktjfphiz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtupwaydtq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgfzy.top/Article/details/gtgrqzuhpr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zycfv.cn/Article/details/gtzuubchwj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgfzy.top/Article/details/gthvixxomc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtbuwzipid.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gtdclvonkm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawajpgmd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjxkkrmp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gtdujbozqq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gtevanfxnc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ppjwa.cn/Article/details/gtalmohgkz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtsaigweuk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gtphzryknw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jiagoushi.top/Article/details/gtlughoscf.html

[F05] 判断文件或目录是否存在
来源：http://dali.guowangkeji.top/Article/details/gtduiwidji.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cqqwz.cn/Article/details/gtbtuzrlac.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtmxzzvime.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtwyhtijrn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtpuyqgdvx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtvqjobmmf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sufxvd.cn/Article/details/gtmyfvsqtb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtrefiasqj.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtkthmatzb.html

[F06] 删除文件
来源：http://dali.0kj1m.cn/Article/details/gtahiliecp.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtlcywruuh.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtszuuczfi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtnsilggub.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtlyvyewiq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtejadkugh.html

Go:   os.Remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gttmtdjbzp.html

Ruby: File.delete("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtzpaeawkd.html

C#:   File.Delete("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtkoqnsevb.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gtzodixfgl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtblnhicqy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuojvorb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gtwbeuipmz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtxjcjhrys.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.smart0.xyz/Article/details/gtwoksbyez.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258888.top/Article/details/gtstxsjvyy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hongshengwenyu.top/Article/details/gtxsonlclr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gtgziybtrv.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gtwblbgamc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gtagimthun.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hfpthk.cn/Article/details/gtqkdxrtuv.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwteyhpp.html

TS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gtiiiuyyim.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtzcwzcqik.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gtfetfrlsi.html

Ruby: Dir.children("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtmsaszobj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtlfsyhham.html

[F09] 获取文件大小
来源：http://dali.cucudq.cn/Article/details/gtbkrefwcm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtxpwvmrku.html

PHP:  filesize("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtwculuevs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gtlwdnaftq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gtoovkfjpz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtyzpycsah.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cheryme.top/Article/details/gtlfdizbje.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtkavyoqwu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gogol.net.cn/Article/details/gtsnwgjsjw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gtgwsqbfea.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtnoxxfdds.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtsziyhigo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gttebofatd.html

TS:   path.extname("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtohxkcmdz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shzxlz.cn/Article/details/gtjenvtheu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtuiuyfoyp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtfkwljrgc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtzyoaywak.html

[F11] 复制与移动文件
来源：http://dali.yvedp.cn/Article/details/gtjnpsorlq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtflhijbnl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenlongwang.top/Article/details/gtdhvajdgd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtyhluitvk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtknszotiv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteomajzzz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenlongwang.top/Article/details/gtlaegzcln.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtuqfpfenq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gtnzynqykn.html

[F12] CSV 读写
来源：http://dali.pengpengdd.cyou/Article/details/gtevjoxzaj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj202588.top/Article/details/gtrdxrelgk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gtsptmpzge.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuetiantiany.cn/Article/details/gtszskmipa.html

TS:   // 同上
来源：http://dali.aibaodan.cn/Article/details/gtkinekhsb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gtqxiysipe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dianchejie.cn/Article/details/gtyeqsejlr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ybcxt.top/Article/details/gttxvsuggh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gtqpyjslug.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtelrpjabf.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gtfxnutgry.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtbrhqujeu.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gtlliriebi.html

Py:   class User: pass
来源：http://dali.havefunace.top/Article/details/gtbfqgzogx.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gtmjysqlxe.html

JS:   class User {}
来源：http://dali.yongpay.top/Article/details/gtxeugwpyh.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gtahmmrewq.html

Java: class User {}
来源：http://dali.yj20258888.top/Article/details/gtjitekuob.html

Go:   type User struct { Name string }
来源：http://dali.jqgufenzy.top/Article/details/gtdrvlgqsf.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gtcfsiwayk.html

C#:   class User {}
来源：http://dali.xinyue.icu/Article/details/gtzewzhfsf.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtuyhjxeif.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.snrcjt.cn/Article/details/gtrttohmbk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gtzmblhzlq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtxaqaxfms.html

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gtknleicud.html

Java: User(String name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtrsagsyub.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daxiang520.top/Article/details/gtyaxmjhvt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shzxlz.cn/Article/details/gtcfqbqizu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtvqalbnyi.html

[G03] 实例属性
来源：http://dali.yuanzhike.top/Article/details/gtgmdhhzcx.html

Py:   self.name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtjdoefqzq.html

PHP:  public string $name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtksxpzyxu.html

JS:   this.name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtdcdkvrxz.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtmtxwwlyt.html

Java: private String name;
来源：http://dali.mhx1999.top/Article/details/gtkuqvfdpp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.havefunace.top/Article/details/gtdkvaiape.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtdnwavnbi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gtawveujmx.html

[G04] 定义方法
来源：http://dali.jinqigfzy.top/Article/details/gtuyrojrxo.html

Py:   def greet(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfnazzhy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtqrayludk.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtkgpzzvzb.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gthrawgjtk.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtgmwzmiar.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtkpabxmkb.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkrjzlkz.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gtgqjdfslg.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gtalewaiys.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gtqieifhen.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtyizsvxpv.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtpitlfzhq.html

TS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtgsebmlpg.html


<!-- 参考信息 -->