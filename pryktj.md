代发 wailian999

[E02] 重复字符串
来源：http://dali.tianlin.xyz/Article/details/gt2bvvhweoh.html

Py:   "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gt2zqdngptm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2waepvlra.html

JS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gt2pxsawpad.html

TS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gt2gjlmtlbl.html

Java: "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gt2rrxtwrvt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ppjwa.cn/Article/details/gt2ravkzmee.html

Ruby: "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gt2gvwqkrbv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.svipenyu.cn/Article/details/gt2focvxpse.html

[E03] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gt2gfukkwit.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2qftgkeai.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gt2mvckgppj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gt2iruxdbdn.html

TS:   s.slice(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gt2nagqvxqz.html

Java: s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gt2mirzemre.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gt2fgrwoyqi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tianlin.xyz/Article/details/gt2qvkvlhxb.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gt2jjlyquoz.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gt2lrlmkddb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gt2kcvbopco.html

PHP:  strpos($s, "x");
来源：http://dali.nwbrower.top/Article/details/gt2ficjmdsm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenlongwang.top/Article/details/gt2xdnpzpys.html

TS:   s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gt2ctzexyij.html

Java: s.indexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gt2lfztzvyg.html

Go:   strings.Index(s, "x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2crlwsbqn.html

Ruby: s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gt2tiwfegix.html

C#:   s.IndexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gt2jooxaozz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.fengsongda.top/Article/details/gt2ntoshmfz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2nutlnfok.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhoulong.xyz/Article/details/gt2ryalpysz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcymfwgr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2qnqakzxx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sysykeji.top/Article/details/gt2kbyufepw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvvrukb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnqzz.top/Article/details/gt2joecplhb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yuxming.cn/Article/details/gt2utwepkev.html

[E06] 替换子串
来源：http://dali.hysaishi.cn/Article/details/gt2siwqrnio.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gt2szbysgcl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gt2ljprzaey.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2gchhasyb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmfzdwux.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2rlbivpbq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gt2jrbsyxxl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2ztovlnng.html

C#:   s.Replace("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2hismafqc.html

[E07] 按分隔符拆分
来源：http://dali.smart0.xyz/Article/details/gt2xdttrobb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ehwqpu.com/Article/details/gt2cqpjetzd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lxjhqbgp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hywenlv.cn/Article/details/gt2xaamrblt.html

TS:   s.split(",")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zpitkthe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.haohaochexian.top/Article/details/gt2xldrdsya.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hysaishi.cn/Article/details/gt2hkgdqvjq.html

Ruby: s.split(",");  s.split
来源：http://dali.sufxvd.cn/Article/details/gt2kdatyoan.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zdqjudy.top/Article/details/gt2goujfwbw.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258.top/Article/details/gt2lgudyxeg.html

Py:   ",".join(items)
来源：http://dali.zhoulong.xyz/Article/details/gt2trsxzrwd.html

PHP:  implode(",", $items);
来源：http://dali.316326.xyz/Article/details/gt2xluvakfb.html

JS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zsjfvnxc.html

TS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gt2vfdaktrw.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gt2gkjfnmcr.html

Go:   strings.Join(items, ",")
来源：http://dali.ydzc1.top/Article/details/gt2xzmgxmxz.html

Ruby: items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gt2yljgwtln.html

C#:   string.Join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gt2cdetxmje.html

[E09] 去除所有空白字符
来源：http://dali.sufxvd.cn/Article/details/gt2nmwuwamv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hysaishi.cn/Article/details/gt2acaqtwky.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2aywewxfc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gt2yfgzqjlt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gt2mwzfmikz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gt2ozavhrcw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgfzy.top/Article/details/gt2xejyebwg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shuidangran.top/Article/details/gt2jpckyjzr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2uexqlzrq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.kuanghao11.cn/Article/details/gt2sabhsoea.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czkwiaco.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnxiangtu.top/Article/details/gt2xgrstldy.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gt2lhtdlbuz.html

TS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2jzbsviiy.html

Java: String.format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gt2uvvrcwhw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gt2zrkzkuws.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggkhlyfg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shangyingyoupin.top/Article/details/gt2nmfsjjuu.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gt2fsfcutok.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gt2dbisurgf.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gt2mihvcvnv.html

JS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gt2gdvvrxtk.html

TS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gt2obvaqgyu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hfpthk.cn/Article/details/gt2lslwdxis.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daria6918.cn/Article/details/gt2bvkukrxc.html

Ruby: s.reverse
来源：http://dali.nanxinkj.top/Article/details/gt2nmstwhov.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gt2ctlubopd.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gt2jsxdxuya.html

Py:   s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gt2xdtvhsgn.html

PHP:  substr_count($s, "a");
来源：http://dali.xuetiantiany.cn/Article/details/gt2phsleooa.html

JS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gt2yrwjipqi.html

TS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gt2rgxxxqgu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sysykeji.top/Article/details/gt2exzzlzcv.html

Go:   strings.Count(s, "a")
来源：http://dali.hysaishi.cn/Article/details/gt2ktqypvwk.html

Ruby: s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2mmwramun.html

C#:   s.Count(c => c == 'a')
来源：http://dali.c1oappe.top/Article/details/gt2clulcmqo.html

[E13] 逐字符遍历
来源：http://dali.sweek.top/Article/details/gt2wdoctpfm.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gt2yxqyvdhv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shzxlz.cn/Article/details/gt2umbzefeg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2kqsqwldy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2mbzndhze.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2hnyybbuo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2lukiqpav.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hfpthk.cn/Article/details/gt2zpwahxzv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gt2pgwkvtbo.html

[E14] URL 编码与 Base64
来源：http://dali.shuidangran.top/Article/details/gt2fskkldge.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cqqwz.cn/Article/details/gt2gtivpijz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj202588.top/Article/details/gt2vzutgetl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wrjhbzxr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gt2ymveekhd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigufen.top/Article/details/gt2cywvhqbp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gt2gaynspoz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daxiang520.top/Article/details/gt2edmzvacw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gt2ngdjlfzn.html

[E15] HTML 转义 / 反转义
来源：http://dali.birdmap.top/Article/details/gt2fpmfiwvx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jyoumei.cn/Article/details/gt2hwsunkam.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fzhhl.top/Article/details/gt2ggkrdesn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zzwkhzfm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2yplrkcjs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.0kj1m.cn/Article/details/gt2gklwalqi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tanke756.top/Article/details/gt2slqnemzp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2iznkmwnq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tanke756.top/Article/details/gt2vinapfrh.html

[E16] 数字千分位
来源：http://dali.iojbl.cn/Article/details/gt2onreipnv.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gt2krvwrbsi.html

PHP:  number_format(1234567);
来源：http://dali.yj20258888.top/Article/details/gt2lvptsnxz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ebcqmjkl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gt2ccrwdjqu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sufxvd.cn/Article/details/gt2qobpmkov.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aizwys.cn/Article/details/gt2qaznnybc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2redoddjr.html

C#:   1234567.ToString("N0")
来源：http://dali.hnxiangtu.top/Article/details/gt2haynncub.html

[E17] 首字母大写
来源：http://dali.sxryk.cn/Article/details/gt2ifygumgf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guannengcc.top/Article/details/gt2aikcciie.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gt2oxhrzemr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gt2zpmdpqtp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gt2exuwzozd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xylfe.cn/Article/details/gt2uayropyl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fengsongda.top/Article/details/gt2hgnifamc.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gt2hhbuikvs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cdnleiting.top/Article/details/gt2syfkyrjh.html

[E18] 模板占位符替换
来源：http://dali.jinqigfzy.top/Article/details/gt2rpqhiamd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lyqxemrc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gt2wfmmnvux.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gt2rgxomodu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2cilqrlkp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukcuqdpa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2lanqppqa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhoulong.xyz/Article/details/gt2lkxdcmlm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gt2qydpaeuh.html

[E19] 多行文本按行拆分
来源：http://dali.hnqzz.top/Article/details/gt2htukbosg.html

Py:   s.splitlines()
来源：http://dali.ybcxt.top/Article/details/gt2gxbjrqpp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cheryme.top/Article/details/gt2cnbpfkza.html

JS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gt2wlflpnpz.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gt2rensesse.html

Java: s.lines().toList()
来源：http://dali.dashuyun.cn/Article/details/gt2xpmzdriz.html

Go:   strings.Split(s, "\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtsqrwxx.html

Ruby: s.lines
来源：http://dali.yj202588.top/Article/details/gt2qzyyswro.html

C#:   s.Split('\n')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dgnyucll.html

[E20] 判断字符串是否为空
来源：http://dali.316326.xyz/Article/details/gt2nwyilgxa.html

Py:   if not s:
来源：http://dali.hongshengwenyu.top/Article/details/gt2iuwulvlb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxinkj.top/Article/details/gt2obrxznpd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gt2sfarawqn.html

TS:   if (s === "") {}
来源：http://dali.andypj.xyz/Article/details/gt2shhyjapr.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gt2oycfxofm.html

Go:   if s == "" {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2trasnven.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mpxnqfdb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tanke756.top/Article/details/gt2fsriqczw.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gt2ryimozya.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxuanxn.top/Article/details/gt2iomalpen.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gt2zjsegobd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2qbqrrhlm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gt2xogcchgn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2kfmtzaau.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ybcxt.top/Article/details/gt2ddlofhuu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhwzmuih.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2fnsjmzry.html

[E22] 字节长度与字符长度
来源：http://dali.andypj.xyz/Article/details/gt2fdkuwxpw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cheryme.top/Article/details/gt2cnibbelm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gt2zrucfmmh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2cxlglzbv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gt2rlnzmpvi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tianlin.xyz/Article/details/gt2elsqhktt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hongshengwenyu.top/Article/details/gt2qzrbybav.html

Ruby: s.bytesize;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmxezrlq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yvedp.cn/Article/details/gt2bdpxglbl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2yurcrvlw.html

F. 文件与目录
来源：http://dali.aizwys.cn/Article/details/gt2iprkukwl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2qjvovigf.html

[F01] 读取整个文件
来源：http://dali.9152youxi.cn/Article/details/gt2nygrpmtc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aizwys.cn/Article/details/gt2otfclnlc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2klmolvbm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gt2qbzjjhsp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2gtdnaceo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2hpsrlfxe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gt2zamfvvwg.html

Ruby: File.read("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2sqokbwpj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2urbwvnhf.html

[F02] 逐行读取文件
来源：http://dali.kuanghao11.cn/Article/details/gt2bujvdpdz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkyhxddw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shzxlz.cn/Article/details/gt2vrativxc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gt2yjwvmzlk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gt2wybprwik.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gt2tmefmfqj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gt2fvlxxtyn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rgkykznh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yanxiufei.cn/Article/details/gt2smtoecqi.html

[F03] 写入文件（覆盖）
来源：http://dali.0kj1m.cn/Article/details/gt2bpumpjkf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gzezzses.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2gfkhbdhp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gt2frcwxrkc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gyjdqfle.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhagngyk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hammf.cn/Article/details/gt2phldpgbo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hammf.cn/Article/details/gt2iaydfmqq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gt2gogbozjw.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gt2madeczgs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2zyvgncxr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sufxvd.cn/Article/details/gt2fpivosue.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gt2hsfqlgdu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gt2upzcbzay.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zycfv.cn/Article/details/gt2rcbyqcmn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2jjomencp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cdnleiting.top/Article/details/gt2hfdsuivk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ppjwa.cn/Article/details/gt2xdihubwn.html

[F05] 判断文件或目录是否存在
来源：http://dali.jyoumei.cn/Article/details/gt2dkorqogs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gt2rutcrudk.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2hlghwxhw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2algmqblw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxhpoiax.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2helgfjan.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daxiang520.top/Article/details/gt2jqtugssx.html

Ruby: File.exist?("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2oexrzzlb.html

C#:   File.Exists("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2gbbmngzu.html

[F06] 删除文件
来源：http://dali.fzhhl.top/Article/details/gt2cwufuhzc.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2lecnvmce.html

PHP:  unlink("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2elstodqb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2lwnmvytu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2enoezaht.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gt2oltosjdi.html

Go:   os.Remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2xjviszsv.html

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2bwmotqcc.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2ssiqnmry.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gt2tgbqpnim.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gt2arjouzir.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gogol.net.cn/Article/details/gt2vueytcfu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gt2hqlzwhbo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gt2gwlawluc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.svipenyu.cn/Article/details/gt2skgnrgot.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jiagoushi.top/Article/details/gt2mzrgzbcl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gt2lpuvcaxq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cucudq.cn/Article/details/gt2fuitdoil.html

[F08] 遍历目录
来源：http://dali.sxryk.cn/Article/details/gt2gunmblsy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuanzhike.top/Article/details/gt2yjebeiss.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gt2nowccgqf.html

JS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gt2aioiknnq.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gt2atfnsdse.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gt2stkkpqfl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2qrinbfme.html

Ruby: Dir.children("dir")
来源：http://dali.ybcxt.top/Article/details/gt2ykdgsjjn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gt2artfxnfz.html

[F09] 获取文件大小
来源：http://dali.wangshuangyany.cn/Article/details/gt2svqemmpf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2uccuhxbs.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2lftybfec.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gt2xuhczrmt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2slyqzouw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2vzglpavt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.birdmap.top/Article/details/gt2contjgiw.html

Ruby: File.size("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2axjqawmc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gt2yabxuxof.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gt2vbmibari.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2egwgmlxn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2trsqpgpw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2eldkplvk.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2rcrrtchu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.smart0.xyz/Article/details/gt2jlscwhsb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2obkkdeeq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2opkkzila.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2cyasswto.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gt2kylodxlo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2vndexfup.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gt2tqmljlef.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2exgqeldq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2itbbkioy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gt2oqaifpmm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xinyue.icu/Article/details/gt2lnpuwvzi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2bugeutyv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcusfvdw.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gt2rdxsatvu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pycfn.com/Article/details/gt2eikglwlj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnxiangtu.top/Article/details/gt2cainbpge.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.svipenyu.cn/Article/details/gt2wtxcougi.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gt2liivftjp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yueranfly.top/Article/details/gt2gnvwxoen.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.9152youxi.cn/Article/details/gt2aeroytcd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gt2gppflrlw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdwcshbq.html


<!-- 参考信息 -->