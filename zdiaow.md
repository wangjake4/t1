代发 wailian999

[E02] 重复字符串
来源：http://dali.dashuyun.cn/Article/details/gt2ixiqimzk.html

Py:   "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eoqaggew.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sufxvd.cn/Article/details/gt2pmeyrpzr.html

JS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zqhsdxxd.html

TS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gt2xryzjraf.html

Java: "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2buqlndyl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.316326.xyz/Article/details/gt2zfesacdj.html

Ruby: "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gt2wyisjssh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shuidangran.top/Article/details/gt2cqvgsdfn.html

[E03] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gt2dhombovj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zdqjudy.top/Article/details/gt2ukbgieur.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gt2yvmztsvf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gt2ywmepknf.html

TS:   s.slice(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gt2cinvrvyq.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2netsnfzc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gt2plgyfgoz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.meibo888.top/Article/details/gt2oactufnw.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gt2zrshvwen.html

[E04] 查找子串位置
来源：http://dali.shzxlz.cn/Article/details/gt2hkkvaeyq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gt2zzqzadlu.html

PHP:  strpos($s, "x");
来源：http://dali.dianchejie.cn/Article/details/gt2xzmgjfuy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.birdmap.top/Article/details/gt2crjwqvdw.html

TS:   s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gt2oqgtzxbl.html

Java: s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gt2lfeqljcu.html

Go:   strings.Index(s, "x")
来源：http://dali.aizwys.cn/Article/details/gt2avqmuhya.html

Ruby: s.index("x")
来源：http://dali.mhx1999.top/Article/details/gt2pxvvmkmv.html

C#:   s.IndexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gt2cvonajbx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sysykeji.top/Article/details/gt2qfddmlrr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gt2edowcyty.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shuidangran.top/Article/details/gt2rtdwegpm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2myvguwvd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hysaishi.cn/Article/details/gt2meumoqhj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gt2bsvwrqhr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tanke756.top/Article/details/gt2uwxgokut.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shzxlz.cn/Article/details/gt2mfxgtdmm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.bjfxy.top/Article/details/gt2zvjacskz.html

[E06] 替换子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2fozweljy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2syjkpknf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.svipenyu.cn/Article/details/gt2ccpkkpvi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2mcduxhnm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2payqpqim.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2arxzgoha.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ketqokhi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2bstgohyj.html

C#:   s.Replace("a", "b")
来源：http://dali.aizwys.cn/Article/details/gt2xpyomaxb.html

[E07] 按分隔符拆分
来源：http://dali.yanxiufei.cn/Article/details/gt2orewffoy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnqzz.top/Article/details/gt2rrowonmj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bisfozgl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.bjfxy.top/Article/details/gt2jfckrewg.html

TS:   s.split(",")
来源：http://dali.xziqi.cn/Article/details/gt2vuzocxrr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.smart0.xyz/Article/details/gt2pxijyzke.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pycfn.com/Article/details/gt2honjjxxw.html

Ruby: s.split(",");  s.split
来源：http://dali.wangshuangyany.cn/Article/details/gt2gypnsmxm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ybcxt.top/Article/details/gt2mmvufapb.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gt2ilqinnft.html

Py:   ",".join(items)
来源：http://dali.nanxinkj.top/Article/details/gt2viubtjjw.html

PHP:  implode(",", $items);
来源：http://dali.shzxlz.cn/Article/details/gt2acfhxego.html

JS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gt2rplcerwy.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gt2mfzvqtaw.html

Java: String.join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ksjlipls.html

Go:   strings.Join(items, ",")
来源：http://dali.kuanghao11.cn/Article/details/gt2bfzfffnp.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gt2tyewojqp.html

C#:   string.Join(",", items)
来源：http://dali.aizwys.cn/Article/details/gt2dvbhuzam.html

[E09] 去除所有空白字符
来源：http://dali.yangfankeji.com/Article/details/gt2zgvmjdkm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2rrnmirvg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2wulkqnqr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gt2ravrhcux.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gt2zqfonapm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gt2zxesizkv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jsxwqyui.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pmjzrkal.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xylfe.cn/Article/details/gt2qeguctjv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cashguo.top/Article/details/gt2gwflzmod.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2hizmzwsv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guannengcc.top/Article/details/gt2tolsqjnj.html

JS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2qhdbutif.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gt2avqwfpma.html

Java: String.format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gt2lsplolfe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gt2pcmnvnoj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gt2uwephlgp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gogol.net.cn/Article/details/gt2kjceqmxy.html

[E11] 反转字符串
来源：http://dali.ehwqpu.com/Article/details/gt2phojlagv.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gt2ppppipmx.html

PHP:  strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gt2ojexmway.html

JS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2hukylyve.html

TS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2urbsjwsi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aizwys.cn/Article/details/gt2igxrylpm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuanzhike.top/Article/details/gt2ybhukjfw.html

Ruby: s.reverse
来源：http://dali.gotoacloud.top/Article/details/gt2gfoxobid.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gt2tsnjwkok.html

[E12] 统计某字符出现次数
来源：http://dali.nanxuanxn.top/Article/details/gt2ooaxhmaq.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gt2qijdbgmx.html

PHP:  substr_count($s, "a");
来源：http://dali.wangshuangyany.cn/Article/details/gt2jtrpmcns.html

JS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gt2xuirevai.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gt2bffzbsrf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.9152youxi.cn/Article/details/gt2pubqwvpf.html

Go:   strings.Count(s, "a")
来源：http://dali.cheryme.top/Article/details/gt2hpmwwgkw.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gt2ywroosnz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fengsongda.top/Article/details/gt2nwthjtqx.html

[E13] 逐字符遍历
来源：http://dali.bjfxy.top/Article/details/gt2hebezeru.html

Py:   for ch in s: print(ch)
来源：http://dali.redwolf501.top/Article/details/gt2icxkdjrm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guannengcc.top/Article/details/gt2vphresfi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2tmxzdhyg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2kmtthvcc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cdnleiting.top/Article/details/gt2atmgualk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gogol.net.cn/Article/details/gt2vcvxbfql.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sufxvd.cn/Article/details/gt2berkbzmw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2smdgqydf.html

[E14] URL 编码与 Base64
来源：http://dali.0kj1m.cn/Article/details/gt2hwqhkybz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gt2gdedgikr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gt2nakysdrv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gt2zamgbbib.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tian-w.cn/Article/details/gt2ymlnbhjo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gt2kbsufqts.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gt2udhlxhgj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmjjrwlx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shzxlz.cn/Article/details/gt2sjxoxreu.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnxiangtu.top/Article/details/gt2qctlxyxq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cdnleiting.top/Article/details/gt2utmvorbd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.9152youxi.cn/Article/details/gt2uslhaksd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangdashe.top/Article/details/gt2qqlxaoli.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shuidangran.top/Article/details/gt2onolyvwa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mkrhermz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2dcbwpfda.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jiagoushi.top/Article/details/gt2cpnzmiui.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gt2jyeyavhv.html

[E16] 数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vrkdnjhe.html

Py:   f"{1234567:,}"
来源：http://dali.ivvv.top/Article/details/gt2hyuzffvz.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gt2kebwpizb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gt2fmfstnpw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gt2xdxodcmp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gt2puuhhprv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sweek.top/Article/details/gt2jdetdwyd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gt2qmvylnvf.html

C#:   1234567.ToString("N0")
来源：http://dali.wangdashe.top/Article/details/gt2rthwccfo.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2irbmhizc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gt2dfrpfnul.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhengqikj.top/Article/details/gt2peicsgih.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gt2kifvhppg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gt2qijzvvuh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aizwys.cn/Article/details/gt2hurnzenw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.meibo888.top/Article/details/gt2cdsiijqq.html

Ruby: s.capitalize
来源：http://dali.yueranfly.top/Article/details/gt2oueditcc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hongshengwenyu.top/Article/details/gt2owfwyski.html

[E18] 模板占位符替换
来源：http://dali.yueranfly.top/Article/details/gt2gxjmzkra.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aizwys.cn/Article/details/gt2qqxboetz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xylfe.cn/Article/details/gt2btkyhzzd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2pzbiifnl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2qusruwfk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2kwibubvz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gt2cmbwqsix.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnxiangtu.top/Article/details/gt2qfxjcuvc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.iojbl.cn/Article/details/gt2uaucvjbd.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bxnktkzv.html

Py:   s.splitlines()
来源：http://dali.yvedp.cn/Article/details/gt2tnknttat.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2rsgmycil.html

JS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gt2mutrnelj.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rothaxmn.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gt2btezcdim.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gt2xelhrcdl.html

Ruby: s.lines
来源：http://dali.tian-w.cn/Article/details/gt2fwzoobhu.html

C#:   s.Split('\n')
来源：http://dali.aizwys.cn/Article/details/gt2wipiutfx.html

[E20] 判断字符串是否为空
来源：http://dali.jianghu66.top/Article/details/gt2vfcvlsqe.html

Py:   if not s:
来源：http://dali.jqgfzy.top/Article/details/gt2yifqmfzg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.meibo888.top/Article/details/gt2mvvcmgkw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gt2gbivemrx.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gt2yhrikjbv.html

Java: if (s.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gt2ttunsyrm.html

Go:   if s == "" {}
来源：http://dali.chenlongwang.top/Article/details/gt2zsvqdnti.html

Ruby: if s.empty?
来源：http://dali.wangshuangyany.cn/Article/details/gt2ykzxxssn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2jalerozm.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gt2hdijzilc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sxryk.cn/Article/details/gt2auyxzsrc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2hiyjlswi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qyrjdbtr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2epjsnire.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2kwvlmfug.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gt2jzylyafd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2yxbgtuzd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2mjeyvgmq.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gt2tuzpxdlf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ybcxt.top/Article/details/gt2qrdxovzo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2uhmdjezd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gt2bjqiplgi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gt2spzaxlsh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gzhubu.top/Article/details/gt2qyjlvpyk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgufenzy.top/Article/details/gt2dushokpn.html

Ruby: s.bytesize;  s.length
来源：http://dali.ehwqpu.com/Article/details/gt2knetupgv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbtsxccc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2gcmjdrrq.html

F. 文件与目录
来源：http://dali.xziqi.cn/Article/details/gt2wsrfolgp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2xrdtvaix.html

[F01] 读取整个文件
来源：http://dali.ehwqpu.com/Article/details/gt2iwyaflto.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yongpay.top/Article/details/gt2qfsvlylv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2onwikabn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gt2jipydqvp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2esxmmpjd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2flhxnbog.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cucnebta.html

Ruby: File.read("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2mdhitrla.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2pwezmzbe.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gt2lfqrjhjx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pengpengdd.cyou/Article/details/gt2eduycrvf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gt2jntykkqz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jdnzapnp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rreqnxoi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gt2vbbdxfxv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuanzhike.top/Article/details/gt2tvwotdju.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gogol.net.cn/Article/details/gt2xbtibjsq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jyoumei.cn/Article/details/gt2qlqyzajv.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mplhnqbq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gt2kysxrcgg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ucpnqdmi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2ewbvubit.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gt2hdudrzsq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hlzgtctc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dianchejie.cn/Article/details/gt2ftleubxt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daxiang520.top/Article/details/gt2omezkaxr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gt2betgwgws.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btdomasb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuxming.cn/Article/details/gt2auiguoar.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ppjwa.cn/Article/details/gt2julhmzpa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gt2aarukoop.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gt2dxlgupyl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gt2hxshpfry.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2tvravhtl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gt2toogevry.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zycfv.cn/Article/details/gt2wvkvovmc.html

[F05] 判断文件或目录是否存在
来源：http://dali.ehwqpu.com/Article/details/gt2ufeyikaz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gt2atzpolpf.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2vsozrzjl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2uwtsguxc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ubfllfsr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gt2sgtwcsdg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenlongwang.top/Article/details/gt2iohmjbkr.html

Ruby: File.exist?("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2qtpqllti.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2exbbpxit.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gt2kflokxjw.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2dmqqvvmj.html

PHP:  unlink("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2shwcmbge.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2hxejkicj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hfcdrvdj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2ddgnjith.html

Go:   os.Remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2haxpijxc.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2zooavtxc.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eibydbdh.html

[F07] 创建目录（含多级）
来源：http://dali.wangdashe.top/Article/details/gt2wznboife.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gt2mvjzsler.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gogol.net.cn/Article/details/gt2sytkmbaw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gt2kijdqjdo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gt2atlvhptp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yanxiufei.cn/Article/details/gt2deuuemdc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gogol.net.cn/Article/details/gt2oomgosih.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhongyouzk.top/Article/details/gt2ezryuyfv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnqzz.top/Article/details/gt2pdyuippp.html

[F08] 遍历目录
来源：http://dali.yanxiufei.cn/Article/details/gt2vbukiwit.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gt2reydfcxd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehekahxz.html

JS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2erpbogkp.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gt2pdaafpgl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gt2kwhmqccd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2rmajbrrx.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gt2bnbqkntg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ybcxt.top/Article/details/gt2lliarqfh.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gt2gqgqokon.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2yhwetlap.html

PHP:  filesize("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2lodqfesv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gt2wcmrrbll.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gt2boapzays.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gt2ftjofeet.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gt2sclorftz.html

Ruby: File.size("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hfaawvub.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hyaimncn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gt2zutgzxxk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2qgwfjdxc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2dedxmnex.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2ttnfkgod.html

TS:   path.extname("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2yexgfsnw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ivvv.top/Article/details/gt2vdqqlmas.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xutfhfxb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2idrubxkk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2rhvtdsow.html

[F11] 复制与移动文件
来源：http://dali.yuanzhike.top/Article/details/gt2vldbyfjr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gt2lfaaciys.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2piemixlt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2dsljppmt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2tnzycyxt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.0kj1m.cn/Article/details/gt2sgcppram.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hysaishi.cn/Article/details/gt2icwkdntm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gt2krodhbgz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yueranfly.top/Article/details/gt2oorrsxmy.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gt2xciafybe.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.0kj1m.cn/Article/details/gt2bhnpvhiq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.316326.xyz/Article/details/gt2lkzvaxre.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuxming.cn/Article/details/gt2mtrxhyfl.html

TS:   // 同上
来源：http://dali.mhx1999.top/Article/details/gt2lmzghnlt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gt2kksfkuww.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnxiangtu.top/Article/details/gt2belpwoid.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.redwolf501.top/Article/details/gt2reittyvq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gt2aafpzoje.html


<!-- 参考信息 -->