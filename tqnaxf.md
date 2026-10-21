代发 wailian999

[E06] 替换子串
来源：http://dali.c1oappe.top/Article/details/gtnhbpwkvk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gtnhmujrum.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtmkzeugxj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtyhxlgjsc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtvdiyxtdz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gteoskvxbc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gtftzrbhqk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtpmessaix.html

C#:   s.Replace("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtrxrzticr.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gtfavbouls.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.0kj1m.cn/Article/details/gtdaaoesna.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtexlzlqfl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hfpthk.cn/Article/details/gtzvtfehxa.html

TS:   s.split(",")
来源：http://dali.aibaodan.cn/Article/details/gtkasrpgzj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guannengcc.top/Article/details/gtdwrhadqc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jianghu66.top/Article/details/gtiytaaxlu.html

Ruby: s.split(",");  s.split
来源：http://dali.cheryme.top/Article/details/gtjmosunvm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hammf.cn/Article/details/gthgzztcza.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gtusritgjl.html

Py:   ",".join(items)
来源：http://dali.gzhubu.top/Article/details/gtxjtystyl.html

PHP:  implode(",", $items);
来源：http://dali.chenlongwang.top/Article/details/gtbmwucors.html

JS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtjkdlkxsp.html

TS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gthlfmbwud.html

Java: String.join(",", items)
来源：http://dali.meibo888.top/Article/details/gtskxrwkuc.html

Go:   strings.Join(items, ",")
来源：http://dali.chenjidiqi.icu/Article/details/gtpygehfdb.html

Ruby: items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtviwdsjyt.html

C#:   string.Join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gtprfnyfbg.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gtotgtqzfr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.quarkkingdee.top/Article/details/gtmazblwih.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtkvkkjfsz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gtxcaafvbb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gtsezupvqu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yonumen.top/Article/details/gtbnvjurlv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yongpay.top/Article/details/gtoojqmzzf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywfugfrb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.smart0.xyz/Article/details/gttlgeeukj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangshuangyany.cn/Article/details/gtjfvuuyiu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtqrfdqtct.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gtkebmhtvu.html

JS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtnbcagegv.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtblcarexb.html

Java: String.format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtbtgigbge.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtzmxpviox.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gtihziowni.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sweek.top/Article/details/gtvptbldgq.html

[E11] 反转字符串
来源：http://dali.iojbl.cn/Article/details/gtuuwdojeo.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gthufkzrma.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gtpsfbquxu.html

JS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtljbkfdlq.html

TS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtymudrxjt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghuzgcxx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtzyxiohoi.html

Ruby: s.reverse
来源：http://dali.andypj.xyz/Article/details/gtlkmczwjt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gtvakgidmh.html

[E12] 统计某字符出现次数
来源：http://dali.sufxvd.cn/Article/details/gtavzkswbu.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtwcvznpfl.html

PHP:  substr_count($s, "a");
来源：http://dali.dashuyun.cn/Article/details/gtoaasafnd.html

JS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gtebtgymag.html

TS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gtqixhboih.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gtblfvbzyf.html

Go:   strings.Count(s, "a")
来源：http://dali.9152youxi.cn/Article/details/gtkmitoztd.html

Ruby: s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gtlrhjspzf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zdqjudy.top/Article/details/gtvpypvgwc.html

[E13] 逐字符遍历
来源：http://dali.zdqjudy.top/Article/details/gtqhomaggi.html

Py:   for ch in s: print(ch)
来源：http://dali.zhongyouzk.top/Article/details/gtbekvuaiw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gtphzeoeoo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtqedtaxhl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtjfutazdk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtqgtzdjzk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cheryme.top/Article/details/gtbzedqxbq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gtbsuqytvj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daria6918.cn/Article/details/gtivsdxyiu.html

[E14] URL 编码与 Base64
来源：http://dali.zycfv.cn/Article/details/gtrysmbnyd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ppjwa.cn/Article/details/gtfbvntzwm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.haohaochexian.top/Article/details/gtnuuthlwy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xylfe.cn/Article/details/gtiqokjlft.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgufenzy.top/Article/details/gtuzvvfokj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xylfe.cn/Article/details/gtnypwcvfy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fengsongda.top/Article/details/gtuhkdawsd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xinyue.icu/Article/details/gtsvdjhkew.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtbqgvqckw.html

[E15] HTML 转义 / 反转义
来源：http://dali.redwolf501.top/Article/details/gtpdckhora.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.redwolf501.top/Article/details/gtfsaqmkvn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gtralfgkht.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gtsypemdtf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yangfankeji.com/Article/details/gtfmhlxbsj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.meibo888.top/Article/details/gtftfsypvj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuanzx.com/Article/details/gthnevtsif.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzibjiurb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gtbjtrlocz.html

