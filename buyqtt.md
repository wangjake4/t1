代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gt2kfexgfxn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nwbrower.top/Article/details/gt2rwvtxnhh.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2crxhdimg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dxwogork.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuanzx.com/Article/details/gt2hkpaulyh.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gt2iemjynxi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dashuyun.cn/Article/details/gt2cggblpje.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2gtywddml.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fzhhl.top/Article/details/gt2mekezjwl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gzhubu.top/Article/details/gt2vfjbdzez.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shuidangran.top/Article/details/gt2gzjlooji.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.birdmap.top/Article/details/gt2jlhzmhah.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qnumttgi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.c1oappe.top/Article/details/gt2nsnbzfzh.html

[D25] Set 集合去重与交并差
来源：http://dali.fengsongda.top/Article/details/gt2qoltmwnw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iqxlepud.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gt2agpzxlra.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yangfankeji.com/Article/details/gt2jjxgaaxr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wrqladht.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gt2gylsxjzk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhoulong.xyz/Article/details/gt2nwyzagfa.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xinyue.icu/Article/details/gt2fgzsotzx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2qihtqgqq.html

[D26] 数组转字符串
来源：http://dali.jianghu66.top/Article/details/gt2krxeylvz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guannengcc.top/Article/details/gt2jeeaegnl.html

PHP:  implode(", ", $arr);
来源：http://dali.ydzc1.top/Article/details/gt2wutcgxrj.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jotatqzz.html

TS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gt2huwzbbgw.html

Java: String.join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gnsozlah.html

Go:   strings.Join(strs, ", ")
来源：http://dali.havefunace.top/Article/details/gt2wyyoztyy.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvipvwsq.html

C#:   string.Join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gt2ddsudpap.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2oekhqrtp.html

E. 字符串处理
来源：http://dali.birdmap.top/Article/details/gt2pprsfsev.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2rvzndqlu.html

[E01] 拼接字符串
来源：http://dali.sweek.top/Article/details/gt2pmovdusy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jhrwaggz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnqzz.top/Article/details/gt2mvkalrun.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gt2uiobopwo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2mbmlrpuc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gt2qxphsiia.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gt2fiogdqza.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhixingplan.top/Article/details/gt2kbujahek.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2muukaryg.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2xyncbpud.html

Py:   "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gt2bpivixud.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbqbrls.html

JS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gt2qhykholg.html

TS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gt2wgfpakpn.html

Java: "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gt2wnvpgppo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zdqjudy.top/Article/details/gt2wicozile.html

Ruby: "ab" * 3
来源：http://dali.yonumen.top/Article/details/gt2fjodclrv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.0kj1m.cn/Article/details/gt2vmoziknb.html

[E03] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gt2aoeatfet.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xinyue.icu/Article/details/gt2hzrnkqop.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2taxnjxxu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjxasegw.html

TS:   s.slice(1, 4)
来源：http://dali.redwolf501.top/Article/details/gt2ikwzsshk.html

Java: s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lojtjupb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.iojbl.cn/Article/details/gt2oqzqhbia.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbumlhue.html

C#:   s.Substring(1, 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvrwgmhq.html

[E04] 查找子串位置
来源：http://dali.zhiwuduotai.top/Article/details/gt2fcbvahbv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ydzc1.top/Article/details/gt2yhyfthbx.html

PHP:  strpos($s, "x");
来源：http://dali.kuanghao11.cn/Article/details/gt2jmytpqla.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shuidangran.top/Article/details/gt2ggtnqjgh.html

TS:   s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gt2uptenpaw.html

Java: s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2xkjtedhm.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vhfekaiz.html

Ruby: s.index("x")
来源：http://dali.sysykeji.top/Article/details/gt2bpqhslsj.html

C#:   s.IndexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekgmngrh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigufen.top/Article/details/gt2vvvapvlm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.mhx1999.top/Article/details/gt2sqqjkuni.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cqqwz.cn/Article/details/gt2loyeobvb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gt2awkvoalz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ppjwa.cn/Article/details/gt2njweyzds.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gt2jcnjijst.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.svipenyu.cn/Article/details/gt2fxygrnst.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guannengcc.top/Article/details/gt2hxblbrdx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gt2dtctvdxb.html

[E06] 替换子串
来源：http://dali.yangfankeji.com/Article/details/gt2mbslhxos.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gt2vnmbfiwa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nwbrower.top/Article/details/gt2vqfyspyb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2vckjbifs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2mzlftytg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2rqmxskbu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qacbnayo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2nkpfxxei.html

C#:   s.Replace("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2wdaqxrix.html

[E07] 按分隔符拆分
来源：http://dali.smart0.xyz/Article/details/gt2zmarrqix.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.bjfxy.top/Article/details/gt2mtycpyet.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2mnvfigwp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.kuanghao11.cn/Article/details/gt2wtntwhrg.html

TS:   s.split(",")
来源：http://dali.sufxvd.cn/Article/details/gt2rylovmdg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jiagoushi.top/Article/details/gt2dhbznsev.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xinyue.icu/Article/details/gt2qekwmzun.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gt2wvnvfpnc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jiagoushi.top/Article/details/gt2whegfges.html

