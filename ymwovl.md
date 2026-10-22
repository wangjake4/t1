代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258.top/Article/details/gt2kuqiirgi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigufen.top/Article/details/gt2llvlzxof.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hvvrdoid.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ajdoxvra.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gt2meislgwz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cheryme.top/Article/details/gt2evtqdvca.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gogol.net.cn/Article/details/gt2eexdlfgm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tian-w.cn/Article/details/gt2bgwvceyq.html

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gt2kxqsimbj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hammf.cn/Article/details/gt2sahdkwke.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tanke756.top/Article/details/gt2okvgawmk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2tylcarhs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzvvzll.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2saepvfoc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gt2tzrkeosm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2doeveqpj.html

C#:   s.Replace("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2tsdworxo.html

[E07] 按分隔符拆分
来源：http://dali.c1oappe.top/Article/details/gt2iunjzhyb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258.top/Article/details/gt2htvrrrjs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2qpgojhbl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ykypayzj.html

TS:   s.split(",")
来源：http://dali.guannengcc.top/Article/details/gt2paywkcrs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhixingplan.top/Article/details/gt2hfitacug.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2gyaczwba.html

Ruby: s.split(",");  s.split
来源：http://dali.ydzc1.top/Article/details/gt2qrybxesk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sxryk.cn/Article/details/gt2jcdnsqvo.html

[E08] 数组按分隔符合并
来源：http://dali.yueranfly.top/Article/details/gt2jlrctzdt.html

Py:   ",".join(items)
来源：http://dali.ppjwa.cn/Article/details/gt2aihbppdn.html

PHP:  implode(",", $items);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2myjejmwr.html

JS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gt2pofggewg.html

TS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2lilvlcig.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqiictoo.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxuanxn.top/Article/details/gt2fwylmhko.html

Ruby: items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gt2jkbraoru.html

C#:   string.Join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwryyfhx.html

[E09] 去除所有空白字符
来源：http://dali.fengsongda.top/Article/details/gt2yeqhwaji.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2gykvhesl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2rbeqyiod.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gt2naeoijnj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gt2zkgzcdan.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gt2ygrcdxlt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pnuegvxx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fzhhl.top/Article/details/gt2nwvehayl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cucudq.cn/Article/details/gt2euumxhtj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yonumen.top/Article/details/gt2lkdqdawp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pzdjcrxr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnqzz.top/Article/details/gt2ihrcoaop.html

JS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oascnjzt.html

TS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gt2vzygznck.html

Java: String.format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gt2jyjzfgir.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xtbdzehn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gt2uzmvajge.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gotoacloud.top/Article/details/gt2ovxzhvyz.html

[E11] 反转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2duicoujb.html

Py:   s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gt2sihdzdqo.html

PHP:  strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xdxbzwep.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2thueixtp.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gt2jlbggjxg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.andypj.xyz/Article/details/gt2jzllfkpf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yongpay.top/Article/details/gt2oyzyaeog.html

Ruby: s.reverse
来源：http://dali.yvedp.cn/Article/details/gt2jzugczuf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gt2wrfdsrud.html

[E12] 统计某字符出现次数
来源：http://dali.gzhubu.top/Article/details/gt2swxdnybr.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gt2ofaksgus.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gt2cgvkudfu.html

JS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gt2xtyifiiv.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gt2yogxwbqb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gt2dvttwbjf.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258.top/Article/details/gt2vmwlxjsy.html

Ruby: s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gt2uffktghu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gt2wbaxxoll.html

[E13] 逐字符遍历
来源：http://dali.dashuyun.cn/Article/details/gt2mzqjbrua.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gt2kqvvlwzb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dianchejie.cn/Article/details/gt2wikrouhq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2phtdivyd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2jflivmjm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tanke756.top/Article/details/gt2jqdnjjsd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yvedp.cn/Article/details/gt2mtjdtios.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gt2fsijivco.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2qyocozzk.html

[E14] URL 编码与 Base64
来源：http://dali.zhengqikj.top/Article/details/gt2uwcqejmt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jlsjyb.cn/Article/details/gt2obiuybcc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2xcpuicnn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jiagoushi.top/Article/details/gt2roskkrtn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.smart0.xyz/Article/details/gt2qhaswaso.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrvnnhrj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gt2jrgksrvl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jyoumei.cn/Article/details/gt2esqmhacj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gogol.net.cn/Article/details/gt2vtoscfro.html

[E15] HTML 转义 / 反转义
来源：http://dali.xylfe.cn/Article/details/gt2eyzgkhur.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gotoacloud.top/Article/details/gt2ifobwcke.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2dcvqevuc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2jvhkncgj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gt2pbpyagtj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.redwolf501.top/Article/details/gt2kmicomko.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuanzx.com/Article/details/gt2rovadryq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zycfv.cn/Article/details/gt2ylvbcuoz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lxqrlirs.html