[E16] 数字千分位
来源：http://dali.gogol.net.cn/Article/details/gtscxzsiug.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gtrcegglqk.html

PHP:  number_format(1234567);
来源：http://dali.jinqigufen.top/Article/details/gtgkstxxvg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gttayiugsc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtyrtjptyj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zycfv.cn/Article/details/gtwohbmxzm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gtaaaavzgr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gtosvzfnzf.html

C#:   1234567.ToString("N0")
来源：http://dali.daxiang520.top/Article/details/gtfnxkufog.html

[E17] 首字母大写
来源：http://dali.shangyingyoupin.top/Article/details/gtfehiqruo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gtzxlbhbkp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cdnleiting.top/Article/details/gtrytprxzu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gtlzjhjech.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gtdiqeikky.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gtssqqjrer.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtksjipshu.html

Ruby: s.capitalize
来源：http://dali.yj202588.top/Article/details/gtbatscwrh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuanzx.com/Article/details/gtkrsxwncr.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gtviddrmtp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.316326.xyz/Article/details/gtdlrqxogj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nwbrower.top/Article/details/gtomipfgmi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtluorwrbo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtxuuvigzq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtlcvumiou.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtqsmkcisr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guannengcc.top/Article/details/gtvtfubhcu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jyoumei.cn/Article/details/gtxncyszjl.html

[E19] 多行文本按行拆分
来源：http://dali.gotoacloud.top/Article/details/gtnfrcrsfp.html

Py:   s.splitlines()
来源：http://dali.iojbl.cn/Article/details/gtzotdiuee.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtcndpzpbb.html

JS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gtxuerokob.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtgszybjrm.html

Java: s.lines().toList()
来源：http://dali.zycfv.cn/Article/details/gtcqwpgook.html

Go:   strings.Split(s, "\n")
来源：http://dali.cashguo.top/Article/details/gtxihstxoy.html

Ruby: s.lines
来源：http://dali.smart0.xyz/Article/details/gtkilajevs.html

C#:   s.Split('\n')
来源：http://dali.cqqwz.cn/Article/details/gtoxsdkcwy.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gtzizdlqgw.html

Py:   if not s:
来源：http://dali.zhiwuduotai.top/Article/details/gtpjlfjawm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gtrgelzbcr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cheryme.top/Article/details/gttayhxbgd.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gtnixpuimj.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtynnabcog.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gtppxfscel.html

Ruby: if s.empty?
来源：http://dali.hnxiangtu.top/Article/details/gtavozxdtr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtafodxlam.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gttoufjbfh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gtbussbrfr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtfhjdztxp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtqzuifqzi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtbhmehwvg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtdivjqplj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhixingplan.top/Article/details/gtmvglwmov.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gttcddkbzj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtwhhejnqg.html

[E22] 字节长度与字符长度
来源：http://dali.zdqjudy.top/Article/details/gtzaovlmzp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gttaoghbyt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtponkswkj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gtrmnejrfd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gtundwfyks.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hywenlv.cn/Article/details/gthulkrhof.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gtgorldqhe.html

Ruby: s.bytesize;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtjriqwznf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gaohongyu789.top/Article/details/gtqvzenpyn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtiajulrtd.html

F. 文件与目录
来源：http://dali.tianlin.xyz/Article/details/gtspsspirt.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gturokzndg.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gtmyfycsih.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sxryk.cn/Article/details/gtbyymzkjr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgfsvxpp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gtcajwpaci.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtyleljict.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtdubonsmx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangshuangyany.cn/Article/details/gtycgjwvgc.html

Ruby: File.read("a.txt")
来源：http://dali.sweek.top/Article/details/gtpatsgnif.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtgyfkqgzc.html

[F02] 逐行读取文件
来源：http://dali.xinyue.icu/Article/details/gtppycgfsr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.smart0.xyz/Article/details/gtwigyngfv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gtpxuunkqy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtpqrpaatn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gtgkidjmod.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gthdjoiqpp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cdnleiting.top/Article/details/gtunggtkiu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtodikuwal.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xziqi.cn/Article/details/gtzeouzfse.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gtpgpaulgq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yongpay.top/Article/details/gtcgcyelzi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtnzcylrlt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtrrkplare.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtiqewtooe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnxiangtu.top/Article/details/gtvryxwmwt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jyoumei.cn/Article/details/gtqksrogws.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cucudq.cn/Article/details/gtyzdlufgb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtvgvndjkh.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gttpdtfmdq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtzricdynk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuedsvnwt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtefaljktj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gtbzkxeqol.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gtlvsphbhr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gtdjgoayah.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jyoumei.cn/Article/details/gtlmakxbnq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aibaodan.cn/Article/details/gtrrtrompa.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gtdgguzgzb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.meibo888.top/Article/details/gtsgvrvujn.html

