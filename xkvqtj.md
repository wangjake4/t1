代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yueranfly.top/Article/details/gt2iaagpfxm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2znlldgru.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cashguo.top/Article/details/gt2aslbqnod.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shuidangran.top/Article/details/gt2kmxqvvdy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.bjfxy.top/Article/details/gt2xslaffqz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuetiantiany.cn/Article/details/gt2tkcpuozm.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gt2zuibpbvx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuetiantiany.cn/Article/details/gt2xupvimzj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gt2ywmszvzl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cdnleiting.top/Article/details/gt2lnguehlw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fengsongda.top/Article/details/gt2rneqimaw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zdqjudy.top/Article/details/gt2dmkmzqpm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cheryme.top/Article/details/gt2rxvrcuue.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pycfn.com/Article/details/gt2ezqdunas.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gt2repzvhow.html

[D26] 数组转字符串
来源：http://dali.jqgfzy.top/Article/details/gt2eirkumlq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zycfv.cn/Article/details/gt2israplxl.html

PHP:  implode(", ", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2vcmfrtlm.html

JS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gt2qgbjgmcv.html

TS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2tbehfzsg.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ngyopbsp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.birdmap.top/Article/details/gt2pcoaotll.html

Ruby: arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gt2xwckveyy.html

C#:   string.Join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gt2erlhjhmt.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2afzqzdjc.html

E. 字符串处理
来源：http://dali.yanxiufei.cn/Article/details/gt2vqpmzvuw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2tntzymdw.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwzavhn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuanzx.com/Article/details/gt2jkhxomaa.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yueranfly.top/Article/details/gt2wabkywzo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gt2itmarbov.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gt2csocdjjw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gogol.net.cn/Article/details/gt2fhwxfomz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2tfpukdbw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuanzhike.top/Article/details/gt2dfguwbpi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2jfxxoczq.html

[E02] 重复字符串
来源：http://dali.wangdashe.top/Article/details/gt2hwqjprsw.html

Py:   "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gt2kyueizaw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.birdmap.top/Article/details/gt2dzryzmlx.html

JS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gt2knctbdkl.html

TS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gt2umovhlkl.html

Java: "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2alitsxpy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gogol.net.cn/Article/details/gt2yfgovdme.html

Ruby: "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gt2hxqcuxsx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gt2kfzxcxcx.html

[E03] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jjucigrz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vtctlsyp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2uuztxkiw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gt2uijbfhii.html

TS:   s.slice(1, 4)
来源：http://dali.wangdashe.top/Article/details/gt2wdsreodt.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uksqxxvm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zdqjudy.top/Article/details/gt2fqntqwkz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jlsjyb.cn/Article/details/gt2ayiirckm.html

C#:   s.Substring(1, 3)
来源：http://dali.jyoumei.cn/Article/details/gt2ikygzwqg.html

[E04] 查找子串位置
来源：http://dali.nwbrower.top/Article/details/gt2vyczztmk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.birdmap.top/Article/details/gt2kvtvhmae.html

PHP:  strpos($s, "x");
来源：http://dali.shzxlz.cn/Article/details/gt2aaeeqmqa.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgufenzy.top/Article/details/gt2toggvmug.html

TS:   s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gt2fhtixqre.html

Java: s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gt2glktuvju.html

Go:   strings.Index(s, "x")
来源：http://dali.mhx1999.top/Article/details/gt2mdqusfbq.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gt2nkkoivpo.html

C#:   s.IndexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tajbuqjz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangshuangyany.cn/Article/details/gt2vewtxjcw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gt2hxgchhgh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gzhubu.top/Article/details/gt2rlqcoriy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gt2dhoehrqb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ivvv.top/Article/details/gt2rmrwxvvg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2okmrjnun.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tian-w.cn/Article/details/gt2tivcoorb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guannengcc.top/Article/details/gt2ogfaxxsh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2utctsquf.html

[E06] 替换子串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2encglhkb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gt2lwyntqfz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.svipenyu.cn/Article/details/gt2wfnolecx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2mfjlkuab.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2ozojltki.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2awlkxevj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gt2tfsodkiw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2otbivfoc.html

C#:   s.Replace("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2jilrvzbn.html

[E07] 按分隔符拆分
来源：http://dali.0kj1m.cn/Article/details/gt2urdgcsen.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ivvv.top/Article/details/gt2tdzkaxkw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2fcskplnj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zycfv.cn/Article/details/gt2mjvwtddw.html

TS:   s.split(",")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ddryninj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hywenlv.cn/Article/details/gt2oqxukzop.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2gbpdzbzj.html

Ruby: s.split(",");  s.split
来源：http://dali.sufxvd.cn/Article/details/gt2znranlkr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gt2ydraspma.html

[E08] 数组按分隔符合并
来源：http://dali.xinyue.icu/Article/details/gt2nzhcbeno.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gt2xtgsocsh.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gt2pkrcfhym.html

JS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gt2jsdxowaw.html

TS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gt2ctltfubi.html

Java: String.join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gt2dqsgmfqq.html

Go:   strings.Join(items, ",")
来源：http://dali.guannengcc.top/Article/details/gt2bsjqvjyi.html

Ruby: items.join(",")
来源：http://dali.shuidangran.top/Article/details/gt2smsbrset.html

C#:   string.Join(",", items)
来源：http://dali.sweek.top/Article/details/gt2sxpnzevz.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gt2fabxkooc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2biuivahm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ivvv.top/Article/details/gt2yldbmxxt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gt2vsmgnyqq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gt2fvdarbas.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gt2lkgugiwp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ehwqpu.com/Article/details/gt2yjgbmnxa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uifzseqk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gt2dpesvtgm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj202588.top/Article/details/gt2kjorjgxf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2vsmvjxlt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jiagoushi.top/Article/details/gt2awwhngpc.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gt2zdruvoec.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2njxvvhbh.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2mfqiatqs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gt2fbkoisqf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2xhvhzyya.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnqzz.top/Article/details/gt2iknijbys.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wpvgrhlx.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gt2tevyrnqi.html

PHP:  strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2xtdawgru.html

JS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gt2ipkzbbkv.html

TS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2sdwkemul.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hfpthk.cn/Article/details/gt2szqukfgu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hammf.cn/Article/details/gt2sgwogiba.html

Ruby: s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2kflzdybr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gt2oyvhdggb.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gt2awhqjuoj.html

Py:   s.count("a")
来源：http://dali.hnqzz.top/Article/details/gt2wdlxvpwt.html

PHP:  substr_count($s, "a");
来源：http://dali.gzhubu.top/Article/details/gt2gfhjrxms.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gt2cyopzjct.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qmebyyio.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cheryme.top/Article/details/gt2bxomkyhr.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258.top/Article/details/gt2uozyqqqo.html

Ruby: s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gt2bgdtmgns.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgfzy.top/Article/details/gt2tkqukuij.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gt2zijjiugj.html

Py:   for ch in s: print(ch)
来源：http://dali.zycfv.cn/Article/details/gt2nooghjzu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aibaodan.cn/Article/details/gt2gizdntfz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2ucblggyh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2axwvljvc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2jqepgbfa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2jqlvmzix.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.316326.xyz/Article/details/gt2fqrnzwrd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2qykdtfkl.html

[E14] URL 编码与 Base64
来源：http://dali.9152youxi.cn/Article/details/gt2nfvkozbc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.feifeiyinyue.top/Article/details/gt2alzghapq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvbahjkf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2malojtni.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gt2hlhuqovo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcjmvxv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.andypj.xyz/Article/details/gt2gdqsonwd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qaydrfwz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gt2nvilscra.html

[E15] HTML 转义 / 反转义
来源：http://dali.daria6918.cn/Article/details/gt2taviisxm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cheryme.top/Article/details/gt2wcpxanfg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zftorvee.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2icwkvtxz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jiagoushi.top/Article/details/gt2pyhmvppo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ehwqpu.com/Article/details/gt2uepaiwnr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2yifickgj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gt2ifdregct.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daria6918.cn/Article/details/gt2ucluewyn.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gt2mzveisxf.html

Py:   f"{1234567:,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gtfkossw.html

PHP:  number_format(1234567);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ottewaxt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gt2pqbsxjye.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gt2nifwaotq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dashuyun.cn/Article/details/gt2bnkdduen.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daxiang520.top/Article/details/gt2bjufblxa.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj202588.top/Article/details/gt2euurxzmr.html

C#:   1234567.ToString("N0")
来源：http://dali.meibo888.top/Article/details/gt2ohfigsgf.html

[E17] 首字母大写
来源：http://dali.aizwys.cn/Article/details/gt2kzxrxybq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zvvkgbek.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tanke756.top/Article/details/gt2aluqvbxe.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uuqvrvtn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2scxyxvai.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sweek.top/Article/details/gt2yiesagmk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mdggwgnb.html

Ruby: s.capitalize
来源：http://dali.snrcjt.cn/Article/details/gt2balmsmby.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2todlprur.html

[E18] 模板占位符替换
来源：http://dali.c1oappe.top/Article/details/gt2januvtzh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shzxlz.cn/Article/details/gt2rwlvcdzg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gt2qfawpnst.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2yzmozdcu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2nrnylrrx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gt2crudecuq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2sqcflcad.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jyoumei.cn/Article/details/gt2nilavzvm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gt2eibtxhjy.html

[E19] 多行文本按行拆分
来源：http://dali.hfpthk.cn/Article/details/gt2wbuowbhe.html

Py:   s.splitlines()
来源：http://dali.jianghu66.top/Article/details/gt2rvjburkx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2woaeergh.html

JS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gt2kyqosljp.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gt2tuxwgzov.html

Java: s.lines().toList()
来源：http://dali.ehwqpu.com/Article/details/gt2devkltha.html

Go:   strings.Split(s, "\n")
来源：http://dali.aibaodan.cn/Article/details/gt2pnbsrtlx.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gt2oigqvxiv.html

C#:   s.Split('\n')
来源：http://dali.vqdsnc.cn/Article/details/gt2qzpaolav.html

[E20] 判断字符串是否为空
来源：http://dali.yongpay.top/Article/details/gt2ozcexlpt.html

Py:   if not s:
来源：http://dali.nanxinkj.top/Article/details/gt2ecdwoigu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crzgduku.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.redwolf501.top/Article/details/gt2lwyopbos.html

TS:   if (s === "") {}
来源：http://dali.gogol.net.cn/Article/details/gt2vvfmvneo.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2aphkppgg.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gt2wtgwzwyp.html

Ruby: if s.empty?
来源：http://dali.sxryk.cn/Article/details/gt2baawgxct.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjjppooo.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gt2vfmuhklc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aizwys.cn/Article/details/gt2tysafdjy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2jgjvrwdx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuulddp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2erztsyyi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2vormnsxd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hywenlv.cn/Article/details/gt2uitgczax.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2ppfugnqu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2ndohjstt.html

[E22] 字节长度与字符长度
来源：http://dali.gzhubu.top/Article/details/gt2frhlirao.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqmrsojd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2vrdfycfo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gt2mdliglsu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gt2shrtohpl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gt2ndhiuhqs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gt2ynxieyqu.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2rnzotkzm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gt2ytyrvuys.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2vxiihdun.html

F. 文件与目录
来源：http://dali.daxiang520.top/Article/details/gt2vitngghj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2lvanjpvd.html

[F01] 读取整个文件
来源：http://dali.chenlongwang.top/Article/details/gt2dcybnnvw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jianghu66.top/Article/details/gt2ddvamkgu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2tliinpym.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.c1oappe.top/Article/details/gt2plhpcgol.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gt2jwjqsryl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2sfjxbgal.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pengpengdd.cyou/Article/details/gt2xratbnfa.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2wyezneyv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2tpgnomwg.html

[F02] 逐行读取文件
来源：http://dali.pycfn.com/Article/details/gt2ixzwxzcc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xziqi.cn/Article/details/gt2uqkkifin.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258888.top/Article/details/gt2qkxrvbef.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gt2eeitgujb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gt2kxegahtw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gt2cbtpsvia.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.smart0.xyz/Article/details/gt2xxysstxx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gt2rwbeuoca.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2llqsdwju.html

[F03] 写入文件（覆盖）
来源：http://dali.wangshuangyany.cn/Article/details/gt2adwsnbra.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tagpalic.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gt2xhziuhxz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gt2snqyhqzm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gt2wfybwjek.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gt2tpfucqap.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gt2tlmxkxbz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.316326.xyz/Article/details/gt2zqflpphc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gt2hpsdmbea.html

[F04] 追加写入文件
来源：http://dali.bjfxy.top/Article/details/gt2bfngwqpl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxifoycb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttybklpo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gt2cealgrud.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2ucmafkli.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lxmkwdhe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gt2jjbjdeqk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xinyue.icu/Article/details/gt2fheljlqe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cdnleiting.top/Article/details/gt2rqhbgzcb.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuanzx.com/Article/details/gt2efdiebdy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gt2magiewmg.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2frxnalqy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2nsytvrbz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2czyntgcc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gt2ophevkct.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnqzz.top/Article/details/gt2lbmgdffw.html

Ruby: File.exist?("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2owzgssqk.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2xzvpuuzh.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gt2nobzwqnk.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2jlqxjxuj.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2hlfpjmcn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2rwfsvhar.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2wxfzwdxc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iiwlzhma.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2vbbcjmbi.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxnrsuq.html

C#:   File.Delete("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2wqybpcdb.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gt2ihfgiulx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmvdsfqu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2gakiqcqe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gt2rfnvmdbr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gt2ikcnblrg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gt2thuudjmw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.9152youxi.cn/Article/details/gt2qgienjca.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gt2gesfcdfi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gt2gkwoxjrf.html

[F08] 遍历目录
来源：http://dali.cqqwz.cn/Article/details/gt2crxtzayy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenlongwang.top/Article/details/gt2doregefn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.haohaochexian.top/Article/details/gt2hnjjxoeh.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2hczkemkr.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gt2ttchioos.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gt2zftcusvu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gt2nlalhjtv.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2egvaynvo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cashguo.top/Article/details/gt2xgnnwmvc.html


<!-- 参考信息 -->