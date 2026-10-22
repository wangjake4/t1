代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gt2bofszoga.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2lygmlsaj.html

TS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gt2wqhpmvjv.html

Java: String.join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hkitnvjv.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxyovws.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2xwxnfcvy.html

C#:   string.Join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gt2lhsyuqou.html

[E09] 去除所有空白字符
来源：http://dali.wangdashe.top/Article/details/gt2precdrmb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gt2mcpjsmob.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj202588.top/Article/details/gt2ygzbinrn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2mnhfwsjf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gt2niiiqtxi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gt2noholgwo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yvedp.cn/Article/details/gt2yxmxdgtr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2eclzaree.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gt2kbbnvyfd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pengpengdd.cyou/Article/details/gt2mmshbrdy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cucudq.cn/Article/details/gt2bewzlide.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sxryk.cn/Article/details/gt2kzlthnzp.html

JS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gt2mohsyufd.html

TS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2gzynrfbx.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gt2gnsihseo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gt2klbfvkmr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gt2ovjujiri.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swqodjtu.html

[E11] 反转字符串
来源：http://dali.yonumen.top/Article/details/gt2khhlttth.html

Py:   s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2cceomamx.html

PHP:  strrev($s);
来源：http://dali.cheryme.top/Article/details/gt2seffdnrd.html

JS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hehzoqao.html

TS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2vcrauwks.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.andypj.xyz/Article/details/gt2augdlnan.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2whezdkib.html

Ruby: s.reverse
来源：http://dali.daria6918.cn/Article/details/gt2leqskhyv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gt2vnfakoup.html

[E12] 统计某字符出现次数
来源：http://dali.zhengqikj.top/Article/details/gt2oddlkagz.html

Py:   s.count("a")
来源：http://dali.ydzc1.top/Article/details/gt2uqhoxzwf.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gt2efnitaos.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zzobxall.html

TS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gt2tsraldgx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daria6918.cn/Article/details/gt2ywlubspz.html

Go:   strings.Count(s, "a")
来源：http://dali.ivvv.top/Article/details/gt2pyoanfpo.html

Ruby: s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2gmxqilvj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gt2kqasdebg.html

[E13] 逐字符遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzazvqbz.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gt2zgermiwd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.0kj1m.cn/Article/details/gt2lzoqfgsk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gt2gaoskfli.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ypfreawp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2swieraqu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2dwsfykwr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgktbsqh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmbkzcz.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzaidfqy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhongyouzk.top/Article/details/gt2dbdmezyr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aizwys.cn/Article/details/gt2lpyewlsr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nwbrower.top/Article/details/gt2ynirbluw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj202588.top/Article/details/gt2oqisrcgc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.bjfxy.top/Article/details/gt2xzcoarqs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqzbbggp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenzaomai.com/Article/details/gt2afbojukc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.svipenyu.cn/Article/details/gt2ezjbnagf.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gt2xomndmmc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gt2tinjaxsm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shuidangran.top/Article/details/gt2vqepaqtd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gt2jhseittj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sxryk.cn/Article/details/gt2djvhsogz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guowangkeji.top/Article/details/gt2fjjzonel.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2fwlhssiq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gt2hkrjgezg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.svipenyu.cn/Article/details/gt2tnvuuobl.html

[E16] 数字千分位
来源：http://dali.snrcjt.cn/Article/details/gt2zfixefdx.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gt2yqzbfppj.html

PHP:  number_format(1234567);
来源：http://dali.haohaochexian.top/Article/details/gt2wfgubuoz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gt2ifamkzpi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gt2oiplmvhl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gt2adqakwge.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.mhx1999.top/Article/details/gt2uhrrqdru.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sufxvd.cn/Article/details/gt2yssyfcyk.html

C#:   1234567.ToString("N0")
来源：http://dali.ivvv.top/Article/details/gt2ctyjjtyk.html

[E17] 首字母大写
来源：http://dali.jinqigfzy.top/Article/details/gt2uffmjwoc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gt2ebgdwohj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cqqwz.cn/Article/details/gt2fwgoevdh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gt2tanbucwn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gt2esxhnzbm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gogol.net.cn/Article/details/gt2llrhsxrr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guannengcc.top/Article/details/gt2rpepccap.html

Ruby: s.capitalize
来源：http://dali.hammf.cn/Article/details/gt2qxcpryef.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gt2whmqunva.html