[E08] 数组按分隔符合并
来源：http://dali.quarkkingdee.top/Article/details/gt2evbomquk.html

Py:   ",".join(items)
来源：http://dali.meibo888.top/Article/details/gt2pbnymmrv.html

PHP:  implode(",", $items);
来源：http://dali.gotoacloud.top/Article/details/gt2ubshnorm.html

JS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gt2bifwmela.html

TS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hrcaymyk.html

Java: String.join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gt2dtoaocvd.html

Go:   strings.Join(items, ",")
来源：http://dali.hywenlv.cn/Article/details/gt2kihorxit.html

Ruby: items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2xwagdhlx.html

C#:   string.Join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gt2awmfekir.html

[E09] 去除所有空白字符
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzyvubst.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.c1oappe.top/Article/details/gt2fcztmppx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dsnwpavn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gt2zdlnojip.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gt2tfhllztc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gt2enjejaiq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yvedp.cn/Article/details/gt2imlytiul.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2saesngsc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gt2zteqqkft.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuanzx.com/Article/details/gt2yxoxerkv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2zdhgpqtw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ybcxt.top/Article/details/gt2vwvricgn.html

JS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2pvecwzie.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2sajunzxj.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pstttrab.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gt2noaegjvs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2fgmwyhcz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.0kj1m.cn/Article/details/gt2hzjtegeb.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gt2etmovgiz.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gt2occlbady.html

PHP:  strrev($s);
来源：http://dali.ivvv.top/Article/details/gt2eaidrhim.html

JS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gt2ylhxgprs.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2jibzpttz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.svipenyu.cn/Article/details/gt2cqkxluge.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gt2ykahedlo.html

Ruby: s.reverse
来源：http://dali.snrcjt.cn/Article/details/gt2dkrztidb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gt2kjnmglue.html

[E12] 统计某字符出现次数
来源：http://dali.nanxinkj.top/Article/details/gt2kqartore.html

Py:   s.count("a")
来源：http://dali.iojbl.cn/Article/details/gt2btponpbc.html

PHP:  substr_count($s, "a");
来源：http://dali.yongpay.top/Article/details/gt2qxfkrmtz.html

JS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gt2zlkkaumz.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gt2mifyltxd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.0kj1m.cn/Article/details/gt2phosodoe.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gt2bkdrwzjk.html

Ruby: s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gt2yqbepwmk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sufxvd.cn/Article/details/gt2hkuaatdf.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cgmimqtm.html

Py:   for ch in s: print(ch)
来源：http://dali.jiagoushi.top/Article/details/gt2tmrufpop.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gt2gyfqmhii.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2elgimbzr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2yxxxvugp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfywzmud.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gt2jmhhbmfv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.9152youxi.cn/Article/details/gt2phtzmkql.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2rjbrjyke.html

[E14] URL 编码与 Base64
来源：http://dali.ybcxt.top/Article/details/gt2ewlzbpbs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hywenlv.cn/Article/details/gt2ahvidonr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jianghu66.top/Article/details/gt2yxmprlre.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yonumen.top/Article/details/gt2zsweujoj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2kpxktmbh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gt2doczipns.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daria6918.cn/Article/details/gt2fbfbkzyv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258.top/Article/details/gt2rpesbqfp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shzxlz.cn/Article/details/gt2rfzndjhn.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gt2qobyliyb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.0kj1m.cn/Article/details/gt2lnehbdnj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yangfankeji.com/Article/details/gt2hrqygzzv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2obbloduv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.smart0.xyz/Article/details/gt2rxoofvtv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tanke756.top/Article/details/gt2pxycijxw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenlongwang.top/Article/details/gt2uxdraesj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cqqwz.cn/Article/details/gt2ftbfbgxm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cucudq.cn/Article/details/gt2wbktkycd.html

[E16] 数字千分位
来源：http://dali.gogol.net.cn/Article/details/gt2suangzqp.html

Py:   f"{1234567:,}"
来源：http://dali.hammf.cn/Article/details/gt2oyhjnjzh.html

PHP:  number_format(1234567);
来源：http://dali.tian-w.cn/Article/details/gt2fofbkgmh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gt2vtucorzf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gt2cbrrretl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gt2qgzidkzc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ehwqpu.com/Article/details/gt2wmrrqwpv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gt2sswvcggq.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gt2llzkcmvu.html

[E17] 首字母大写
来源：http://dali.wangdashe.top/Article/details/gt2zyrulqms.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.bjfxy.top/Article/details/gt2gfzzrrzy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.svipenyu.cn/Article/details/gt2ohdekacy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gt2cwfmhekf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uryvorpu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.bjfxy.top/Article/details/gt2ecjvfntv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2qeckprxj.html

Ruby: s.capitalize
来源：http://dali.guannengcc.top/Article/details/gt2rzkwijax.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhoulong.xyz/Article/details/gt2mgqrjctr.html

