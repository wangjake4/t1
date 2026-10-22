代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.zdqjudy.top/Article/details/gt2vmhaviya.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gt2lxogfscl.html

[E08] 数组按分隔符合并
来源：http://dali.0kj1m.cn/Article/details/gt2yzspxnai.html

Py:   ",".join(items)
来源：http://dali.pycfn.com/Article/details/gt2bsfhzgik.html

PHP:  implode(",", $items);
来源：http://dali.zhongyouzk.top/Article/details/gt2btfhaskn.html

JS:   items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gt2gilwetzx.html

TS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gt2yslzuxkz.html

Java: String.join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gt2bvnljzhr.html

Go:   strings.Join(items, ",")
来源：http://dali.guannengcc.top/Article/details/gt2urguiwra.html

Ruby: items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gt2qmdmcpim.html

C#:   string.Join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gt2twqhqyvo.html

[E09] 去除所有空白字符
来源：http://dali.yj20258.top/Article/details/gt2lutrjtcq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gt2sxlpxtya.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dlzpvpbf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gt2vxjyywgn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gt2bemovsrv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gt2gedsufxh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xylfe.cn/Article/details/gt2upwictgv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.quarkkingdee.top/Article/details/gt2vloltydg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gt2nsggsxbc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cdnleiting.top/Article/details/gt2axkuhevp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2wncdkwlz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tian-w.cn/Article/details/gt2msmzsktj.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2prpgdhhi.html

TS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbqcqejf.html

Java: String.format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gt2adodcxxs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gt2upqfbyek.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gt2hxjawtmt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dashuyun.cn/Article/details/gt2lmaefszc.html

[E11] 反转字符串
来源：http://dali.chenzaomai.com/Article/details/gt2dzhskntt.html

Py:   s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gt2tlnaivhm.html

PHP:  strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2zwuiowfq.html

JS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2kwydztfi.html

TS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2xjetyrni.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tanke756.top/Article/details/gt2wassleii.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tian-w.cn/Article/details/gt2kttwytgt.html

Ruby: s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zuvujajm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gt2xnnbdkth.html

[E12] 统计某字符出现次数
来源：http://dali.sweek.top/Article/details/gt2yqwdhkru.html

Py:   s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gt2tbgrlnnb.html

PHP:  substr_count($s, "a");
来源：http://dali.hammf.cn/Article/details/gt2jiktvujh.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gt2uyjkedoo.html

TS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gt2fklugxqx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ywlfiuzo.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gt2juebvzky.html

Ruby: s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqzhxoqg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gt2umsxosjw.html

[E13] 逐字符遍历
来源：http://dali.tian-w.cn/Article/details/gt2isexnuyu.html

Py:   for ch in s: print(ch)
来源：http://dali.zhoulong.xyz/Article/details/gt2nqeszgny.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sxryk.cn/Article/details/gt2wvseczxc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gt2ziyliduj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gt2mutehdzm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zdqjudy.top/Article/details/gt2fwnvbhof.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmdtopkl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258.top/Article/details/gt2vdxdohbx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2ogjxqkdb.html

[E14] URL 编码与 Base64
来源：http://dali.c1oappe.top/Article/details/gt2qckzxvwr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gt2naippjrw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdgllsad.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.316326.xyz/Article/details/gt2xpxrlkue.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sxryk.cn/Article/details/gt2wqjyknxq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ssnpltrk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.andypj.xyz/Article/details/gt2fkfjopgg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ydzc1.top/Article/details/gt2oqfmxuhy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jianghu66.top/Article/details/gt2kxelozqr.html

[E15] HTML 转义 / 反转义
来源：http://dali.smart0.xyz/Article/details/gt2mpnpoges.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gt2rqmimktt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ivvv.top/Article/details/gt2hgpwcaaq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.9152youxi.cn/Article/details/gt2ydupayie.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xinyue.icu/Article/details/gt2pundyofr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqahzhlg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cdnleiting.top/Article/details/gt2kkcvbxel.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2evyskaqg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daxiang520.top/Article/details/gt2cossgveb.html

[E16] 数字千分位
来源：http://dali.gogol.net.cn/Article/details/gt2iqlwzuqq.html

Py:   f"{1234567:,}"
来源：http://dali.chenzaomai.com/Article/details/gt2akelkpfp.html

PHP:  number_format(1234567);
来源：http://dali.ivvv.top/Article/details/gt2ivkbigtz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gt2kyepoquw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gt2ofyljvnp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gt2jiluoexy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.mhx1999.top/Article/details/gt2ombqdlih.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuxming.cn/Article/details/gt2qtwjttcp.html

C#:   1234567.ToString("N0")
来源：http://dali.quarkkingdee.top/Article/details/gt2ianyylfm.html