[E18] 模板占位符替换
来源：http://dali.andypj.xyz/Article/details/gt2cdtymryk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yueranfly.top/Article/details/gt2oyjvaayp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cucudq.cn/Article/details/gt2znrpwwrh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gt2vxkhyhfz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bdokldfg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gt2mgjfjgwi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aizwys.cn/Article/details/gt2ivrhqkms.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ajmyolun.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.vqdsnc.cn/Article/details/gt2yoogixwz.html

[E19] 多行文本按行拆分
来源：http://dali.andypj.xyz/Article/details/gt2wsmalwmb.html

Py:   s.splitlines()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ayoofbrz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2uygxuqpl.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gt2kgwkosvd.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gt2bgdfzmjk.html

Java: s.lines().toList()
来源：http://dali.redwolf501.top/Article/details/gt2bhagdtsb.html

Go:   strings.Split(s, "\n")
来源：http://dali.shzxlz.cn/Article/details/gt2llyqiqbp.html

Ruby: s.lines
来源：http://dali.tanke756.top/Article/details/gt2duwodecq.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gt2xaztqlph.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gt2teskxgms.html

Py:   if not s:
来源：http://dali.vqdsnc.cn/Article/details/gt2gcrgzxnq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gt2duybumia.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.svipenyu.cn/Article/details/gt2nwerwupt.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdvcnfwu.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gt2pmcjqjoc.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gt2wfepmfbu.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gt2isxclwvy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnqzz.top/Article/details/gt2wozxlvuu.html

[E21] 超长截断加省略号
来源：http://dali.jyoumei.cn/Article/details/gt2nrsedyjb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bgvvrhhb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gt2wxoslaql.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2nudnsdew.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2txpswnsb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2rolxjbgk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nndjpvdc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2vvuyfwcy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2zyohskhh.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gt2vqgcxory.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gt2dziiidqt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gt2zhnagglm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eqlubazm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gt2qttttbgu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zdqjudy.top/Article/details/gt2jmvwlwbf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hongshengwenyu.top/Article/details/gt2jqnxagzd.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2yvlmsinx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gt2ndzgvazb.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2rxhzmcju.html

F. 文件与目录
来源：http://dali.nanxinkj.top/Article/details/gt2sbsznbap.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2vhragmjw.html

[F01] 读取整个文件
来源：http://dali.zhongyouzk.top/Article/details/gt2hcuzjsmk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hfpthk.cn/Article/details/gt2uinvwzjh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2gsktabmh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gt2huzpcufl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.smart0.xyz/Article/details/gt2bzoiyybe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2toqfdwym.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gt2fbeexzgn.html

