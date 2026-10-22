代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2aujzvley.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgfzy.top/Article/details/gt2uqlysrsk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gt2byxlhchu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.havefunace.top/Article/details/gt2ipwrnlyl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gt2eqfglnzl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxuanxn.top/Article/details/gt2gqodgyun.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.svipenyu.cn/Article/details/gt2zatyumtn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tanke756.top/Article/details/gt2xehawgcm.html

[E06] 替换子串
来源：http://dali.wangdashe.top/Article/details/gt2ppzochrn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldyzoyhj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gt2ahlqvwwt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2ktkdrdcn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2nmwzjzcr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2efuifjpr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gt2nhgxknki.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2uxqcyqap.html

C#:   s.Replace("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2noylkfep.html

[E07] 按分隔符拆分
来源：http://dali.redwolf501.top/Article/details/gt2umtegnmc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dashuyun.cn/Article/details/gt2pjdznqol.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yongpay.top/Article/details/gt2jacknehg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yvedp.cn/Article/details/gt2jyfwhcbt.html

TS:   s.split(",")
来源：http://dali.jinqigufen.top/Article/details/gt2ztfokboe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj202588.top/Article/details/gt2gtsxtjed.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.aibaodan.cn/Article/details/gt2fdfaihmb.html

Ruby: s.split(",");  s.split
来源：http://dali.chenlongwang.top/Article/details/gt2qrwhwivv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gt2lpayqncg.html

[E08] 数组按分隔符合并
来源：http://dali.guowangkeji.top/Article/details/gt2iijceaoo.html

Py:   ",".join(items)
来源：http://dali.guannengcc.top/Article/details/gt2nkynfnpo.html

PHP:  implode(",", $items);
来源：http://dali.ivvv.top/Article/details/gt2beyazzct.html

JS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2wjllgkzd.html

TS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gt2vectyikl.html

Java: String.join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gt2tmulebky.html

Go:   strings.Join(items, ",")
来源：http://dali.shzxlz.cn/Article/details/gt2astcsxsi.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gt2ozodbhvj.html

C#:   string.Join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gt2iagpylyi.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gt2lbjpcflr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhengqikj.top/Article/details/gt2vgmhemou.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.c1oappe.top/Article/details/gt2sklxawip.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gt2brzihjig.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gt2gjqkmoph.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gt2mlgmjvxw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tianlin.xyz/Article/details/gt2kgbnofso.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2slqkobea.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpdrradv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhixingplan.top/Article/details/gt2kjxfemmn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2lmsydwgp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gt2iapvjtjx.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2qvezluit.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2fpxnfioi.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gt2awikuzep.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gt2wnpvjszf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gt2wlrbfzeq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gotoacloud.top/Article/details/gt2exlhavhb.html

[E11] 反转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2sxmtqith.html

Py:   s[::-1]
来源：http://dali.meibo888.top/Article/details/gt2swffxnhv.html

PHP:  strrev($s);
来源：http://dali.yj20258888.top/Article/details/gt2fyceptgl.html

JS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2nkjkfxqr.html

TS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zpdufodf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.316326.xyz/Article/details/gt2linvjbpy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.svipenyu.cn/Article/details/gt2kxzycwxq.html

Ruby: s.reverse
来源：http://dali.xylfe.cn/Article/details/gt2vbarnbly.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gt2mpoxejrg.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gt2kcsipyzw.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gt2bhwkgfrt.html

PHP:  substr_count($s, "a");
来源：http://dali.snrcjt.cn/Article/details/gt2dgnjqvzp.html

JS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gt2yofjtriz.html

TS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gt2kknyysza.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbhuhfyd.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bkeiydge.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxumrdk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guannengcc.top/Article/details/gt2zxudncrn.html

[E13] 逐字符遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vykgdgws.html

Py:   for ch in s: print(ch)
来源：http://dali.yueranfly.top/Article/details/gt2dvdwanpk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhixingplan.top/Article/details/gt2siveseib.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2baiaalbv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2dcvnyyyq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gt2oimebvvt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nwbrower.top/Article/details/gt2tsircxdz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yueranfly.top/Article/details/gt2dztzezbk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tian-w.cn/Article/details/gt2hdhuwbyc.html

[E14] URL 编码与 Base64
来源：http://dali.yueranfly.top/Article/details/gt2ussgyvqx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcwfxqxv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lgxgjdin.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yonumen.top/Article/details/gt2qbhrfoou.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gt2trcxlrfn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gt2kfndtrji.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gt2lhmmqmvx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hfpthk.cn/Article/details/gt2mbtbcswb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krlbmpll.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhixingplan.top/Article/details/gt2zqpaihgb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2ssijbpav.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gt2todivasm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.redwolf501.top/Article/details/gt2ywfsyyen.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2thggnepo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tianlin.xyz/Article/details/gt2qcxexnht.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuanzx.com/Article/details/gt2aaenxjkb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zycfv.cn/Article/details/gt2esubxyeb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zycfv.cn/Article/details/gt2evybydof.html

