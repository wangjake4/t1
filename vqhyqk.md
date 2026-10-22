代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xziqi.cn/Article/details/gt2uamtqkbh.html

[D24] 字典 / Map 基本操作
来源：http://dali.jianghu66.top/Article/details/gt2qlatkajj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zycfv.cn/Article/details/gt2bqfewwly.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tianlin.xyz/Article/details/gt2pifxknhc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gt2hymzhbod.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gt2hpsljszs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yueranfly.top/Article/details/gt2dawdtszk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daria6918.cn/Article/details/gt2cqklhcun.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.316326.xyz/Article/details/gt2iaaffajd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gt2pnfonqos.html

[D25] Set 集合去重与交并差
来源：http://dali.andypj.xyz/Article/details/gt2nsqoxqfe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuanzhike.top/Article/details/gt2dtdkosjq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gogol.net.cn/Article/details/gt2vvrdpgil.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypectlno.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ppjwa.cn/Article/details/gt2uamsurld.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.c1oappe.top/Article/details/gt2uankcano.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shuidangran.top/Article/details/gt2klhyswhs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2byunfdvb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shuidangran.top/Article/details/gt2dmlpvwyd.html

[D26] 数组转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghdkghlv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2qawbwhey.html

PHP:  implode(", ", $arr);
来源：http://dali.dashuyun.cn/Article/details/gt2tisuinmw.html

JS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gt2fpfnxtuw.html

TS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gt2fjsfbndo.html

Java: String.join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gt2yghlzwko.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yvedp.cn/Article/details/gt2idezyqgo.html

Ruby: arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2duysnrhp.html

C#:   string.Join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gt2wsrllkhm.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2ifjidneg.html

E. 字符串处理
来源：http://dali.jqgufenzy.top/Article/details/gt2lxxqxbyt.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2fqgsnqzj.html

[E01] 拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2avnracsp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cashguo.top/Article/details/gt2fgbkgilz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gt2kkubbnqi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gt2ojxiffnd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gt2hjngjamq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.vqdsnc.cn/Article/details/gt2vrroguzm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktmjefso.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wjgshjuy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vsfhcwot.html

[E02] 重复字符串
来源：http://dali.nwbrower.top/Article/details/gt2jyzwzhzn.html

Py:   "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gt2zgfbzznr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cidauglx.html

JS:   "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gt2dvjumcyi.html

TS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uzdogdni.html

Java: "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gt2vezolupx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ydzc1.top/Article/details/gt2ssdkxpay.html

Ruby: "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gt2empxvdbc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pycfn.com/Article/details/gt2wcfqedbj.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gt2pxgurwzy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zdqjudy.top/Article/details/gt2brpieacr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2fwpbhfbv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gt2lqugmeen.html

TS:   s.slice(1, 4)
来源：http://dali.yj202588.top/Article/details/gt2hmrunfcp.html

Java: s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gt2mdvsvunt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangdashe.top/Article/details/gt2vpoumyro.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuanzhike.top/Article/details/gt2ixukesir.html

C#:   s.Substring(1, 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uhwcmfyd.html

[E04] 查找子串位置
来源：http://dali.wangdashe.top/Article/details/gt2dahyiefi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sxryk.cn/Article/details/gt2ihpcnnda.html

PHP:  strpos($s, "x");
来源：http://dali.xziqi.cn/Article/details/gt2dokrufil.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gt2bcrxwmqx.html

TS:   s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gt2fosvvobn.html

Java: s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gt2qkelfaxc.html

Go:   strings.Index(s, "x")
来源：http://dali.zhongyouzk.top/Article/details/gt2mrqfndvi.html

Ruby: s.index("x")
来源：http://dali.cucudq.cn/Article/details/gt2zyvtquvu.html

C#:   s.IndexOf("x")
来源：http://dali.sxryk.cn/Article/details/gt2lsmmmtnj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.mhx1999.top/Article/details/gt2zrjlheho.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gt2vdhdtocw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gt2izdrwyjo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gt2hotamaxk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.birdmap.top/Article/details/gt2bbifiuce.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gt2lxkkvklp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sweek.top/Article/details/gt2dhsubczo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yueranfly.top/Article/details/gt2jmivdhyh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gzuawlni.html

[E06] 替换子串
来源：http://dali.sysykeji.top/Article/details/gt2aqqqdtog.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gt2jekqomds.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.316326.xyz/Article/details/gt2woldegfm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2undspowv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2tkbaskek.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2haqukjbt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gt2gjivhovo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2zfndxiqv.html

C#:   s.Replace("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2mqhqhqvs.html

[E07] 按分隔符拆分
来源：http://dali.9152youxi.cn/Article/details/gt2xclhgght.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aizwys.cn/Article/details/gt2ccwsoste.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2kyewqlge.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cashguo.top/Article/details/gt2ahriyrmb.html

TS:   s.split(",")
来源：http://dali.jianghu66.top/Article/details/gt2mciemzts.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.svipenyu.cn/Article/details/gt2fmbpzapd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqnutlif.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gt2yzrlkjlj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gzhubu.top/Article/details/gt2abvlcjyl.html

