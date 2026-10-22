代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgrrkwow.html

TS:   s.split(",")
来源：http://dali.xylfe.cn/Article/details/gt2jqbjjmlg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hongshengwenyu.top/Article/details/gt2njwcvnmy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ckwxhqdj.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gt2eqcfyjft.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jlysjuqz.html

[E08] 数组按分隔符合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ttbfuhvi.html

Py:   ",".join(items)
来源：http://dali.quarkkingdee.top/Article/details/gt2fpfpmqkc.html

PHP:  implode(",", $items);
来源：http://dali.shuidangran.top/Article/details/gt2tdlejooi.html

JS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2pusjyphd.html

TS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2qcbxtnch.html

Java: String.join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjkkgqky.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxinkj.top/Article/details/gt2tglfybje.html

Ruby: items.join(",")
来源：http://dali.guannengcc.top/Article/details/gt2pzevzagt.html

C#:   string.Join(",", items)
来源：http://dali.gzhubu.top/Article/details/gt2sgoewdko.html

[E09] 去除所有空白字符
来源：http://dali.yanxiufei.cn/Article/details/gt2gyisoebp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ydzc1.top/Article/details/gt2fnvuyltu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guannengcc.top/Article/details/gt2zvupztfl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gt2drsltchu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gt2rmgobyys.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gpjjvgfx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gt2bqrmlfnp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xylfe.cn/Article/details/gt2ltfdpekc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gt2iutesvpr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnqzz.top/Article/details/gt2wsrufmxx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jekmzpbc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fengsongda.top/Article/details/gt2karnkjmz.html

JS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2mlhrrkeg.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cqulipcq.html

Java: String.format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gt2hnvwmlrl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2osxsolnt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2qpljpsum.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.bjfxy.top/Article/details/gt2cqmxzphu.html

[E11] 反转字符串
来源：http://dali.yangfankeji.com/Article/details/gt2rijswcbn.html

Py:   s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gt2msvfkdcx.html

PHP:  strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2qmmyaxqb.html

JS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2hghqyeow.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsblzyjg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kvejipqo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.316326.xyz/Article/details/gt2ihjcuucs.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gt2qrlgsbte.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gt2nsseqlqm.html

[E12] 统计某字符出现次数
来源：http://dali.nanxuanxn.top/Article/details/gt2vbfjpuel.html

Py:   s.count("a")
来源：http://dali.316326.xyz/Article/details/gt2jobskhxm.html

PHP:  substr_count($s, "a");
来源：http://dali.gzhubu.top/Article/details/gt2odgdfpoo.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gt2fpftjlxp.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gt2oadyzavy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hzvvpokd.html

Go:   strings.Count(s, "a")
来源：http://dali.redwolf501.top/Article/details/gt2tftkcivp.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjnarwo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258888.top/Article/details/gt2orqrnfbx.html

[E13] 逐字符遍历
来源：http://dali.fzhhl.top/Article/details/gt2ozvapqtz.html

Py:   for ch in s: print(ch)
来源：http://dali.yvedp.cn/Article/details/gt2olwhlyxo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xxbabmpg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2wlswtsem.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2raiiuhif.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2ufsibvyh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258888.top/Article/details/gt2pzxrtwsg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhongyouzk.top/Article/details/gt2eelyfdmy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxinkj.top/Article/details/gt2etmtrfsc.html

[E14] URL 编码与 Base64
来源：http://dali.yueranfly.top/Article/details/gt2glnxnmmy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gt2tgawzkvp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nqzqvwvh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.andypj.xyz/Article/details/gt2dmtkeqbi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tanke756.top/Article/details/gt2hqxpcatr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2whgwgehd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgfzy.top/Article/details/gt2ghqiznpp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yonumen.top/Article/details/gt2axjkveci.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gt2vxvromdh.html

[E15] HTML 转义 / 反转义
来源：http://dali.guowangkeji.top/Article/details/gt2wzqwkeku.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hywenlv.cn/Article/details/gt2lpfihggd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.havefunace.top/Article/details/gt2wkbsjrec.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifhvilbt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avvlpgmo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jyoumei.cn/Article/details/gt2cqfnuoov.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.mhx1999.top/Article/details/gt2whsdrdhu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenlongwang.top/Article/details/gt2wvovuouv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gt2itphcixx.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gt2ryuqbisj.html

Py:   f"{1234567:,}"
来源：http://dali.yueranfly.top/Article/details/gt2seuopxrb.html

PHP:  number_format(1234567);
来源：http://dali.316326.xyz/Article/details/gt2svyhksxh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gt2pkffnfnq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xykcvqot.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gt2bivfnarb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tianlin.xyz/Article/details/gt2ntrlwvjq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2zmnthdrp.html

