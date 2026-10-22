代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.yj20258888.top/Article/details/gt2zwonndli.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.bjfxy.top/Article/details/gt2uibqvjan.html

[E08] 数组按分隔符合并
来源：http://dali.quarkkingdee.top/Article/details/gt2ftmhupiy.html

Py:   ",".join(items)
来源：http://dali.yuxming.cn/Article/details/gt2cliycgwj.html

PHP:  implode(",", $items);
来源：http://dali.jinqigufen.top/Article/details/gt2egrazabo.html

JS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gt2dqryeysy.html

TS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gt2qgucjibz.html

Java: String.join(",", items)
来源：http://dali.c1oappe.top/Article/details/gt2xwpwgtav.html

Go:   strings.Join(items, ",")
来源：http://dali.tian-w.cn/Article/details/gt2xycscmbq.html

Ruby: items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gt2cfwrvjix.html

C#:   string.Join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2djhsvxrt.html

[E09] 去除所有空白字符
来源：http://dali.hongshengwenyu.top/Article/details/gt2mnvopqnt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ppjwa.cn/Article/details/gt2vytaqaqk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hftixgwr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gt2kncmllaw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gt2cmqdeqnm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gt2nndmdzim.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cucudq.cn/Article/details/gt2icilwjuu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gt2prhcgtku.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckrqjopx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenzaomai.com/Article/details/gt2vyitoypo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2atcjrxit.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gt2tyqoonur.html

JS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2meveaxbi.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2ytwzilda.html

Java: String.format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gt2pxdabtpa.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2zdhjffta.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yyssyjuh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxinkj.top/Article/details/gt2ytbtkdqf.html

[E11] 反转字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2myazpjul.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gt2owzeukjk.html

PHP:  strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gt2boyauhse.html

JS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gt2nxlssfzo.html

TS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cqxmcqxm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hysaishi.cn/Article/details/gt2lgtxoycx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gt2quopofuj.html

Ruby: s.reverse
来源：http://dali.snrcjt.cn/Article/details/gt2dhturyur.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gt2bzeesgyg.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gt2ifyoonip.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2nfmhnbsz.html

PHP:  substr_count($s, "a");
来源：http://dali.redwolf501.top/Article/details/gt2zqtlylqa.html

JS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gt2qawdgobj.html

TS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gt2cltofwcf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pycfn.com/Article/details/gt2hlxjswni.html

Go:   strings.Count(s, "a")
来源：http://dali.nwbrower.top/Article/details/gt2lcidsfqt.html

Ruby: s.count("a")
来源：http://dali.aibaodan.cn/Article/details/gt2jtiyucep.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ppjwa.cn/Article/details/gt2efltabst.html

[E13] 逐字符遍历
来源：http://dali.chenlongwang.top/Article/details/gt2sgewuwme.html

Py:   for ch in s: print(ch)
来源：http://dali.cheryme.top/Article/details/gt2opcboyzk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgfzy.top/Article/details/gt2tjakjkvs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2beovqpca.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gt2qytxuzec.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2sscvivga.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gt2zamuujqk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhongyouzk.top/Article/details/gt2xouefupf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cdnleiting.top/Article/details/gt2gzzdrwwz.html

[E14] URL 编码与 Base64
来源：http://dali.feifeiyinyue.top/Article/details/gt2imhvcfln.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yongpay.top/Article/details/gt2czazjzfh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2ykxrjepb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ppjwa.cn/Article/details/gt2xblfetyd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuxming.cn/Article/details/gt2utgpgkpz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gt2jcjpgcls.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.andypj.xyz/Article/details/gt2rcuzsqdu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.andypj.xyz/Article/details/gt2kzknrjdv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zdqjudy.top/Article/details/gt2bfuufcqe.html

[E15] HTML 转义 / 反转义
来源：http://dali.redwolf501.top/Article/details/gt2bytjarkz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gt2eakwksqx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjozgtgi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.mhx1999.top/Article/details/gt2uvccyhkn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcgzodzs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ydzc1.top/Article/details/gt2hiticexz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2zmynykso.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gt2kyyoqprc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gt2kkfymhsq.html

[E16] 数字千分位
来源：http://dali.daxiang520.top/Article/details/gt2vduqense.html

Py:   f"{1234567:,}"
来源：http://dali.cdnleiting.top/Article/details/gt2xfsaqjxs.html

PHP:  number_format(1234567);
来源：http://dali.quarkkingdee.top/Article/details/gt2oasnghuc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2swonwrzi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gt2drxhbmlh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gt2ylyakdtq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ydzc1.top/Article/details/gt2vrqxqlnf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gt2qkkslreb.html

C#:   1234567.ToString("N0")
来源：http://dali.9152youxi.cn/Article/details/gt2tzukabgj.html

