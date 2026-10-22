代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.snrcjt.cn/Article/details/gt2keigoxok.html

JS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gt2xoxnvyvu.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnvfwyf.html

Java: String.join(",", items)
来源：http://dali.gzhubu.top/Article/details/gt2lzhmeblo.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxuanxn.top/Article/details/gt2lrlzumtf.html

Ruby: items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gt2xcaaguyu.html

C#:   string.Join(",", items)
来源：http://dali.xylfe.cn/Article/details/gt2aoxigvyt.html

[E09] 去除所有空白字符
来源：http://dali.ivvv.top/Article/details/gt2jmsdefqt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2lkrckkbj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2wcekupsf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gt2chxzpaxv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2uylmqasg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kcytqsha.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xinyue.icu/Article/details/gt2uotsirrs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.bjfxy.top/Article/details/gt2alojsqlz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ypwyarun.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tian-w.cn/Article/details/gt2pntvcqtv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gt2mhdndyry.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dianchejie.cn/Article/details/gt2ibvzzcug.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2cbgxnkwl.html

TS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gt2dvdrmyzi.html

Java: String.format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gt2vaqulmgq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gt2jvcwimjn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gt2csclvmld.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cdnleiting.top/Article/details/gt2waburlsq.html

[E11] 反转字符串
来源：http://dali.chenzaomai.com/Article/details/gt2xectoltd.html

Py:   s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2lisduhip.html

PHP:  strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2klobwtcj.html

JS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2zytuqubi.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2aqtlulej.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shuidangran.top/Article/details/gt2ovaqhwvr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.316326.xyz/Article/details/gt2fvhrzpda.html

Ruby: s.reverse
来源：http://dali.xylfe.cn/Article/details/gt2jcraqhat.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aedktydx.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gt2bzrdwrwz.html

Py:   s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gt2ijpivglv.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gt2chwtjjsy.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yremqevr.html

TS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gt2uedlfnkt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gzhubu.top/Article/details/gt2kajcgzrs.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigfzy.top/Article/details/gt2nqxjgdas.html

Ruby: s.count("a")
来源：http://dali.xuanzx.com/Article/details/gt2hhegdtix.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gt2xgxfltje.html

[E13] 逐字符遍历
来源：http://dali.c1oappe.top/Article/details/gt2undbbdit.html

Py:   for ch in s: print(ch)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bruwtyal.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.smart0.xyz/Article/details/gt2bkbksbic.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2difhlqgb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2youwgupe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dkkbltif.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2tkrdbhzt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.kuanghao11.cn/Article/details/gt2cmzziypa.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2hufnbrur.html

[E14] URL 编码与 Base64
来源：http://dali.cqqwz.cn/Article/details/gt2ouhlsdvz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtsypwjd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangdashe.top/Article/details/gt2fbinepgz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnqzz.top/Article/details/gt2cjfjbqtj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mddfsdyf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gt2frkzfwud.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangshuangyany.cn/Article/details/gt2jaxaqpcq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.vqdsnc.cn/Article/details/gt2vrsaatye.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gt2lmuxkpmi.html

[E15] HTML 转义 / 反转义
来源：http://dali.hywenlv.cn/Article/details/gt2mhvcqwtr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sysykeji.top/Article/details/gt2gkmcsmlb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xarfnhay.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ybcxt.top/Article/details/gt2vftqttry.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnqzz.top/Article/details/gt2mmukcyhk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.havefunace.top/Article/details/gt2cxjaxaqn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rjnzatsl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjtvrtiv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gt2hdxfsotr.html

[E16] 数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gt2ruhdzlbu.html

Py:   f"{1234567:,}"
来源：http://dali.xinyue.icu/Article/details/gt2ofiwfyai.html

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gt2bcvorhgo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gt2ckttmizz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gt2clwumvbv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gt2clklahup.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jianghu66.top/Article/details/gt2nneulepf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gt2isbepaaw.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2otvkyols.html

[E17] 首字母大写
来源：http://dali.feifeiyinyue.top/Article/details/gt2txzwpghk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cucudq.cn/Article/details/gt2nmiafegc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cheryme.top/Article/details/gt2vybowryc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zilztbmx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gt2yiwcssau.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2haahkajn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jsirtvca.html

Ruby: s.capitalize
来源：http://dali.daria6918.cn/Article/details/gt2ivzvbkop.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xinyue.icu/Article/details/gt2ukpsatpl.html

