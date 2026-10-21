代发 wailian999

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtwnovxlpe.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.mhx1999.top/Article/details/gtwpvhwosi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.birdmap.top/Article/details/gtfbtekand.html

TS:   [...arr];
来源：http://dali.zhixingplan.top/Article/details/gtlvpgycxd.html

Java: new ArrayList<>(list);
来源：http://dali.nwbrower.top/Article/details/gtizfasbto.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gtmkcjsdfj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.andypj.xyz/Article/details/gtkhwzvjvo.html

C#:   new List<int>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtldmfmluz.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gtsubdcggx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gtuwcowocp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtpcfwjljh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtcweikepr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gtepnobknd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj202588.top/Article/details/gtqdsbmfvo.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gtzwwrpnuv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuxming.cn/Article/details/gtrmjqjtsh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cqqwz.cn/Article/details/gtbaodsgtz.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuanzhike.top/Article/details/gtmabnepkp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gtmxqmhhus.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tian-w.cn/Article/details/gtkphzootn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gtnjqnmxqz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtvtumahbb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gtywgnvzcm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gotoacloud.top/Article/details/gtdmwnfldg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258888.top/Article/details/gtcbhygjnf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhongyouzk.top/Article/details/gttksaulbq.html

[D25] Set 集合去重与交并差
来源：http://dali.kuanghao11.cn/Article/details/gtizwedbto.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xylfe.cn/Article/details/gtxeecnift.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dashuyun.cn/Article/details/gtafmjtpiq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dashuyun.cn/Article/details/gtqeaklxxj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ppjwa.cn/Article/details/gthfahqdjo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtbxrnefpr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daria6918.cn/Article/details/gtzxffmzzj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pycfn.com/Article/details/gttyvvvocc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sxryk.cn/Article/details/gtbvijfdzp.html

[D26] 数组转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtjrgismer.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gtdfrypepd.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gtoyskzujf.html

JS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtievffsrv.html

TS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gtlhqsoxjb.html

Java: String.join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtmjeyykfh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shzxlz.cn/Article/details/gtpuhqpqij.html

Ruby: arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gthmpezwnf.html

C#:   string.Join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gtzvvzjqja.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttmbwrfne.html

E. 字符串处理
来源：http://dali.gaohongyu789.top/Article/details/gtwtnvdkia.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtdfwcalvr.html

[E01] 拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtfemmhbtr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cashguo.top/Article/details/gtkllffdkr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.kuanghao11.cn/Article/details/gtubpqbgrf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtuwamjofk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtlqvjvgko.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gtctstvzcq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.iojbl.cn/Article/details/gtxxhbyvni.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sweek.top/Article/details/gtnhcrogyi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtddofwoia.html

[E02] 重复字符串
来源：http://dali.quarkkingdee.top/Article/details/gtkcizfekz.html

Py:   "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtdmkqugkv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.meibo888.top/Article/details/gtkdlmimfb.html

JS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrjitonk.html

TS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtodtjmcbr.html

Java: "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtxnlkgcht.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nwbrower.top/Article/details/gttjwcysfc.html

Ruby: "ab" * 3
来源：http://dali.hammf.cn/Article/details/gtymmsncnp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtkdtlobnt.html

[E03] 截取子串
来源：http://dali.havefunace.top/Article/details/gtpxegzcyw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangshuangyany.cn/Article/details/gtnqiheitb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtltyfsfsw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtxicliayz.html

