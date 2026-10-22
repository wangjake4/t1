代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2azubrqog.html

[E07] 按分隔符拆分
来源：http://dali.havefunace.top/Article/details/gt2ijhwrmny.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shangyingyoupin.top/Article/details/gt2thumfujl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2riewrfsb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwnlpwk.html

TS:   s.split(",")
来源：http://dali.cqqwz.cn/Article/details/gt2avxclpwo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aibaodan.cn/Article/details/gt2wtxdpxfo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.316326.xyz/Article/details/gt2flsyknpi.html

Ruby: s.split(",");  s.split
来源：http://dali.kuanghao11.cn/Article/details/gt2hnyxntqg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dianchejie.cn/Article/details/gt2fnbsxkeh.html

[E08] 数组按分隔符合并
来源：http://dali.nwbrower.top/Article/details/gt2duervptt.html

Py:   ",".join(items)
来源：http://dali.yangfankeji.com/Article/details/gt2wtdsccej.html

PHP:  implode(",", $items);
来源：http://dali.c1oappe.top/Article/details/gt2jtijbocz.html

JS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gt2ekmpwglt.html

TS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gt2ucfqyypw.html

Java: String.join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gt2ygqsuwqy.html

Go:   strings.Join(items, ",")
来源：http://dali.ybcxt.top/Article/details/gt2ygjhustl.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gt2etphqyag.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bbaryyel.html

[E09] 去除所有空白字符
来源：http://dali.chenlongwang.top/Article/details/gt2cxfwwlfz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qseriyqe.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2rhwugjlx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gt2zijhniyl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gt2luyqtzvo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gt2abvlfxfs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guannengcc.top/Article/details/gt2mflifgbr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenlongwang.top/Article/details/gt2fkptoesw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cheryme.top/Article/details/gt2hsdurcus.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gt2nbwmzcay.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gt2aootwqcw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zdqjudy.top/Article/details/gt2oiuxhlkz.html

JS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gt2uwnxpovf.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2txsfqvsx.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gt2xtflkjmf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gt2icmcqliw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2myjqrgxz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gaohongyu789.top/Article/details/gt2ycgwtzmn.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gt2myfcltaq.html

Py:   s[::-1]
来源：http://dali.ybcxt.top/Article/details/gt2funnpskp.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gt2fzpglzry.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2solqghwj.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2onjynkvc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2xfjptnbp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ydzc1.top/Article/details/gt2bduhhjbf.html

Ruby: s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2esmooybg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gt2fwzmyvoh.html

[E12] 统计某字符出现次数
来源：http://dali.jianghu66.top/Article/details/gt2tyctxkhh.html

Py:   s.count("a")
来源：http://dali.xziqi.cn/Article/details/gt2lmrszobl.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gt2dwagqgku.html

JS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gt2kxjjygmt.html

TS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gt2ngimqbax.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxuanxn.top/Article/details/gt2ypcemtnj.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gt2evyqwiug.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gt2udlgrfqj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhengqikj.top/Article/details/gt2pofnjmtl.html

[E13] 逐字符遍历
来源：http://dali.guowangkeji.top/Article/details/gt2pdeakmns.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gt2piihnbgf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gt2itsxxczg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gt2vcqtspus.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gt2ggtmpugc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2esugxabo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ivvv.top/Article/details/gt2tznrnstd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shzxlz.cn/Article/details/gt2lsbgkity.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gt2xvrbssav.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2inuoxslq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sxryk.cn/Article/details/gt2jhclykgy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gsevtxpg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258888.top/Article/details/gt2thccajks.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tian-w.cn/Article/details/gt2gqhrfmve.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ppjwa.cn/Article/details/gt2xukwfjmx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zrvatfpf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cqqwz.cn/Article/details/gt2eenbfxvv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kuumbsml.html

[E15] HTML 转义 / 反转义
来源：http://dali.gogol.net.cn/Article/details/gt2jclwzcnb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.smart0.xyz/Article/details/gt2pthkttwx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuanzx.com/Article/details/gt2opmiaftm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2csenrqsa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.c1oappe.top/Article/details/gt2uqjwcntn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sysykeji.top/Article/details/gt2mjtsmzos.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gt2xuahrplp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2fkmivama.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gt2mgrvqlke.html

[E16] 数字千分位
来源：http://dali.tian-w.cn/Article/details/gt2ugzkccpd.html

Py:   f"{1234567:,}"
来源：http://dali.smart0.xyz/Article/details/gt2ivgbooye.html

