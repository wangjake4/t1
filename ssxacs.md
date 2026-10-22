代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cashguo.top/Article/details/gt2vxjwtuni.html

[E03] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vzdcyijk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dytdzgwl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gt2pwpwtpix.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gt2msqssmbu.html

TS:   s.slice(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2bmwifrcg.html

Java: s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gt2kvawwdqp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yvedp.cn/Article/details/gt2ougukoxz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gt2nokbwrvo.html

C#:   s.Substring(1, 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jjeyakkw.html

[E04] 查找子串位置
来源：http://dali.yanxiufei.cn/Article/details/gt2yejilywc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gt2mfuzrmqi.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gt2plllkxhh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fzhhl.top/Article/details/gt2mkwanqys.html

TS:   s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gt2duenafrv.html

Java: s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gt2bfcgahgq.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gt2pasdoemt.html

Ruby: s.index("x")
来源：http://dali.ydzc1.top/Article/details/gt2efpcofdj.html

C#:   s.IndexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xesmmoen.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.snrcjt.cn/Article/details/gt2hfilufzq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dashuyun.cn/Article/details/gt2jajrsxdq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sufxvd.cn/Article/details/gt2mqfkgscv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gt2njfzgrec.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.mhx1999.top/Article/details/gt2tpygozix.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gt2tfkepbsy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tetvieiw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2kdyuomzp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jianghu66.top/Article/details/gt2jctcrmgv.html

[E06] 替换子串
来源：http://dali.hongshengwenyu.top/Article/details/gt2ufpojmxt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gt2watgpynn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guowangkeji.top/Article/details/gt2mujoxqiq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2ladivdhe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2zxrsczmc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2fqxmxyzm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gt2ciysvksy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2udcpdekf.html

C#:   s.Replace("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2iuxfarpq.html

[E07] 按分隔符拆分
来源：http://dali.yuxming.cn/Article/details/gt2sgfitrqf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangshuangyany.cn/Article/details/gt2hasyqewm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2frznqttk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gt2uiedcqhv.html

TS:   s.split(",")
来源：http://dali.jianghu66.top/Article/details/gt2qxivpizv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.redwolf501.top/Article/details/gt2yyvebkla.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2dcaytmui.html

Ruby: s.split(",");  s.split
来源：http://dali.pycfn.com/Article/details/gt2paotobzq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cucudq.cn/Article/details/gt2jkcyqqcn.html

[E08] 数组按分隔符合并
来源：http://dali.andypj.xyz/Article/details/gt2tkzvvhbd.html

Py:   ",".join(items)
来源：http://dali.iojbl.cn/Article/details/gt2xapfgfsh.html

PHP:  implode(",", $items);
来源：http://dali.jinqigufen.top/Article/details/gt2gcyogjqr.html

JS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gt2gqcdrfek.html

TS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gt2vsmuwymw.html

Java: String.join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gt2tqmyaerv.html

Go:   strings.Join(items, ",")
来源：http://dali.xinyue.icu/Article/details/gt2ijalktsa.html

Ruby: items.join(",")
来源：http://dali.smart0.xyz/Article/details/gt2dmsiuudg.html

C#:   string.Join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gt2fqfrmzap.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gt2oahzoogm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yangfankeji.com/Article/details/gt2djqbggnb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2rabsqupu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2enpuelxw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yamdrcdv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.iojbl.cn/Article/details/gt2lukrbtbl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hammf.cn/Article/details/gt2dlfykpkq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuanzhike.top/Article/details/gt2odsgbsfr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xinyue.icu/Article/details/gt2jkdqsptv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjfdfzep.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xziqi.cn/Article/details/gt2kyykzpql.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxinkj.top/Article/details/gt2yrcfajhv.html

JS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gt2hunlpuuz.html

TS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2ktggsshp.html

Java: String.format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2ceicydxx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gt2tcwjaicj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gt2elcvrytl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigfzy.top/Article/details/gt2wjwvnqnb.html

[E11] 反转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2hgcampds.html

Py:   s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2voljgpwe.html

PHP:  strrev($s);
来源：http://dali.birdmap.top/Article/details/gt2ehvsazgr.html

JS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gt2zszdhgsc.html

TS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2eulwhuud.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2gxismxds.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigufen.top/Article/details/gt2opozyzis.html

Ruby: s.reverse
来源：http://dali.hnqzz.top/Article/details/gt2xpsbbbqc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gt2qdtwfjmh.html

[E12] 统计某字符出现次数
来源：http://dali.cheryme.top/Article/details/gt2anhrkgsc.html

Py:   s.count("a")
来源：http://dali.cucudq.cn/Article/details/gt2nbljnezz.html

PHP:  substr_count($s, "a");
来源：http://dali.andypj.xyz/Article/details/gt2rwhfvqum.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gt2iaiofetq.html

TS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ikqgqbha.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.andypj.xyz/Article/details/gt2hlnxlypt.html

Go:   strings.Count(s, "a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2turjgfvy.html

Ruby: s.count("a")
来源：http://dali.aibaodan.cn/Article/details/gt2svpvdvum.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gt2skdjzsgx.html

[E13] 逐字符遍历
来源：http://dali.haohaochexian.top/Article/details/gt2lecjhaek.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ituazdab.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dianchejie.cn/Article/details/gt2cryyzyii.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gt2dotddege.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gt2zxcwhaaq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cheryme.top/Article/details/gt2xgacyktn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhixingplan.top/Article/details/gt2thchrybk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zdqjudy.top/Article/details/gt2aadqhyvg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gt2dkgynjrq.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gt2qhjlitsd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258.top/Article/details/gt2qvcqpotb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhixingplan.top/Article/details/gt2addmwamy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rqrqdxui.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shuidangran.top/Article/details/gt2fpyhaczy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqcczav.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sweek.top/Article/details/gt2tfwfzwpw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnqzz.top/Article/details/gt2iolfnlos.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.smart0.xyz/Article/details/gt2dahwkhht.html

[E15] HTML 转义 / 反转义
来源：http://dali.haohaochexian.top/Article/details/gt2rvmaqpfu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2psvqrwok.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gt2nngrdirq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gt2igwogmfk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gt2ltjztovc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangdashe.top/Article/details/gt2kliruqmv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2fiiqoioj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgfzy.top/Article/details/gt2tqkwodrj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cdnleiting.top/Article/details/gt2pvbwepnc.html

[E16] 数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gt2zmkqfiuc.html

Py:   f"{1234567:,}"
来源：http://dali.yonumen.top/Article/details/gt2jqzebgbg.html

PHP:  number_format(1234567);
来源：http://dali.ivvv.top/Article/details/gt2igihqqzc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gt2hzlgnybe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gt2uvjrmwqs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gt2wlbepqdh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnxiangtu.top/Article/details/gt2ombsuwlb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daxiang520.top/Article/details/gt2xnptkxfm.html

C#:   1234567.ToString("N0")
来源：http://dali.xinyue.icu/Article/details/gt2hlruvatn.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2shpqwmjk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.snrcjt.cn/Article/details/gt2npbpryhc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tdpglxxu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gt2lnxbbsea.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajhmonzy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fengsongda.top/Article/details/gt2bjjklain.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yueranfly.top/Article/details/gt2qpmfidzy.html

Ruby: s.capitalize
来源：http://dali.0kj1m.cn/Article/details/gt2qbifrdbm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2usvwuwnj.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gt2qmbpbvhv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258.top/Article/details/gt2kujqgkiu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xziqi.cn/Article/details/gt2nlgisiws.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gt2tjoiasgk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gt2zvgncdbs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sohfphwb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aizwys.cn/Article/details/gt2kdxafpem.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.redwolf501.top/Article/details/gt2izoljyds.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yvedp.cn/Article/details/gt2tqjpieyu.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gt2ogrkqshs.html

Py:   s.splitlines()
来源：http://dali.yuxming.cn/Article/details/gt2iqgcgedn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj202588.top/Article/details/gt2ssifroxj.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gt2vkiorelz.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wtbgkbhr.html

Java: s.lines().toList()
来源：http://dali.bjfxy.top/Article/details/gt2jgyibsai.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2obplaeen.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gt2syhapolr.html

C#:   s.Split('\n')
来源：http://dali.cucudq.cn/Article/details/gt2jucaepvz.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krcwhfxf.html

Py:   if not s:
来源：http://dali.sxryk.cn/Article/details/gt2adlncyke.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gt2wqbljcvu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.svipenyu.cn/Article/details/gt2xrgfoepg.html

TS:   if (s === "") {}
来源：http://dali.cdnleiting.top/Article/details/gt2aoqqfdud.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gt2ycwnyfnh.html

Go:   if s == "" {}
来源：http://dali.shzxlz.cn/Article/details/gt2aowpyzxr.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gt2yhupqzer.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tigifyva.html

[E21] 超长截断加省略号
来源：http://dali.jyoumei.cn/Article/details/gt2upcxwwvs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aizwys.cn/Article/details/gt2jqkkosnz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2cugbfiiv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2udjuoqdu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2cbckhgwt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2wbdvvgjv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hysaishi.cn/Article/details/gt2gvfrufxo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2qzyqcyra.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2fwphpkuu.html

[E22] 字节长度与字符长度
来源：http://dali.ppjwa.cn/Article/details/gt2azreqzff.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2uvwkymes.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2exqpwewf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjzubwc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2mtzmhckt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gt2sqhxvuaf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dianchejie.cn/Article/details/gt2bnydfvor.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gt2uslgqxke.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuanzx.com/Article/details/gt2ekiwckaj.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2icwlarkt.html

F. 文件与目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2srahrqtk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2dxuaovnb.html

[F01] 读取整个文件
来源：http://dali.c1oappe.top/Article/details/gt2rpaibfnx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.snrcjt.cn/Article/details/gt2nttuoald.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2qtxvgtip.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gt2cdosvcwo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gt2uenpatfy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2cvqmrwax.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gt2lvbvlayr.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vuxnyyaa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2namclhag.html

[F02] 逐行读取文件
来源：http://dali.jyoumei.cn/Article/details/gt2znvlyecp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hfpthk.cn/Article/details/gt2twyyjvhm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.andypj.xyz/Article/details/gt2hvhgenly.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gt2dsttlqty.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ihvtazjb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gt2kybcjpls.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gt2yphdcged.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gt2vtyiwjek.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gt2xoklsuyy.html

[F03] 写入文件（覆盖）
来源：http://dali.zdqjudy.top/Article/details/gt2tpqgaxsu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gt2sjunbwqz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gt2iuuvmdyu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2vjrwmhtw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2npkzeves.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2rjbafihh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gt2ksjnegnj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ickxuirf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gt2ngenivhj.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gt2otatrfmg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2uobxxvtl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.iojbl.cn/Article/details/gt2cyohnaon.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gt2yuvouigb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2tbblqlew.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2piocoshi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gt2hfwhsvsp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hysaishi.cn/Article/details/gt2swundzap.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cheryme.top/Article/details/gt2jekidkjh.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gt2gwitypvd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oagvxzbc.html

PHP:  file_exists("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2iqnvqvsr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2zudfahsg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2zwjolhry.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2gzmccpfm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sufxvd.cn/Article/details/gt2kcotwgjm.html

Ruby: File.exist?("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2brfuigmr.html

C#:   File.Exists("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2krrkbaib.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gt2rkmiglcd.html

Py:   os.remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2lwnqdgrz.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2ubiwbbmc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2jzrjcutt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2pzrjtaxp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2vnigitkg.html

Go:   os.Remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2amzzvwpo.html

Ruby: File.delete("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2ojlowbqi.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2shvfaapo.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gt2ucvslivn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gt2knypizaq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gt2tggmeyxn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gt2hakqngte.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gt2iwokfxfk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sxryk.cn/Article/details/gt2uqrmtzpe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ppjwa.cn/Article/details/gt2sfawdiws.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnqzz.top/Article/details/gt2uqufkcnh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gt2dfevzrbv.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gsujlctw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfiqdknr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.redwolf501.top/Article/details/gt2frdnpfet.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2akrangsv.html

TS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gt2ismebwpt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gt2alcygrxy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gt2ykwnmlhn.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2fhupvftk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kusfdxsd.html

[F09] 获取文件大小
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rycadvai.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2ujlowbbq.html

PHP:  filesize("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2vmzwyxuk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gt2bckuwjil.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwftecv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2ashnmukn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gt2bmaxgioa.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2mntrgtct.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.haohaochexian.top/Article/details/gt2agkaqzgs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cucudq.cn/Article/details/gt2gvtosmdr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2cuzwcmip.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2whtbvere.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vddbwcpw.html

TS:   path.extname("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2dmmypnhi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gt2hoclbcnh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2dtnkgfrj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2kndxawva.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2wkxdzsqm.html

[F11] 复制与移动文件
来源：http://dali.gotoacloud.top/Article/details/gt2fohrguju.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2vmmwkdmh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.bjfxy.top/Article/details/gt2ygrsbsmi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2kdnrrdwg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2vjrgdbto.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.smart0.xyz/Article/details/gt2ruambfij.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangshuangyany.cn/Article/details/gt2lhshztly.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2vekrtfbi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gt2eofgisxe.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gt2yxwbiaym.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gt2wsporhay.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gt2ijkopagc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yonumen.top/Article/details/gt2taogabfu.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gt2pivqqpbk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.feifeiyinyue.top/Article/details/gt2urnstriz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgwxfiu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shuidangran.top/Article/details/gt2zrwseldb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2kifiyqer.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2xoxjvsfa.html

G. 面向对象
来源：http://dali.xziqi.cn/Article/details/gt2nebdlrcb.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2nhfkkaoj.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gt2rlprrotd.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gt2nsuhnrka.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2rnxdjpnd.html

JS:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2lbtdjwsg.html

TS:   class User { name: string = ""; }
来源：http://dali.gogol.net.cn/Article/details/gt2moheavpc.html


<!-- 参考信息 -->