[E17] 首字母大写
来源：http://dali.shzxlz.cn/Article/details/gt2cktwxcrh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.redwolf501.top/Article/details/gt2ahgynjdf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2qsbnxbyl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gt2vmucqsmg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gt2mqglaxtx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jyoumei.cn/Article/details/gt2prtraryg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2liwndmbe.html

Ruby: s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gt2zjjkhkaa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hammf.cn/Article/details/gt2jspfehkx.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pcgurnbt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigufen.top/Article/details/gt2tgsabagk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jlsjyb.cn/Article/details/gt2gdlqegem.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gt2cbskxjzl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2ofnedywp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2nhxnmzsi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2toshwflc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yueranfly.top/Article/details/gt2ccotaolp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gt2vqtlozua.html

[E19] 多行文本按行拆分
来源：http://dali.yj202588.top/Article/details/gt2swmuitzr.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gt2xflazgop.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bchumgar.html

JS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gt2spxjemgx.html

TS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gt2vsqfeoyw.html

Java: s.lines().toList()
来源：http://dali.ybcxt.top/Article/details/gt2vzecvaky.html

Go:   strings.Split(s, "\n")
来源：http://dali.daxiang520.top/Article/details/gt2lnaxcsvz.html

Ruby: s.lines
来源：http://dali.fzhhl.top/Article/details/gt2tzepilec.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gt2bloequto.html

[E20] 判断字符串是否为空
来源：http://dali.ydzc1.top/Article/details/gt2kbsttjgu.html

Py:   if not s:
来源：http://dali.jqgfzy.top/Article/details/gt2mqwggfzg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhiwuduotai.top/Article/details/gt2whscyrtf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuxming.cn/Article/details/gt2xbksbopc.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gt2xeqjfkiz.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gt2luimtdfl.html

Go:   if s == "" {}
来源：http://dali.gotoacloud.top/Article/details/gt2axfvbfsl.html

Ruby: if s.empty?
来源：http://dali.aizwys.cn/Article/details/gt2gtqsvslw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gzhubu.top/Article/details/gt2cxzsvnqe.html

[E21] 超长截断加省略号
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vchuuokq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gt2wmsqjiiv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwwfeply.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2opsehwtd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2epgqaacc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2matreauf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gt2yawnoatu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2kkleqbqn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2rzehhsic.html

[E22] 字节长度与字符长度
来源：http://dali.guannengcc.top/Article/details/gt2xgzjogmn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dashuyun.cn/Article/details/gt2rchaabom.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2pqyessqw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2ffknhttj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gt2osrbnasq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gt2eumfwmvi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gt2iyujmecq.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2bztrmqfh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gt2iakfljmz.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2qjnankqp.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gt2cgveknpf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2dvbrhghg.html

[F01] 读取整个文件
来源：http://dali.dashuyun.cn/Article/details/gt2fwwcybjv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gt2taorolnq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2klvbjwgs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cheryme.top/Article/details/gt2tlwphzvk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hwhpjywz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2wmdqfjfs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.andypj.xyz/Article/details/gt2lieyiouf.html