PHP:  number_format(1234567);
来源：http://dali.yuanzhike.top/Article/details/gt2zcqxrqdv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gt2wfcyvvwg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gt2rrtnqtio.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shuidangran.top/Article/details/gt2xxsdxbuz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2esnnknql.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhixingplan.top/Article/details/gt2qypjqlhz.html

C#:   1234567.ToString("N0")
来源：http://dali.fzhhl.top/Article/details/gt2vuupvmnb.html

[E17] 首字母大写
来源：http://dali.guannengcc.top/Article/details/gt2vfnzflak.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gotoacloud.top/Article/details/gt2gtewskag.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daxiang520.top/Article/details/gt2umgsnkxs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gt2zpfkkudc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vemvscuy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fengsongda.top/Article/details/gt2hqgphurm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2viwnword.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gt2zoqjaxli.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangshuangyany.cn/Article/details/gt2qtloljxh.html

[E18] 模板占位符替换
来源：http://dali.aibaodan.cn/Article/details/gt2wrhmmfez.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jruobtnw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhiwuduotai.top/Article/details/gt2avclpxyo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2ljjjzthp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2camdfkkz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2zbgbpulg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2omstubzg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenlongwang.top/Article/details/gt2fnuomfsj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258.top/Article/details/gt2oaviccnx.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gt2nqjhqqfe.html

Py:   s.splitlines()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kezxwafu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2mquuhgbi.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugckbptx.html

TS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqtanyah.html

Java: s.lines().toList()
来源：http://dali.ehwqpu.com/Article/details/gt2rizvnzfj.html