TS:   s.slice(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtqqyfsdxk.html

Java: s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtszxesyjz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xziqi.cn/Article/details/gtjwxwxlmx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gtabzfrfle.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gtnyjdltcd.html

[E04] 查找子串位置
来源：http://dali.jqgfzy.top/Article/details/gtxzczuhwl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtryyogtbw.html

PHP:  strpos($s, "x");
来源：http://dali.zhongyouzk.top/Article/details/gtiyesbehs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yuanzhike.top/Article/details/gtqwqjvvyi.html

TS:   s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtuvywriax.html

Java: s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtflvelvhl.html

Go:   strings.Index(s, "x")
来源：http://dali.andypj.xyz/Article/details/gtiwlbignz.html

Ruby: s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtiphbuizf.html

C#:   s.IndexOf("x")
来源：http://dali.meibo888.top/Article/details/gtwalxkqxu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenlongwang.top/Article/details/gtuirtgkou.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtbpbvrfqv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ybcxt.top/Article/details/gtoysjcwll.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtmvvgjnvj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258.top/Article/details/gttfycjwej.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gtwcglkams.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.bjfxy.top/Article/details/gthtjonpqp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.vqdsnc.cn/Article/details/gtjipcbyon.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.316326.xyz/Article/details/gtiumyriio.html

[E06] 替换子串
来源：http://dali.vqdsnc.cn/Article/details/gtcdykeflz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gteoetwsow.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cucudq.cn/Article/details/gtkzhopbou.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtkrvhyxhf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtptnesfot.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtcuhawoon.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hammf.cn/Article/details/gttpxlpjea.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.havefunace.top/Article/details/gtttublynz.html

C#:   s.Replace("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbjbdopi.html

[E07] 按分隔符拆分
来源：http://dali.jianghu66.top/Article/details/gtmgbfstys.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tian-w.cn/Article/details/gtggrbxdnk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gturvtevcn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenzaomai.com/Article/details/gttbffejhy.html

TS:   s.split(",")
来源：http://dali.fengsongda.top/Article/details/gtctkjaixx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.9152youxi.cn/Article/details/gtrzjhiilw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthybsptaz.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxinkj.top/Article/details/gtxrtkmnzd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hywenlv.cn/Article/details/gtmknipeet.html

[E08] 数组按分隔符合并
来源：http://dali.yuxming.cn/Article/details/gtpgtcxrxo.html

Py:   ",".join(items)
来源：http://dali.cucudq.cn/Article/details/gtgxscvbjm.html

PHP:  implode(",", $items);
来源：http://dali.daria6918.cn/Article/details/gtxmeayxcy.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gtgvixgwhy.html

TS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtijmtidca.html

Java: String.join(",", items)
来源：http://dali.smart0.xyz/Article/details/gtyzanwgzy.html

Go:   strings.Join(items, ",")
来源：http://dali.fengsongda.top/Article/details/gtxxxqtvki.html

Ruby: items.join(",")
来源：http://dali.pycfn.com/Article/details/gtbidgwkvh.html

C#:   string.Join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtybdcgwhe.html

[E09] 去除所有空白字符
来源：http://dali.tian-w.cn/Article/details/gtfdleckyq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gtslriknun.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xinyue.icu/Article/details/gtgqrfzkfv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtauidtfin.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gtsvnseuue.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtdcpoxezi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxuanxn.top/Article/details/gtogsnesaf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cashguo.top/Article/details/gtcmjpzken.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gtvxfqvteg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.0kj1m.cn/Article/details/gtbotakhgf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtrktjkovp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zdqjudy.top/Article/details/gtuccyxxmi.html

JS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutrnojls.html

TS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtqoemvjwz.html

Java: String.format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtgpjouakq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtxowymypz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gthsnkobju.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenlongwang.top/Article/details/gtjdxzdiqa.html

[E11] 反转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgehljeyf.html

Py:   s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtwduasoee.html

PHP:  strrev($s);
来源：http://dali.cheryme.top/Article/details/gtkkxcrhod.html

JS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gttxuzbviw.html

TS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtsbzhpgxi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cdnleiting.top/Article/details/gtwtevpjbx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtfahjfyll.html

Ruby: s.reverse
来源：http://dali.gzhubu.top/Article/details/gtohjhakgb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gttjftueei.html

[E12] 统计某字符出现次数
来源：http://dali.iojbl.cn/Article/details/gtsroycgpc.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gtaynnrqon.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gtdldmqthq.html

JS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gtukdftehy.html

TS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gtcvxbvyzm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.9152youxi.cn/Article/details/gtzpgfhctn.html

Go:   strings.Count(s, "a")
来源：http://dali.tian-w.cn/Article/details/gtctiphwye.html

Ruby: s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gtykdmqazy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jianghu66.top/Article/details/gtwjmxueae.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtrexdpqou.html

Py:   for ch in s: print(ch)
来源：http://dali.pycfn.com/Article/details/gtphdtvxwf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gtvhfjynlj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmsemlgw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtiptjlnxf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zycfv.cn/Article/details/gtmnvzbxzy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sweek.top/Article/details/gtiymqxuma.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnqzz.top/Article/details/gthzodqxdo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ivvv.top/Article/details/gtpstxidvd.html

[E14] URL 编码与 Base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylbqdium.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cashguo.top/Article/details/gtetgdlhmr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtbejmurns.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cheryme.top/Article/details/gttqunytwa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigfzy.top/Article/details/gttqnywfub.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtwxhwardx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hammf.cn/Article/details/gtmrycfcej.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinghuilouyu.cn/Article/details/gttjvstxgy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sweek.top/Article/details/gtvlxyilis.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhixingplan.top/Article/details/gttoljdxzv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ppjwa.cn/Article/details/gtiefzxmnb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtplwhcwzt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hywenlv.cn/Article/details/gtlpvoobti.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gzhubu.top/Article/details/gtgfjoqwty.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sysykeji.top/Article/details/gtrocxqluk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigfzy.top/Article/details/gtrltpnjel.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gtojgeomsb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.bjfxy.top/Article/details/gtcmqsknrk.html

[E16] 数字千分位
来源：http://dali.tanke756.top/Article/details/gtwrtwcmhq.html

Py:   f"{1234567:,}"
来源：http://dali.tanke756.top/Article/details/gtradlrfjo.html

PHP:  number_format(1234567);
来源：http://dali.ehwqpu.com/Article/details/gtxwzurjne.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gtuigvvgfj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtxhmwuten.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gtwzztooai.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgfzy.top/Article/details/gtqmqoagjk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gtwoqrwngo.html

C#:   1234567.ToString("N0")
来源：http://dali.wangdashe.top/Article/details/gtmyxsteiv.html

[E17] 首字母大写
来源：http://dali.tianlin.xyz/Article/details/gtawoqehuo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gtkplvwxdj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.smart0.xyz/Article/details/gtpkydydrq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtecjluzzs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gtaxjmeoxo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gtrqljtnos.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ehwqpu.com/Article/details/gtyjvucahh.html

Ruby: s.capitalize
来源：http://dali.hnqzz.top/Article/details/gtqswhzbme.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cqqwz.cn/Article/details/gtuotarzua.html

[E18] 模板占位符替换
来源：http://dali.wangdashe.top/Article/details/gtvmgoecgs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tianlin.xyz/Article/details/gtrdjvhzqa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xinyue.icu/Article/details/gtqrheojoh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtdbkpspdn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtswllptou.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtnskilngq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yonumen.top/Article/details/gtqygpqqzw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gtfehcrrht.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.vqdsnc.cn/Article/details/gtzbfnycri.html

[E19] 多行文本按行拆分
来源：http://dali.hammf.cn/Article/details/gtthxyzwin.html

Py:   s.splitlines()
来源：http://dali.chenlongwang.top/Article/details/gtohibofuq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtuhthbyyy.html

JS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gtueybgdtm.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtpnxrfvld.html

Java: s.lines().toList()
来源：http://dali.guannengcc.top/Article/details/gtxdhjards.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gtiedztgdx.html

Ruby: s.lines
来源：http://dali.zhengqikj.top/Article/details/gteurikmoq.html

C#:   s.Split('\n')
来源：http://dali.shuidangran.top/Article/details/gtzydmtqrd.html

[E20] 判断字符串是否为空
来源：http://dali.svipenyu.cn/Article/details/gtmqxssnqd.html

Py:   if not s:
来源：http://dali.daria6918.cn/Article/details/gtincmijue.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gtjkfqjcac.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zdqjudy.top/Article/details/gtuynncosv.html

TS:   if (s === "") {}
来源：http://dali.dashuyun.cn/Article/details/gtlbmcpvtc.html

Java: if (s.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtovwmlqlj.html

Go:   if s == "" {}
来源：http://dali.jinqigfzy.top/Article/details/gtwuvbzijd.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gtkaybtxfg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufbqgobt.html

[E21] 超长截断加省略号
来源：http://dali.316326.xyz/Article/details/gtneouhugn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gtsqiuajzj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtmgdijbik.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkorrlhfg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtcpbgvxvo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtyngmixas.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pycfn.com/Article/details/gtlajotufg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gttsmzsaab.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtucqywigx.html

[E22] 字节长度与字符长度
来源：http://dali.hfpthk.cn/Article/details/gtfkbeeprn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.0kj1m.cn/Article/details/gtbdmfeiwe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtenyrcsui.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gtgauiwapl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gtjzaotczc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtqrsnntvx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtohokpdcy.html

Ruby: s.bytesize;  s.length
来源：http://dali.sweek.top/Article/details/gtjgbstrwt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtumxuioww.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyvrzkiq.html

F. 文件与目录
来源：http://dali.yanxiufei.cn/Article/details/gtpbqvexot.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtmgznqron.html

[F01] 读取整个文件
来源：http://dali.hongshengwenyu.top/Article/details/gtpkktyggs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinghuilouyu.cn/Article/details/gthgfhjldc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtdoblgefa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gtubpqiaxl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtlhfkouzs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtfteugmwf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gtdxvavmgm.html

Ruby: File.read("a.txt")
来源：http://dali.yongpay.top/Article/details/gtkfuiuyjj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtlhqeffmq.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gtjjmsobrd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gzhubu.top/Article/details/gtbuwnqnoc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtdbohjouo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtytszyxpu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gtueoccqnd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtpoxxjbkq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhongyouzk.top/Article/details/gtjquvsxrf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ppjwa.cn/Article/details/gtjmavxelu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.vqdsnc.cn/Article/details/gtchnteogk.html

[F03] 写入文件（覆盖）
来源：http://dali.zhengqikj.top/Article/details/gtmdavtbrm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fzhhl.top/Article/details/gtqglnemcl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtacquifob.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtcwjbamli.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtkzrxclow.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cheryme.top/Article/details/gtuofbuvxa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ppjwa.cn/Article/details/gtlwlzqgnl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhixingplan.top/Article/details/gttkufsrqv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbedvzpfm.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gtmvcavfto.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtemfazcff.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gtraleurez.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gtkanoglkj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynkldgor.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nwbrower.top/Article/details/gtdmyxwqyq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtwqqquqdy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.birdmap.top/Article/details/gtlysotqik.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gtaafplneo.html

[F05] 判断文件或目录是否存在
来源：http://dali.guowangkeji.top/Article/details/gtkjaicnbr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jianghu66.top/Article/details/gtojxqifxd.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtrfekqeut.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjsfhpvh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtxszpscxm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtzltegsac.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jlsjyb.cn/Article/details/gtdagfhtil.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteohwgeuf.html

C#:   File.Exists("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtwrojfbif.html

[F06] 删除文件
来源：http://dali.birdmap.top/Article/details/gttotzfyqm.html

Py:   os.remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtqxgxlcid.html

PHP:  unlink("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtsbqfbyks.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtfcydurpl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtpcdjytup.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtuzffjnlt.html

Go:   os.Remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtfjdgbruu.html


<!-- 参考信息 -->