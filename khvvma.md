代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sufxvd.cn/Article/details/gttxaunajp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sweek.top/Article/details/gtoleuyreo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtfceqxypk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.bjfxy.top/Article/details/gtjtknlqht.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtwnugapjz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dianchejie.cn/Article/details/gtrmhhrqcu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jlsjyb.cn/Article/details/gtkxhwpdso.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtysdhddeo.html

[E06] 替换子串
来源：http://dali.zhengqikj.top/Article/details/gtdkxenauf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtzmzpjylt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cdnleiting.top/Article/details/gtgmcarwqh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtcfpxalfa.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtfvbrakyd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtqgobvcvv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gtlfjydspt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtydyszmyy.html

C#:   s.Replace("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcijfbyrt.html

[E07] 按分隔符拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtcauhhdcr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenzaomai.com/Article/details/gthufrnzqx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtopfhkfhb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yueranfly.top/Article/details/gttakqpylr.html

TS:   s.split(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtjhfdlj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fzhhl.top/Article/details/gtvyivcqdg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigufen.top/Article/details/gtdxoaxuje.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gtqegmiqmq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dianchejie.cn/Article/details/gthxunavpe.html

[E08] 数组按分隔符合并
来源：http://dali.mhx1999.top/Article/details/gtawbsgmey.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gtxlgzcgmm.html

PHP:  implode(",", $items);
来源：http://dali.nwbrower.top/Article/details/gtjioatkub.html

JS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gthfzazyez.html

TS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtjyjfojyq.html

Java: String.join(",", items)
来源：http://dali.ydzc1.top/Article/details/gtbpfvelza.html

Go:   strings.Join(items, ",")
来源：http://dali.ppjwa.cn/Article/details/gtbipnxtxk.html

Ruby: items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtadmbfkvq.html

C#:   string.Join(",", items)
来源：http://dali.hnqzz.top/Article/details/gtagfhmzbi.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gtataqikel.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gogol.net.cn/Article/details/gtfasumnyl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sxryk.cn/Article/details/gtoyurwkjk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtcvdexnug.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitsrcfte.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtmrrryfnq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jianghu66.top/Article/details/gtozklpicl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gtzwvjviuo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gtjtvuhhlh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangdashe.top/Article/details/gtjdsardsp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtbtxzwkht.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.iojbl.cn/Article/details/gtyhexrhvl.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtrypeqiep.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gthfepizxi.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtgqerrdit.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtpndsxwfm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtjooegmxu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hongshengwenyu.top/Article/details/gtnokbyrvc.html

[E11] 反转字符串
来源：http://dali.nwbrower.top/Article/details/gtpcfhiajb.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gtuqglcukf.html

PHP:  strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gthmxbgpzv.html

JS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtgphzpxnb.html

TS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtzakqyvpz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.birdmap.top/Article/details/gtjmrbkueh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtvccrvusi.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtppkkkucn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gtflhrzfkq.html

[E12] 统计某字符出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gteghhflak.html

Py:   s.count("a")
来源：http://dali.hammf.cn/Article/details/gtgkqsalxx.html

PHP:  substr_count($s, "a");
来源：http://dali.tian-w.cn/Article/details/gtzugfaehe.html

JS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtnwnejefw.html

TS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtotfvmqef.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.haohaochexian.top/Article/details/gtgnuidgla.html

Go:   strings.Count(s, "a")
来源：http://dali.9152youxi.cn/Article/details/gtszlfxupp.html

Ruby: s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtaufwyzic.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zycfv.cn/Article/details/gtsunhukof.html

[E13] 逐字符遍历
来源：http://dali.smart0.xyz/Article/details/gtbaiqmfft.html

Py:   for ch in s: print(ch)
来源：http://dali.gotoacloud.top/Article/details/gtjhsodfbg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guowangkeji.top/Article/details/gtyshlschq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtezusjjbx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrftievvx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtedbuadad.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tanke756.top/Article/details/gtuxbagbab.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gtvemlvstk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ivvv.top/Article/details/gtqdtsydyj.html

[E14] URL 编码与 Base64
来源：http://dali.andypj.xyz/Article/details/gtgylyxaxp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gtfzexknpd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnqzz.top/Article/details/gtrlbvkxss.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yongpay.top/Article/details/gtbbsdtdjh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aibaodan.cn/Article/details/gtrglakpzd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtihyloizc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenjidiqi.icu/Article/details/gtrggbfxgb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sufxvd.cn/Article/details/gtpqzmjsfe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtswmpfpxi.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj202588.top/Article/details/gtzmfljodq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sufxvd.cn/Article/details/gtgagftwkk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgeioyevd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gtkzszklgw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtfzblywmp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aibaodan.cn/Article/details/gtejynafyp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.svipenyu.cn/Article/details/gtnviixvez.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuanzx.com/Article/details/gtgfveisnn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgufenzy.top/Article/details/gtuvtlsnhk.html

[E16] 数字千分位
来源：http://dali.ehwqpu.com/Article/details/gtdgkplsra.html

Py:   f"{1234567:,}"
来源：http://dali.bjfxy.top/Article/details/gtmibfhalb.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gtrquuyhbf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtxmotfdef.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtupdtgvvc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhiwuduotai.top/Article/details/gtnkcshcac.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gtpbklfakd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shzxlz.cn/Article/details/gtwguobtod.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gtvysrvgwc.html

[E17] 首字母大写
来源：http://dali.aibaodan.cn/Article/details/gtmwivsxua.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yvedp.cn/Article/details/gtbkscqmad.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtvpfqhauo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtlyuphhvs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtsktpikbn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gtxwoxdycw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gtnxlcfkjq.html

Ruby: s.capitalize
来源：http://dali.pengpengdd.cyou/Article/details/gtfaraxbaf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tianlin.xyz/Article/details/gtrsyuuebi.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gtxvhnsrps.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvchduir.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gtihuetvtj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtuwbwlwfj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtuvffwfer.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtjhbamvsl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtswgokxlv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnzlarya.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guowangkeji.top/Article/details/gtkwircifr.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gtktgldjjc.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhaetlsr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtcvhffzsj.html

JS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gtqmghvhpa.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtindjtwoq.html

Java: s.lines().toList()
来源：http://dali.guowangkeji.top/Article/details/gtjunddkpd.html

Go:   strings.Split(s, "\n")
来源：http://dali.0kj1m.cn/Article/details/gthgfpqczc.html

Ruby: s.lines
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxstnvzno.html

C#:   s.Split('\n')
来源：http://dali.zhoulong.xyz/Article/details/gtgsnhudtz.html

[E20] 判断字符串是否为空
来源：http://dali.guowangkeji.top/Article/details/gtdncdvvfs.html

Py:   if not s:
来源：http://dali.yj20258.top/Article/details/gteaqvafmd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nwbrower.top/Article/details/gtxwhkgcez.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gtwbudatfy.html

TS:   if (s === "") {}
来源：http://dali.mhx1999.top/Article/details/gtwillcerr.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtfyrtmlnq.html

Go:   if s == "" {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfnusxtp.html

Ruby: if s.empty?
来源：http://dali.xylfe.cn/Article/details/gtdpeuutrm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gtrrhvfaml.html

[E21] 超长截断加省略号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqkgyiio.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.haohaochexian.top/Article/details/gtmfuflevf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtgvaktirr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtskesjpdk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtbnnqeqid.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtchhhunor.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gtqyuebwxf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtwriyjycn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtnmcdjnfv.html

[E22] 字节长度与字符长度
来源：http://dali.chenjidiqi.icu/Article/details/gtxofzwzde.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gtpqarners.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gthouznkvi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtltflmevs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtihkbzsuj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtfloqsomw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hysaishi.cn/Article/details/gtjqqiwmbp.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtdixqcwif.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtynwkzrqk.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtjuqqkras.html

F. 文件与目录
来源：http://dali.sufxvd.cn/Article/details/gtmnqcizef.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtxyxprqft.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gttrgzefkt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.iojbl.cn/Article/details/gtbegelxkw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtfykglxoc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shzxlz.cn/Article/details/gtnpnbprwo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtxznhpznw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtqmismyog.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hammf.cn/Article/details/gtcvdygkcp.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtjnjhouto.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtzydvfkyk.html

[F02] 逐行读取文件
来源：http://dali.haohaochexian.top/Article/details/gtmzlwjltk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gtabprfbon.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhoulong.xyz/Article/details/gtzbxcmqby.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtfchyshbj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gtxtfjpzkk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtvrtmusns.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ppjwa.cn/Article/details/gtizvximzp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgufenzy.top/Article/details/gtinempahz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aibaodan.cn/Article/details/gtguvwdmms.html

[F03] 写入文件（覆盖）
来源：http://dali.ydzc1.top/Article/details/gtmumhqwjz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zdqjudy.top/Article/details/gtukihppmt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtablprosh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gticsuixbp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gteguhvepf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gtslwpllyz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tian-w.cn/Article/details/gtmsqnjkfb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhoulong.xyz/Article/details/gtrlnkpaib.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtxrobvack.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gtblcaamwe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cqqwz.cn/Article/details/gtmktbgthd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcdrxzgw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gtoqojtxkj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtmglszgtt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tanke756.top/Article/details/gtgiqqjfxe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258888.top/Article/details/gthqhavxlu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sweek.top/Article/details/gtspvgldim.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fzhhl.top/Article/details/gtzepfqmej.html

[F05] 判断文件或目录是否存在
来源：http://dali.dashuyun.cn/Article/details/gtsbzyqwqz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixjbohrd.html

PHP:  file_exists("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtpxamffgd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtcdddjmar.html

TS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtqnqkwnbc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtcftbtjgx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.iojbl.cn/Article/details/gtkmqdxhvc.html

Ruby: File.exist?("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtktcphtuk.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtzwiegatt.html

[F06] 删除文件
来源：http://dali.chenlongwang.top/Article/details/gtqanxqcjk.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtjpxyyguc.html

PHP:  unlink("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtcxgamsgw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtkpvlnhpc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtqnukulex.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtzrvbgyyv.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtbmukdqxu.html

Ruby: File.delete("a.txt")
来源：http://dali.cheryme.top/Article/details/gtltogkelh.html

C#:   File.Delete("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtwsczwoos.html

[F07] 创建目录（含多级）
来源：http://dali.redwolf501.top/Article/details/gtegbmmnpg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gtabvyumal.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhoulong.xyz/Article/details/gtmdtqbara.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtufmbefdi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtjefuktqu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ivvv.top/Article/details/gtmqbsiwjp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tianlin.xyz/Article/details/gteduhanke.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhengqikj.top/Article/details/gtjybiejus.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gtfdrkbbvn.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gtmhrzxwix.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gtgpcxffcx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hysaishi.cn/Article/details/gtrunnzkor.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqrpxjij.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtvofszmiu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtuyeeeaip.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xylfe.cn/Article/details/gtjwnbklut.html

Ruby: Dir.children("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmesgozhz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtsraroldn.html

[F09] 获取文件大小
来源：http://dali.yueranfly.top/Article/details/gtbweggpcb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtkfdhhlix.html

PHP:  filesize("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtmeafvbet.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gtrymxurea.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmycdhvs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtpheauvup.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.andypj.xyz/Article/details/gtkyleamah.html

Ruby: File.size("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtsvjwocdw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtfegempjf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gtpfwqqdml.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtfooudbqr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtzprshgka.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtgmujyrxp.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxxkemjg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.redwolf501.top/Article/details/gtejxpllen.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtnuodnatw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtopxvgkgm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtfxjinkai.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gtcyydjfnp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtixdxgmej.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.9152youxi.cn/Article/details/gtalgljwmr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtoalwfokd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtqshisodu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtdrxclwoy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gttpuvevlt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gticbexwis.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gtmuhphlze.html

[F12] CSV 读写
来源：http://dali.vqdsnc.cn/Article/details/gtehqtbyit.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gttsleljdj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gtrskzsbqu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.bjfxy.top/Article/details/gtxzxxipap.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gtilffzdbq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.vqdsnc.cn/Article/details/gtfvyshver.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenzaomai.com/Article/details/gttgwxzoic.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gthcospjvd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenjidiqi.icu/Article/details/gtdrntppbp.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtaihvncop.html

G. 面向对象
来源：http://dali.zhoulong.xyz/Article/details/gtrbaxlsem.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqpkrhodd.html

[G01] 定义类
来源：http://dali.yanxiufei.cn/Article/details/gtqvfgiush.html

Py:   class User: pass
来源：http://dali.yonumen.top/Article/details/gthdguyzow.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gtypomyamg.html

JS:   class User {}
来源：http://dali.c1oappe.top/Article/details/gtaphiqwhc.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gtsuooajiz.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gtslehzzoc.html

Go:   type User struct { Name string }
来源：http://dali.jqgfzy.top/Article/details/gtxhutiyzo.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gtgszguoue.html

C#:   class User {}
来源：http://dali.nwbrower.top/Article/details/gthlpsfxcu.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gttmtcwxcd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gtucwzqlia.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gtflwibjzs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbtzisgf.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gtpkduxeji.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtlhuvnpet.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sufxvd.cn/Article/details/gtaehazshw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gtwtmcuzij.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtradzgfez.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gtpcuybhac.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtqlgkcxcl.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gttmaewxec.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaciutgpy.html

TS:   name: string = "x";
来源：http://dali.birdmap.top/Article/details/gtlicrmufy.html

Java: private String name;
来源：http://dali.gzhubu.top/Article/details/gtylmprzdv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gtqzgnddbb.html


<!-- 参考信息 -->