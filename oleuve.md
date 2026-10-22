代发 wailian999

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2fwyxhncr.html

E. 字符串处理
来源：http://dali.tian-w.cn/Article/details/gt2ykmoeynh.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2bjpdfklz.html

[E01] 拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gt2urbjbiec.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yanxiufei.cn/Article/details/gt2axexgtqh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sysykeji.top/Article/details/gt2gyqbqzst.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gt2tikqypvm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gt2dymuauev.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xxmywmjr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.quarkkingdee.top/Article/details/gt2oibnclur.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zdqjudy.top/Article/details/gt2acuibkvj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2fmutpfja.html

[E02] 重复字符串
来源：http://dali.fzhhl.top/Article/details/gt2roozfprx.html

Py:   "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gt2kcsgujfw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenlongwang.top/Article/details/gt2gveuaksb.html

JS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gt2nqezgsad.html

TS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gt2ugpwpjiw.html

Java: "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gt2pxwxrmju.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gt2wloamtex.html

Ruby: "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gt2idnwckbz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj202588.top/Article/details/gt2jbycpdvg.html

[E03] 截取子串
来源：http://dali.aizwys.cn/Article/details/gt2mjmmdpjk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daxiang520.top/Article/details/gt2aaaldqfb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gt2jqnrlqup.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gt2jokbvzpu.html

TS:   s.slice(1, 4)
来源：http://dali.yj202588.top/Article/details/gt2dqjpdiax.html

Java: s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gt2llmqlonh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tianlin.xyz/Article/details/gt2olfxohwt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hfpthk.cn/Article/details/gt2jaiuybsq.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2mojzgvcd.html

[E04] 查找子串位置
来源：http://dali.haohaochexian.top/Article/details/gt2bptqllbk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pycfn.com/Article/details/gt2hpggfocp.html

PHP:  strpos($s, "x");
来源：http://dali.smart0.xyz/Article/details/gt2vsnfmgbb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hywenlv.cn/Article/details/gt2dcsnmpwv.html

TS:   s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jtyngnpa.html

Java: s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gt2wivabgkh.html

Go:   strings.Index(s, "x")
来源：http://dali.jianghu66.top/Article/details/gt2lahfjtoc.html

Ruby: s.index("x")
来源：http://dali.yvedp.cn/Article/details/gt2rhjkkpof.html

C#:   s.IndexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gt2awbrbdnj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.iojbl.cn/Article/details/gt2wznvcjlc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jyoumei.cn/Article/details/gt2kzajtpry.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gzhubu.top/Article/details/gt2wglcjusj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2aocjyirs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aibaodan.cn/Article/details/gt2oavjjeju.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gt2xqsavnob.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nwbrower.top/Article/details/gt2nehsikwt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ybcxt.top/Article/details/gt2ylbybybu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2kjnnijjw.html

[E06] 替换子串
来源：http://dali.fzhhl.top/Article/details/gt2ezkdsvqr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gt2pdavtsig.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenzaomai.com/Article/details/gt2zclbxcza.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2yyjhxitw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2ptixdlav.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2hclvwybb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gt2xqzkdhwr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2fvyiugoc.html

C#:   s.Replace("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2kzelukkj.html

[E07] 按分隔符拆分
来源：http://dali.yangfankeji.com/Article/details/gt2vdoqdjzr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pengpengdd.cyou/Article/details/gt2izsnvfpo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2ofzzkady.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yanxiufei.cn/Article/details/gt2atduqgxj.html

TS:   s.split(",")
来源：http://dali.daxiang520.top/Article/details/gt2npebqmet.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gzhubu.top/Article/details/gt2ddyxuyqb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2gqnclqvt.html

Ruby: s.split(",");  s.split
来源：http://dali.bjfxy.top/Article/details/gt2tlzvnixk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.9152youxi.cn/Article/details/gt2mnfvpmog.html

[E08] 数组按分隔符合并
来源：http://dali.jiagoushi.top/Article/details/gt2wiknjemh.html

Py:   ",".join(items)
来源：http://dali.cheryme.top/Article/details/gt2vrkozroo.html

PHP:  implode(",", $items);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hseytjkl.html

JS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2zlvssmwk.html

TS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hsymtmlt.html

Java: String.join(",", items)
来源：http://dali.ydzc1.top/Article/details/gt2bipbspkt.html