[E16] 数字千分位
来源：http://dali.hywenlv.cn/Article/details/gt2veaxygaj.html

Py:   f"{1234567:,}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxgbolvt.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlloxlq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gt2ghcgsots.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gt2yrgpnlxc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fengsongda.top/Article/details/gt2owvllnaw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gt2xdixxuqi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dianchejie.cn/Article/details/gt2diwhibox.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxuanxn.top/Article/details/gt2pgdjabzi.html

[E17] 首字母大写
来源：http://dali.zdqjudy.top/Article/details/gt2ksefyaih.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yvedp.cn/Article/details/gt2qndhqqmp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zodvsjin.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2ckarcgaq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gt2thzfxwof.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gzhubu.top/Article/details/gt2ytgstojr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.iojbl.cn/Article/details/gt2caluktsm.html

Ruby: s.capitalize
来源：http://dali.mhx1999.top/Article/details/gt2bfihlsrs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gt2imucsevd.html

[E18] 模板占位符替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kmeqxzzh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guannengcc.top/Article/details/gt2jmwjlrdy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.birdmap.top/Article/details/gt2uhnklmrb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2abahnhte.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2tpqqsuks.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2nytwuhxw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gt2tpsepwcn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2yxoewuzf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gt2cgzeotja.html

[E19] 多行文本按行拆分
来源：http://dali.zycfv.cn/Article/details/gt2gwfoxezg.html

Py:   s.splitlines()
来源：http://dali.yj20258888.top/Article/details/gt2wmkdqujj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2nhepdefa.html

JS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gt2ccwhgzdt.html

TS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gt2owfagxuv.html

Java: s.lines().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxzkowug.html

Go:   strings.Split(s, "\n")
来源：http://dali.cdnleiting.top/Article/details/gt2kbzsgpim.html

Ruby: s.lines
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdqnqoxc.html

C#:   s.Split('\n')
来源：http://dali.shzxlz.cn/Article/details/gt2drvhomdk.html

[E20] 判断字符串是否为空
来源：http://dali.cucudq.cn/Article/details/gt2zzamhlsz.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gt2ztkrtnjd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yvedp.cn/Article/details/gt2eyxanrob.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xylfe.cn/Article/details/gt2rpuvivls.html

TS:   if (s === "") {}
来源：http://dali.haohaochexian.top/Article/details/gt2hhcuulvn.html

