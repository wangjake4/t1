代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtkrobbrek.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gtnzsqbpeo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ivvv.top/Article/details/gtgrjtvqqn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtfyajofsf.html

[E06] 替换子串
来源：http://dali.snrcjt.cn/Article/details/gtnykazhqt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtrwxsxqbf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.0kj1m.cn/Article/details/gtdqsprcte.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtqbsvjjkc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtobilpazy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtsitoxksc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwzekems.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtnxbfqbrq.html

C#:   s.Replace("a", "b")
来源：http://dali.birdmap.top/Article/details/gtjpfootae.html

[E07] 按分隔符拆分
来源：http://dali.nanxinkj.top/Article/details/gttrwazfch.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnyqsxyq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtlklhpvwo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yanxiufei.cn/Article/details/gtniznlptm.html

TS:   s.split(",")
来源：http://dali.chenlongwang.top/Article/details/gtfphmgzak.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.svipenyu.cn/Article/details/gtrezopnyp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.smart0.xyz/Article/details/gtsrnhkjfk.html

Ruby: s.split(",");  s.split
来源：http://dali.cdnleiting.top/Article/details/gtyhudgmow.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gzhubu.top/Article/details/gtihvksngz.html

[E08] 数组按分隔符合并
来源：http://dali.xuetiantiany.cn/Article/details/gtraqxwsma.html

Py:   ",".join(items)
来源：http://dali.mhx1999.top/Article/details/gtsqgffemj.html

PHP:  implode(",", $items);
来源：http://dali.birdmap.top/Article/details/gtdeajzzyy.html

JS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtcsksnybr.html

TS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gtpvrfbwwi.html

Java: String.join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gttbhpxfmr.html

Go:   strings.Join(items, ",")
来源：http://dali.pycfn.com/Article/details/gtcdhuiukk.html

Ruby: items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtenfsiryd.html

C#:   string.Join(",", items)
来源：http://dali.havefunace.top/Article/details/gtydtuolwo.html

[E09] 去除所有空白字符
来源：http://dali.yanxiufei.cn/Article/details/gtdqoygxpl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tian-w.cn/Article/details/gtznxknwpl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuanzx.com/Article/details/gtxcrbirza.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gtctviukhr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtgxfdvmur.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tian-w.cn/Article/details/gtrgywkwll.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aizwys.cn/Article/details/gtabwppjdn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgfzy.top/Article/details/gtrcxnwynx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cheryme.top/Article/details/gtfsxqfbkx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sysykeji.top/Article/details/gtvmbamgnb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxypkrjbe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutyvkqnr.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtxrfaakuh.html

TS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtleoyuegk.html

Java: String.format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtrpmoyjwx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtmcvfainm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtpalwkkda.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gtnpeyozig.html

[E11] 反转字符串
来源：http://dali.yvedp.cn/Article/details/gtiaobswxw.html

Py:   s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtdwzbptqg.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gtargswnly.html

JS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtkycfczdc.html

TS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtkikeeood.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gtclhkixji.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtsyoqxhjr.html

Ruby: s.reverse
来源：http://dali.jianghu66.top/Article/details/gtwkhmdxgp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gtxqtvwjqp.html

[E12] 统计某字符出现次数
来源：http://dali.tian-w.cn/Article/details/gtyhddkcmy.html

Py:   s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoeyjudto.html

PHP:  substr_count($s, "a");
来源：http://dali.zhoulong.xyz/Article/details/gtlgdbcbuc.html

JS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gtckrjlqfv.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtvkhgbxaa.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tianlin.xyz/Article/details/gtfahqdkff.html

Go:   strings.Count(s, "a")
来源：http://dali.hywenlv.cn/Article/details/gtzuypdrcn.html

Ruby: s.count("a")
来源：http://dali.tian-w.cn/Article/details/gtessqrgpm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.quarkkingdee.top/Article/details/gttwyuvkxs.html

[E13] 逐字符遍历
来源：http://dali.9152youxi.cn/Article/details/gtzabfbfjh.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gthynnqytm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttrgklovx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gtlkhvemma.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtxujuqfmx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtxnfzyamr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yangfankeji.com/Article/details/gtzstemqfp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gtabaizjlh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xziqi.cn/Article/details/gtwwvvlrjl.html

[E14] URL 编码与 Base64
来源：http://dali.pengpengdd.cyou/Article/details/gtmwdkkckf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gtvvjvlsdw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtlosfpycs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhiwuduotai.top/Article/details/gtdvtvrxgo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daria6918.cn/Article/details/gtircxoier.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ybcxt.top/Article/details/gtvyjyxjvc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gotoacloud.top/Article/details/gtkvysvdzd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnveweyjb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gtkathtmnr.html

