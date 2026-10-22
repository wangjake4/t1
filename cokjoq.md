代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtwzbwernh.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258888.top/Article/details/gtvkmmvfcc.html

C#:   list.Max();  list.Min()
来源：http://dali.zhoulong.xyz/Article/details/gthldsagfp.html

[D18] 扁平化嵌套数组
来源：http://dali.yueranfly.top/Article/details/gtzeomiihk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxuanxn.top/Article/details/gtwmzavvhf.html

PHP:  array_merge(...$nested);
来源：http://dali.chenlongwang.top/Article/details/gtaevvtstl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigfzy.top/Article/details/gtwwjyazif.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpopplver.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtvojfbvzk.html

Go:   // 手写双层循环
来源：http://dali.316326.xyz/Article/details/gtvhykanam.html

Ruby: nested.flatten
来源：http://dali.cqqwz.cn/Article/details/gtgfavknyk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pycfn.com/Article/details/gtstnaaape.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gtqsgcnwup.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gogol.net.cn/Article/details/gtuooecjeg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gtbfjfadgn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yueranfly.top/Article/details/gthypfqafq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shuidangran.top/Article/details/gtgmsjshno.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dashuyun.cn/Article/details/gtmxgmwrdf.html

Go:   // 手写 map[string][]T
来源：http://dali.vqdsnc.cn/Article/details/gteykyytsp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gotoacloud.top/Article/details/gtqrhakezb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj202588.top/Article/details/gtkoqqgzqx.html

[D20] 统计每个元素出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtsqtfyioz.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gtfdczeobc.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmlzidqk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gtrevpcvgu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtadkxfwjc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gtiprastey.html

Go:   // 手写 map[T]int
来源：http://dali.gzhubu.top/Article/details/gtfxelmvtv.html

Ruby: arr.tally
来源：http://dali.hnxiangtu.top/Article/details/gtbcjqoipq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangdashe.top/Article/details/gtblktdklu.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258.top/Article/details/gtfxvkgpjr.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gtnxscdiat.html

PHP:  in_array($x, $arr, true);
来源：http://dali.redwolf501.top/Article/details/gtqsrowadx.html

JS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtevkdjpxw.html

TS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtggsnbsbq.html

Java: list.contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtctatlwuv.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtodmlgfxi.html

Ruby: arr.include?(x)
来源：http://dali.ppjwa.cn/Article/details/gtxtsnezai.html

C#:   list.Contains(x)
来源：http://dali.yongpay.top/Article/details/gtykjzeiyy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aibaodan.cn/Article/details/gteckkbkiu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.bjfxy.top/Article/details/gtoqurcixz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tianlin.xyz/Article/details/gtqdadxuac.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtaoobndpk.html

TS:   [...arr];
来源：http://dali.xinyue.icu/Article/details/gtgowvjced.html

Java: new ArrayList<>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtllffyyzh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dashuyun.cn/Article/details/gthyzertij.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dashuyun.cn/Article/details/gtrmyoppix.html

C#:   new List<int>(list);
来源：http://dali.ivvv.top/Article/details/gtucijwrtv.html

[D23] reduce 累积计算
来源：http://dali.gaohongyu789.top/Article/details/gtwpjbsopi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jyoumei.cn/Article/details/gtlxpysutd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gtfzghkucm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtzxvpydml.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gtbdkudvcy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.0kj1m.cn/Article/details/gtahebvvms.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gtzeokguhb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yangfankeji.com/Article/details/gtkordnecv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmuwruji.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnqzz.top/Article/details/gtppgqxfmy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dianchejie.cn/Article/details/gtjgdtneno.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gtcyyxdzag.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.daria6918.cn/Article/details/gtbylgkrfl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtncbutqvv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aizwys.cn/Article/details/gtsiqkoadk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aibaodan.cn/Article/details/gtknubrqnu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jiagoushi.top/Article/details/gtrruekoun.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ydzc1.top/Article/details/gttagtjyzu.html

