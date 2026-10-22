代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cucudq.cn/Article/details/gtovbthajw.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtqslwbgiq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.havefunace.top/Article/details/gtntjbvjgn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtzfhvripp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtqoyvdnan.html

TS:   s.slice(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtfaqeegim.html

Java: s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtqyaugrjc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258.top/Article/details/gthtywrmvu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zdqjudy.top/Article/details/gtcticmjml.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258888.top/Article/details/gtzmdalkuu.html

[E04] 查找子串位置
来源：http://dali.xinyue.icu/Article/details/gtsiarkgba.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtdjpfkgkc.html

PHP:  strpos($s, "x");
来源：http://dali.andypj.xyz/Article/details/gtcfzibpml.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cashguo.top/Article/details/gtsjvsknrn.html

TS:   s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtgdrdtunz.html

Java: s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtpmvcwsbq.html

Go:   strings.Index(s, "x")
来源：http://dali.tianlin.xyz/Article/details/gtnetjzbza.html

Ruby: s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gtrzexpxfa.html

C#:   s.IndexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsnxoiwd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.andypj.xyz/Article/details/gtujeakhos.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzskypsqx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.andypj.xyz/Article/details/gtyjhkcmyv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtrmhhcpyx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aizwys.cn/Article/details/gtcndqxlpb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtwqzuzzae.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gtbtokujbv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.316326.xyz/Article/details/gtutqpxvjr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtkhhwyfmg.html

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gtiymtpqgj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gtmxkjwpnj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gaohongyu789.top/Article/details/gtscwjeerg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtzatseouq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtinwpquad.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtkeplcian.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gtbudpeoad.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtxhiibqnd.html

C#:   s.Replace("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtqvvtiqsc.html

[E07] 按分隔符拆分
来源：http://dali.zhongyouzk.top/Article/details/gtrhegqkwf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxinkj.top/Article/details/gtfefsfihb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtvrjtdscp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenlongwang.top/Article/details/gtimsoruyr.html

TS:   s.split(",")
来源：http://dali.kuanghao11.cn/Article/details/gtwwtkkrrt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gaohongyu789.top/Article/details/gtlnczojkd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hywenlv.cn/Article/details/gtowmtfssw.html

Ruby: s.split(",");  s.split
来源：http://dali.meibo888.top/Article/details/gtepnkadql.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.birdmap.top/Article/details/gtdgidrcli.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gtjmdmjtcp.html

Py:   ",".join(items)
来源：http://dali.quarkkingdee.top/Article/details/gtgmvhplse.html

PHP:  implode(",", $items);
来源：http://dali.shangyingyoupin.top/Article/details/gtcxsuvwrc.html

JS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtexntizbr.html

TS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtomwaafjg.html

Java: String.join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtwlsnpyzb.html

Go:   strings.Join(items, ",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsejgxki.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gtytichswg.html

C#:   string.Join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtvvomchgc.html

[E09] 去除所有空白字符
来源：http://dali.9152youxi.cn/Article/details/gtpxthxogd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ehwqpu.com/Article/details/gtoiynvbeh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtqdzeixwl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gtbuxfrtzn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gthrurlvya.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.meibo888.top/Article/details/gtltyawueh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigfzy.top/Article/details/gttquqbkpi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dianchejie.cn/Article/details/gtvjojxvqs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sweek.top/Article/details/gtmfhccqsi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dianchejie.cn/Article/details/gttdmjraqb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtkshxjkbb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gtqlitaxtq.html

JS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtstmeqovo.html

TS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtgzpzoihl.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtwagcwtqe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtgidzokks.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtjvkgxekm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zycfv.cn/Article/details/gtepugahrz.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gtuosghdvr.html

Py:   s[::-1]
来源：http://dali.316326.xyz/Article/details/gtoeoaucwy.html

PHP:  strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gtgrzhiirz.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gthzhpdeil.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gteejqavaj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj202588.top/Article/details/gtlfwnsshz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xylfe.cn/Article/details/gtunakgvtc.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gtgoxkpspo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtsdmpwnwl.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gtjbimwwad.html

Py:   s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtpmbqdlje.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnxqxzhy.html

JS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtdyhnfxgc.html

TS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gtakacbgdr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gtijvcpvli.html

Go:   strings.Count(s, "a")
来源：http://dali.jiagoushi.top/Article/details/gtkdwjjagw.html

Ruby: s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gtlbttyeai.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gthfazancb.html

[E13] 逐字符遍历
来源：http://dali.jiagoushi.top/Article/details/gtlkdbomjf.html

Py:   for ch in s: print(ch)
来源：http://dali.ydzc1.top/Article/details/gtywlxblcl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gtqfpxapys.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtmdymyxwd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtjwhcnhiv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gtnxxxuocv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hammf.cn/Article/details/gtmdmgjtnz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhblnksp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrgqbqvk.html

[E14] URL 编码与 Base64
来源：http://dali.havefunace.top/Article/details/gtotjejndc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cheryme.top/Article/details/gtqintguzd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shuidangran.top/Article/details/gtpyhsdrbf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcwasbmx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yangfankeji.com/Article/details/gtdhemzhnb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tian-w.cn/Article/details/gtoxtwrsmi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gtlrzjuzde.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gtfnwgeylm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtfrnijvgn.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnxiangtu.top/Article/details/gthldzrrvx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.smart0.xyz/Article/details/gthxtytqlf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gtxbpxohhc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.haohaochexian.top/Article/details/gtxxjwjfuv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.birdmap.top/Article/details/gthyyrqepv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guowangkeji.top/Article/details/gtelapmcgo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyiqrdlo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shzxlz.cn/Article/details/gturpmlgsp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gtvvrgctbr.html

[E16] 数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtirymeeak.html

Py:   f"{1234567:,}"
来源：http://dali.zhoulong.xyz/Article/details/gtzxvrjybj.html

PHP:  number_format(1234567);
来源：http://dali.aizwys.cn/Article/details/gtcvxjatne.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gtdqqlsibp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtcsqeaqav.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtarpvhboc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnxiangtu.top/Article/details/gtxstlbjhn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.0kj1m.cn/Article/details/gtcwbsgfix.html

C#:   1234567.ToString("N0")
来源：http://dali.tianlin.xyz/Article/details/gtyscfpynq.html

[E17] 首字母大写
来源：http://dali.chenjidiqi.icu/Article/details/gtipfsnyaa.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yanxiufei.cn/Article/details/gtrgdebkrq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gtyqabzwhm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtnnhbirze.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gtuvtaxads.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sweek.top/Article/details/gtqcvppftv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jiagoushi.top/Article/details/gtfblrzhqs.html

Ruby: s.capitalize
来源：http://dali.snrcjt.cn/Article/details/gtxiyhqrjt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigfzy.top/Article/details/gtmhixcvxy.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxtbppow.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dianchejie.cn/Article/details/gtckbdlfvn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gtxjkhsjmq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtxumborri.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtdmkulnxs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtfxmrpabk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtcejwpbpt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwgfgwin.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gtocqansgx.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gtirwwqzem.html

Py:   s.splitlines()
来源：http://dali.feifeiyinyue.top/Article/details/gtyslzzobv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtxnbxqlxo.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtofcwti.html

TS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtfndozlep.html

Java: s.lines().toList()
来源：http://dali.yuanzhike.top/Article/details/gtyscbbxhf.html

Go:   strings.Split(s, "\n")
来源：http://dali.daxiang520.top/Article/details/gtdcjmsxun.html

Ruby: s.lines
来源：http://dali.ivvv.top/Article/details/gtgbncnjlg.html

C#:   s.Split('\n')
来源：http://dali.andypj.xyz/Article/details/gtaqxiqnpw.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gttexuoroq.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gtaxqhkoxp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aizwys.cn/Article/details/gtbpyvpsjz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjigrnvpg.html

TS:   if (s === "") {}
来源：http://dali.shzxlz.cn/Article/details/gtqgiibeui.html

Java: if (s.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gtkraxbxsg.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gtfkjczzcb.html

Ruby: if s.empty?
来源：http://dali.andypj.xyz/Article/details/gtzsdqcndw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shzxlz.cn/Article/details/gthddyjywv.html

[E21] 超长截断加省略号
来源：http://dali.yongpay.top/Article/details/gtyasodctp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ybcxt.top/Article/details/gtzuuufqfb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gteghgcyax.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtbkauhywd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtuyintqsa.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtsnnkhckd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxuanxn.top/Article/details/gtxrsjpgfl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gteogadxua.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtsujibhwr.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gthstasuvo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gttxrgxfrz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtmisruhrf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtslvxuuud.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gtlwubnibw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtonzkhgbk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.andypj.xyz/Article/details/gtlqzumbrd.html

Ruby: s.bytesize;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtciyccbrd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxquezydm.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthorouucr.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gtehxtxzdd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtpcqhbvnb.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gtbcfwjgfd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sweek.top/Article/details/gtzkprwnla.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtimnkdxpv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sysykeji.top/Article/details/gtnhqqqypp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtiukpwfon.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtargfyeel.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gtxlalokyt.html

Ruby: File.read("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtyycjpgla.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtobymbdcy.html

[F02] 逐行读取文件
来源：http://dali.svipenyu.cn/Article/details/gtfnxowduy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ppjwa.cn/Article/details/gtaajxynto.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtvszqcrwn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtinwrgltc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtfzbweegm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtjfucrrvj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigufen.top/Article/details/gtohzokswn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpnfxhqn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gotoacloud.top/Article/details/gtbwigrtsj.html

[F03] 写入文件（覆盖）
来源：http://dali.xuanzx.com/Article/details/gtpoujfwul.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gtafexlefw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtmqaaqqhc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gttnqakjzm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtfiqpvxhb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gtbsmtrlwo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigfzy.top/Article/details/gtvyrelewh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.bjfxy.top/Article/details/gttvezsict.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtqdiuirlu.html

[F04] 追加写入文件
来源：http://dali.guannengcc.top/Article/details/gtmxultusl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtdmlbcdsd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj202588.top/Article/details/gtnjymekog.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gthltohhln.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gthuoycmmt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnqzz.top/Article/details/gtkkqtqyeq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gttapbtrck.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gtiwiqtsoy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guowangkeji.top/Article/details/gtgpjsyfbn.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gthzmhdpxv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gtktvwjkzs.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gtowmrijow.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtbsrcljxg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtvgedjyvh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtlnvymnbh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuxming.cn/Article/details/gtuxdvilel.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtgjeouaam.html

C#:   File.Exists("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtlisshsfs.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gtmxjwbwoo.html

Py:   os.remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtqvbkajrw.html

PHP:  unlink("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtxwjexyge.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtbebbqpoz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gthpzcrlus.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtvempbytb.html

Go:   os.Remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gteezwlzhh.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtzfdpgqvo.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtfxtwrcvl.html

[F07] 创建目录（含多级）
来源：http://dali.yangfankeji.com/Article/details/gtryqnxhkb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtobxyrudv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxinkj.top/Article/details/gtuppeieqm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtqzewixsg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtwrmfwaak.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwssreiy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gtsqwfpiii.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.c1oappe.top/Article/details/gtipokekgx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gtwtupbcsd.html

[F08] 遍历目录
来源：http://dali.havefunace.top/Article/details/gttxdmvwvl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gtnpjyljct.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daria6918.cn/Article/details/gtwxrtsujt.html

JS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gthupwcmxb.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtokbyeosr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtvowbpnqe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zdqjudy.top/Article/details/gtgevckcod.html

Ruby: Dir.children("dir")
来源：http://dali.zhixingplan.top/Article/details/gttabxsnwf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmnlsaqk.html

[F09] 获取文件大小
来源：http://dali.cucudq.cn/Article/details/gtygrldvjh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtardzqkdx.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtsrjewino.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtdtnytiyd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gtozuxxcog.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtfwoygocz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.smart0.xyz/Article/details/gtkbjuvdjk.html

Ruby: File.size("a.txt")
来源：http://dali.guannengcc.top/Article/details/gttzsyptsu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.redwolf501.top/Article/details/gttxfnfmbz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gtyaheypjc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtcphczjzt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtadxzwogy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gttwxiagnq.html

TS:   path.extname("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtpxkirjha.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gtibaqqtvn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtbbjpwzvg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtsgxidzme.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtehvrgtmu.html

[F11] 复制与移动文件
来源：http://dali.yuxming.cn/Article/details/gtzkhausoi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gttuzxbauo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258888.top/Article/details/gthkaedeqw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtqynqvaje.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtxcetahub.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtsjytwnzl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gtoulesoqp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtelmhtvuo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gttcqdvndg.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gtfckultcq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gtnvuvpzqg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jiagoushi.top/Article/details/gtltuhqnqu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gtsdplevjl.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gtmdvfburz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj202588.top/Article/details/gtiqznajqp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nwbrower.top/Article/details/gtsqxbkhrv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuanzhike.top/Article/details/gtkhnlawud.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gttfdkuban.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtjzmkgprg.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gtzfyykuki.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtwahfhbgt.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gtejtvfgxo.html

Py:   class User: pass
来源：http://dali.dianchejie.cn/Article/details/gtmndwrrel.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gtjilavqgh.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtxgqksklp.html

TS:   class User { name: string = ""; }
来源：http://dali.haohaochexian.top/Article/details/gtumzsxmxc.html


<!-- 参考信息 -->