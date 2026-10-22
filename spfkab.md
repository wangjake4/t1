代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.feifeiyinyue.top/Article/details/gt2rgaujabe.html

[E03] 截取子串
来源：http://dali.sysykeji.top/Article/details/gt2qgrrlvaw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guowangkeji.top/Article/details/gt2wpvvxkyy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2euttfrcr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2rgszzcaz.html

TS:   s.slice(1, 4)
来源：http://dali.jianghu66.top/Article/details/gt2hjplisun.html

Java: s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gt2reunfuit.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2miruprti.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2etzjqllp.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aiovqbdg.html

[E04] 查找子串位置
来源：http://dali.dashuyun.cn/Article/details/gt2zqbbjcgb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ybcxt.top/Article/details/gt2tmhomjhi.html

PHP:  strpos($s, "x");
来源：http://dali.havefunace.top/Article/details/gt2tztmwlpi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wrrrrkmf.html

TS:   s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbyjskyx.html

Java: s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gt2qxnbmjik.html

Go:   strings.Index(s, "x")
来源：http://dali.zhengqikj.top/Article/details/gt2hpnzjmfd.html

Ruby: s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2pdlfgobf.html

C#:   s.IndexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gt2uoohcweb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xylfe.cn/Article/details/gt2lfaiedcw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.316326.xyz/Article/details/gt2jfxmblgs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ehwqpu.com/Article/details/gt2gatmassw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gt2jktmzang.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yvedp.cn/Article/details/gt2drhzesno.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gt2lpatotbr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuanzhike.top/Article/details/gt2vnghwvqy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guannengcc.top/Article/details/gt2mwhqwkyl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfpbysec.html

[E06] 替换子串
来源：http://dali.gaohongyu789.top/Article/details/gt2sbnbeazy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gt2vkyvlssx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2hsjvewpv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2vcdkoows.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2trhcrmkd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wlailvhy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yahqvcmr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2mlfiwbjs.html

C#:   s.Replace("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttzpotaq.html

[E07] 按分隔符拆分
来源：http://dali.sufxvd.cn/Article/details/gt2zyraqzxu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wlawzxmv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gt2ktwtnsnp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.meibo888.top/Article/details/gt2tfkiyhza.html