Ruby: File.read("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2wogcojjo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2bukhzsjy.html

[F02] 逐行读取文件
来源：http://dali.guannengcc.top/Article/details/gt2cghnacbb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hywenlv.cn/Article/details/gt2wavpjswc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yangfankeji.com/Article/details/gt2mwcrlopl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gt2vevfovxl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gt2lqnzjdkp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gt2emtckkpi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yonumen.top/Article/details/gt2wqpnhnzv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258.top/Article/details/gt2unbmkxoi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnxiangtu.top/Article/details/gt2rzwtimps.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gt2zlvawzfo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258888.top/Article/details/gt2hysihynf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gt2iivtziuj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2foukzxbi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gt2lkfqsimp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2nwufdsks.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gt2pmrdxltv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gt2hmyolymh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gt2pyoliefk.html

[F04] 追加写入文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2tzpvsejn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gt2uisxjdph.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxinkj.top/Article/details/gt2moovudlf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2uumenqdw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2njmhgnbk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenjidiqi.icu/Article/details/gt2loyubygx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2kjjkqqbs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zycfv.cn/Article/details/gt2zsutlbvj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gogol.net.cn/Article/details/gt2dfanygkv.html

[F05] 判断文件或目录是否存在
来源：http://dali.pycfn.com/Article/details/gt2gfkkcevk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.vqdsnc.cn/Article/details/gt2bpygfnah.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2mqkvewrs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hkzvodok.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2hkzfytvl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2girwupwj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cashguo.top/Article/details/gt2qeraazth.html

Ruby: File.exist?("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2clplgyej.html

C#:   File.Exists("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2kitldjzh.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gt2mmlkdgoq.html

Py:   os.remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2dfoqpyre.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldfxwxoc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2iqqrrcbc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2pzuqidlm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqnuymt.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pigiqbiy.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2wqhhlotq.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2jgywsqua.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gt2kltrjnvq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gt2ocaghexc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yvedp.cn/Article/details/gt2luukabar.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gt2lbswbboy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gt2sjivjvqs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.redwolf501.top/Article/details/gt2uwyaxcdq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gt2mxdkinhr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gt2irapmoyr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guannengcc.top/Article/details/gt2xnpsrknf.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gt2tygxxlks.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gt2rsqmkxya.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gt2pbbbrkyx.html

JS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gt2faazzygd.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsphazl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dichalbm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tanke756.top/Article/details/gt2cciefzeb.html

Ruby: Dir.children("dir")
来源：http://dali.yongpay.top/Article/details/gt2xodiuzmy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xziqi.cn/Article/details/gt2bpqkenjs.html

[F09] 获取文件大小
来源：http://dali.hongshengwenyu.top/Article/details/gt2rsingrog.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjgfomgc.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2uumtbqzv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gt2whazqrae.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gt2vdzpqxjl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2kijyvbfr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gt2rphuvxiq.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2ejotsusj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guowangkeji.top/Article/details/gt2hrihtakv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daria6918.cn/Article/details/gt2fseyljwz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2jtujaczs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2fldanrrz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2lddwmkui.html

TS:   path.extname("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2cdyqnvqf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxinkj.top/Article/details/gt2cukezgev.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2thoaqjxs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2rmqaabju.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpalmbir.html

[F11] 复制与移动文件
来源：http://dali.cqqwz.cn/Article/details/gt2jhqoivya.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2osvaojow.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gt2hgojpwbt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2anqbtpdu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gt2hgjcsqzc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258.top/Article/details/gt2icnijewj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258.top/Article/details/gt2hszytojy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2sbxllhlp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daxiang520.top/Article/details/gt2hmhyvgtb.html

[F12] CSV 读写
来源：http://dali.yvedp.cn/Article/details/gt2dmtbhwaf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gt2tpqrzsfx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwjnlfpw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenjidiqi.icu/Article/details/gt2sajklepi.html

TS:   // 同上
来源：http://dali.nwbrower.top/Article/details/gt2icwblkbp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shuidangran.top/Article/details/gt2wlthivlp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gogol.net.cn/Article/details/gt2jziaswyq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gt2kjvzeilx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnxiangtu.top/Article/details/gt2vwhxqdng.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2zefwdzzi.html

G. 面向对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2skcewbxz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2bvzallsu.html

[G01] 定义类
来源：http://dali.ybcxt.top/Article/details/gt2jnklfeav.html

Py:   class User: pass
来源：http://dali.xziqi.cn/Article/details/gt2bkybcizq.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2oivvijsq.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2lvzfydqh.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gt2kvylwtfr.html

Java: class User {}
来源：http://dali.daxiang520.top/Article/details/gt2gfuytgmp.html

Go:   type User struct { Name string }
来源：http://dali.yuanzhike.top/Article/details/gt2rgxzyfgy.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2focuknxa.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gt2lvfhfwsx.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gt2mvvvjjfd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fengsongda.top/Article/details/gt2seiphmnw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.mhx1999.top/Article/details/gt2vdiuqvrh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gt2ssdihrnf.html

TS:   constructor(public name: string) {}
来源：http://dali.cdnleiting.top/Article/details/gt2iivyettg.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gt2phvyhatm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.havefunace.top/Article/details/gt2hneaswci.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2uzcmnnws.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2vjrnfidj.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gt2gecnarfa.html

Py:   self.name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nklnsydy.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2zssirrlt.html

JS:   this.name = "x";
来源：http://dali.sweek.top/Article/details/gt2scuhgjml.html

TS:   name: string = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2matwxqvt.html

Java: private String name;
来源：http://dali.smart0.xyz/Article/details/gt2zskallfh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gt2yqgslgub.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gt2qbdgnucr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gt2sbnmpesh.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gt2bpvqsdme.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gt2eeymmzsm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2lgqjdpoq.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2qerxecgt.html

TS:   greet(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gt2wonwqvbe.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2fodqkcmz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gt2itbqqbto.html

Ruby: def greet; @name; end
来源：http://dali.daxiang520.top/Article/details/gt2vfctdbgn.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gt2wxhiwbry.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gt2ewbnibyq.html

Py:   class Admin(User): pass
来源：http://dali.yongpay.top/Article/details/gt2winryqhq.html

PHP:  class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2rkmkzpqi.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2zfubzrsv.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2wlzyngqe.html

Java: class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2cwcqihrc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ehwqpu.com/Article/details/gt2pxladyin.html

Ruby: class Admin < User; end
来源：http://dali.nanxuanxn.top/Article/details/gt2jtoksxjp.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2epioqjtu.html

[G06] 重写方法
来源：http://dali.hysaishi.cn/Article/details/gt2voxzbcet.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gt2swgjqwvy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2vlkvmgyq.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2kqjkizcc.html


<!-- 参考信息 -->