[E15] HTML 转义 / 反转义
来源：http://dali.ehwqpu.com/Article/details/gtxarmhqmk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbzttpno.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daria6918.cn/Article/details/gtxitqjwka.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gtkwgnjrgg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cqqwz.cn/Article/details/gtofqemnvj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.meibo888.top/Article/details/gtzbikvjcf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtrdgzkccl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ppjwa.cn/Article/details/gtqieztoak.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sweek.top/Article/details/gtbfkowieb.html

[E16] 数字千分位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnhvouus.html

Py:   f"{1234567:,}"
来源：http://dali.tian-w.cn/Article/details/gtuctditbs.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gtscffpijp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtfkcthxwm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtmlbzdlrw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sweek.top/Article/details/gtwlgutweb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.haohaochexian.top/Article/details/gtandvdupo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yongpay.top/Article/details/gtfnrhmoli.html

C#:   1234567.ToString("N0")
来源：http://dali.chenjidiqi.icu/Article/details/gtsdfnormk.html

[E17] 首字母大写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjzoihnj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gtignrcrpb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ydzc1.top/Article/details/gtxymbfpky.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gtsktufgvr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtprxiwiwj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwxlfwdn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258.top/Article/details/gtrrthfcme.html

Ruby: s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gtiyecurbv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqgzhkdj.html

[E18] 模板占位符替换
来源：http://dali.meibo888.top/Article/details/gtxhhdtqab.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gtothscszr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gtkrmwriqu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gteyqfjoyg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtwacvukme.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtftxfnrgv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258888.top/Article/details/gthmajblrp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtbdkcrflz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gthejqnbbn.html

[E19] 多行文本按行拆分
来源：http://dali.yonumen.top/Article/details/gtzdyzsqbo.html

Py:   s.splitlines()
来源：http://dali.hywenlv.cn/Article/details/gtuymdkozb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gzhubu.top/Article/details/gtjnqhjstn.html

JS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtnsatpmbb.html

TS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gtuigslqyn.html

Java: s.lines().toList()
来源：http://dali.xuanzx.com/Article/details/gttrjqnvth.html