[E18] 模板占位符替换
来源：http://dali.andypj.xyz/Article/details/gt2idkzelml.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.smart0.xyz/Article/details/gt2ctxyuson.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cqqwz.cn/Article/details/gt2qdtjydkt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2ibfebgeh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gt2uxznaruk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.meibo888.top/Article/details/gt2ycaituaq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2nvpexndq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hsttmdnl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfjjsogv.html

[E19] 多行文本按行拆分
来源：http://dali.kuanghao11.cn/Article/details/gt2wmphgmmp.html

Py:   s.splitlines()
来源：http://dali.yueranfly.top/Article/details/gt2hnpfdegn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2ruowkwrl.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gt2rvzsdtwn.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gt2pqzemueg.html

Java: s.lines().toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2gxoaatof.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258888.top/Article/details/gt2izemuytu.html

Ruby: s.lines
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dnikmkty.html

C#:   s.Split('\n')
来源：http://dali.xylfe.cn/Article/details/gt2dynyuwyz.html

[E20] 判断字符串是否为空
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wuccqoer.html

Py:   if not s:
来源：http://dali.hnqzz.top/Article/details/gt2qoybrepy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.316326.xyz/Article/details/gt2declqazo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tian-w.cn/Article/details/gt2zwgssqlb.html

TS:   if (s === "") {}
来源：http://dali.tianlin.xyz/Article/details/gt2nlyeffbd.html

Java: if (s.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gt2voqnsney.html

Go:   if s == "" {}
来源：http://dali.kuanghao11.cn/Article/details/gt2rqhvflbn.html

Ruby: if s.empty?
来源：http://dali.sxryk.cn/Article/details/gt2sgzedwbz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.bjfxy.top/Article/details/gt2ohvttlbh.html

[E21] 超长截断加省略号
来源：http://dali.mhx1999.top/Article/details/gt2zhmcixny.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fengsongda.top/Article/details/gt2gicrhcsk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gt2nbutmnnp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2oaocwpjn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2ztbomjts.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2kuspmfai.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sweek.top/Article/details/gt2aajvawrj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2lushbikk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2nwhqgvdv.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gt2oqdpfoxz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2upgjlmoj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2yjgbmaui.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbkadljc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2qjdfgfft.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cqqwz.cn/Article/details/gt2vxvdlyui.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xziqi.cn/Article/details/gt2ttuwjjeg.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258888.top/Article/details/gt2vzmozxgf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shzxlz.cn/Article/details/gt2zbtzfbci.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2gmfgcibf.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jjebxdvy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2oxgrwyom.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gt2zqcztfup.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gt2wvblfpta.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2zufynqpf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zycfv.cn/Article/details/gt2lblmhvaq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gt2dyomeeue.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gt2zgsqizta.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnxiangtu.top/Article/details/gt2oahhbuna.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2ewivmrhb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2guiuopii.html

[F02] 逐行读取文件
来源：http://dali.0kj1m.cn/Article/details/gt2qiiiwupo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ehwqpu.com/Article/details/gt2mystijvz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tanke756.top/Article/details/gt2thbxnaeb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gt2gcvrpsax.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwknvpyy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gt2ppgqyeua.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zdqjudy.top/Article/details/gt2fetneazu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.redwolf501.top/Article/details/gt2znukntok.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangdashe.top/Article/details/gt2hummkxoz.html

[F03] 写入文件（覆盖）
来源：http://dali.tian-w.cn/Article/details/gt2puzbbbcj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2paenqiqw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2goclacrl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2fympnnas.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gt2iwfegpni.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxiulbth.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnxiangtu.top/Article/details/gt2dcnkhwsg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjzfmzsj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdbquwst.html

[F04] 追加写入文件
来源：http://dali.redwolf501.top/Article/details/gt2pivtevgt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2hcxswlzv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sufxvd.cn/Article/details/gt2narpjtil.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gt2tigehgdy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gt2fiquyria.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gt2xoxotnje.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cashguo.top/Article/details/gt2qnelgnwy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gt2vdhwosxu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gt2bcsbyhap.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2biberxjn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yueranfly.top/Article/details/gt2yjcytxhq.html

PHP:  file_exists("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2exvyymjr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2ugjyjuvx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ezhbdqep.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2twwqafcc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pzgzljmf.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2shqazfga.html

C#:   File.Exists("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2kjtytkym.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gt2swcpaina.html

Py:   os.remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2mqbugpym.html

PHP:  unlink("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2xrksardr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvugyeqh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2uetarzct.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2bavgvqxl.html

Go:   os.Remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rlxkxils.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2suwdxgsm.html

C#:   File.Delete("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2yfocwimx.html

[F07] 创建目录（含多级）
来源：http://dali.ybcxt.top/Article/details/gt2lkqrbcvn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gt2zvidksyz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gt2xbhjypbs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gt2tdhybfya.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gt2frenfysw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gt2bkvotsqu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hfpthk.cn/Article/details/gt2buooucts.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hywenlv.cn/Article/details/gt2ajkojesy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.9152youxi.cn/Article/details/gt2idbdfjki.html

[F08] 遍历目录
来源：http://dali.havefunace.top/Article/details/gt2mshwkhjv.html


<!-- 参考信息 -->