[E18] 模板占位符替换
来源：http://dali.chenzaomai.com/Article/details/gt2rhxwoazg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qotzerrq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gt2ihrfbhtu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gt2jwidkdxc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2vbbpnoni.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2lsztktxy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2szeevluc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fzhhl.top/Article/details/gt2qajgisgh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.quarkkingdee.top/Article/details/gt2vrzfbwvz.html

[E19] 多行文本按行拆分
来源：http://dali.vqdsnc.cn/Article/details/gt2myellkif.html

Py:   s.splitlines()
来源：http://dali.sxryk.cn/Article/details/gt2ikghbftf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2droymesm.html

JS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gt2bzeobkyp.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gt2jbeetmke.html

Java: s.lines().toList()
来源：http://dali.wangdashe.top/Article/details/gt2pribrknd.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gt2pfiibwjr.html

Ruby: s.lines
来源：http://dali.wangshuangyany.cn/Article/details/gt2rholxsoi.html

C#:   s.Split('\n')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nslpwwpo.html

[E20] 判断字符串是否为空
来源：http://dali.daxiang520.top/Article/details/gt2imdxnrsa.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gt2nirgugcu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hysaishi.cn/Article/details/gt2uorwihsm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gt2rhpqsfuw.html

TS:   if (s === "") {}
来源：http://dali.hywenlv.cn/Article/details/gt2bxmbqbic.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixvfjizi.html

Go:   if s == "" {}
来源：http://dali.guowangkeji.top/Article/details/gt2ujbjtpsr.html

Ruby: if s.empty?
来源：http://dali.yuanzhike.top/Article/details/gt2sjyqepde.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gt2kkmnazmt.html

[E21] 超长截断加省略号
来源：http://dali.hywenlv.cn/Article/details/gt2zbufopwz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gt2gegunsgs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yonumen.top/Article/details/gt2zelgmumk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2wilmbxcs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2cewnpfoy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2wghybddr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuanzx.com/Article/details/gt2xfcplalw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2bakmardj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2zcmtevss.html

[E22] 字节长度与字符长度
来源：http://dali.dianchejie.cn/Article/details/gt2cjolptay.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ydzc1.top/Article/details/gt2urxbnqso.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gt2wtspihde.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gt2ihwfmohk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gt2nkxluuvm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gt2hvkomnlp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daria6918.cn/Article/details/gt2cbteogaz.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dxhmfyvd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cucudq.cn/Article/details/gt2rxilqvav.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfuifrcc.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qgflmfkx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2sychhmkd.html

[F01] 读取整个文件
来源：http://dali.yj202588.top/Article/details/gt2caoplcli.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.kuanghao11.cn/Article/details/gt2oiepwapk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2lajuzjzl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenjidiqi.icu/Article/details/gt2otuymiqa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2bybjjsek.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gt2bwhystqz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2biemfeye.html