Go:   strings.Split(s, "\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtphpifkav.html

Ruby: s.lines
来源：http://dali.chenlongwang.top/Article/details/gtefxoxgkh.html

C#:   s.Split('\n')
来源：http://dali.jqgufenzy.top/Article/details/gtqkqygfhp.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gtamkagnhy.html

Py:   if not s:
来源：http://dali.jqgfzy.top/Article/details/gtgyazzaxi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hysaishi.cn/Article/details/gtlmtqmast.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgfzy.top/Article/details/gtszanbaej.html

TS:   if (s === "") {}
来源：http://dali.xinyue.icu/Article/details/gtyoodlqdf.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtlujhwlro.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gtyegfowus.html

Ruby: if s.empty?
来源：http://dali.daria6918.cn/Article/details/gtqmvibmgn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gtaxmcqjrm.html

[E21] 超长截断加省略号
来源：http://dali.hywenlv.cn/Article/details/gteaagiykn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnxiangtu.top/Article/details/gtsqbcrpgp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtvwgcbxsn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtlvgbfief.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtahepupby.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtwhbbfpnw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hammf.cn/Article/details/gtvbhtgtiu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtsszgrgez.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gtravivfkw.html

[E22] 字节长度与字符长度
来源：http://dali.zhixingplan.top/Article/details/gtnnueigra.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhoulong.xyz/Article/details/gtezlkrdkl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtryezezyh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtgslbcjsh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gtcjllvkxa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj202588.top/Article/details/gtfjyfagdv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ybcxt.top/Article/details/gtklkkqlaj.html

Ruby: s.bytesize;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtrkletoao.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuxming.cn/Article/details/gtlspoyass.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtdjmiuyva.html

F. 文件与目录
来源：http://dali.hysaishi.cn/Article/details/gtlutwkten.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtbkiaaejp.html

[F01] 读取整个文件
来源：http://dali.gogol.net.cn/Article/details/gtzuqplkvx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zycfv.cn/Article/details/gtkxsxrvhl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yueranfly.top/Article/details/gttfntrvdg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ydzc1.top/Article/details/gtfyldywin.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtohghfgbd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtdkmbbvld.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gtsrnflhsn.html

Ruby: File.read("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtvbkpinwr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtnpkaazld.html

[F02] 逐行读取文件
来源：http://dali.jinqigfzy.top/Article/details/gtgsezlrmj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xylfe.cn/Article/details/gthvlhqmbl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aibaodan.cn/Article/details/gtcyuvivza.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtbemzfema.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gtrefdaqau.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtbdstdzht.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tianlin.xyz/Article/details/gtfrtstrtp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hywenlv.cn/Article/details/gthgqxbsmm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jiagoushi.top/Article/details/gtcypcmoau.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxypicrp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.quarkkingdee.top/Article/details/gtdrdqdjae.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtiqtpuyoi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtysoralow.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtrbhyacum.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xinyue.icu/Article/details/gtcecwkztf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yvedp.cn/Article/details/gtdzhptykp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtkegpmejx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtvvqbuogi.html

[F04] 追加写入文件
来源：http://dali.ehwqpu.com/Article/details/gttdjkbmwu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmgjckbi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gtqcfezpbm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtvmmsdgmh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtmfdghykj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jlsjyb.cn/Article/details/gtrjcucdpp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xziqi.cn/Article/details/gtgntuzmoq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.redwolf501.top/Article/details/gtsmowftjk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jiagoushi.top/Article/details/gtckywwtak.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtcmggwmew.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.havefunace.top/Article/details/gtswwkbxwi.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtjgsvwbwm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtvsiaglhx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewjwwort.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtfvfaypqo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcjdrlbh.html

Ruby: File.exist?("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gttexrtdaf.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258.top/Article/details/gtohucapiy.html

[F06] 删除文件
来源：http://dali.dashuyun.cn/Article/details/gttmbbqeef.html

Py:   os.remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gtbtnitoog.html

PHP:  unlink("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtvieblccr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtixwhuscd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtohwkzrox.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtxtoakdaz.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqgpiaeh.html

Ruby: File.delete("a.txt")
来源：http://dali.hammf.cn/Article/details/gtcxpcmyiw.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtntdgyejj.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gtnnianagr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gthzvbjxqp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gthnqmktbv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtbofwihrj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymkxqvpj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dashuyun.cn/Article/details/gtzpidlqge.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gtyarjhomc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenlongwang.top/Article/details/gtgjnmlpqi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfhtvtkg.html

[F08] 遍历目录
来源：http://dali.redwolf501.top/Article/details/gtsfyrqmdv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gthmhmupbn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shzxlz.cn/Article/details/gtraytmafc.html

JS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtaetageio.html

TS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtirelnyzx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtmbufbibr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gtbukexitt.html

Ruby: Dir.children("dir")
来源：http://dali.yongpay.top/Article/details/gtdmwljsrz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258.top/Article/details/gtzyifegzv.html

[F09] 获取文件大小
来源：http://dali.smart0.xyz/Article/details/gtbjlhythi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtjkmcvsay.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtxxnhimos.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtpamaolkr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtegaalouk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtqscyzzaf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cucudq.cn/Article/details/gtlrszrvez.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtjfzzpktr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtbntpywzj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gtxsfxkujr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtsybpwito.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtcvgoeslq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtlttjuyqk.html

TS:   path.extname("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtdtqtflbt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gtkghauadw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtzcngtpxq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtfidtfmpg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtdnggcbct.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatgbxxwd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtftshdocl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gthixtttkh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtnbgrbkyh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtsudqlnjk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwuodjun.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.andypj.xyz/Article/details/gtsfwivmce.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gthkhfqpzn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aizwys.cn/Article/details/gtwrvukuie.html

[F12] CSV 读写
来源：http://dali.pengpengdd.cyou/Article/details/gtsymvvgix.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jianghu66.top/Article/details/gtjyebvihh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hongshengwenyu.top/Article/details/gtybzrfczb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xylfe.cn/Article/details/gtcnocfsrx.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgowzrzpk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xylfe.cn/Article/details/gtcxdznlhh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daxiang520.top/Article/details/gtnqpmybsc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhoulong.xyz/Article/details/gtobgbyeew.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gtfhfqziok.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtoejztwgw.html

G. 面向对象
来源：http://dali.shuidangran.top/Article/details/gtwanjipuq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtruqudshf.html

[G01] 定义类
来源：http://dali.shzxlz.cn/Article/details/gtarxoualk.html

Py:   class User: pass
来源：http://dali.hfpthk.cn/Article/details/gtqxflvmxr.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gtdshegypv.html

JS:   class User {}
来源：http://dali.pycfn.com/Article/details/gtqciystrl.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gturqrpjcr.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gtkyhcmwtv.html

Go:   type User struct { Name string }
来源：http://dali.zhongyouzk.top/Article/details/gtcnvjufaa.html

Ruby: class User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodidnbpc.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlbbplew.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gtygqdobyr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gtdqrqfccg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gtvzutxszz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtofhaiufr.html

TS:   constructor(public name: string) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtzvcptjhp.html

Java: User(String name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwgdppyc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.vqdsnc.cn/Article/details/gtbsikfexx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.c1oappe.top/Article/details/gtlugafpcr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtqwulpvld.html

[G03] 实例属性
来源：http://dali.xuetiantiany.cn/Article/details/gtwddcivmb.html

Py:   self.name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtylghnten.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gtwwpvyisq.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gtttztgyen.html

TS:   name: string = "x";
来源：http://dali.xylfe.cn/Article/details/gtkhpzzfmw.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gtuktwsjsc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gtxjzbtrss.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtethiuprj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hammf.cn/Article/details/gtfeeydchp.html

[G04] 定义方法
来源：http://dali.zycfv.cn/Article/details/gtvjfdpztz.html

Py:   def greet(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gtyirjsshe.html


<!-- 参考信息 -->