[E16] 数字千分位
来源：http://dali.wangdashe.top/Article/details/gt2jcywtlbv.html

Py:   f"{1234567:,}"
来源：http://dali.birdmap.top/Article/details/gt2tyeacclm.html

PHP:  number_format(1234567);
来源：http://dali.jqgufenzy.top/Article/details/gt2smcqhtjn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gt2arljdwvb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gt2pfigctng.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gt2wplbsnzn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnxiangtu.top/Article/details/gt2twvqmzex.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2faslrcob.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnqxctvv.html

[E17] 首字母大写
来源：http://dali.yuanzhike.top/Article/details/gt2ktftfoyl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guowangkeji.top/Article/details/gt2gtqzzqsh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ehwqpu.com/Article/details/gt2kfadjepx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gt2zplilaib.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fuazlgbr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.meibo888.top/Article/details/gt2vtdnsufs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuxming.cn/Article/details/gt2miylwwpd.html

Ruby: s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gt2uankfnmv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cqqwz.cn/Article/details/gt2vddsschl.html

[E18] 模板占位符替换
来源：http://dali.yangfankeji.com/Article/details/gt2mnbsbpou.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqmoljyu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gt2ngvumnva.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gt2xogymcbt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gt2fmvrhnsv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gt2tdxflkrh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2hqwlvfuu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gt2plyklrry.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.snrcjt.cn/Article/details/gt2eihmpazt.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gt2gkikbjev.html

Py:   s.splitlines()
来源：http://dali.ivvv.top/Article/details/gt2fcsnrwdg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2qnxljrtx.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cgumuwxh.html

TS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gt2lctbeadl.html

Java: s.lines().toList()
来源：http://dali.zhixingplan.top/Article/details/gt2dcreszrz.html