[D25] Set 集合去重与交并差
来源：http://dali.jlsjyb.cn/Article/details/gthiwxeodx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjjtqubf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigufen.top/Article/details/gtfqlcbmkh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gtisdrkqcs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xinyue.icu/Article/details/gttutzrftj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtgdatudcr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigfzy.top/Article/details/gtvdloaskc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxinkj.top/Article/details/gthuzzlioq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtmwglmszg.html

[D26] 数组转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjoetdnat.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtonbspnhu.html

PHP:  implode(", ", $arr);
来源：http://dali.yj202588.top/Article/details/gtbjcqhzqf.html

JS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtxongvujt.html

TS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtaavlpbcc.html

Java: String.join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcouxxkvx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shzxlz.cn/Article/details/gtfbvjojkk.html

Ruby: arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtgyypqjqy.html

C#:   string.Join(", ", list)
来源：http://dali.ivvv.top/Article/details/gtwptphaaw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtuansvtwh.html

E. 字符串处理
来源：http://dali.chenzaomai.com/Article/details/gtszuvcgdg.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtfwyicwye.html

[E01] 拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtcatdbhsv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hysaishi.cn/Article/details/gtlgadoocv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gtsytpxdav.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtcwqlystb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gtrmodvprn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sufxvd.cn/Article/details/gthorcsfkp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tianlin.xyz/Article/details/gtabyidyaq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.meibo888.top/Article/details/gtyantyaro.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtbyuzdjqz.html

[E02] 重复字符串
来源：http://dali.havefunace.top/Article/details/gtjtlkbwjy.html

Py:   "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gtkyytqsvv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenlongwang.top/Article/details/gtcctpfddw.html

JS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqqlgfqw.html

TS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkmlcgja.html

Java: "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtwebwcluv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ybcxt.top/Article/details/gtzxbsmhyr.html

Ruby: "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gthtwbomkt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fengsongda.top/Article/details/gtwxgxinyb.html

[E03] 截取子串
来源：http://dali.hnqzz.top/Article/details/gtyquyuavl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gtqdsjcbwm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtenetefcp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sxryk.cn/Article/details/gtmbdlqncv.html