C#:   1234567.ToString("N0")
来源：http://dali.chenzaomai.com/Article/details/gt2ibpbkzli.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gt2pwftexew.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daxiang520.top/Article/details/gt2lsbpkapx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zdqjudy.top/Article/details/gt2fpfdhnvt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2fnfeugcj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gt2ffynvhzm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.haohaochexian.top/Article/details/gt2jleasown.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikkrzjkd.html

Ruby: s.capitalize
来源：http://dali.ybcxt.top/Article/details/gt2ugobdzcr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gt2klseimzf.html

[E18] 模板占位符替换
来源：http://dali.zhengqikj.top/Article/details/gt2wyffoytt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jqtrxyhk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yongpay.top/Article/details/gt2vlejzjgv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2uamaavpp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2yskosmgr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njcshavq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2nygmxplh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yvedp.cn/Article/details/gt2qkieglbx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.smart0.xyz/Article/details/gt2paddvlak.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gt2ksmrzxll.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gt2firbypvy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2lositkzf.html

JS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gt2wsiyyrth.html

TS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gt2bwtkrdiy.html

Java: s.lines().toList()
来源：http://dali.zhengqikj.top/Article/details/gt2nhipgjvx.html

Go:   strings.Split(s, "\n")
来源：http://dali.hysaishi.cn/Article/details/gt2bcmjrogo.html

Ruby: s.lines
来源：http://dali.zdqjudy.top/Article/details/gt2lmfsbaft.html

C#:   s.Split('\n')
来源：http://dali.pycfn.com/Article/details/gt2fuuogvmv.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gt2aiktflxa.html

Py:   if not s:
来源：http://dali.ivvv.top/Article/details/gt2ksyzyzde.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigfzy.top/Article/details/gt2zubrfxqa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj202588.top/Article/details/gt2gajkftxz.html

TS:   if (s === "") {}
来源：http://dali.nanxuanxn.top/Article/details/gt2fayawvos.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2riwmqhwt.html

Go:   if s == "" {}
来源：http://dali.jianghu66.top/Article/details/gt2rquhlymm.html

Ruby: if s.empty?
来源：http://dali.svipenyu.cn/Article/details/gt2zeiwvwpg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hysaishi.cn/Article/details/gt2vbhlkvvx.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gt2pktuexmz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.snrcjt.cn/Article/details/gt2avtdjprc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2kqebipan.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2ombnsxsg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2fbjiqdad.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2arvotgjb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hysaishi.cn/Article/details/gt2wabwzzdj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gt2uipmsanl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2qvwjlkyf.html

[E22] 字节长度与字符长度
来源：http://dali.yongpay.top/Article/details/gt2shvzpevd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gt2eabommce.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gt2nvykzvux.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gt2usbgqhge.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gt2lufjtnfg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gt2sloshxnr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cucudq.cn/Article/details/gt2cwbtlkxo.html

Ruby: s.bytesize;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2tnkrvjnc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangdashe.top/Article/details/gt2ztyehkcf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2jbcmsbsu.html

F. 文件与目录
来源：http://dali.zhongyouzk.top/Article/details/gt2lneacbgn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2hldkzyfj.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gt2ctvtufva.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuetiantiany.cn/Article/details/gt2xufetfgq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2tbvqfebv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sxryk.cn/Article/details/gt2cbitkfhr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zycfv.cn/Article/details/gt2mitnslvx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2syegqzeu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gt2qlitpfeq.html