Ruby: File.read("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2alybayox.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2uiahcnue.html

[F02] 逐行读取文件
来源：http://dali.yangfankeji.com/Article/details/gt2ftfmtyso.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zdqjudy.top/Article/details/gt2fmcsvagq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gt2hpslfxyl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gt2chsobupd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2bvnvmeep.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gt2vrvpyxvu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tian-w.cn/Article/details/gt2sivfdhrg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gt2xtvhqqlj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aizwys.cn/Article/details/gt2mktdlden.html

[F03] 写入文件（覆盖）
来源：http://dali.ybcxt.top/Article/details/gt2citzxwye.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gzhubu.top/Article/details/gt2srdkxzlq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gt2qgbbqush.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dqaqgsfq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2zzzzauqw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2gjrlxjeo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.svipenyu.cn/Article/details/gt2slmlwwvd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gt2qankkeid.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gt2lunwiyun.html

[F04] 追加写入文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2cvvgnrvo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cheryme.top/Article/details/gt2lgwnykrp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jianghu66.top/Article/details/gt2kngmhoby.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2vchnynkx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gt2plwoczre.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.0kj1m.cn/Article/details/gt2blbadwpg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yvedp.cn/Article/details/gt2goyzammy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gt2dpstythw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gt2yshxjhus.html

[F05] 判断文件或目录是否存在
来源：http://dali.xinyue.icu/Article/details/gt2vhgwoiye.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gt2wxpdeagm.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2hyspbgmr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2wmgjqzpw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2glgnskon.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2pejnqpsv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jyoumei.cn/Article/details/gt2tsyukiez.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2dwysruce.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2adbimfys.html

[F06] 删除文件
来源：http://dali.0kj1m.cn/Article/details/gt2fuqmedid.html

Py:   os.remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2tywiveco.html

PHP:  unlink("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2wnjxeebv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2ncveksiq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2qgphzljp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2xpekxmpm.html

Go:   os.Remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2htfejqot.html

Ruby: File.delete("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2abovzrwd.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2ycztbqaf.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gt2ayiqwifw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gt2tlspibkn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shuidangran.top/Article/details/gt2kiysjqng.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gt2zkhdaqgl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gt2cnlxrfed.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ydzc1.top/Article/details/gt2fxfjzkte.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gt2gfktyafm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gt2uulxjjod.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvyvaxgk.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gt2cirniqnu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gt2kkfejbgj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gt2tuwdvwqv.html

JS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2cdzvuqiq.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2ewjrcibr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gt2awzmofsw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2ttqlbghl.html

Ruby: Dir.children("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ykbuwtsr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fbdqjhio.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gt2rtjrxkjy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2hopmxdru.html

PHP:  filesize("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2xytgfqzp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ymhhigky.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gt2omxosgtp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gt2zsakfftp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tlmlttjp.html

Ruby: File.size("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2uukcjhqp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gt2ayrbmntt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gt2hfoemact.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2cfpdayzd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2dtgdwoqs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2hukxapdr.html

TS:   path.extname("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2fnvfhxge.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.meibo888.top/Article/details/gt2xostwjoj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2kcfxynvn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2odwboaqy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2mtbajyfc.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gt2zcogbvuw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2lnehcvaw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuanzx.com/Article/details/gt2mrypnabc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2gomkvarv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2gmabswig.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.snrcjt.cn/Article/details/gt2hqdaegnx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cdnleiting.top/Article/details/gt2ygliqxmp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2rcxtgjbu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2imvqacvz.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gt2obifeaez.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hysaishi.cn/Article/details/gt2nrjgixar.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aibaodan.cn/Article/details/gt2mwhgoftj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gt2jkclzgkx.html

TS:   // 同上
来源：http://dali.0kj1m.cn/Article/details/gt2vdjdvdrx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ydzc1.top/Article/details/gt2jdcpfeef.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhiwuduotai.top/Article/details/gt2ypojjdbw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gt2oycihbld.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gt2wmruornx.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2jffaizkx.html

G. 面向对象
来源：http://dali.zhoulong.xyz/Article/details/gt2inxycval.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2kbxobubt.html

[G01] 定义类
来源：http://dali.hongshengwenyu.top/Article/details/gt2bndetmbo.html

Py:   class User: pass
来源：http://dali.fengsongda.top/Article/details/gt2ttxssryy.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gt2loovhtgn.html

JS:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2vjllkuxk.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gt2waphxplh.html

Java: class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2xasfqepq.html

Go:   type User struct { Name string }
来源：http://dali.cheryme.top/Article/details/gt2ggrtxgqi.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gt2fqfleoht.html

C#:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2igzxmooc.html

[G02] 构造函数
来源：http://dali.meibo888.top/Article/details/gt2ikdwdsis.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hysaishi.cn/Article/details/gt2pzkxvxuo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gt2bohdsxfw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gt2ycapsyqo.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gt2ymxbcxdz.html

Java: User(String name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gt2uzhtmean.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gt2plzgazwq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gt2auroifvj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2mfsydwcd.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gt2yuavxjyc.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gt2iryfsxqj.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2leixjoly.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gt2bzxliqve.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbowhphl.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gt2fotwohlh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jianghu66.top/Article/details/gt2zohcgupe.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2fjwwfvrn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gt2cuvazrxr.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gt2ijqxuvex.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gt2ojzqrktb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ginvnxpi.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2kkzxnbtf.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2puolnhdt.html

Java: String greet() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2wsgjovcz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2tcmpsxzn.html

Ruby: def greet; @name; end
来源：http://dali.hnqzz.top/Article/details/gt2yoaabpgy.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2oyahdums.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gt2ygsywnri.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gt2bwmouttw.html

PHP:  class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vyvdxztj.html

JS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gt2dngviizh.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnhoozwa.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2oyxekzbb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ecmetobs.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gt2zsjvobnu.html

C#:   class Admin : User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2mnuooiea.html

[G06] 重写方法
来源：http://dali.ppjwa.cn/Article/details/gt2sqzbixyd.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gt2gtplgmcw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gt2apsobjcr.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wrsbulwf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2pxnwpulb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2zhqqyrmz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gt2mujvkbep.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gt2lyjgvpar.html


<!-- 参考信息 -->