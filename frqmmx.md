代发 wailian999

[E02] 重复字符串
来源：http://dali.dianchejie.cn/Article/details/gtlwxbwfyl.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmckjkjz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aibaodan.cn/Article/details/gtztjihbce.html

JS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtfkyvoyrz.html

TS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtrdedsfxw.html

Java: "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtanpivbva.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.mhx1999.top/Article/details/gtkomgsgmy.html

Ruby: "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtjmjfeybl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258888.top/Article/details/gtaosxobfn.html

[E03] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtmudrxpsb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yanxiufei.cn/Article/details/gtnxjujmwp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtlzlbpdcw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsdmjldh.html

TS:   s.slice(1, 4)
来源：http://dali.redwolf501.top/Article/details/gtdlhkfkhu.html

Java: s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gtgbbeiowm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aizwys.cn/Article/details/gtcgjbkgaf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sysykeji.top/Article/details/gtgvrgpbbb.html

C#:   s.Substring(1, 3)
来源：http://dali.cucudq.cn/Article/details/gtretirkmg.html

[E04] 查找子串位置
来源：http://dali.chenjidiqi.icu/Article/details/gtzdqndzkr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtbtpsgwmb.html

PHP:  strpos($s, "x");
来源：http://dali.yongpay.top/Article/details/gtildqzrnr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guowangkeji.top/Article/details/gtozqujuzu.html

TS:   s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtkrlwofdq.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtqjohhkbh.html

Go:   strings.Index(s, "x")
来源：http://dali.xuanzx.com/Article/details/gtukazvnmr.html

Ruby: s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtgjdvcfrp.html

C#:   s.IndexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtsmksxeev.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gogol.net.cn/Article/details/gtmpaqftov.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.9152youxi.cn/Article/details/gtjmaygjez.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinghuilouyu.cn/Article/details/gtitrjpcme.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtuxydgizk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.316326.xyz/Article/details/gtulpevkww.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtyufqcbrt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gzhubu.top/Article/details/gtdtbkxmwg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlckicwqs.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtmcvvngee.html

[E06] 替换子串
来源：http://dali.hongshengwenyu.top/Article/details/gtblfeqsvx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtyqzgoeeu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.birdmap.top/Article/details/gtnryakpbp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhhnlozm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtjbjlmmcd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtnjjkuepx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gttsvnpjlv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj202588.top/Article/details/gtetpqeysp.html

C#:   s.Replace("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gteeexryhc.html

[E07] 按分隔符拆分
来源：http://dali.redwolf501.top/Article/details/gtukpgduxh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258.top/Article/details/gthfplpogj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.mhx1999.top/Article/details/gtcivhzkzw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenzaomai.com/Article/details/gttdzfhwes.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gtsoqxhobx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhengqikj.top/Article/details/gtxxhjzeda.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.birdmap.top/Article/details/gthseccahf.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxuanxn.top/Article/details/gthnivhmpi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnqzz.top/Article/details/gtjsnzocmb.html

[E08] 数组按分隔符合并
来源：http://dali.hywenlv.cn/Article/details/gtehbjooas.html

Py:   ",".join(items)
来源：http://dali.mhx1999.top/Article/details/gtbjcmyszh.html

PHP:  implode(",", $items);
来源：http://dali.guowangkeji.top/Article/details/gtbyfdcrok.html

JS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtliesjyrr.html

TS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokfnpnno.html

Java: String.join(",", items)
来源：http://dali.c1oappe.top/Article/details/gtrzhhaqgr.html

Go:   strings.Join(items, ",")
来源：http://dali.shangyingyoupin.top/Article/details/gteuqjfvpr.html

Ruby: items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtkypvefno.html

C#:   string.Join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gtytlnkjiu.html

[E09] 去除所有空白字符
来源：http://dali.yangfankeji.com/Article/details/gttxsckbuv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigufen.top/Article/details/gttxaxpthk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtmgmjgdpp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gtwhakgrwz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtmfulquap.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gtgnclczlk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gteorshxfu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daxiang520.top/Article/details/gtbmcocusx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtqhiatjzf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.andypj.xyz/Article/details/gtnmwzczif.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtelusinim.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.quarkkingdee.top/Article/details/gthyughzid.html

JS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtudtqfrzi.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtsiybzrma.html

Java: String.format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtvdeusean.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtgpxplzvf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtrcklkcna.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yvedp.cn/Article/details/gthkicavkx.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtzyjrqmdt.html

Py:   s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtojvnfpro.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhzsrqgy.html

JS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtonhjmdyk.html

TS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtjyajaeeh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrwxfurg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gtatxzzsai.html

Ruby: s.reverse
来源：http://dali.xziqi.cn/Article/details/gtaziiezzv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gtwybckpsh.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gtxzeharfb.html