Ruby: File.read("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2clyxqslx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2jvaiehed.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gt2qroeieis.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gt2aimapynm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fengsongda.top/Article/details/gt2apaqxcmy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gt2xrbruztd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gt2gvogneaw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gt2lhkbiwox.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gt2nilhnbqc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuanzx.com/Article/details/gt2lmadmhpv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xinyue.icu/Article/details/gt2dgcostpt.html

[F03] 写入文件（覆盖）
来源：http://dali.sweek.top/Article/details/gt2mbqtulof.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gt2ssklceds.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gt2eevbglrx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gt2wlcuxwkb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gt2stwyykxe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.meibo888.top/Article/details/gt2gbmrxnza.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.birdmap.top/Article/details/gt2cpabfwnt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sysykeji.top/Article/details/gt2oemjqaai.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gt2uixcibrj.html

[F04] 追加写入文件
来源：http://dali.jiagoushi.top/Article/details/gt2bbxmszhg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2ppupvrko.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhongyouzk.top/Article/details/gt2bbkozeqv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gt2ytqeelch.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2bmfucjdb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jianghu66.top/Article/details/gt2zxjxnsmd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2kkzbvhck.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxlfwotm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cucudq.cn/Article/details/gt2haoaubhk.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gt2tbmtwfle.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gt2zfouknys.html

PHP:  file_exists("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2siklywvi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2appufokr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2kojzaayn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2ysjkxedk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tdoniocu.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aohccwof.html

C#:   File.Exists("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2khnhhyge.html

[F06] 删除文件
来源：http://dali.cucudq.cn/Article/details/gt2uxtqjirc.html

Py:   os.remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2clehqypb.html

PHP:  unlink("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2vzbvhgbd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2fegixeef.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qylrenwy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2hzmuqhsi.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2zeauljjt.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2pzmcbhly.html

C#:   File.Delete("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2mjhqflvl.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gt2ydsxqtxn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gt2ieffhqeq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gt2kxovpujr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gt2yexloyvq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gt2xccgprpj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gt2znqqtlxr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jyoumei.cn/Article/details/gt2bwxttzgs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hammf.cn/Article/details/gt2ftfphbac.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fengsongda.top/Article/details/gt2dcluqone.html

[F08] 遍历目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2ailyyvlg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gt2nwcvmyti.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gt2ztufsdxi.html

JS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2fwwwcmhw.html

TS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gt2jhneudfd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gt2xodpxpgi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenzaomai.com/Article/details/gt2ynsvwnrw.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2jzaxevbl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cashguo.top/Article/details/gt2hwkweihb.html

[F09] 获取文件大小
来源：http://dali.zycfv.cn/Article/details/gt2jolszuno.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2pnhielwm.html

PHP:  filesize("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2ryohrnki.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gt2tqvivxlw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gt2qdpsxdpg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2vbzjvtel.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zfelfiik.html

Ruby: File.size("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2juhmlqus.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.0kj1m.cn/Article/details/gt2oqxkkesm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj202588.top/Article/details/gt2rmzaibcf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2bcxrjpij.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2tstffnni.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2elourzfe.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2ltvrleaa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gt2fsssrqjt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2byakhmwa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kklwdcwe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2seqokmal.html

[F11] 复制与移动文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yeqecjhn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2upzauupp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gt2hxmlehgu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2oaouielu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgxlgruv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuxming.cn/Article/details/gt2cllgkbuz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gt2fhylbipi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejkzjqyn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2nkdyjiup.html

[F12] CSV 读写
来源：http://dali.zhixingplan.top/Article/details/gt2whfpybje.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gt2urutptfs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gt2krfhtbwo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gt2fbrxhzyd.html

TS:   // 同上
来源：http://dali.xylfe.cn/Article/details/gt2hnyacqlo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ehwqpu.com/Article/details/gt2ibgmwgnd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gt2twvmntjl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gt2lsugbsaa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gt2locfjdon.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2yrqxhthk.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gt2mnxfgsoi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2sunxotww.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gt2jofcouiq.html

Py:   class User: pass
来源：http://dali.yj202588.top/Article/details/gt2hqxdhexe.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ypfhgrpe.html

JS:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2flgzyrze.html

TS:   class User { name: string = ""; }
来源：http://dali.zhongyouzk.top/Article/details/gt2abdlxuvp.html

Java: class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2dlprcqcn.html

Go:   type User struct { Name string }
来源：http://dali.gzhubu.top/Article/details/gt2nngblafv.html

Ruby: class User; end
来源：http://dali.aizwys.cn/Article/details/gt2mzftfhii.html

C#:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2fcydgkcd.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gt2gtigicav.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gt2oskxoxhi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gt2swxnluvd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gt2fahofkoe.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2xootfnuv.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gt2smnklyfg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gt2zoltnmgv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2tdpigsku.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2jiihusoz.html

[G03] 实例属性
来源：http://dali.cdnleiting.top/Article/details/gt2hvrahlpj.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2akvtkmvd.html

PHP:  public string $name = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2psieokpd.html

JS:   this.name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2rmdufgle.html

TS:   name: string = "x";
来源：http://dali.xziqi.cn/Article/details/gt2negvznse.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gt2hrlhudhp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gt2fcwwxqym.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ziqlqzid.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2temdmwlc.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gt2cfbfzgaz.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gt2yvwnypwf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2ovrflpww.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2fpmpmpfb.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2tnsfovay.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2fmasmigc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gt2wixrlutq.html

Ruby: def greet; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2kagnpmyf.html

C#:   public string Greet() => Name;
来源：http://dali.daxiang520.top/Article/details/gt2lzyryfin.html

[G05] 继承
来源：http://dali.yonumen.top/Article/details/gt2cyppdbwr.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gt2vzbltrhq.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2qmxfrejv.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2sfwkrzct.html

TS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2syufdnbx.html

Java: class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2oxsvsgou.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gt2swulszrp.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gt2dcryrygh.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gt2mwzcpfnr.html

[G06] 重写方法
来源：http://dali.cashguo.top/Article/details/gt2sdzqkany.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gt2qctsloqk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2iahkcuox.html

JS:   greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2fuenshsl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2mjihabzr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gt2vgsqlmzl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gt2fusjqhtr.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gt2xcsrfcpt.html


<!-- 参考信息 -->