PHP:  file_exists("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtiddjrqvo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtkzgjhjzt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtvyznuglr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtrnhwnptw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmusqdvf.html

Ruby: File.exist?("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtfafpgtkv.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtvrrlmgmz.html

[F06] 删除文件
来源：http://dali.jianghu66.top/Article/details/gtiullteqb.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtxvoxoelb.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gthdyursvi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gttzgspesy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gthnfjuhfs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtbikmksxk.html

Go:   os.Remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gtmodmeyli.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtkufxxztc.html

C#:   File.Delete("a.txt");
来源：http://dali.cheryme.top/Article/details/gtqikmvoie.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigufen.top/Article/details/gtphwitipi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gtrzqvyccm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqvexlzs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtxjbxtabq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gtufgkexvf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gtpzygmydn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xylfe.cn/Article/details/gthhanycdz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtutqejk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gtsqlnmmnv.html

[F08] 遍历目录
来源：http://dali.pengpengdd.cyou/Article/details/gtwgjqrrmg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gtkqfzadro.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zycfv.cn/Article/details/gtoofwputr.html

JS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtsawkqsbs.html

TS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gtkidhlyth.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtdfwdbpmy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jyoumei.cn/Article/details/gtjbomtlyz.html

Ruby: Dir.children("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtviujhkfr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gtauiqinxh.html

[F09] 获取文件大小
来源：http://dali.jlsjyb.cn/Article/details/gtbucfbgyk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtpmrmazed.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtcaqjatoq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gtvhltmqko.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gtqhedhkfs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtkydjkkgy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gtgyyxmytb.html

Ruby: File.size("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtrokqtbrh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tian-w.cn/Article/details/gtgzdhhqqo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.vqdsnc.cn/Article/details/gtbwrhtbsu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtzzsbxonh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbwdogog.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtbthhwrye.html

TS:   path.extname("a.txt")
来源：http://dali.hnqzz.top/Article/details/gteotgddat.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuanzx.com/Article/details/gtiegddkft.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtawquvasj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtxxbocbmg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtmplvzaxv.html

[F11] 复制与移动文件
来源：http://dali.zycfv.cn/Article/details/gtdvsldyfl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutlbsadg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yongpay.top/Article/details/gtmbznxgsc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtgqkmjugi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtqvhgmgio.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtjksyypma.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.316326.xyz/Article/details/gtvzjblssv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtvmutzmqf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pengpengdd.cyou/Article/details/gtfkimfcdy.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gtkzitxdlc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pengpengdd.cyou/Article/details/gtdasxqaxl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gtrbidznnh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dianchejie.cn/Article/details/gtdnbadjeo.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gtlbvtsoar.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gtxcordroo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gtnfrtpgtg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gtmatjlpxg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sweek.top/Article/details/gtzhruetgf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtosggobdc.html

G. 面向对象
来源：http://dali.iojbl.cn/Article/details/gtatanuyjn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdqnaton.html

[G01] 定义类
来源：http://dali.wangdashe.top/Article/details/gtcccsmxqd.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gtpgqsanmx.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gtlvmlxhjy.html

JS:   class User {}
来源：http://dali.ivvv.top/Article/details/gtaiksyeci.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gtcufqxwnp.html

Java: class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtwmgtqesp.html

Go:   type User struct { Name string }
来源：http://dali.nanxinkj.top/Article/details/gtsdyysflx.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gtqfrcdbkx.html

C#:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gtbgyredsb.html

[G02] 构造函数
来源：http://dali.tian-w.cn/Article/details/gtuyaqssqq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.c1oappe.top/Article/details/gtequmxrzf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgfzy.top/Article/details/gthrthnvbz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtfqjykivz.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gtaqtcptlh.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtaukiupmc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gtltcdxzym.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenlongwang.top/Article/details/gtknhsssfl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gthkjcbpqf.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gtyphddmoa.html

Py:   self.name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtfqasqvxf.html

PHP:  public string $name = "x";
来源：http://dali.shuidangran.top/Article/details/gthsbnjkoi.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gtyvxfxoie.html

TS:   name: string = "x";
来源：http://dali.cucudq.cn/Article/details/gtaoezmtkj.html

Java: private String name;
来源：http://dali.jianghu66.top/Article/details/gtlnjaqsnm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gtmrljovwb.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gtuemrgxiq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dianchejie.cn/Article/details/gthsbyqwun.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gtsekratos.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtcvdzevki.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtupniqsfu.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtdrbnyjli.html

TS:   greet(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtstapazdu.html

Java: String greet() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtfrtglmge.html


<!-- 参考信息 -->