Py:   s.count("a")
来源：http://dali.gzhubu.top/Article/details/gtqdflahet.html

PHP:  substr_count($s, "a");
来源：http://dali.andypj.xyz/Article/details/gtozufwljt.html

JS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gttgqjoqzs.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtumfrgmku.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gtbbtxtmik.html

Go:   strings.Count(s, "a")
来源：http://dali.hfpthk.cn/Article/details/gtshlbrutr.html

Ruby: s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gtinenjqyc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gtotxjrxvs.html

[E13] 逐字符遍历
来源：http://dali.dashuyun.cn/Article/details/gtgqvpodww.html

Py:   for ch in s: print(ch)
来源：http://dali.xziqi.cn/Article/details/gtifidljlr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gtxnplsvci.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gtbyfnebvc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtfelhwsmn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtflqjcgav.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.316326.xyz/Article/details/gtzmzdtjid.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pengpengdd.cyou/Article/details/gtthpyimox.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tianlin.xyz/Article/details/gthvnqqdjk.html

[E14] URL 编码与 Base64
来源：http://dali.yuxming.cn/Article/details/gtgtnexugo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xinyue.icu/Article/details/gtgwqsmnub.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.havefunace.top/Article/details/gtuzbgymek.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gtdmvxxeeh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.smart0.xyz/Article/details/gtjshriyby.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xylfe.cn/Article/details/gtnaccmnjp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.meibo888.top/Article/details/gtivcsizwc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guowangkeji.top/Article/details/gtjzvrgyxs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gtfuklukqy.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gtzbfkuuvs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daria6918.cn/Article/details/gtibmyenyc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtftbnipdr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gtuwkviyww.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jianghu66.top/Article/details/gtcftafjin.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxuanxn.top/Article/details/gtwxleoyin.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cqqwz.cn/Article/details/gthambngjk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhengqikj.top/Article/details/gtnqogzpgb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.birdmap.top/Article/details/gtdirownbh.html

[E16] 数字千分位
来源：http://dali.meibo888.top/Article/details/gtrpmuxgbb.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtbmylruwv.html

PHP:  number_format(1234567);
来源：http://dali.iojbl.cn/Article/details/gtoqgzbbwf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gtprmrymrd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gtlgbmiuwc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sxryk.cn/Article/details/gtrxmhcjen.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tanke756.top/Article/details/gtqfacgcxj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.meibo888.top/Article/details/gtxhyicycm.html

C#:   1234567.ToString("N0")
来源：http://dali.yuxming.cn/Article/details/gtnxxrvqju.html

[E17] 首字母大写
来源：http://dali.zhengqikj.top/Article/details/gtbjfidyae.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tanke756.top/Article/details/gteqzequlq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenzaomai.com/Article/details/gtfqcqzscz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtgexfasfx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtjfrhujsx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxinkj.top/Article/details/gthzhtccbu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gttjgfnxbu.html

Ruby: s.capitalize
来源：http://dali.jqgufenzy.top/Article/details/gtykniwomh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gtmpihtfln.html

[E18] 模板占位符替换
来源：http://dali.nanxinkj.top/Article/details/gtetqdodyl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqzjdlga.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.mhx1999.top/Article/details/gttdvlbbdy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtovfwfjul.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtqplwlklj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihuwxtfe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtlmecppgn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gtfvxvpetc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gtesyettdc.html

[E19] 多行文本按行拆分
来源：http://dali.jiagoushi.top/Article/details/gtppxahfvx.html

Py:   s.splitlines()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjzqecam.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtmlacmihg.html

JS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gtjuhvvgxd.html

TS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gtkajjjros.html

Java: s.lines().toList()
来源：http://dali.sysykeji.top/Article/details/gtwfgbaxce.html

Go:   strings.Split(s, "\n")
来源：http://dali.jiagoushi.top/Article/details/gtenvybzol.html

Ruby: s.lines
来源：http://dali.wangdashe.top/Article/details/gthxsyhkaa.html

C#:   s.Split('\n')
来源：http://dali.jinqigfzy.top/Article/details/gtexxzfqlm.html

[E20] 判断字符串是否为空
来源：http://dali.yangfankeji.com/Article/details/gteqwveund.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gtmmswtszr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hammf.cn/Article/details/gtbqipgkod.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.smart0.xyz/Article/details/gtvfkutvud.html