TS:   s.slice(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtobqpjuvo.html

Java: s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtgdpoajty.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlvpeyyn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhengqikj.top/Article/details/gtuqurjfhw.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhkelevh.html

[E04] 查找子串位置
来源：http://dali.yj20258888.top/Article/details/gttnxvfexa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aizwys.cn/Article/details/gtkerddups.html

PHP:  strpos($s, "x");
来源：http://dali.andypj.xyz/Article/details/gtmwijuhcq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigufen.top/Article/details/gtcgdytddw.html

TS:   s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gtqpyaygiw.html

Java: s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtnugjqnfb.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgfzy.top/Article/details/gtulsgantw.html

Ruby: s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gtzutdqudi.html

C#:   s.IndexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtzmobenve.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yongpay.top/Article/details/gtqggqfrdi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtmmkirgzl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hfpthk.cn/Article/details/gtqnarogzo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gttlyykect.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jianghu66.top/Article/details/gtnkeztsth.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtluhellro.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuxming.cn/Article/details/gtlcdudtnj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hywenlv.cn/Article/details/gtbvhnqsep.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcgfcnpv.html

[E06] 替换子串
来源：http://dali.yongpay.top/Article/details/gtnaeknfxb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtsswytasr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258.top/Article/details/gttdtloqss.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtxnzoarcb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtcpegfxky.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtwhkrobto.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gttfabneht.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj202588.top/Article/details/gtvwrucqcf.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtawydjctj.html

[E07] 按分隔符拆分
来源：http://dali.sufxvd.cn/Article/details/gtreybbakf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgfzy.top/Article/details/gtdkmwqvbz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gthmqmptwr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtutmdja.html

TS:   s.split(",")
来源：http://dali.daria6918.cn/Article/details/gtyqqqzcta.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.birdmap.top/Article/details/gtjsauvzre.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhoulong.xyz/Article/details/gtawujkojp.html

Ruby: s.split(",");  s.split
来源：http://dali.gaohongyu789.top/Article/details/gtmuqrgxsk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangdashe.top/Article/details/gtnnykzkvu.html

[E08] 数组按分隔符合并
来源：http://dali.zhiwuduotai.top/Article/details/gtbzigojux.html

Py:   ",".join(items)
来源：http://dali.jqgfzy.top/Article/details/gtjuajkejc.html

PHP:  implode(",", $items);
来源：http://dali.dashuyun.cn/Article/details/gtjeqrqxcj.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtolntanvr.html

TS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtrobrssnb.html

Java: String.join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gtqexszphq.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gtikgdmgdx.html

Ruby: items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtzyhtyqmu.html

C#:   string.Join(",", items)
来源：http://dali.mhx1999.top/Article/details/gtzzcurtdl.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gtcmnlavcq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhixingplan.top/Article/details/gtyqfgycwt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnqzz.top/Article/details/gtanhdhuvi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gtbiiuztkt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gtwwyksmke.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gtmujnmwcv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcreqcem.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gtimauznmz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xinyue.icu/Article/details/gtsxlfwbue.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pengpengdd.cyou/Article/details/gtehcfuyhr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtvmweioeq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhgnstif.html

JS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtgdxuakgn.html

TS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtrlnqnkcl.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtevbivjhc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtvodrjjqz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtqldrthja.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dashuyun.cn/Article/details/gtqgsyhydw.html

[E11] 反转字符串
来源：http://dali.hnqzz.top/Article/details/gtoumtmoxd.html

Py:   s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtxabsiqyg.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmxcjxsh.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtklncfiua.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtrpkocidj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hammf.cn/Article/details/gtqhaflakn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nwbrower.top/Article/details/gtspdapnuj.html

Ruby: s.reverse
来源：http://dali.birdmap.top/Article/details/gtcemezoxi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtmlkfujdo.html

[E12] 统计某字符出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnhfgzjz.html

Py:   s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtpvxnjeqt.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangtech.top/Article/details/gtnilncdfa.html

JS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gtkwmcsemk.html

TS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gtvyymxpsm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gtmamtrmuy.html

Go:   strings.Count(s, "a")
来源：http://dali.xylfe.cn/Article/details/gtauvfnnnv.html

Ruby: s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtxlvpujkj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxinkj.top/Article/details/gtnwhdbmtu.html

[E13] 逐字符遍历
来源：http://dali.jinqigfzy.top/Article/details/gtvdvutpek.html

Py:   for ch in s: print(ch)
来源：http://dali.hongshengwenyu.top/Article/details/gtpjbiydyr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yongpay.top/Article/details/gtfnjiesuc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtlgnbnudh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtvwzgvtpk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sxryk.cn/Article/details/gtbidpayls.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.c1oappe.top/Article/details/gtwocxefmq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pycfn.com/Article/details/gtqfjkugyj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtygavpnys.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmohzbqes.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gtdonetins.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtbuwirqun.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yangfankeji.com/Article/details/gtmoiqeynz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj202588.top/Article/details/gtnnctajkz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gthrhzsynm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhixingplan.top/Article/details/gtjuixadnq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.andypj.xyz/Article/details/gtfozpunrq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sysykeji.top/Article/details/gtkxfoeetn.html

[E15] HTML 转义 / 反转义
来源：http://dali.aibaodan.cn/Article/details/gtmhukhsur.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.smart0.xyz/Article/details/gtzatyizps.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pycfn.com/Article/details/gtjitbxwoo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yanxiufei.cn/Article/details/gthrvltdoh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tanke756.top/Article/details/gtdcxwaszc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tian-w.cn/Article/details/gtcryxudpv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cashguo.top/Article/details/gtxunilzhx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yueranfly.top/Article/details/gtpsmclnur.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtpmrzowqt.html

[E16] 数字千分位
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyakyihg.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gtohsxeeno.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gtlslrtrli.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtkbtrkeqt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gttszzxyhq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gtzlritnyy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.birdmap.top/Article/details/gtsagqfrus.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hammf.cn/Article/details/gtbzckrlix.html

C#:   1234567.ToString("N0")
来源：http://dali.ppjwa.cn/Article/details/gtbqivgwud.html

[E17] 首字母大写
来源：http://dali.chenjidiqi.icu/Article/details/gtwnqlfzqa.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gtktilcwlj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtveoirdmj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gtrdkuvmaj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gtkgwmhath.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gotoacloud.top/Article/details/gtyavcwwmb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrrvjzlq.html

Ruby: s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gtnlwafwev.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aizwys.cn/Article/details/gtumsdmoao.html

[E18] 模板占位符替换
来源：http://dali.yj20258.top/Article/details/gtmjswmswt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.andypj.xyz/Article/details/gtujwppllm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hfpthk.cn/Article/details/gtxgyxuktk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtlcvqynrh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtfwfrmnxb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtmgihymeu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtgkghxulp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gtawuifxpk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gtfzzdhqif.html

[E19] 多行文本按行拆分
来源：http://dali.zhongyouzk.top/Article/details/gtpkqnpldd.html

Py:   s.splitlines()
来源：http://dali.chenjidiqi.icu/Article/details/gtqsabnrvg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtvkybqanh.html

JS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gtqezgvpqf.html

TS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtjjalulbe.html

Java: s.lines().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtuhrqehgb.html

Go:   strings.Split(s, "\n")
来源：http://dali.hammf.cn/Article/details/gtnkbiyzub.html

Ruby: s.lines
来源：http://dali.ehwqpu.com/Article/details/gtsiwmrgoy.html

C#:   s.Split('\n')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpitjkmgq.html

[E20] 判断字符串是否为空
来源：http://dali.tianlin.xyz/Article/details/gtcjpawhxs.html

Py:   if not s:
来源：http://dali.chenjidiqi.icu/Article/details/gtblmnrbft.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.meibo888.top/Article/details/gthvflzqih.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dianchejie.cn/Article/details/gtwxpxbktf.html

TS:   if (s === "") {}
来源：http://dali.gotoacloud.top/Article/details/gtbxgtpjgt.html

Java: if (s.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gtllwhbcok.html

Go:   if s == "" {}
来源：http://dali.mhx1999.top/Article/details/gtmfumfghd.html

Ruby: if s.empty?
来源：http://dali.jinqigfzy.top/Article/details/gtpqalrakn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtztmtgbvs.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gtnnkcmidp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhiwuduotai.top/Article/details/gtwrsjtckg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtvcwbbqqo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtsgcqeysb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtobxfnkxr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtfpuxquhs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gtdvyareqv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gtdyjagfdd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtltwgrhib.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gtdvmnbpsn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gtvbpdeacq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtfrzjjltq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtbwuunyeo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtbwohekaf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yangfankeji.com/Article/details/gtmllublhm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtsbyhrbxe.html

Ruby: s.bytesize;  s.length
来源：http://dali.daxiang520.top/Article/details/gtuyscnbhz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtmxhygzen.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtahrbflkf.html

F. 文件与目录
来源：http://dali.wangshuangyany.cn/Article/details/gtsungelsw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtthcuodww.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gtewdvcxjq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhixingplan.top/Article/details/gtvgivyvqm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtrixbpqkx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxinkj.top/Article/details/gtxwwoaotk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtvulxekod.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtxbjhyvwk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gthsguixiq.html

Ruby: File.read("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtpkurcmnb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtzqyiktxs.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gtohebbtvr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zdqjudy.top/Article/details/gtmifxtfxo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gteklhhcye.html


<!-- 参考信息 -->