TS:   s.split(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2zresblsx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zycfv.cn/Article/details/gt2uhfbqblx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yonumen.top/Article/details/gt2tkdhtzhn.html

Ruby: s.split(",");  s.split
来源：http://dali.ivvv.top/Article/details/gt2xhjepqyh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenjidiqi.icu/Article/details/gt2odxtdijd.html

[E08] 数组按分隔符合并
来源：http://dali.jiagoushi.top/Article/details/gt2hpxzauzj.html

Py:   ",".join(items)
来源：http://dali.gogol.net.cn/Article/details/gt2mqnmcbhy.html

PHP:  implode(",", $items);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qlterwrv.html

JS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gt2caxejpdp.html

TS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gt2zpwxdgwj.html

Java: String.join(",", items)
来源：http://dali.zycfv.cn/Article/details/gt2biayhplm.html

Go:   strings.Join(items, ",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ircfulsy.html

Ruby: items.join(",")
来源：http://dali.andypj.xyz/Article/details/gt2reemhplj.html

C#:   string.Join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gt2mrowpsmh.html

[E09] 去除所有空白字符
来源：http://dali.nanxinkj.top/Article/details/gt2blbwaouj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shuidangran.top/Article/details/gt2mcncwvnm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2ckpwwgwr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gt2ttienfow.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gt2yfjarrzb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gt2hcxmzrnr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qgrohdxb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gt2zjpvgrgu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gt2folpkagd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpauebk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2tkfodsmb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daxiang520.top/Article/details/gt2itjuqgre.html

JS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gt2ypphamwr.html

TS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gt2nzlhobez.html

Java: String.format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gwjyjtwv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2imvpgidm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2brpcvgzm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuanzhike.top/Article/details/gt2hwrrafpq.html

[E11] 反转字符串
来源：http://dali.xuanzx.com/Article/details/gt2uwxkxgud.html

Py:   s[::-1]
来源：http://dali.yj20258888.top/Article/details/gt2gkuolphx.html

PHP:  strrev($s);
来源：http://dali.fengsongda.top/Article/details/gt2zogrnnmu.html

JS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2dmdmrebr.html

TS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gt2gcafyajw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gzhubu.top/Article/details/gt2qixukith.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tian-w.cn/Article/details/gt2dsjkenoj.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2fxbndtyo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gt2xwlvzcih.html

[E12] 统计某字符出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmlnijsx.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gt2iqohqsih.html

PHP:  substr_count($s, "a");
来源：http://dali.zhiwuduotai.top/Article/details/gt2jkutotpm.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gt2wfuewksn.html

TS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gt2uuyrgqaw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubinigrn.html

Go:   strings.Count(s, "a")
来源：http://dali.gogol.net.cn/Article/details/gt2zljtvqob.html

Ruby: s.count("a")
来源：http://dali.nwbrower.top/Article/details/gt2dwmhwsnz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gt2jxhhwpza.html

[E13] 逐字符遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2tfkeiias.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gt2ubuvcjya.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nlokwnkg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gt2qtzqkfre.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2yqgwccyw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zdqjudy.top/Article/details/gt2hymuqofo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cashguo.top/Article/details/gt2brlulfat.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xinyue.icu/Article/details/gt2mbmhdbsg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2hkjiobus.html

[E14] URL 编码与 Base64
来源：http://dali.haohaochexian.top/Article/details/gt2wasrhzca.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.havefunace.top/Article/details/gt2nrpkhwyb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yangfankeji.com/Article/details/gt2uphgjnka.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fengsongda.top/Article/details/gt2qkbihaok.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ivvv.top/Article/details/gt2rwzfeklt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oitijsik.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gt2tlahyahc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gt2ffnuitdp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yongpay.top/Article/details/gt2bruoklfi.html

[E15] HTML 转义 / 反转义
来源：http://dali.xziqi.cn/Article/details/gt2baxbzalo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2zmhyxrks.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.redwolf501.top/Article/details/gt2qnmafyhz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.havefunace.top/Article/details/gt2rwqjzzgk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2wcbclych.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tanke756.top/Article/details/gt2abhveivp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2cgnvtspf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tian-w.cn/Article/details/gt2yxsoddjb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shzxlz.cn/Article/details/gt2rgzomlok.html

[E16] 数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gt2ptlfbbvw.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gt2guzlmjmt.html

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gt2gvbakajx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gt2keeuhjcu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gt2jopfblrf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gt2xgownmgo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hammf.cn/Article/details/gt2gjjvbeee.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hfpthk.cn/Article/details/gt2yyptodqv.html

C#:   1234567.ToString("N0")
来源：http://dali.sweek.top/Article/details/gt2ejrxilll.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gt2gnhvhdtt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dianchejie.cn/Article/details/gt2odjsuevq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2chsxgmup.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gt2lvqudman.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gt2ilnlmjdg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgkykmri.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gt2wermmodk.html

Ruby: s.capitalize
来源：http://dali.yuanzhike.top/Article/details/gt2grsfsaxn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ydzc1.top/Article/details/gt2xjixlmxg.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqpomkte.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gt2liziwetj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hammf.cn/Article/details/gt2jgjjqhkc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gt2sjddtzvm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gt2fsquewfd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2wzzfbhez.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sweek.top/Article/details/gt2htesmowc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhongyouzk.top/Article/details/gt2vcuigafu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.kuanghao11.cn/Article/details/gt2ywgvknel.html

[E19] 多行文本按行拆分
来源：http://dali.gogol.net.cn/Article/details/gt2cysrbyla.html

Py:   s.splitlines()
来源：http://dali.birdmap.top/Article/details/gt2nkwgcdhz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2xtjdivnf.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akkfbqwm.html

TS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gt2fcosryqe.html

Java: s.lines().toList()
来源：http://dali.zdqjudy.top/Article/details/gt2msotwhpo.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258888.top/Article/details/gt2mjfbvafa.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gt2vcoqytdw.html

C#:   s.Split('\n')
来源：http://dali.tianlin.xyz/Article/details/gt2owrsvnda.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gt2dlhcawpk.html

Py:   if not s:
来源：http://dali.nanxuanxn.top/Article/details/gt2lzyzmxrh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fzhhl.top/Article/details/gt2jlmkfica.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dianchejie.cn/Article/details/gt2hggxmgqu.html

TS:   if (s === "") {}
来源：http://dali.nwbrower.top/Article/details/gt2eugyqjkm.html

Java: if (s.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gt2jfwplise.html

Go:   if s == "" {}
来源：http://dali.zdqjudy.top/Article/details/gt2bkucytya.html

Ruby: if s.empty?
来源：http://dali.yj202588.top/Article/details/gt2xbgjejpf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gt2wmtxmlkc.html

[E21] 超长截断加省略号
来源：http://dali.chenzaomai.com/Article/details/gt2warmzvfy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gt2eebbvboq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2znzovans.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2xnvpiuhl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2kacgufzl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2pwriukwa.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258888.top/Article/details/gt2aixmtcbx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2icjgrjyk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2kgtjerze.html

[E22] 字节长度与字符长度
来源：http://dali.hnxiangtu.top/Article/details/gt2zuucbkuv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nwbrower.top/Article/details/gt2qghekusx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2gdvmffhr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2cdwmidme.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gt2mspqvhvn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gt2onqkkuar.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xinyue.icu/Article/details/gt2zmxlvwcb.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gt2tdyeacrf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgfzy.top/Article/details/gt2gvfqjpky.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2lrtlsunm.html

F. 文件与目录
来源：http://dali.jianghu66.top/Article/details/gt2gvkcnjan.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2bwnzhmbt.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nplhcwak.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jyoumei.cn/Article/details/gt2fjgzubys.html

PHP:  file_get_contents("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2qxgdmzas.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shuidangran.top/Article/details/gt2ckuzssln.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gt2juoxlvut.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2gllgqzgu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yanxiufei.cn/Article/details/gt2nesghctz.html

Ruby: File.read("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ujmecxdp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2mmuoqlsl.html

[F02] 逐行读取文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjpzpoqi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ybcxt.top/Article/details/gt2uxrxwyiy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hysaishi.cn/Article/details/gt2ykxzmfcw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gt2cmirewnj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gt2jwqnhrfm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gt2rvpafjjs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bgnpyiip.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnljvhue.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gt2hqeizzzc.html

[F03] 写入文件（覆盖）
来源：http://dali.sweek.top/Article/details/gt2wtsewspb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gt2jxyxnhge.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2buspuahf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gt2xsvbovrl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gt2urwxgdoq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dianchejie.cn/Article/details/gt2vwzenqrc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kipcfkwh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gogol.net.cn/Article/details/gt2nrpbbqss.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gt2wgcbysyq.html

[F04] 追加写入文件
来源：http://dali.xuanzx.com/Article/details/gt2txxfiorp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2rwiczept.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhongyouzk.top/Article/details/gt2xtbktqxz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2kkqvugci.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gt2rlqljinm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gotoacloud.top/Article/details/gt2xjboxdoh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tianlin.xyz/Article/details/gt2rmkhsxje.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2uccsozna.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gt2qwdeioyi.html

[F05] 判断文件或目录是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2ffvlixuj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gt2fgtldgxw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2skhveuet.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2gnaksuzv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ucujdolu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2imgovryn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gt2xgyjnsrn.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2prqekvsa.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2fqfkijjm.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gt2bzazotqj.html

Py:   os.remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2savdagbd.html

PHP:  unlink("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhaboyqb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jrxxpcqx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2yjypsbva.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2vegqqmhj.html

Go:   os.Remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2iqzboxbz.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2vdhnfbqz.html

C#:   File.Delete("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2teeufeti.html

[F07] 创建目录（含多级）
来源：http://dali.jqgufenzy.top/Article/details/gt2nyqcrjri.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gt2jmkrsomx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.9152youxi.cn/Article/details/gt2hdcxynzx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gt2rzvrtkho.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gt2ozdkxoym.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gt2dgxznoif.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gt2deqjqutt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gt2ootehcpy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkeqbqhf.html

[F08] 遍历目录
来源：http://dali.sxryk.cn/Article/details/gt2rsnnfndr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hywenlv.cn/Article/details/gt2uwoltvhw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ivvv.top/Article/details/gt2hadmnocp.html

JS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2ikqpiplq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2askgdbmc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gt2kzwbegzi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2krkyhmwe.html

Ruby: Dir.children("dir")
来源：http://dali.ybcxt.top/Article/details/gt2lyjvesmc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gt2bxreaaxd.html

[F09] 获取文件大小
来源：http://dali.smart0.xyz/Article/details/gt2lfdocfqz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2qusfsehi.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2jenvfpdi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtjhyszl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gt2qubzykze.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2erxtjgoo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gt2rjxmvkch.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2glbcyygk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jianghu66.top/Article/details/gt2viuakliw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gt2iptzfnkc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2vchejkhy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2iveupkhf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2dwrtqppn.html

TS:   path.extname("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2lxyjyoks.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gt2tajidjke.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2gfiooiud.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2ptnuqakx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2npihccqy.html

[F11] 复制与移动文件
来源：http://dali.sufxvd.cn/Article/details/gt2gyaolpze.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2jpdyznqb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2frwzpqow.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2bqpnwdmq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2qebpphoc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2umspknby.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rwikubsp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2hrrsonjo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gt2wyxwgzhj.html

[F12] CSV 读写
来源：http://dali.kuanghao11.cn/Article/details/gt2tnqcbnsm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.redwolf501.top/Article/details/gt2jxfprhvs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gt2fvrnuuec.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gt2vjtajqns.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2amukaekn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shangyingyoupin.top/Article/details/gt2drgcmgea.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gt2ykcregrc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aibaodan.cn/Article/details/gt2nrkqazqp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.0kj1m.cn/Article/details/gt2xmoceshq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2oeiprjgn.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gt2sjwwfuca.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2tzmndvxw.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2uplsjaus.html

Py:   class User: pass
来源：http://dali.aibaodan.cn/Article/details/gt2yvdpcidv.html

PHP:  class User {}
来源：http://dali.daxiang520.top/Article/details/gt2ufktxaqz.html

JS:   class User {}
来源：http://dali.wangdashe.top/Article/details/gt2bkmvcehu.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2djrxclgx.html


<!-- 参考信息 -->