TS:   if (s === "") {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqplfnrdq.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtkgldplvv.html

Go:   if s == "" {}
来源：http://dali.gogol.net.cn/Article/details/gtftavaabh.html

Ruby: if s.empty?
来源：http://dali.ppjwa.cn/Article/details/gtgorppood.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gotoacloud.top/Article/details/gtqabkihmy.html

[E21] 超长截断加省略号
来源：http://dali.316326.xyz/Article/details/gtpvsjxrru.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gtzvugmcsn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtqjtagvqh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtyvcshacu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtbepuaeha.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtfuppvrva.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yanxiufei.cn/Article/details/gtjfzjijxw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtvdcvfroe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtpdmurxog.html

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gtdimaqucs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gtccalbsxz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtdyuqxbos.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtlkdmkjxx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtkvptejzd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxinkj.top/Article/details/gtkejubqel.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tanke756.top/Article/details/gtjrsrlema.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkpulzun.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtdwknjrxl.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqwljkhc.html

F. 文件与目录
来源：http://dali.meibo888.top/Article/details/gtffjzgdcg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttvpzeces.html

[F01] 读取整个文件
来源：http://dali.cdnleiting.top/Article/details/gtjnxyzlpp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cucudq.cn/Article/details/gtowiphlcn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtdknbkxrq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gtxvwhakuk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtlvcvnehl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtqgtssusk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigfzy.top/Article/details/gtfrzaixpt.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gthkyesqqe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtwcwbumqp.html

[F02] 逐行读取文件
来源：http://dali.hnqzz.top/Article/details/gtfwddegdz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gtpmushjdw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jiagoushi.top/Article/details/gtjyggcanu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtydgmogip.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtchjwquqh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gtitgdspzy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gtshqvkdoc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenzaomai.com/Article/details/gtciwgbjtn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gtzuttqwps.html

[F03] 写入文件（覆盖）
来源：http://dali.gogol.net.cn/Article/details/gtlguhqtiq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtahhoihjn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtgwbpbksw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtkrfaxnto.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtvmhmgmfz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuxming.cn/Article/details/gtmcodnyzv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ydzc1.top/Article/details/gtalqxjefu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.meibo888.top/Article/details/gtfotjgzsh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gthdrbwhoe.html

[F04] 追加写入文件
来源：http://dali.havefunace.top/Article/details/gtcqnykcmz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhibzbvb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shzxlz.cn/Article/details/gtmgbemcuc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gtvprsvcoa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gtpajbfodt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.0kj1m.cn/Article/details/gtwboodgjn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigufen.top/Article/details/gtgupzmlko.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.redwolf501.top/Article/details/gtqmrcpjuc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxinkj.top/Article/details/gtmsbomcjc.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gtacadqauc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gtbsimjasb.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gtpcmekqhn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtbawcdbma.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtslxaanmh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtpvdtfygf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xziqi.cn/Article/details/gtonscayks.html

Ruby: File.exist?("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtmropzcfx.html

C#:   File.Exists("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtffomzglv.html

[F06] 删除文件
来源：http://dali.jyoumei.cn/Article/details/gtxvawjplp.html

Py:   os.remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtgaqletuf.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtrsqtiqdz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtichcnvzr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gthfctgnke.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtxazgrrxy.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtaagllzlw.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtkzrpdddb.html

C#:   File.Delete("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtbtmxnopd.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gtkfhtyaea.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gtmkkejcok.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangdashe.top/Article/details/gtjlioxlgb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtjofshwbh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtsgztohrr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmokvsbc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gtkobrwwwh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fengsongda.top/Article/details/gtgbecxmlk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nwbrower.top/Article/details/gtketsxgit.html

[F08] 遍历目录
来源：http://dali.iojbl.cn/Article/details/gtudlzvbbi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gtjlrjwpzm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gtdvdwhocn.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtsedfmdud.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gthfwbrklq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gtfkyhgedz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenzaomai.com/Article/details/gtjzzbrima.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258.top/Article/details/gtjowhnzic.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gtekifhcxj.html

[F09] 获取文件大小
来源：http://dali.jiagoushi.top/Article/details/gtpqqjfzjh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtyytohueb.html

PHP:  filesize("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvitqivl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gtqkkifdqs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gtizugsxdf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtagblqlax.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenlongwang.top/Article/details/gtxcodjqng.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtgaqqkfpc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nwbrower.top/Article/details/gtajjxdrcz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hongshengwenyu.top/Article/details/gtthlfdhhg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtilcxfhsx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gtaxlkwrbd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtnpkdiosc.html

TS:   path.extname("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtloxeckbm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkmpvlda.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtlhmftudp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtymoofxef.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtwaqsifgu.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gtwdwajnhq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gttqhnadfs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtqtkyfref.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtxlvfnfdl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtnrvrclaf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtcsmkxsib.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqnehpnq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtwjlwrvch.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gtpcnfjkbj.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gtjbhcagrx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gtghjbqtau.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gtzbrgswjz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezmyxidt.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gtoieoxwtu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gtssvyzlco.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gogol.net.cn/Article/details/gtaomxemgf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.vqdsnc.cn/Article/details/gtmfckyxuz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hfpthk.cn/Article/details/gtqlxbdncq.html


<!-- 参考信息 -->