[E08] 数组按分隔符合并
来源：http://dali.snrcjt.cn/Article/details/gt2onzkjqeb.html

Py:   ",".join(items)
来源：http://dali.ydzc1.top/Article/details/gt2upyqirsl.html

PHP:  implode(",", $items);
来源：http://dali.xziqi.cn/Article/details/gt2ayfwgfpq.html

JS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gt2kdkdrogy.html

TS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gt2fqxonjcf.html

Java: String.join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gt2ptosdryx.html

Go:   strings.Join(items, ",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2irzumela.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2fnteivmh.html

C#:   string.Join(",", items)
来源：http://dali.316326.xyz/Article/details/gt2jsyzzhic.html

[E09] 去除所有空白字符
来源：http://dali.xylfe.cn/Article/details/gt2oypqedte.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sxryk.cn/Article/details/gt2czvrasim.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuxming.cn/Article/details/gt2fgafihfg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gt2rtiwncrp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gt2ghbmzpxh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gt2gyzuiiku.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xwehigbm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhixingplan.top/Article/details/gt2hbrtwnif.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gt2klfyqfjm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hywenlv.cn/Article/details/gt2jkcvxitg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gt2fynmjqdb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hfpthk.cn/Article/details/gt2dtzmmiyl.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gt2mbvhlbsk.html

TS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gt2jstpbmcj.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gt2fynllxxl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gt2lhssdylx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ckqtxfnh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tanke756.top/Article/details/gt2rtyfmybz.html

[E11] 反转字符串
来源：http://dali.yuxming.cn/Article/details/gt2mnhdqfeu.html

Py:   s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gt2jsbqxxbj.html

PHP:  strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gt2kdywgimv.html

JS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnhewitt.html

TS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2hyzwraap.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sweek.top/Article/details/gt2otwietgp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qtrlcmzu.html

Ruby: s.reverse
来源：http://dali.jyoumei.cn/Article/details/gt2sryuztik.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gt2bboosscq.html

[E12] 统计某字符出现次数
来源：http://dali.zhengqikj.top/Article/details/gt2ertxabfk.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gt2bkousznb.html

PHP:  substr_count($s, "a");
来源：http://dali.chenzaomai.com/Article/details/gt2lkfrcioj.html

JS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gt2beztejzw.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gt2ttqqwzsg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yueranfly.top/Article/details/gt2tyfmtbxd.html

Go:   strings.Count(s, "a")
来源：http://dali.ppjwa.cn/Article/details/gt2ewdwhzmf.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gt2vbglhomx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mgtncfjh.html

[E13] 逐字符遍历
来源：http://dali.haohaochexian.top/Article/details/gt2yfvlrxgb.html

Py:   for ch in s: print(ch)
来源：http://dali.zdqjudy.top/Article/details/gt2lvzcflvt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ubjgvzds.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gt2remyaxvr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2mdkqikch.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2yxmxxiac.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2laulnesx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gt2msipcxnu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2ygheyura.html

[E14] URL 编码与 Base64
来源：http://dali.sweek.top/Article/details/gt2vgmldjro.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenjidiqi.icu/Article/details/gt2rpkrqsxw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gt2irefrftq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hywenlv.cn/Article/details/gt2bkwhchuu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2cvxqwnlc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2xobcfbom.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.c1oappe.top/Article/details/gt2vtfkdsqs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2inwkojde.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.smart0.xyz/Article/details/gt2epjxykiz.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenlongwang.top/Article/details/gt2dyozwkqk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gt2yplzwvrz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gt2bbzbeqgz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.meibo888.top/Article/details/gt2dawugccw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.c1oappe.top/Article/details/gt2zgllwlaf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuxming.cn/Article/details/gt2chbujflb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2ehtxixok.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sufxvd.cn/Article/details/gt2qipoolmg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2bjtxdbtl.html

[E16] 数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gt2mdewgxoo.html

Py:   f"{1234567:,}"
来源：http://dali.yuxming.cn/Article/details/gt2djqxoekn.html

PHP:  number_format(1234567);
来源：http://dali.dashuyun.cn/Article/details/gt2krdqbbyb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gt2uoaerwbp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gt2kwxpxsyb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fengsongda.top/Article/details/gt2afyszfpn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hysaishi.cn/Article/details/gt2bnfvczqg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.iojbl.cn/Article/details/gt2omxeirmw.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gt2thhhixpe.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gt2cctgvsvs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gaohongyu789.top/Article/details/gt2ndtlzvci.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dashuyun.cn/Article/details/gt2knfhxxer.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2dfuuuwee.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uonwfqos.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258.top/Article/details/gt2jofcdunl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gt2uylxzvsq.html

Ruby: s.capitalize
来源：http://dali.hongshengwenyu.top/Article/details/gt2zglexxzk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrksokrd.html

[E18] 模板占位符替换
来源：http://dali.mhx1999.top/Article/details/gt2qwawshgg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sreknqih.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ukdbihhh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2gvqdckrw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2dklbzwce.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2jkcijiym.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gt2ixaynlxm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ydzc1.top/Article/details/gt2kcepsxgw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258.top/Article/details/gt2hbwrxcrw.html

[E19] 多行文本按行拆分
来源：http://dali.zhongyouzk.top/Article/details/gt2twgjfqln.html

Py:   s.splitlines()
来源：http://dali.hammf.cn/Article/details/gt2orjjletm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ilejwaoq.html

JS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gt2rfrmquxq.html

TS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gt2dvkibamc.html

Java: s.lines().toList()
来源：http://dali.yj202588.top/Article/details/gt2ugacqgso.html

Go:   strings.Split(s, "\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2tuxjtmry.html

Ruby: s.lines
来源：http://dali.xuanzx.com/Article/details/gt2camumuik.html

C#:   s.Split('\n')
来源：http://dali.316326.xyz/Article/details/gt2ukvhiwkg.html

[E20] 判断字符串是否为空
来源：http://dali.jlsjyb.cn/Article/details/gt2gtazbvgi.html

Py:   if not s:
来源：http://dali.daxiang520.top/Article/details/gt2hykcomhl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gt2ejjjmjvt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gt2trhyyhem.html

TS:   if (s === "") {}
来源：http://dali.yongpay.top/Article/details/gt2ajnjhody.html

Java: if (s.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2sokhcqdt.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oaygorzr.html

Ruby: if s.empty?
来源：http://dali.jinqigfzy.top/Article/details/gt2mpgcsyri.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gt2uecpahoi.html

[E21] 超长截断加省略号
来源：http://dali.gogol.net.cn/Article/details/gt2svxzfrhy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.mhx1999.top/Article/details/gt2uxameebs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2dzxgohkc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2tnfepxlx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gt2sjpfojgr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2uimtcxoc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yanxiufei.cn/Article/details/gt2jmetehhr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2vmejmaao.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2pclecfjg.html

[E22] 字节长度与字符长度
来源：http://dali.gaohongyu789.top/Article/details/gt2rtqsgnxd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gt2nmnhhzxa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2mjeqpxlh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtynrtab.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gt2pjoqtmie.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gt2oyjtbxrw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guowangkeji.top/Article/details/gt2hdlhygvu.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gt2vlfsfysw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gt2sovjnxjm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2yujtlvjy.html

F. 文件与目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mbpeftlo.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2ryyqufzg.html

[F01] 读取整个文件
来源：http://dali.gzhubu.top/Article/details/gt2hemivgiv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hongshengwenyu.top/Article/details/gt2fpgdotza.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2jsvhzguj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gt2vrjmidpv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uagsbmuj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gt2nxfqjejw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xlwdkmdv.html

Ruby: File.read("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2pginblpm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2oyqcoxfp.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2hclzjqhn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.haohaochexian.top/Article/details/gt2mfnmimhm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gt2rjzhqpny.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gt2erawrsji.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gt2izsktmjc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hevykrxb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gt2idsylmzm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigufen.top/Article/details/gt2bbqvkozr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aizwys.cn/Article/details/gt2sfmrwalc.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gt2euhqfwfs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gt2cwrdtpzg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gt2sfvinhjx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gt2frfusuwk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2ljtjldhv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijsajjzs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.svipenyu.cn/Article/details/gt2xgwgxwsb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnafkjeq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gt2ummummfz.html

[F04] 追加写入文件
来源：http://dali.9152youxi.cn/Article/details/gt2msvwqkov.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gt2jdkfxyjp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gt2dilcojfs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2ibqrqwjp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gt2fawulhnp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.haohaochexian.top/Article/details/gt2guobqxtb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gt2leyykkyc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gt2irtukzwn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yvedp.cn/Article/details/gt2rzizrsdr.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gt2njnlrtla.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgufenzy.top/Article/details/gt2pstdvopp.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymqxezie.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2pnjnsrtj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hzkkwlxb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2zfmhqmmh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sysykeji.top/Article/details/gt2rqhpsewx.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2cbifpsfj.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2jrinsswg.html

[F06] 删除文件
来源：http://dali.wangdashe.top/Article/details/gt2pjqogsod.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gecanvvc.html

PHP:  unlink("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2depjpidg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2ulknduhn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2omylukqf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2cdodgatr.html

Go:   os.Remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2yetdlhsn.html

Ruby: File.delete("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2wrhdpgrr.html

C#:   File.Delete("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2rmyzrnfu.html

[F07] 创建目录（含多级）
来源：http://dali.nanxuanxn.top/Article/details/gt2mylbcehc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gt2bivrfzte.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tianlin.xyz/Article/details/gt2xcdjcbxq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gt2cvoapjow.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gt2sryidxua.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gt2ztuanzbg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuanzx.com/Article/details/gt2msfwzxae.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yvedp.cn/Article/details/gt2znptdadm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.feifeiyinyue.top/Article/details/gt2pilvuwgr.html

[F08] 遍历目录
来源：http://dali.zdqjudy.top/Article/details/gt2nuasdidz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.quarkkingdee.top/Article/details/gt2vvospaqa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yanxiufei.cn/Article/details/gt2qdzlyjnc.html

JS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2misjjbsa.html

TS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gt2xyvjgtwz.html


<!-- 参考信息 -->