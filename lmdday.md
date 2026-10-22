代发 wailian999

[E02] 重复字符串
来源：http://dali.ybcxt.top/Article/details/gtyuieffqc.html

Py:   "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtzwcbdyjf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangdashe.top/Article/details/gtwqpughqo.html

JS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtigruabub.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtewhxvxso.html

Java: "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gturkkffvq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gaohongyu789.top/Article/details/gtadtlgqhs.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtgjiwrjxs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.bjfxy.top/Article/details/gtbqejvbrq.html

[E03] 截取子串
来源：http://dali.shuidangran.top/Article/details/gtzpcgkjja.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.0kj1m.cn/Article/details/gtqjchfeav.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtmyjlvkvc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aizwys.cn/Article/details/gtqyiuhcnk.html

TS:   s.slice(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtkioysfxq.html

Java: s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtqomakmsj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyssmjkpb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jlsjyb.cn/Article/details/gtyjtnyxek.html

C#:   s.Substring(1, 3)
来源：http://dali.fengsongda.top/Article/details/gtuascjhjt.html

[E04] 查找子串位置
来源：http://dali.sysykeji.top/Article/details/gtwmeeqgyv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtpykeyine.html

PHP:  strpos($s, "x");
来源：http://dali.jlsjyb.cn/Article/details/gtituiaapq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aibaodan.cn/Article/details/gtcrjgnhdq.html

TS:   s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtdkyjtjlp.html

Java: s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtmliagflz.html

Go:   strings.Index(s, "x")
来源：http://dali.meibo888.top/Article/details/gtrztjzxno.html

Ruby: s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gttspxcwto.html

C#:   s.IndexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtvugrmieg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gogol.net.cn/Article/details/gtmtaetaar.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pycfn.com/Article/details/gtzenelfwn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gtmktybvfm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtxmgqgtvz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.andypj.xyz/Article/details/gtuwitgewd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gtsgzktgqw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nwbrower.top/Article/details/gtyywwnrna.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pycfn.com/Article/details/gtascieokr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtqaaapepb.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gtbljeyzoc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gtnarykwfv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gaohongyu789.top/Article/details/gtthhxjyny.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtwvbxixbs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtuylnrkks.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gttsjbbndp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gteeecipiu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtkhvwjgae.html

C#:   s.Replace("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtttqiiuoi.html

[E07] 按分隔符拆分
来源：http://dali.yanxiufei.cn/Article/details/gtnafgdzyi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigfzy.top/Article/details/gtgjkqnwfs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtxwhfhupb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsyghdwvl.html

TS:   s.split(",")
来源：http://dali.birdmap.top/Article/details/gtynqazlzo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxinkj.top/Article/details/gtxhhzocki.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sxryk.cn/Article/details/gtfjizqpfn.html

Ruby: s.split(",");  s.split
来源：http://dali.daxiang520.top/Article/details/gttihjtmvc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmzwmceh.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gtavlhgkqq.html

Py:   ",".join(items)
来源：http://dali.jinqigfzy.top/Article/details/gtkmwipvuu.html

PHP:  implode(",", $items);
来源：http://dali.0kj1m.cn/Article/details/gtmrhxurxj.html

JS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gtgaxtqjmz.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gthaxjhggm.html

Java: String.join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtblzauoqx.html

Go:   strings.Join(items, ",")
来源：http://dali.meibo888.top/Article/details/gtnfguhvdr.html

Ruby: items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtgsoyoynl.html

C#:   string.Join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gtkumfldna.html

[E09] 去除所有空白字符
来源：http://dali.xziqi.cn/Article/details/gtionmhsgm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ppjwa.cn/Article/details/gtonhazpxl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gturtcueko.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtngsxbzwk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtmmbnvrkv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.birdmap.top/Article/details/gtjggyfygy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuanzx.com/Article/details/gtlggibdim.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gtnnvwvsqy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtxswnwfqj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gogol.net.cn/Article/details/gtvsewzgdk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtrckyqlmc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnxiangtu.top/Article/details/gtgxsnmwaw.html

JS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtqdxzdmtq.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtivbtkblx.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtrlbtbhod.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtqezdazih.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtjzicfuvm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnqzz.top/Article/details/gtyrvkirds.html

[E11] 反转字符串
来源：http://dali.ppjwa.cn/Article/details/gtbhlcsrdt.html

Py:   s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gtqtrdxkqg.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigcuovkt.html

JS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtldgvlfpm.html

TS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gttbhwabdo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbbrryus.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gteucoyyto.html

Ruby: s.reverse
来源：http://dali.dashuyun.cn/Article/details/gtbifphgnh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gtztvvsdxo.html

[E12] 统计某字符出现次数
来源：http://dali.zhengqikj.top/Article/details/gtsskmckmf.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtnoqbdsum.html

PHP:  substr_count($s, "a");
来源：http://dali.jianghu66.top/Article/details/gtmqyhbezq.html

JS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gtkywrzqdv.html

TS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gtvohejynw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gthtnejhck.html

Go:   strings.Count(s, "a")
来源：http://dali.feifeiyinyue.top/Article/details/gtzwrxstsc.html

Ruby: s.count("a")
来源：http://dali.fengsongda.top/Article/details/gttiqpeknc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.andypj.xyz/Article/details/gtbtrfcyba.html

[E13] 逐字符遍历
来源：http://dali.sufxvd.cn/Article/details/gtrhyjteal.html

Py:   for ch in s: print(ch)
来源：http://dali.zdqjudy.top/Article/details/gtgoygeatf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258.top/Article/details/gtwtffvnqx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtqntnpnym.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gthzouzmsk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtivzskecq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.quarkkingdee.top/Article/details/gthodhtlpt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tian-w.cn/Article/details/gtlkeitxvb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daxiang520.top/Article/details/gtuuwenkjx.html

[E14] URL 编码与 Base64
来源：http://dali.316326.xyz/Article/details/gtjgabodxk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xylfe.cn/Article/details/gtfejvotww.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gtwhxaqsmd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yanxiufei.cn/Article/details/gtuogwkumw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jiagoushi.top/Article/details/gtxamvpqsm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtfxkbvomf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shangyingyoupin.top/Article/details/gttqfhlmqw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhengqikj.top/Article/details/gtvenjjddi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnqzz.top/Article/details/gtdyrlaxmn.html

[E15] HTML 转义 / 反转义
来源：http://dali.feifeiyinyue.top/Article/details/gtfnntlbdc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gtizkcszet.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gtwoiteeul.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.haohaochexian.top/Article/details/gtqttzzmas.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gthwnotyfv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gogol.net.cn/Article/details/gtlqtvhrjp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtjctjpafw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cqqwz.cn/Article/details/gtzgudhqky.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yvedp.cn/Article/details/gttabacppm.html

[E16] 数字千分位
来源：http://dali.hammf.cn/Article/details/gtkslnmrau.html

Py:   f"{1234567:,}"
来源：http://dali.snrcjt.cn/Article/details/gtxwghijet.html

PHP:  number_format(1234567);
来源：http://dali.fengsongda.top/Article/details/gtwpayxvtv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtscejxvmx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtdxtxbijj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tian-w.cn/Article/details/gtyictnbkk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yonumen.top/Article/details/gtbbzeumwx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.snrcjt.cn/Article/details/gtxphypztk.html

C#:   1234567.ToString("N0")
来源：http://dali.jiagoushi.top/Article/details/gtkgeunlth.html

[E17] 首字母大写
来源：http://dali.guannengcc.top/Article/details/gtcrmwvgnz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gtazdrhptb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangshuangyany.cn/Article/details/gteratnmte.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gtgtlraiib.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtxczmalup.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yonumen.top/Article/details/gtlstbnunw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.andypj.xyz/Article/details/gtitwnwsxk.html

Ruby: s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuavjubo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gtsvfvlyub.html

[E18] 模板占位符替换
来源：http://dali.nanxinkj.top/Article/details/gtxyyyxvdh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sysykeji.top/Article/details/gthojjykyu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangshuangyany.cn/Article/details/gtccvjqqqb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtljrpmgyf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtbaitrtro.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtpzdvmyfk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtpygvuelb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigfzy.top/Article/details/gtnqejdgdb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jianghu66.top/Article/details/gtaghwciad.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvujuweke.html

Py:   s.splitlines()
来源：http://dali.zhengqikj.top/Article/details/gthcbgqlfs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nwbrower.top/Article/details/gtxkbrctgj.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtstpylbqc.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gtvzfxnsrz.html

Java: s.lines().toList()
来源：http://dali.316326.xyz/Article/details/gtfxeuiyfe.html

Go:   strings.Split(s, "\n")
来源：http://dali.hywenlv.cn/Article/details/gtduuzinta.html

Ruby: s.lines
来源：http://dali.ybcxt.top/Article/details/gtkwqopoql.html

C#:   s.Split('\n')
来源：http://dali.jinghuilouyu.cn/Article/details/gtibvmoibm.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfttijhgk.html

Py:   if not s:
来源：http://dali.yj202588.top/Article/details/gtnyxssmvz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnxiangtu.top/Article/details/gtvnuvgalk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yongpay.top/Article/details/gtissqxyah.html

TS:   if (s === "") {}
来源：http://dali.zhengqikj.top/Article/details/gtmxwdordp.html

Java: if (s.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gtbvjubkmb.html

Go:   if s == "" {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxoxfotam.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gtzfgiiqwa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocydtssw.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gtpohbqwxc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gtyyornfdp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtxdyqmyep.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtocwmfsnu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtjphsbtrz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtvewgmfxv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gtaphllkun.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtdeybomjd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtwahbnnzq.html

[E22] 字节长度与字符长度
来源：http://dali.yongpay.top/Article/details/gtsyskgsyf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hywenlv.cn/Article/details/gtgnfijqdw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzigavpy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtjvbcgdha.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtsdzdqwqa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuxming.cn/Article/details/gtylkqeoiy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahdjparv.html

Ruby: s.bytesize;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtjnrszkon.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtxldprnps.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzlfmzlkz.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtihelrwdj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtwxpovhye.html

[F01] 读取整个文件
来源：http://dali.hywenlv.cn/Article/details/gtdmkmvkta.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.meibo888.top/Article/details/gtapyocdim.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtulxcajaz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenlongwang.top/Article/details/gtkjdutimc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtroanwhwk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtxndpxokr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gtjjrrjkaj.html

Ruby: File.read("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtsnyimjsi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtyzkcqohe.html

[F02] 逐行读取文件
来源：http://dali.meibo888.top/Article/details/gtinzvkybz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ppjwa.cn/Article/details/gtmcvztxlm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aibaodan.cn/Article/details/gtazrfxuye.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtqibrxsfc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtzngohefo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtgsocqppt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgufenzy.top/Article/details/gthmafysyz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gtfycxmjct.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xziqi.cn/Article/details/gtokxpulrb.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gtkracanep.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenzaomai.com/Article/details/gtkzyhunio.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gtanzndvgz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtioowmdap.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtckzwipif.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shzxlz.cn/Article/details/gthpusvvdj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shzxlz.cn/Article/details/gtsoryhepk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtrucglizv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtqyivherc.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gtwkqscncs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplgitkra.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfbieaxp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gtzhihpysn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtiwpixzjy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gtqefommqz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtteclhvjx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shuidangran.top/Article/details/gtqoegxqhy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhiwuduotai.top/Article/details/gtipdnnnpn.html

[F05] 判断文件或目录是否存在
来源：http://dali.yangfankeji.com/Article/details/gtsiivsbkc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gtqeqgiuqm.html

PHP:  file_exists("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuhokktv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtnlcpwcov.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtfkkyyjda.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gttizneeuz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gtzcmegqml.html

Ruby: File.exist?("a.txt")
来源：http://dali.meibo888.top/Article/details/gtuxioayhv.html

C#:   File.Exists("a.txt")
来源：http://dali.yj202588.top/Article/details/gtkhkjhkgu.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gtmyxfythm.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtysdihqgb.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtnselhowf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtirhceadd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtqtkirlts.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gthxyamhco.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtwktuanqf.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcsilmwh.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtbbjfpktd.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gtkxxirndh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gtojimgxjv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cheryme.top/Article/details/gtlujsbmym.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtstyfpydp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtxtvhuzcf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jlsjyb.cn/Article/details/gtgyxhyrez.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gtkdrdfvdl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gtghzefwzt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.316326.xyz/Article/details/gtmsxkotzj.html

[F08] 遍历目录
来源：http://dali.zhengqikj.top/Article/details/gtxjgbpadj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gtpsiiqhjf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aibaodan.cn/Article/details/gtupxockkz.html

JS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtlhtonpjg.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtgqspraqh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtbuegysjj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gttdkscrct.html

Ruby: Dir.children("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhaijtto.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gtaghedkwl.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gtcyprbvzu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtppiukqun.html

PHP:  filesize("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gthdkqptax.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gtirpkyskm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtlnytxgnm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtudxpfyzc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aibaodan.cn/Article/details/gtpikxgkyh.html

Ruby: File.size("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklupgfrt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gtxnsoznqo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuanzhike.top/Article/details/gtenfbarmr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtspzaofxc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hfpthk.cn/Article/details/gthzosdtdf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtdmpzgehu.html

TS:   path.extname("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtkmaugume.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yueranfly.top/Article/details/gtghxbbdqd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtefhtwehy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtwgnpscni.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtryutimky.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gttltqukke.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtcyfyuenj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtnqcwymac.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtityyxzac.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtfiivdfek.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gtaxyjyehg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xylfe.cn/Article/details/gtbsepnwxk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gteonledev.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gtjpxqjcwy.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gtvtkkiglk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nwbrower.top/Article/details/gtehduenff.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gtftdxmwbf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yvedp.cn/Article/details/gtvvgyfhop.html

TS:   // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtqifzcrfu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gthxmywplu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gtsrxasqro.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gtyqejelze.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gtludmwisi.html


<!-- 参考信息 -->