[E17] 首字母大写
来源：http://dali.feifeiyinyue.top/Article/details/gt2sijdxpln.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrsqhffz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hywenlv.cn/Article/details/gt2qtvtdxkt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqtcsbny.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gt2ipzwanvc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj202588.top/Article/details/gt2stmvuvsm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.iojbl.cn/Article/details/gt2bwqzboiy.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gt2lbzmpkds.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zycfv.cn/Article/details/gt2mxmoqiam.html

[E18] 模板占位符替换
来源：http://dali.daxiang520.top/Article/details/gt2fetunroz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gt2doyrjusu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nwbrower.top/Article/details/gt2lozrucug.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gt2gmiwisas.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2aeasxxcl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2bjngkjfn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2bkbclqwi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigfzy.top/Article/details/gt2cjcmdrtg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.0kj1m.cn/Article/details/gt2rodnibiu.html

[E19] 多行文本按行拆分
来源：http://dali.zycfv.cn/Article/details/gt2rkrtflsp.html

Py:   s.splitlines()
来源：http://dali.kuanghao11.cn/Article/details/gt2udgcbwaz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2sbnblpqr.html

JS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gt2wgnbmyls.html

TS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gt2vcmxtbvb.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gt2tnozflfa.html

Go:   strings.Split(s, "\n")
来源：http://dali.cheryme.top/Article/details/gt2tljyvzsf.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gt2mtpssgqj.html

C#:   s.Split('\n')
来源：http://dali.nanxuanxn.top/Article/details/gt2bifdjlwz.html

[E20] 判断字符串是否为空
来源：http://dali.zhixingplan.top/Article/details/gt2twsqmvhr.html

Py:   if not s:
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfnarfsa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhtfbtmb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gzhubu.top/Article/details/gt2plhehssd.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gt2uennnhkq.html