Go:   strings.Split(s, "\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2iqivetbz.html

Ruby: s.lines
来源：http://dali.yuanzhike.top/Article/details/gt2vakdilbb.html

C#:   s.Split('\n')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2drlfsomq.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gt2lygcxxfg.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gt2rwvngbhj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gt2knipymec.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gt2ckjlmonm.html

TS:   if (s === "") {}
来源：http://dali.zycfv.cn/Article/details/gt2tixyucht.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gt2jubvwlil.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gt2mwwlutpj.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gt2bkljimxb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.andypj.xyz/Article/details/gt2wknwrpjr.html

[E21] 超长截断加省略号
来源：http://dali.zycfv.cn/Article/details/gt2cquffjsj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnxiangtu.top/Article/details/gt2bpivrrme.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2jijfmdll.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2bkmvzras.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2bnahavmd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2lriubiol.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ivvv.top/Article/details/gt2dvhrxuir.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2aliryvbg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2yiaajwdx.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gt2myvqzpyr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gfrpqkso.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gt2doryxqda.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gt2wglsbmyi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gt2fabczjcr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.havefunace.top/Article/details/gt2yfgoefnx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sufxvd.cn/Article/details/gt2pbwlrone.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqimnart.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenzaomai.com/Article/details/gt2keiljjew.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2bfrlhsfg.html

F. 文件与目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2ttcsgixg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2pjlkghnu.html

[F01] 读取整个文件
来源：http://dali.jyoumei.cn/Article/details/gt2wfhzmoez.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gt2vnqqnvqb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2novektpc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fzhhl.top/Article/details/gt2xscppinm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnqzz.top/Article/details/gt2pbvwrchn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gt2zlgohaff.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guannengcc.top/Article/details/gt2iaglbccc.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2etlxqfie.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ygekzhdd.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gt2huulqwrt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuanzx.com/Article/details/gt2cauoppaf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.svipenyu.cn/Article/details/gt2hwwnyxwh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2yswgobev.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gt2qzercspk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gt2zutojhip.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gt2rzikdlzh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dashuyun.cn/Article/details/gt2mziycucq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gt2tiuiaick.html

[F03] 写入文件（覆盖）
来源：http://dali.jlsjyb.cn/Article/details/gt2qjfzznll.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jiagoushi.top/Article/details/gt2iouybsml.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jjxybigj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gt2kkqyfegl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gt2hctskltp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvychfnb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnxiangtu.top/Article/details/gt2bacvbdsi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sufxvd.cn/Article/details/gt2wfyucjvk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gt2ucxgbkmc.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gt2gnyxoaun.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tanke756.top/Article/details/gt2pfhqsaow.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gt2njwztdfz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2ghiuusns.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gt2ryzgviep.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gt2hhsyaynl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rdgbghpo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fzhhl.top/Article/details/gt2hubxwave.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dashuyun.cn/Article/details/gt2vtqcnwzw.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gt2mdxldebv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2myckgzhh.html

PHP:  file_exists("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2qxqklhmc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2ztjeodzg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2xvdlzwcn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gt2jbxoofro.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.smart0.xyz/Article/details/gt2koshbiku.html

Ruby: File.exist?("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pykpivys.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2hdpglxss.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gt2fjvrdbkn.html

Py:   os.remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jjooakfi.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xoqwdfcy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2witfouoz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2tpdkoxca.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2gecmkxbh.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2ipjevmhl.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2lxxasnif.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2fonlotpa.html

[F07] 创建目录（含多级）
来源：http://dali.yangfankeji.com/Article/details/gt2essihaym.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2xqwmtlyu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258888.top/Article/details/gt2ffxhamrx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gt2huctlumf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qrdpfdrh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gogol.net.cn/Article/details/gt2vjvqwhhn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2agfordka.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhongyouzk.top/Article/details/gt2xecnonug.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shuidangran.top/Article/details/gt2zjtmpatp.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gt2stcnoxoj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.kuanghao11.cn/Article/details/gt2pbwxtepx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mdsegohb.html

JS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gt2qrwrzsat.html

TS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2nhjzzjcf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gt2zfdddlde.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2addkgxww.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gt2ivhjuclg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2oxqfttiw.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gt2ocownmjq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2lsbfjyxh.html

PHP:  filesize("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2pfkdqjxs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gt2zzggtjkg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gt2qnecbbah.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2oagpeuue.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gzhubu.top/Article/details/gt2aktortwg.html

Ruby: File.size("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njvaaiwj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guowangkeji.top/Article/details/gt2gewunssv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzddydde.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2jbvztmfa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sweek.top/Article/details/gt2iiokqkfr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2ymaegadw.html

TS:   path.extname("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2brrhelno.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gt2xnhdshsz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2spbqqyga.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2qriakegz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2kfzxqtpu.html

[F11] 复制与移动文件
来源：http://dali.svipenyu.cn/Article/details/gt2meojnvxs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2plnhjbpm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gt2ryjawmeh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2wnsipxnf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2trkngjel.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gt2ewtdpniw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenzaomai.com/Article/details/gt2xkjajldp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zcnhapbr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhixingplan.top/Article/details/gt2zibobmvg.html

[F12] CSV 读写
来源：http://dali.aibaodan.cn/Article/details/gt2tkimrkjx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2taskwiiz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gt2czneblbi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xyndgsmp.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gt2uwxbbdnx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gt2weqaoyza.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gt2upphjxmv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.kuanghao11.cn/Article/details/gt2tjsfanue.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gt2bhjfedzi.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2wntcpgbw.html

G. 面向对象
来源：http://dali.ydzc1.top/Article/details/gt2gbpmuibh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2khcpmvjq.html

[G01] 定义类
来源：http://dali.ivvv.top/Article/details/gt2uivoqbyl.html

Py:   class User: pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fouriwzy.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gt2fhxrttgi.html

JS:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2jwyfwgxb.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkhzthqo.html

Java: class User {}
来源：http://dali.sxryk.cn/Article/details/gt2eorrmvsi.html

Go:   type User struct { Name string }
来源：http://dali.yj20258.top/Article/details/gt2zzzgvbda.html

Ruby: class User; end
来源：http://dali.hywenlv.cn/Article/details/gt2jhmsvzqk.html

C#:   class User {}
来源：http://dali.aizwys.cn/Article/details/gt2qaonafsq.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2shfzouhn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gt2odjgsqpv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2lbxjvrmq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gt2ihyxxfak.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2mkylhiaq.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gt2ylzkpcbx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vclkxdwf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gt2xjtesyow.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hysaishi.cn/Article/details/gt2qwhdbleb.html

[G03] 实例属性
来源：http://dali.cashguo.top/Article/details/gt2xopuhlel.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gt2ppbrtnir.html

PHP:  public string $name = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2nsbxkzhq.html

JS:   this.name = "x";
来源：http://dali.nwbrower.top/Article/details/gt2coorugzf.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2vuveopso.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gt2pjatjtrc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jianghu66.top/Article/details/gt2sgxsqhdn.html

Ruby: @name = "x"
来源：http://dali.yj20258.top/Article/details/gt2wiejnhay.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2hlrtbxro.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gt2awzshqdp.html

Py:   def greet(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gt2ljqtelkv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gt2newupkur.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2xttcyghb.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2sgkaatxv.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2mzthbkjf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2wxikxtrr.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2vlehybzs.html

C#:   public string Greet() => Name;
来源：http://dali.guannengcc.top/Article/details/gt2tbmmqavl.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gt2eidyzqxm.html

Py:   class Admin(User): pass
来源：http://dali.quarkkingdee.top/Article/details/gt2brddpacs.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2ngyucqcs.html

JS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2tbitmhaw.html

TS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2lywzqzew.html


<!-- 参考信息 -->