Java: if (s.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ecyvuphd.html

Go:   if s == "" {}
来源：http://dali.yanxiufei.cn/Article/details/gt2eivjqtsg.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gt2fmpciihi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2rbckvvan.html

[E21] 超长截断加省略号
来源：http://dali.xuetiantiany.cn/Article/details/gt2llynyzfz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj202588.top/Article/details/gt2qqwespyf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj202588.top/Article/details/gt2vxwfrofv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2bglpatrd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2fppyihnb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhbnzuxw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuxming.cn/Article/details/gt2qntsvvrv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2exiuagrm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2iclssfgv.html

[E22] 字节长度与字符长度
来源：http://dali.nwbrower.top/Article/details/gt2qinczdxy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ofteklbw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2hwdozvqu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gt2fvmifuer.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gt2gnbwmwsh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgfzy.top/Article/details/gt2vizcohjq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shangyingyoupin.top/Article/details/gt2ryhkthgk.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258.top/Article/details/gt2ismkzxlb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ivvv.top/Article/details/gt2rupwtubx.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2fhjutjdd.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2wbdiyphk.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2gpimvxan.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gt2hwcszijy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gt2gzarpdrb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sweek.top/Article/details/gt2cinybman.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hfpthk.cn/Article/details/gt2atjymgzw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcjsdopp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gt2oqvalhbt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fengsongda.top/Article/details/gt2jcpcsuub.html

Ruby: File.read("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2otsvcnvs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2xvmlhvte.html

[F02] 逐行读取文件
来源：http://dali.cdnleiting.top/Article/details/gt2kiekqrau.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.316326.xyz/Article/details/gt2vhvnvett.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jianghu66.top/Article/details/gt2pnmytdpd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gt2penhwnzb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gt2qsckrnjg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gt2cpyqfrii.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnqzz.top/Article/details/gt2rqpaahwn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxuanxn.top/Article/details/gt2klnysddf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gt2midssicq.html

[F03] 写入文件（覆盖）
来源：http://dali.meibo888.top/Article/details/gt2reundxgb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zdqjudy.top/Article/details/gt2cjhisvrr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gt2kdfzzesm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2yucuhsua.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gt2kdpmpzqx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cheryme.top/Article/details/gt2vjpndmgz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ebddcapg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hfpthk.cn/Article/details/gt2qwarvxni.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gt2taktiquo.html

[F04] 追加写入文件
来源：http://dali.yj20258.top/Article/details/gt2hgpyaott.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gt2ttqzlpbt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxinkj.top/Article/details/gt2gexgiizp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gt2wopswhbo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gt2vymkhuhn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aizwys.cn/Article/details/gt2mzmfcslb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yvedp.cn/Article/details/gt2feldusfn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gt2yuenhheq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gt2gsezbuev.html

[F05] 判断文件或目录是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlaftild.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tanke756.top/Article/details/gt2pfyxztco.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2yrjmzijx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2opuwkgwi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2wygsgjmi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vttxkyrw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gt2kjqzpvlr.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2gnkjpzjy.html

C#:   File.Exists("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2tghzbkuf.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gt2qqsilpvz.html

Py:   os.remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2yokwtgaa.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2bcefmook.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2bkoaccye.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2afxchezm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2syhgiblb.html

Go:   os.Remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2ztjwzzck.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2adpfpcxw.html

C#:   File.Delete("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2iccbwyrz.html

[F07] 创建目录（含多级）
来源：http://dali.sweek.top/Article/details/gt2ywmtqtse.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.c1oappe.top/Article/details/gt2txxdvkpq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxinkj.top/Article/details/gt2qjaxpgpy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gt2kcjsruhh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gt2toffzerd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenlongwang.top/Article/details/gt2zhjfqjjz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhongyouzk.top/Article/details/gt2khytlcnm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lahgbgpz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gt2mxpcwahn.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdrimsap.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zycfv.cn/Article/details/gt2azyxkvqm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xylfe.cn/Article/details/gt2waduhuwl.html

JS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gt2pblwnvnt.html

TS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kpbsiiqz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gt2apllrhzb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2fqmmtzzm.html

Ruby: Dir.children("dir")
来源：http://dali.ybcxt.top/Article/details/gt2qmjzyixs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2tlmphivq.html

[F09] 获取文件大小
来源：http://dali.0kj1m.cn/Article/details/gt2qfqemwsb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2bylyfdxz.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2lbgkxbsh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gt2zkbbnrcf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gt2qmvjoskc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2nxlpxjbd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nwbrower.top/Article/details/gt2uchndvpj.html

Ruby: File.size("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxkxgqxn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ybcxt.top/Article/details/gt2wmgtbffv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gaohongyu789.top/Article/details/gt2seujwdml.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2pjnxyodq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yonumen.top/Article/details/gt2frbflods.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2jkbqnhnc.html

TS:   path.extname("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2owbgtdfe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnxiangtu.top/Article/details/gt2nneuklji.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2pgveexzp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2otkjyumw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wkienohd.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gt2ivgkmcpn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2kidjvkbu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gt2ooaxqfyy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2zpkzllvq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2hlzwldid.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2tfspicnv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fzhhl.top/Article/details/gt2psbueuvo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2lbpvdtsl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tian-w.cn/Article/details/gt2vlyihiot.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gt2pkrxnwri.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnqzz.top/Article/details/gt2fcowajbb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gt2icuyzvfk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gt2pjvfqott.html

TS:   // 同上
来源：http://dali.tanke756.top/Article/details/gt2owibhwrx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gt2ommfbxrc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfbxalvx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gt2izuaeilb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gt2irwoyohs.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2iddmsvpp.html

G. 面向对象
来源：http://dali.tianlin.xyz/Article/details/gt2lcmvigky.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2qothqitm.html

[G01] 定义类
来源：http://dali.zhiwuduotai.top/Article/details/gt2tzabzfjo.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gt2oimjoiil.html

PHP:  class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2tfrgpbru.html

JS:   class User {}
来源：http://dali.sysykeji.top/Article/details/gt2nnzofahr.html

TS:   class User { name: string = ""; }
来源：http://dali.xinyue.icu/Article/details/gt2kqkynzih.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2jqgevdlj.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gt2uhjfwotq.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gt2vurmozst.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gt2qgbofrkk.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gt2jvmupnew.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhongyouzk.top/Article/details/gt2jovrjnsw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sufxvd.cn/Article/details/gt2ibjddrfa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2fwnibrsf.html

TS:   constructor(public name: string) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2xylhprsp.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gt2hkjpjvvv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gt2xmcvbgen.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cucudq.cn/Article/details/gt2rqwqyzpo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2wbnpkfkw.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gt2tihjenah.html

Py:   self.name = "x"
来源：http://dali.chenlongwang.top/Article/details/gt2tadqawaq.html

PHP:  public string $name = "x";
来源：http://dali.smart0.xyz/Article/details/gt2hwggwhuw.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2nfkxzrlq.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2yqgasdsm.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gt2ecxohgak.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pycfn.com/Article/details/gt2pcelqbvy.html


<!-- 参考信息 -->