Java: if (s.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gt2hemjnxly.html

Go:   if s == "" {}
来源：http://dali.zhixingplan.top/Article/details/gt2smzpdbwt.html

Ruby: if s.empty?
来源：http://dali.wangdashe.top/Article/details/gt2mbhjnrob.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sufxvd.cn/Article/details/gt2taehfbxp.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gt2nkzcqpwm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigfzy.top/Article/details/gt2itwfxmhi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gt2loicaqpg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2cnmpmpaz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlzjscr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2kemwases.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ydzc1.top/Article/details/gt2rgjxtmfi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2styymwky.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gt2pwhspwfl.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gt2ljchkzaw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenzaomai.com/Article/details/gt2pzlrfjcs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2uxkriswz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gt2jqazztup.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2xyrodepi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258888.top/Article/details/gt2kcmzqjwa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gt2uanicwpu.html

Ruby: s.bytesize;  s.length
来源：http://dali.ehwqpu.com/Article/details/gt2gtvoeabw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gotoacloud.top/Article/details/gt2ndhcjdko.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2pdkpkugw.html

F. 文件与目录
来源：http://dali.gotoacloud.top/Article/details/gt2gudchakn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2tpqvztwv.html

[F01] 读取整个文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2juczfjlv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jyoumei.cn/Article/details/gt2cloooxpw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2ghgabuyu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tian-w.cn/Article/details/gt2uaqxjgrc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2dhctcyjj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gt2gfcrrmvl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guowangkeji.top/Article/details/gt2kymmrozb.html

Ruby: File.read("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yieyrrkj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2xjsgnxop.html

[F02] 逐行读取文件
来源：http://dali.shzxlz.cn/Article/details/gt2dxyemaga.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.bjfxy.top/Article/details/gt2xruvzusp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenzaomai.com/Article/details/gt2cvnqotpc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gt2mjrdlrjd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gt2kbjijpsm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gt2udgssxbk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tianlin.xyz/Article/details/gt2ylpkvqht.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.redwolf501.top/Article/details/gt2pudmzpnx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xziqi.cn/Article/details/gt2lqbfrdvx.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gt2hrfirzvk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yueranfly.top/Article/details/gt2ojoetoyi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gt2ygihbbmb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gt2zdlrswhk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gt2qrmtojre.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxuanxn.top/Article/details/gt2zskervfy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gt2dsddbzeg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gotoacloud.top/Article/details/gt2etuzxmxg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gt2oezdroyv.html

[F04] 追加写入文件
来源：http://dali.hnqzz.top/Article/details/gt2ryrrxjny.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ybcxt.top/Article/details/gt2plmfhsyx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258.top/Article/details/gt2hzmxbwmx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gt2ppqoscmd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2ituholuo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.316326.xyz/Article/details/gt2wdyezrpw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.bjfxy.top/Article/details/gt2vxpcqloo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxinkj.top/Article/details/gt2pjodpwom.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhongyouzk.top/Article/details/gt2igljoumt.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2apwdkmmw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hfpthk.cn/Article/details/gt2forututn.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2hstzeyfm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2kflibonb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2mwtwrjqx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2bztqqfis.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdfhgjka.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2ssmgmbvv.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2rebqmwvz.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gt2ofdqydqs.html

Py:   os.remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2qwsntfbs.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2nkfwpmbi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sgakpzbe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2qmhjkocp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2ungbhpwm.html

Go:   os.Remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2pdiwxfbk.html

Ruby: File.delete("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2cxvecbgc.html

C#:   File.Delete("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2txsnlzzx.html

[F07] 创建目录（含多级）
来源：http://dali.gzhubu.top/Article/details/gt2amdplhje.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jlmakgao.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gt2tvsniali.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gt2kwcvqxrg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gt2fvgopoan.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.c1oappe.top/Article/details/gt2uhibapmm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxinkj.top/Article/details/gt2fttsyqaj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dianchejie.cn/Article/details/gt2sdzikrzb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gt2qdvrjvoz.html

[F08] 遍历目录
来源：http://dali.fzhhl.top/Article/details/gt2faegmwqz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gt2qsihmvrg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hywenlv.cn/Article/details/gt2qpscdmur.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmaqaxiq.html

TS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2lxtjmhbr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gt2qgyhofpa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qtucytmq.html

Ruby: Dir.children("dir")
来源：http://dali.jianghu66.top/Article/details/gt2hssxvtte.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guannengcc.top/Article/details/gt2oagyjdqr.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gt2zyhhjygk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btvdvlcg.html

PHP:  filesize("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2wvvjmtaf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gt2edaniisk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjswbdsj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2bnnlpgiq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yonumen.top/Article/details/gt2dbgrgezo.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2salstwqj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cheryme.top/Article/details/gt2lqzhcdqf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qsjixcpm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2ckoddznl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2vmfgappw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2sztyecnr.html

TS:   path.extname("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2dzfsgmlc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cashguo.top/Article/details/gt2vuebehqn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2gaftwvrc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2hkgtktet.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2tpppvnih.html

[F11] 复制与移动文件
来源：http://dali.sxryk.cn/Article/details/gt2wqksbcby.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2qzahfxho.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ybcxt.top/Article/details/gt2zkqntmgz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2cjjaszfa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2wbgufyzl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258.top/Article/details/gt2ojasmzzg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgfzy.top/Article/details/gt2efaybgcd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2xmhgfvwu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnqzz.top/Article/details/gt2steguxbx.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gt2bkpdbzkq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gt2tjzvidpv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gt2ejkllpbm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gt2pkybiawj.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gt2znxxxbng.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gt2siusyntz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gt2nkhcomer.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuanzx.com/Article/details/gt2iwwngvnn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.0kj1m.cn/Article/details/gt2fcdbdkec.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2yzswvvwr.html

G. 面向对象
来源：http://dali.meibo888.top/Article/details/gt2apavtfyt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2tqyhwgrf.html

[G01] 定义类
来源：http://dali.tianlin.xyz/Article/details/gt2bvceibla.html

Py:   class User: pass
来源：http://dali.iojbl.cn/Article/details/gt2ibadaqnz.html

PHP:  class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2znarnqfw.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2igbknwiu.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhfedfyj.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gt2svhedall.html

Go:   type User struct { Name string }
来源：http://dali.yuxming.cn/Article/details/gt2qbuiaozx.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gt2umxesnbx.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gt2eaivzrcz.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gt2zrmbtpim.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hnxuvswb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gt2lhyzimkj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gt2otzjzsod.html

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gt2dstaicur.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2osqpvlal.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gt2ixcietyf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gt2dtauyjar.html

C#:   public User(string name) { Name = name; }
来源：http://dali.316326.xyz/Article/details/gt2cvomrvqv.html

[G03] 实例属性
来源：http://dali.hongshengwenyu.top/Article/details/gt2ynebfnxe.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gt2ceivezok.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2qefrieii.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2znrwnrji.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2oqgwjfij.html

Java: private String name;
来源：http://dali.chenlongwang.top/Article/details/gt2zwvhufor.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.haohaochexian.top/Article/details/gt2cylbntjx.html

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gt2qntzdnjy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenzaomai.com/Article/details/gt2bqtdyqnn.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gt2chpmeftm.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gt2ezgpcoqt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2fswevuay.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2averjobj.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2hwlxmkcy.html

Java: String greet() { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2mdlhrmww.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2funmhxxe.html

Ruby: def greet; @name; end
来源：http://dali.cheryme.top/Article/details/gt2gfpmcsyx.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2ivceoubx.html

[G05] 继承
来源：http://dali.yongpay.top/Article/details/gt2nhzplpqx.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gt2qzijdmsb.html

PHP:  class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2udchkekx.html

JS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gt2uuujkmln.html

TS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2yexuevyf.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2krspqzof.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.0kj1m.cn/Article/details/gt2jsvnvles.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gt2oxcbanwo.html

C#:   class Admin : User {}
来源：http://dali.c1oappe.top/Article/details/gt2vhpfyyvn.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gt2bkdxndkv.html

Py:   def greet(self): return "admin"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezaanlrp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2wjlwckdd.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2njatyevh.html


<!-- 参考信息 -->