Ruby: File.read("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2pugpdvqs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2pfjkzqxv.html

[F02] 逐行读取文件
来源：http://dali.daria6918.cn/Article/details/gt2breysbce.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tian-w.cn/Article/details/gt2grstozlm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj202588.top/Article/details/gt2dulncpey.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gt2iasgdfek.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2fdstbfkw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gt2shnqdvof.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gt2acooqqfs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jlsjyb.cn/Article/details/gt2qcasygtk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.kuanghao11.cn/Article/details/gt2epvkpgzn.html

[F03] 写入文件（覆盖）
来源：http://dali.hnxiangtu.top/Article/details/gt2rqnwezwl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nclhkvkf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gt2iiaegabm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gt2eegzwlob.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2sbfipgpr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gt2fkagdhiu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ehwqpu.com/Article/details/gt2vdewfibz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gt2hmjekjti.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gt2rxvlcrvf.html

[F04] 追加写入文件
来源：http://dali.ehwqpu.com/Article/details/gt2pevmasfl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jiagoushi.top/Article/details/gt2qshklceo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gt2zgokmjlx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2nqmgtvsi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gt2dprxgfbp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jbngilfw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2zpsvngls.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xziqi.cn/Article/details/gt2cvigrote.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gt2jqwhknys.html

[F05] 判断文件或目录是否存在
来源：http://dali.sweek.top/Article/details/gt2leytmdgk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hfpthk.cn/Article/details/gt2kunntpna.html

PHP:  file_exists("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2rdsdnpnd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2uzaukehf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fofnemph.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2nlmpoues.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shuidangran.top/Article/details/gt2umogwudr.html

Ruby: File.exist?("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2enoitrjv.html

C#:   File.Exists("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2dovmzwaa.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jixyymtc.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ecpilvaj.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2gdsfxiow.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2pkflvxtu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2jdanzwjk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2feogsnuq.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bikrkvpk.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2xisiwakr.html

C#:   File.Delete("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2qaaahrwi.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pultjlfr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gt2xotyossh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.mhx1999.top/Article/details/gt2lppbhfji.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gt2obtskeug.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gt2owonpumn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gt2nlqepmhx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.iojbl.cn/Article/details/gt2lwgtjwpn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gt2kujeqmlr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gt2dnhiyycm.html

[F08] 遍历目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2qvlapsae.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gt2lhjetkhu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gzhubu.top/Article/details/gt2oolynzak.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bgfgmssf.html

TS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gt2zrcjtjsu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gt2zrvtjlay.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2grhkkjjg.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2dwjqyigx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2cwmfrdrl.html

[F09] 获取文件大小
来源：http://dali.wangdashe.top/Article/details/gt2gtomenrr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2fiacthnq.html

PHP:  filesize("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2lntuqotv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gt2sztqpwix.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gt2geqrdetn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2uzbucoqb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gt2vyuyxofc.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2jqvhhckv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gt2icqqwwfg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gt2ynotihcu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2gqwmoose.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2haircplb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2fjhkqykw.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zlkzryzx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhengqikj.top/Article/details/gt2wyrslkqt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2fcyhbfxj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2cnixyxbz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2ukfstamb.html

[F11] 复制与移动文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqjvxaih.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2kffuqioe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2awdfifva.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2qoachsio.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2psvedlih.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2vccxiosj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gt2oymhurzu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2gobvfcwy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2oypkhgtq.html

[F12] CSV 读写
来源：http://dali.sysykeji.top/Article/details/gt2kpfkihcm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnxiangtu.top/Article/details/gt2hgmzdkgd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jlsjyb.cn/Article/details/gt2ufxfvkki.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shuidangran.top/Article/details/gt2ckbmmyxj.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gt2uurtqggm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gt2beyqrhpc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sweek.top/Article/details/gt2ppcsotqp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cashguo.top/Article/details/gt2gzmhrlus.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gt2mquzkipn.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2bfhprscl.html

G. 面向对象
来源：http://dali.xuanzx.com/Article/details/gt2xbqbkdvs.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2odbnvmpv.html

[G01] 定义类
来源：http://dali.yj202588.top/Article/details/gt2ztklxruk.html

Py:   class User: pass
来源：http://dali.meibo888.top/Article/details/gt2ogxasjad.html

PHP:  class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2dmivswha.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gt2mubulgan.html

TS:   class User { name: string = ""; }
来源：http://dali.sufxvd.cn/Article/details/gt2sqpllxqz.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2qbgrcubx.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gt2jepksmsy.html

Ruby: class User; end
来源：http://dali.andypj.xyz/Article/details/gt2fuwktgjp.html

C#:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2esoxzbwn.html

[G02] 构造函数
来源：http://dali.shzxlz.cn/Article/details/gt2ciiriphm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shangyingyoupin.top/Article/details/gt2fugvrzsg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yonumen.top/Article/details/gt2fdfcqlbd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gt2kzqbwsmu.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gt2femlphsg.html

Java: User(String name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2suzpwymy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.havefunace.top/Article/details/gt2jkftbdqe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxinkj.top/Article/details/gt2cnspzpqp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gt2mdddygmq.html

[G03] 实例属性
来源：http://dali.cheryme.top/Article/details/gt2rkrbksub.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gt2qtkbdeqv.html

PHP:  public string $name = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2qrfmsrbs.html

JS:   this.name = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2uyxglvlp.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2pthffmza.html

Java: private String name;
来源：http://dali.jqgfzy.top/Article/details/gt2tdgusduy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gt2wwblejwp.html

Ruby: @name = "x"
来源：http://dali.ehwqpu.com/Article/details/gt2fkieycfu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gt2qdayecvr.html

[G04] 定义方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ellcblpy.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gt2soqhjmep.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gt2mxgmqums.html

JS:   greet() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2fuoxklec.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2djokommp.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hexnseeg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gt2yuywjddw.html

Ruby: def greet; @name; end
来源：http://dali.hywenlv.cn/Article/details/gt2hfnamswf.html

C#:   public string Greet() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qphhklbx.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gt2jmntheua.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gt2skdhvqto.html

PHP:  class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2thqsyybw.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2eqsfwhna.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2fwxbsoqa.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2xaawwaxq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gt2vgucldbl.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqxdtnpz.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gt2lvpxggrp.html


<!-- 参考信息 -->