Go:   strings.Split(s, "\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2elksoopc.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2cftfnogr.html

C#:   s.Split('\n')
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwtzwwio.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gt2crlkxpeb.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gt2yxrkxlfe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yonumen.top/Article/details/gt2cjgjtsnf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2egcaccdh.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bkudyigd.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2hsgmwxkp.html

Go:   if s == "" {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2vzgqyejm.html

Ruby: if s.empty?
来源：http://dali.svipenyu.cn/Article/details/gt2alsvvwtd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2ylujyonu.html

[E21] 超长截断加省略号
来源：http://dali.chenjidiqi.icu/Article/details/gt2mmwxfzzq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cucudq.cn/Article/details/gt2xrneczyb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2bscmmdlw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2vleeahcm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2agdhpwfm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2fjikwbec.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fzhhl.top/Article/details/gt2usxodogg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2vhenfxil.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2pyjzxakq.html

[E22] 字节长度与字符长度
来源：http://dali.yanxiufei.cn/Article/details/gt2hixjqjwl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2dxbeadry.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2jfikzbup.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gt2ahqovesd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gt2xkjornir.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daria6918.cn/Article/details/gt2rswyexog.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gt2dbhubqfi.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2pogdhewj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.andypj.xyz/Article/details/gt2mntedafb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2vosnlwdn.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gt2pcpseofk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2jvaowqto.html

[F01] 读取整个文件
来源：http://dali.0kj1m.cn/Article/details/gt2xrcsodxz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gt2brwfxsko.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2grufmpjp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangdashe.top/Article/details/gt2kqwjsvea.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gt2jyjbbwjz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2fbkihwqo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aizwys.cn/Article/details/gt2psdlmlxd.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2vznvdebg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2pjahavci.html

[F02] 逐行读取文件
来源：http://dali.fzhhl.top/Article/details/gt2qdqktjmw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.redwolf501.top/Article/details/gt2ojuwiakz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.9152youxi.cn/Article/details/gt2hjdxgfmx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2rdjyuzsm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gt2vtvwwfki.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wtlmlcgw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gt2xnbgzami.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dianchejie.cn/Article/details/gt2gspcsnye.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gt2bvlubamc.html

[F03] 写入文件（覆盖）
来源：http://dali.ppjwa.cn/Article/details/gt2xloqgnvy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangdashe.top/Article/details/gt2pkiovbpg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gt2mmdcpmrk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gt2fomluqon.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gt2lipwlrjf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fengsongda.top/Article/details/gt2smhmcrsq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gt2czvkrajs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hysaishi.cn/Article/details/gt2marbjofo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gt2brejnxcp.html

[F04] 追加写入文件
来源：http://dali.haohaochexian.top/Article/details/gt2pgvlqazz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2tgzogvyy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ydzc1.top/Article/details/gt2ihviknhk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gt2bcoyaden.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gt2ymgzdlyv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhixingplan.top/Article/details/gt2plvhinyj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gt2cgegyndy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnxiangtu.top/Article/details/gt2xdihtuic.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jiagoushi.top/Article/details/gt2fxznfium.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gt2cmgvhiru.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gt2wqywsguz.html

PHP:  file_exists("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2zbtuueak.html

JS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2vgppikdk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2suojdmvj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gt2wpeyoejk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gt2aifokfrg.html

Ruby: File.exist?("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2sibzmkix.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2ymqvpuyu.html

[F06] 删除文件
来源：http://dali.svipenyu.cn/Article/details/gt2vsjbggcg.html

Py:   os.remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2furazfbp.html

PHP:  unlink("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2fvuuhafn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2bfgvplsi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2fjrvgdmt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2aunqjbbt.html

Go:   os.Remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wscjhnae.html

Ruby: File.delete("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2dzjuipko.html

C#:   File.Delete("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2wdnmxghn.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gt2xnlnaddj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gt2cdjsstwn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gt2ftznhkkp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gt2rszjoshb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gt2sufgeshw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gt2tlvjcjtf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ccffvofw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gt2rsfzwpit.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gt2vmpibine.html

[F08] 遍历目录
来源：http://dali.daria6918.cn/Article/details/gt2vpzoibdw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.snrcjt.cn/Article/details/gt2tffaovsv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gt2iuwugiaf.html

JS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gt2xsfpazpc.html

TS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gt2xhpllnmq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gt2gghabjem.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gt2cozavhcx.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gt2swwcrzer.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jlfrpynm.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbehygbf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2nfkypuvl.html

PHP:  filesize("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2fpuwizxx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gt2iwskzvwq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2hzxrtckm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfqnszhm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj202588.top/Article/details/gt2jcxgmlmn.html

Ruby: File.size("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2mdgrggaf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gt2vwrqxmcb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gt2urhujpka.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2itbhemtq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2ruqjqdpq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2pqwjdgkc.html

TS:   path.extname("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2wprlbclk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnqzz.top/Article/details/gt2evsomjsj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2dgzuniri.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2hnzvjqai.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2xeozanlt.html

[F11] 复制与移动文件
来源：http://dali.mhx1999.top/Article/details/gt2tlbvqygg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbtkqmdv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ayeulkmz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2ltwfsdyb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2pmbvrzix.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gt2hcjjpnuq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.bjfxy.top/Article/details/gt2szwokihl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2qasjoorf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gt2funqghbi.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gt2ihhncomo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gt2eufxmklq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.bjfxy.top/Article/details/gt2kflowvqt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gt2cmhvdqmq.html

TS:   // 同上
来源：http://dali.xinyue.icu/Article/details/gt2nrvfuoog.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gt2pyyusqzj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gt2zvacdpep.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuanzx.com/Article/details/gt2umhdtgzl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuanzx.com/Article/details/gt2dwysfynb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2jffboysf.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gt2imgqfzav.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2utlekvgj.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnvkima.html

Py:   class User: pass
来源：http://dali.xylfe.cn/Article/details/gt2nfihjjuw.html

PHP:  class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2umnbknfa.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2sfccmlqb.html

TS:   class User { name: string = ""; }
来源：http://dali.316326.xyz/Article/details/gt2gbkjeaad.html

Java: class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2jchjienr.html

Go:   type User struct { Name string }
来源：http://dali.nanxuanxn.top/Article/details/gt2atrvcbqq.html

Ruby: class User; end
来源：http://dali.gaohongyu789.top/Article/details/gt2srfdxape.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2jhsflrgc.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zfpnqlfh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qsjvgqvb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gt2cyqqhjse.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2cjywdpmn.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gt2cfzyhywn.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2jtuaxdtq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gt2uapuqfge.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.mhx1999.top/Article/details/gt2nasovlps.html

C#:   public User(string name) { Name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zhxpdcwy.html

[G03] 实例属性
来源：http://dali.daxiang520.top/Article/details/gt2kawajbei.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gt2azaqcowx.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2vzhvdwvm.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkkcicf.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2uzrrqegu.html

Java: private String name;
来源：http://dali.zdqjudy.top/Article/details/gt2hvltqryh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gt2oivxeerh.html


<!-- 参考信息 -->