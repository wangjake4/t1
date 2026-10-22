代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2egwggdqd.html

[E07] 按分隔符拆分
来源：http://dali.iojbl.cn/Article/details/gt2wcenrxad.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ppjwa.cn/Article/details/gt2gyyiqkvr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2rtisloie.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jiagoushi.top/Article/details/gt2fsrocpkq.html

TS:   s.split(",")
来源：http://dali.bjfxy.top/Article/details/gt2pzvtymzj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gejtlszu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cucudq.cn/Article/details/gt2djbxhocu.html

Ruby: s.split(",");  s.split
来源：http://dali.ivvv.top/Article/details/gt2vsxwuika.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qkcqcvin.html

[E08] 数组按分隔符合并
来源：http://dali.daria6918.cn/Article/details/gt2hluevkcy.html

Py:   ",".join(items)
来源：http://dali.iojbl.cn/Article/details/gt2rwqjzvuz.html

PHP:  implode(",", $items);
来源：http://dali.yj20258.top/Article/details/gt2uqklvtth.html

JS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2ddfyqkre.html

TS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gt2xlxvtwjm.html

Java: String.join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gt2tiyxvrwb.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gt2ptcwdubu.html

Ruby: items.join(",")
来源：http://dali.pycfn.com/Article/details/gt2guutckjb.html

C#:   string.Join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gt2utxgxuhs.html

[E09] 去除所有空白字符
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwordajl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.svipenyu.cn/Article/details/gt2hvssdzhk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.redwolf501.top/Article/details/gt2szjdvotc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gt2gorvrshm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gt2dbsieutg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gt2ngypjjkt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yangfankeji.com/Article/details/gt2gjbrrier.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnxiangtu.top/Article/details/gt2fclvcymv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gt2ehchbqaf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cashguo.top/Article/details/gt2ggpejcse.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gt2zghusvkd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sxryk.cn/Article/details/gt2irjwlrdd.html

JS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2yohqakci.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2byrzzaqj.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gt2cdrkidgj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gt2qsawppto.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2cxxdumuq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wetxzzsy.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gt2nbqjqouu.html

Py:   s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gt2ukojqglv.html

PHP:  strrev($s);
来源：http://dali.jianghu66.top/Article/details/gt2wwecarjq.html

JS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2dcufjzvq.html

TS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2ydjetkri.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hammf.cn/Article/details/gt2qxtefbpk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gzhubu.top/Article/details/gt2keqmsbzg.html

Ruby: s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2ytrivxsv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gt2lewhacye.html

[E12] 统计某字符出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ojgjxnvj.html

Py:   s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gt2tfbiifwj.html

PHP:  substr_count($s, "a");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tnnesukp.html

JS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gt2udzffpac.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gt2pchcmwrj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ydzc1.top/Article/details/gt2rxcqzfsu.html

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gt2ptmddtsg.html

Ruby: s.count("a")
来源：http://dali.yuxming.cn/Article/details/gt2quawznwn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.andypj.xyz/Article/details/gt2tqttxmti.html

[E13] 逐字符遍历
来源：http://dali.haohaochexian.top/Article/details/gt2beuaxpbw.html

Py:   for ch in s: print(ch)
来源：http://dali.xylfe.cn/Article/details/gt2lzdfalki.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gt2fxpiqqnp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gt2uycaqdue.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjlkkqaz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gt2cnpuglnc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gt2ryaqwxnx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shuidangran.top/Article/details/gt2qtztjniq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2hzhyymdg.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gt2hyuwsrrr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oiezgrgj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gt2egjfrtgu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ankxmwxu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gt2jvzxgyia.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pycfn.com/Article/details/gt2unwipswu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhoulong.xyz/Article/details/gt2zqgwjmnm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gt2uwdlxiir.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wnlrswvo.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gt2kgqkklyk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gogol.net.cn/Article/details/gt2lzidnize.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhavsxiv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gt2ufakisyl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2fmpdsmqf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xziqi.cn/Article/details/gt2jstfrrpc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gt2amramvib.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yvedp.cn/Article/details/gt2ayfquwcs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gt2ndhtunaz.html

[E16] 数字千分位
来源：http://dali.ivvv.top/Article/details/gt2otilreya.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gt2xpqkynuu.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gcrlgtnn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gt2rguujbks.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gt2uowvpuwa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gt2rjfhonzy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.bjfxy.top/Article/details/gt2tdxvrequ.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2iijaqxft.html

C#:   1234567.ToString("N0")
来源：http://dali.shzxlz.cn/Article/details/gt2bebhuqxq.html

[E17] 首字母大写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dtgrosfb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yangfankeji.com/Article/details/gt2fcksgmjg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tian-w.cn/Article/details/gt2yxwrchnr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gt2jyrxsdyl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gt2mippngvl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2mqnftwhx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cqqwz.cn/Article/details/gt2ehzqrpfs.html