Go:   strings.Join(items, ",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vnojfjar.html

Ruby: items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2rkpxnyrk.html

C#:   string.Join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gt2lgpiwusx.html

[E09] 去除所有空白字符
来源：http://dali.zhengqikj.top/Article/details/gt2sefqizsi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fengsongda.top/Article/details/gt2ozkwecyk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qzikmgdx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gt2pdavrwip.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjpuwbnc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gzhubu.top/Article/details/gt2rgekvjdz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xinyue.icu/Article/details/gt2knkkzfmr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.quarkkingdee.top/Article/details/gt2kjpikhtp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gt2wtasvepx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tanke756.top/Article/details/gt2rmcokymk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daxiang520.top/Article/details/gt2dmseejkk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gt2ytxrqjeo.html

JS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2bknjfcjn.html

TS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gt2dfupfszn.html

Java: String.format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gt2kwhdfouy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gt2sxhhdnpp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gt2vybczrrp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sufxvd.cn/Article/details/gt2fnnpgvqm.html

[E11] 反转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2svcxvpks.html

Py:   s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gt2dvzpslkd.html

PHP:  strrev($s);
来源：http://dali.hammf.cn/Article/details/gt2yjnuuvrv.html

JS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2suzwomja.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gt2ozpwmaes.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gt2mpkppecu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pycfn.com/Article/details/gt2wdloditq.html

Ruby: s.reverse
来源：http://dali.jyoumei.cn/Article/details/gt2eddamqlb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gt2tabzdmfp.html

[E12] 统计某字符出现次数
来源：http://dali.havefunace.top/Article/details/gt2mqfrqugt.html

Py:   s.count("a")
来源：http://dali.sysykeji.top/Article/details/gt2zlrjtxhm.html

PHP:  substr_count($s, "a");
来源：http://dali.cashguo.top/Article/details/gt2vpqkrknp.html

JS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gt2xpxdhbur.html

TS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gt2hgobcmcq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dashuyun.cn/Article/details/gt2zhkawzce.html

Go:   strings.Count(s, "a")
来源：http://dali.smart0.xyz/Article/details/gt2uvvugnjg.html

Ruby: s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gt2qfxyosdz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gt2mybieqnl.html

[E13] 逐字符遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2qnogbtqf.html

Py:   for ch in s: print(ch)
来源：http://dali.yangfankeji.com/Article/details/gt2znwwlfzt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gt2hkamnywd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2wtyybxkk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gt2btmhqoxu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2krymmkkw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gt2zazvcpli.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yongpay.top/Article/details/gt2haqnbqhu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vlwhoevy.html

[E14] URL 编码与 Base64
来源：http://dali.dashuyun.cn/Article/details/gt2umnpaxvs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gogol.net.cn/Article/details/gt2pjcskpcs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fzhhl.top/Article/details/gt2unkcozjh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shzxlz.cn/Article/details/gt2odmllsaq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhjlhecf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xziqi.cn/Article/details/gt2mazuiesj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ugcndaxw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gt2kqqbcaef.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yongpay.top/Article/details/gt2jjatcngp.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhixingplan.top/Article/details/gt2nsafunrb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gt2gfdrbufz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.svipenyu.cn/Article/details/gt2xzqnxlfj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2vlbaeipj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pengpengdd.cyou/Article/details/gt2kikrfwot.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cucudq.cn/Article/details/gt2tarhlzel.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fengsongda.top/Article/details/gt2seouveli.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hammf.cn/Article/details/gt2xmqfpmms.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guowangkeji.top/Article/details/gt2pctoqnls.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gt2msissjjd.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fjaqeauq.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gt2fcpnhbav.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gt2kgpcsnkw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gt2uthmjtkh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnqzz.top/Article/details/gt2kswoqixc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gogol.net.cn/Article/details/gt2mlvwqbtq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gt2cdbbodbe.html

C#:   1234567.ToString("N0")
来源：http://dali.hnqzz.top/Article/details/gt2xyhjpony.html

[E17] 首字母大写
来源：http://dali.aizwys.cn/Article/details/gt2ovugicvi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gt2uvvfnzbb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daria6918.cn/Article/details/gt2temytlsf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gzucphcn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gt2hkjwkwmx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gt2nyvvuysh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sweek.top/Article/details/gt2oahcnuxk.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gt2qffyqqxy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigfzy.top/Article/details/gt2miykwmuh.html

[E18] 模板占位符替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2yqnrxwho.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgufenzy.top/Article/details/gt2nvixxmhf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gt2rsomtnzu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2zldmaubr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2gbjajfbq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gt2aarlwmby.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvavxwxr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aizwys.cn/Article/details/gt2yarauann.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hywenlv.cn/Article/details/gt2khruvfnq.html

[E19] 多行文本按行拆分
来源：http://dali.nwbrower.top/Article/details/gt2vgdsdrit.html

Py:   s.splitlines()
来源：http://dali.chenjidiqi.icu/Article/details/gt2nwyfehek.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2xrvgwtsf.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gt2qnfobndt.html

TS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gt2faelufmu.html

Java: s.lines().toList()
来源：http://dali.xinyue.icu/Article/details/gt2bmlpscxi.html

Go:   strings.Split(s, "\n")
来源：http://dali.aizwys.cn/Article/details/gt2fzjfexbh.html

Ruby: s.lines
来源：http://dali.sufxvd.cn/Article/details/gt2ijrjqwpz.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gt2uryrkruc.html

[E20] 判断字符串是否为空
来源：http://dali.havefunace.top/Article/details/gt2dgsmrzmz.html

Py:   if not s:
来源：http://dali.gotoacloud.top/Article/details/gt2jvfyfpfu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dashuyun.cn/Article/details/gt2tcfgflqn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hfpthk.cn/Article/details/gt2kxgxslty.html

TS:   if (s === "") {}
来源：http://dali.yangfankeji.com/Article/details/gt2msixlqjz.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aglfbokr.html

Go:   if s == "" {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2eefhsmne.html

Ruby: if s.empty?
来源：http://dali.sweek.top/Article/details/gt2duoodtfw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ybcxt.top/Article/details/gt2rxqouwzf.html

[E21] 超长截断加省略号
来源：http://dali.haohaochexian.top/Article/details/gt2xqublpvi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenzaomai.com/Article/details/gt2ucetdwau.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2mukrqbni.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2ttixvafa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2qxmmxbax.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2ycumpskj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daria6918.cn/Article/details/gt2qyafoywj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gt2azrbdhsa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2tfirtmhx.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gt2jnrijifi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gt2aacgqvxb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2cmsvsvag.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gt2qnttouej.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gt2lifkuuip.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gt2pyjjrjla.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tanke756.top/Article/details/gt2uehclpep.html

Ruby: s.bytesize;  s.length
来源：http://dali.hywenlv.cn/Article/details/gt2ztdcxnoo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gt2pdhsdrzq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2bmipzxnc.html

F. 文件与目录
来源：http://dali.zhoulong.xyz/Article/details/gt2qrqbjuaj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ufmfmsqa.html

[F01] 读取整个文件
来源：http://dali.hnxiangtu.top/Article/details/gt2xtibccdr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hysaishi.cn/Article/details/gt2xlqhislt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2qeizjubm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jiagoushi.top/Article/details/gt2scpzfvif.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2xvtiwrjw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2yklytval.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gt2bwyadgix.html

Ruby: File.read("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2pvkrupld.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njwxszdr.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gt2mgozttrk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yueranfly.top/Article/details/gt2ypkdwyub.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2whglndex.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gt2nqzzppmw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gt2wxkisxcv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gt2mryrmnww.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gt2umzlvhls.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zycfv.cn/Article/details/gt2hgxexatg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gt2qfkxszdn.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gt2mzcucojv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gogol.net.cn/Article/details/gt2wtrlylhe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gt2nyipebqi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2gwoiljjq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gt2cccjsizn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.bjfxy.top/Article/details/gt2ocovzghd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhiwuduotai.top/Article/details/gt2adcozwcw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2fwveqhpj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzjivtrg.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gt2hoobongd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bsahlubf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dashuyun.cn/Article/details/gt2ewaswqjl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2xejkxjzn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2hukixpgo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aizwys.cn/Article/details/gt2euhkyrlm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tian-w.cn/Article/details/gt2hqdvuvqx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gt2kwazbbuc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yhpvbddq.html

[F05] 判断文件或目录是否存在
来源：http://dali.ydzc1.top/Article/details/gt2lbxoesvi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cucudq.cn/Article/details/gt2xgsgqqqw.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2lpdnkhcn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2zlgnqnwv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2jkobyrbe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2qhjytfgr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gt2tsothdlc.html

Ruby: File.exist?("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2bofxgkrt.html

C#:   File.Exists("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2ravpbojk.html

[F06] 删除文件
来源：http://dali.yangfankeji.com/Article/details/gt2evfpvgmv.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2zleddzne.html

PHP:  unlink("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2sbhrjyoj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2uprnwvum.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nsdwbqub.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gt2uqepnysj.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2cwotpkbi.html

Ruby: File.delete("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2steghvoq.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2sozguibi.html

[F07] 创建目录（含多级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2btckmcit.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gt2pnnyixdc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sufxvd.cn/Article/details/gt2gwqdvcft.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gt2ctaogmlu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gt2ixhsnjkl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gt2voikcrsh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gt2lxexzdvz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pivyursh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gt2stxyioug.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gt2ahrvwulz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hammf.cn/Article/details/gt2omkvajkb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenzaomai.com/Article/details/gt2eybcyhtu.html

JS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2bxrziikm.html

TS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2sivzqnre.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gt2jdbuqtmg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2xoysapoy.html

Ruby: Dir.children("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2wkfqlrul.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2hglopsvk.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gt2cwdwgdgq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2nxcjtqzk.html

PHP:  filesize("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2qgkfaypv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2vaezhrre.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gt2amjdstql.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2ahpmywiy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gt2qqfnhkvd.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2mqfaxpbc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gt2nlcxxtgy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gt2vrdkfmxi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2cvpztjwt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2xbbsiscj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2lihouglo.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2ccvcngrg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gt2madrwvhb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2bjbowgew.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2zxbjpeaj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2dmzhxehy.html

[F11] 复制与移动文件
来源：http://dali.svipenyu.cn/Article/details/gt2negvtwss.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2misjptbv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2dhfxwbte.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2topajjtw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2ojovgyow.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2eggunoth.html


<!-- 参考信息 -->