Ruby: s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gt2aelidrxw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gt2njxifqvm.html

[E18] 模板占位符替换
来源：http://dali.0kj1m.cn/Article/details/gt2bbzvceez.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.svipenyu.cn/Article/details/gt2hcfqcvrx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ppjwa.cn/Article/details/gt2wazzzjva.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gt2oxqzlbbx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gt2wlzhyjma.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2eaxwvapn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2diadtvhp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ybcxt.top/Article/details/gt2wtrwdjno.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.andypj.xyz/Article/details/gt2eomyzwul.html

[E19] 多行文本按行拆分
来源：http://dali.tian-w.cn/Article/details/gt2qdfosqgi.html

Py:   s.splitlines()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rroiyvyo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gt2inzvbumb.html

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gt2iqgwndns.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gt2qcvetblz.html

Java: s.lines().toList()
来源：http://dali.fengsongda.top/Article/details/gt2nkffsbtu.html

Go:   strings.Split(s, "\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2qwyxxpnl.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gt2irweuczo.html

C#:   s.Split('\n')
来源：http://dali.chenlongwang.top/Article/details/gt2riosqcab.html

[E20] 判断字符串是否为空
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckjfvkbo.html

Py:   if not s:
来源：http://dali.chenjidiqi.icu/Article/details/gt2qiabbdrv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fengsongda.top/Article/details/gt2xvhkadij.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gt2fzhdzahy.html

TS:   if (s === "") {}
来源：http://dali.nanxuanxn.top/Article/details/gt2xwlvuetg.html

Java: if (s.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gt2mlioxdoj.html

Go:   if s == "" {}
来源：http://dali.jianghu66.top/Article/details/gt2jvbunjwi.html

Ruby: if s.empty?
来源：http://dali.ppjwa.cn/Article/details/gt2lugfovpx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hysaishi.cn/Article/details/gt2qnrtcscl.html

[E21] 超长截断加省略号
来源：http://dali.cqqwz.cn/Article/details/gt2wnimkxkr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gt2bcruzgcc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gt2gsvdkrhe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2cbnehtoc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2ygxncgsy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2tptobqno.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gt2iguxtjdd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2adlgtxkc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwgkfzsj.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gt2ovjdevqd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gzhubu.top/Article/details/gt2obacnaug.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gt2gydcubdj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2hffbpbzm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gt2kwozzgyj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gt2jsgengon.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gt2fiscgdzf.html

Ruby: s.bytesize;  s.length
来源：http://dali.meibo888.top/Article/details/gt2gagwofrx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gt2lylnciqz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2vaesnbct.html

F. 文件与目录
来源：http://dali.xziqi.cn/Article/details/gt2lovajlze.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2jauwtbel.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gt2bnzsnqzn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sxryk.cn/Article/details/gt2sgxgrgrd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2gjsgjrrn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gt2ipizizdx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.316326.xyz/Article/details/gt2zeezonpi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2gilcadnz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ivvv.top/Article/details/gt2sjadifzw.html

Ruby: File.read("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2omxfbfzr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2xhvgcbaf.html

[F02] 逐行读取文件
来源：http://dali.jyoumei.cn/Article/details/gt2snetnbfj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cucudq.cn/Article/details/gt2ppjvitql.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgufenzy.top/Article/details/gt2wioplfbh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gt2ebgpznhy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gt2lowymlbg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gt2kctbuprn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aajpsmxw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.meibo888.top/Article/details/gt2fzhqoaen.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gt2hdtjcnke.html

[F03] 写入文件（覆盖）
来源：http://dali.snrcjt.cn/Article/details/gt2lpjdmnqd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yongpay.top/Article/details/gt2fcbyawge.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2hribkvbi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gt2qactboni.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2avihcxci.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2jfsizoyu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gt2anuoskiw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gt2qdgowlet.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gt2olndbpue.html

[F04] 追加写入文件
来源：http://dali.yuanzhike.top/Article/details/gt2oatlbhej.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bevdiwvd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ppjwa.cn/Article/details/gt2ibhcszli.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2fdymodmj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gt2onpxgbgl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bgafmimp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cheryme.top/Article/details/gt2mrulixgw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tanke756.top/Article/details/gt2lafywyjh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhongyouzk.top/Article/details/gt2dnblhgfs.html

[F05] 判断文件或目录是否存在
来源：http://dali.0kj1m.cn/Article/details/gt2nxqygufv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgfzy.top/Article/details/gt2bkwduqvc.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mollejmt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2jopngcfg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2moezxhxg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2endbymjs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xziqi.cn/Article/details/gt2fgtujcja.html

Ruby: File.exist?("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2jzgpotvc.html

C#:   File.Exists("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2pqicraju.html

[F06] 删除文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwqnffmr.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2eajpfuin.html

PHP:  unlink("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2sfqydnuj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2fnczstdk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2skyrlvvf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2qjbrvunw.html

Go:   os.Remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2vayoghfd.html

Ruby: File.delete("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dnejlbqz.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2oiytyotw.html

[F07] 创建目录（含多级）
来源：http://dali.316326.xyz/Article/details/gt2orcxzprq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gt2afvaubri.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jianghu66.top/Article/details/gt2yjictupn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gt2lkhhcukc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gt2ketwkmgb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tianlin.xyz/Article/details/gt2frnnajdp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigfzy.top/Article/details/gt2saxrcrqz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenjidiqi.icu/Article/details/gt2akjuvtea.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gt2ptfytgqz.html

[F08] 遍历目录
来源：http://dali.yongpay.top/Article/details/gt2zrzajqvw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wgbpficm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gt2ittbtbgf.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gt2niflbrbd.html

TS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tajasnjy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gt2wzdsafrw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gt2tpxyayse.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gt2mfpxfnbp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pycfn.com/Article/details/gt2nsixplci.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2naivkqhs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2xqnxgjne.html

PHP:  filesize("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2rdcctllq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gt2fzvoypvu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gt2odkwmicb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gt2puxbvnxj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gt2katbaufl.html

Ruby: File.size("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2aituvufp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.haohaochexian.top/Article/details/gt2jwtxgmex.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.bjfxy.top/Article/details/gt2byuefwps.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2ikzghbvw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2gcdwyppz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2aqyxyavk.html

TS:   path.extname("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2fwvrubwn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gt2lgmgzxoe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2bynrfphf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2zbypdaki.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2todlgdwx.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gt2svrgcojk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2vewrgxsw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aizwys.cn/Article/details/gt2rvzhmnfd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2jdyxniyj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2gqlwpagv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gt2lrnxciau.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sufxvd.cn/Article/details/gt2yosxqngc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2qoqvdgdl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gt2ntdrojnw.html

[F12] CSV 读写
来源：http://dali.yuxming.cn/Article/details/gt2zeuooruy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jwerdpwa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gt2lkgyiufr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.316326.xyz/Article/details/gt2nyucagmq.html

TS:   // 同上
来源：http://dali.chenlongwang.top/Article/details/gt2ougfeprs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gt2sbdffynz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jiejhzhw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gt2luscyykv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gt2dbpatvhc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2hirtjhrc.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gt2otagcbmw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2sbyvtlva.html

[G01] 定义类
来源：http://dali.cqqwz.cn/Article/details/gt2udtnrqzz.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gt2nstishvi.html

PHP:  class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2noufvnlt.html

JS:   class User {}
来源：http://dali.meibo888.top/Article/details/gt2lmcpfgfs.html

TS:   class User { name: string = ""; }
来源：http://dali.smart0.xyz/Article/details/gt2qgoyyezt.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2aucsaqkj.html

Go:   type User struct { Name string }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwmrvzke.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gt2kkziqtqg.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2hokdhdhz.html

[G02] 构造函数
来源：http://dali.tian-w.cn/Article/details/gt2gpntoefg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenzaomai.com/Article/details/gt2uxthoepe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tanke756.top/Article/details/gt2aoymvexb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ebdokgpu.html

TS:   constructor(public name: string) {}
来源：http://dali.andypj.xyz/Article/details/gt2rsfgrkbg.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gt2sepkkexh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.9152youxi.cn/Article/details/gt2siqqlccz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.9152youxi.cn/Article/details/gt2iugtgxhk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zdqjudy.top/Article/details/gt2yiwqbicm.html

[G03] 实例属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqmkxmfn.html

Py:   self.name = "x"
来源：http://dali.tanke756.top/Article/details/gt2rpzqhdyi.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gt2jtwhqwjt.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2tqyryung.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2vgwfqnms.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gt2innoazje.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gt2vkozvuwo.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gt2edrfifur.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2zcyelxsk.html

[G04] 定义方法
来源：http://dali.cashguo.top/Article/details/gt2jaoamoyv.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gt2vcrvpcnm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2lqdwhvwg.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2ezxnlhkq.html

TS:   greet(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gt2fyunuwds.html

Java: String greet() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2inptqent.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2bnvbygtv.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gt2xwhhrzpk.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxnfibsz.html

[G05] 继承
来源：http://dali.ydzc1.top/Article/details/gt2rrymwdwl.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gt2tjieicjs.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2awrestjk.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2wvutkprd.html

TS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gt2ckavliqn.html


<!-- 参考信息 -->