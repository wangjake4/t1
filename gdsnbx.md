代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.316326.xyz/Article/details/gtytcwtefl.html

Java: Collections.reverse(list);
来源：http://dali.cdnleiting.top/Article/details/gtjalynmhr.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gtxodcbvix.html

Ruby: arr.reverse
来源：http://dali.cheryme.top/Article/details/gtewiqlrkn.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gtslgnzutm.html

[D12] 查找元素下标
来源：http://dali.jinqigfzy.top/Article/details/gtiejtzqon.html

Py:   arr.index(x);  x in arr
来源：http://dali.meibo888.top/Article/details/gtxkgbfvwr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpogijerq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gtognxuqpt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzvicwsf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pycfn.com/Article/details/gtywhwsipy.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtyjvsiyxk.html

Ruby: arr.index(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtxwwuhcre.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gtndtrdqft.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gtknnxugvq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.316326.xyz/Article/details/gtahnusoru.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuanzhike.top/Article/details/gtawazzatb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtnpybhvgb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gtoycxvqxz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cheryme.top/Article/details/gtoxpifgmf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gogol.net.cn/Article/details/gtipcfywsh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gtwpfspjbo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258.top/Article/details/gtguzyatvt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sufxvd.cn/Article/details/gtbmzzkefj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guannengcc.top/Article/details/gtpykpnodr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtxzabwqmu.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtippjcrmr.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gtcjjcqsku.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gtqjemmkvp.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gtfrvgjfao.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtdreshtrh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtmubhnjtf.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gtwsuqzrlw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtftkijtcd.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gtvzpkabau.html

JS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtdgjdbdsl.html

TS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtmarrczfq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fzhhl.top/Article/details/gtleeohvhh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gtahevbpxy.html

Ruby: arr.uniq
来源：http://dali.c1oappe.top/Article/details/gtgjdhydnz.html

C#:   list.Distinct().ToList()
来源：http://dali.hywenlv.cn/Article/details/gtibydkwck.html

[D16] 求和与平均值
来源：http://dali.shuidangran.top/Article/details/gtqlnxonqp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gtyzmqjbyy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gteqyxbrip.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gtdtoimjyp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtqmhmyuks.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dianchejie.cn/Article/details/gtxnhcziej.html

Go:   // 手写循环累加
来源：http://dali.xinyue.icu/Article/details/gtimpahsxe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdthhwvle.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gtjuzjquca.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gthuuydydd.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gtcgldjwxy.html

PHP:  max($arr);  min($arr);
来源：http://dali.fengsongda.top/Article/details/gtzwmkqdwd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xinyue.icu/Article/details/gtrowidpyh.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwyuoxfa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aibaodan.cn/Article/details/gtwapewcvt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gthlqriwtp.html

Ruby: arr.max;  arr.min
来源：http://dali.pengpengdd.cyou/Article/details/gtjslydbjx.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gtfbcvufio.html

[D18] 扁平化嵌套数组
来源：http://dali.fzhhl.top/Article/details/gtulokegea.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tianlin.xyz/Article/details/gtfogrcvpq.html

PHP:  array_merge(...$nested);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttoplhchq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gaohongyu789.top/Article/details/gtsjieeujp.html

TS:   nested.flat();
来源：http://dali.wangdashe.top/Article/details/gtsruivyrz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.0kj1m.cn/Article/details/gtpkgniqwe.html

Go:   // 手写双层循环
来源：http://dali.zhoulong.xyz/Article/details/gtvppdozcp.html

Ruby: nested.flatten
来源：http://dali.meibo888.top/Article/details/gteyzsgyuu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yvedp.cn/Article/details/gtrtjjmegn.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gtgltgfrbd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnqzz.top/Article/details/gtxccwqkjb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gttutewpop.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gtwkgpknol.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbpzspdj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnqzz.top/Article/details/gttdtmvnll.html

Go:   // 手写 map[string][]T
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdjxjwmp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zdqjudy.top/Article/details/gtzfkxubpv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ydzc1.top/Article/details/gtpkosrgwh.html

[D20] 统计每个元素出现次数
来源：http://dali.mhx1999.top/Article/details/gtiodsgxmf.html

Py:   Counter(arr)
来源：http://dali.sweek.top/Article/details/gtdwmtjgjy.html

PHP:  array_count_values($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtwrqhxhih.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gtetrokwoh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gtzylgkald.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hammf.cn/Article/details/gtcoweoevf.html

Go:   // 手写 map[T]int
来源：http://dali.shzxlz.cn/Article/details/gtxofjvcuo.html

Ruby: arr.tally
来源：http://dali.gotoacloud.top/Article/details/gtwpzumkhu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigfzy.top/Article/details/gttslkxmno.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gtxxlucukr.html

Py:   x in arr
来源：http://dali.hammf.cn/Article/details/gtuvzapncu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.svipenyu.cn/Article/details/gtfzqkggrm.html

JS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtcxgnmnxl.html

TS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtkzsmfqld.html

Java: list.contains(x)
来源：http://dali.fengsongda.top/Article/details/gtemgbburf.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gteuvcivid.html

Ruby: arr.include?(x)
来源：http://dali.c1oappe.top/Article/details/gtcimzejhr.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnsjjrjx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.meibo888.top/Article/details/gtfjcrhptd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ehwqpu.com/Article/details/gtkhvuokpc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yongpay.top/Article/details/gtizxksfny.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gtunedurvl.html

TS:   [...arr];
来源：http://dali.jlsjyb.cn/Article/details/gtaknkspko.html

Java: new ArrayList<>(list);
来源：http://dali.0kj1m.cn/Article/details/gttqozqqpl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gtljqqasmw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdtruxur.html

C#:   new List<int>(list);
来源：http://dali.ehwqpu.com/Article/details/gteupdwsmr.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gtwpsvkqdb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ehwqpu.com/Article/details/gterujgjjx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.andypj.xyz/Article/details/gtzehmdiws.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gtsjyhthfy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gtncciljri.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shzxlz.cn/Article/details/gtvheetaqc.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gtqbhipyex.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxinkj.top/Article/details/gtervdcsva.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.svipenyu.cn/Article/details/gtenqbtxrs.html

[D24] 字典 / Map 基本操作
来源：http://dali.cucudq.cn/Article/details/gtdpnbxzon.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gtygnvtnss.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ydzc1.top/Article/details/gtjvrsnwwz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guannengcc.top/Article/details/gtbbtwaukn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xylfe.cn/Article/details/gteoapelkw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtzawbcdkz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gtfdtauukm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwgpgmrv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gtajkudaqs.html

[D25] Set 集合去重与交并差
来源：http://dali.pengpengdd.cyou/Article/details/gtrgslbabq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shuidangran.top/Article/details/gtjjubmaus.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gtkvshcekh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guowangkeji.top/Article/details/gttliewboq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gtqvmdflct.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gogol.net.cn/Article/details/gtunzvtwmx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pycfn.com/Article/details/gtcfaydiau.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.vqdsnc.cn/Article/details/gtrdgttrnq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guannengcc.top/Article/details/gtvoemuekq.html

[D26] 数组转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtrzbcljmv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ybcxt.top/Article/details/gtvigumkrg.html

PHP:  implode(", ", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzlhmlsi.html

JS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtrxpagjvp.html

TS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtgtvpdymc.html

Java: String.join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtucqmxvtx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgqkewqd.html

Ruby: arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmacktvr.html

C#:   string.Join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gtgmlkczfw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtgbufvaco.html

E. 字符串处理
来源：http://dali.zhixingplan.top/Article/details/gttaddpdnh.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtrcklfffd.html

[E01] 拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gttacvwujn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.redwolf501.top/Article/details/gtpcguhrzk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtswteubln.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtvbaspjpn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gtyhzkqetl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.havefunace.top/Article/details/gtpjqbbgts.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtqsfwndre.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gtklwyluvm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtptxhemzm.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gtrzwnwyxi.html

Py:   "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtdjzwpvsf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtafgvlpjj.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfotbowpr.html

TS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtgimvetcy.html

Java: "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtxdfzgukc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtncjjeqhq.html

Ruby: "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gtbcwfvxqa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gtyfhkcfeh.html

[E03] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gtseadmxlv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zdqjudy.top/Article/details/gtxyducckm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtcjxpnczw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtmtpupeez.html

TS:   s.slice(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtcwtjaaqb.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtyazdtqcm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zycfv.cn/Article/details/gttpwyhdpv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.iojbl.cn/Article/details/gtnupvqxwi.html

C#:   s.Substring(1, 3)
来源：http://dali.aizwys.cn/Article/details/gtbngzvrxt.html

[E04] 查找子串位置
来源：http://dali.quarkkingdee.top/Article/details/gtgkqbsqqp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgelcokmb.html

PHP:  strpos($s, "x");
来源：http://dali.hfpthk.cn/Article/details/gtapdrewsi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cheryme.top/Article/details/gtmzemdypu.html

TS:   s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtrmvhbycx.html

Java: s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gtpytuucxe.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gtwxxqrxot.html

Ruby: s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtqniubwvs.html

C#:   s.IndexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtkkhwaktl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuanzx.com/Article/details/gtgwyydyod.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aibaodan.cn/Article/details/gtsckrjoue.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhixingplan.top/Article/details/gtzafuuftn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtrrxexyom.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shzxlz.cn/Article/details/gtqkmhiswf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtbklfbjvv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.svipenyu.cn/Article/details/gtdoxdljwu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yvedp.cn/Article/details/gtfrjufyuy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hammf.cn/Article/details/gtwtqmweyf.html

[E06] 替换子串
来源：http://dali.pengpengdd.cyou/Article/details/gtxfmiwmst.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtrqlyfhsk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jiagoushi.top/Article/details/gttttawyfg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtfalqhchx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtwdkyeydx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtnqfvmdbu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gtirnnhhhl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtbdcbzntl.html

C#:   s.Replace("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtbksmhavg.html

[E07] 按分隔符拆分
来源：http://dali.shangyingyoupin.top/Article/details/gthgddilks.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgfzy.top/Article/details/gtpkqpjafe.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtmkxczhmf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gtmizjgmum.html

TS:   s.split(",")
来源：http://dali.aibaodan.cn/Article/details/gtlgztnpen.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xylfe.cn/Article/details/gtncheifdu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hywenlv.cn/Article/details/gtzokmeeao.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gtggxxcylt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xylfe.cn/Article/details/gtbrfblsph.html

[E08] 数组按分隔符合并
来源：http://dali.daria6918.cn/Article/details/gtphquwljw.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gtdyuzzyrm.html

PHP:  implode(",", $items);
来源：http://dali.tian-w.cn/Article/details/gtluvfqqxa.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtdtgxqtij.html

TS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtucklhokp.html

Java: String.join(",", items)
来源：http://dali.cashguo.top/Article/details/gtcavbsuep.html

Go:   strings.Join(items, ",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuehvupia.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtidpnynov.html

C#:   string.Join(",", items)
来源：http://dali.yvedp.cn/Article/details/gtilwvgjlv.html

[E09] 去除所有空白字符
来源：http://dali.yuxming.cn/Article/details/gthhximqbj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cqqwz.cn/Article/details/gtqiphjhit.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gogol.net.cn/Article/details/gthpasuvna.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gaohongyu789.top/Article/details/gtqmmhhadw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gtgytnkaxg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gtpbtinudk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.svipenyu.cn/Article/details/gtbsajvvnv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.quarkkingdee.top/Article/details/gtrjssxouy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sysykeji.top/Article/details/gtsiybnsbg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gogol.net.cn/Article/details/gtudvvtmkm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gttcztssmc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yonumen.top/Article/details/gtetslkpnu.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtihsjujsr.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtwyzbcbir.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvkoxrve.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtpaiyakvm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gtqauwpoow.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhiwuduotai.top/Article/details/gtswdvlbiy.html

[E11] 反转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabqztuel.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gthlwdovsr.html

PHP:  strrev($s);
来源：http://dali.tian-w.cn/Article/details/gtyqtheeej.html

JS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gthdqtogcc.html

TS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtmiqftkwl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yanxiufei.cn/Article/details/gtrlelymrs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sysykeji.top/Article/details/gtzljvornd.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtirdrqfax.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gtujqrbzau.html

[E12] 统计某字符出现次数
来源：http://dali.pycfn.com/Article/details/gtvusdmnah.html

Py:   s.count("a")
来源：http://dali.cucudq.cn/Article/details/gtxfolqnqo.html

PHP:  substr_count($s, "a");
来源：http://dali.snrcjt.cn/Article/details/gtwgwxjjfi.html

JS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtxpxywmwo.html

TS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gtfhgfqqhq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.0kj1m.cn/Article/details/gtpbvvxcdd.html

Go:   strings.Count(s, "a")
来源：http://dali.chenlongwang.top/Article/details/gtnetoiahy.html

Ruby: s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtqncxgqlk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258888.top/Article/details/gtbdsbcspu.html

[E13] 逐字符遍历
来源：http://dali.birdmap.top/Article/details/gtnrxkwnzm.html

Py:   for ch in s: print(ch)
来源：http://dali.cheryme.top/Article/details/gtrhiflltn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gthffxcmip.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gteqqlfcdi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtajddbccr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtbuhmkmyw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.iojbl.cn/Article/details/gtviofmrxf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gtopshvezd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.meibo888.top/Article/details/gtqamlsiqg.html

[E14] URL 编码与 Base64
来源：http://dali.hongshengwenyu.top/Article/details/gtbrarbqhx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.fengsongda.top/Article/details/gtykbswoyw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.iojbl.cn/Article/details/gtlwecskla.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hongshengwenyu.top/Article/details/gtmvsmvwpg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtdxochpiz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.c1oappe.top/Article/details/gttdgyzqyg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guannengcc.top/Article/details/gtgyqkzvqo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.smart0.xyz/Article/details/gtqtblyurq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtruxhpxkw.html

[E15] HTML 转义 / 反转义
来源：http://dali.meibo888.top/Article/details/gtuquazlbe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.0kj1m.cn/Article/details/gtwfxbkrvh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnghctym.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.smart0.xyz/Article/details/gtzojbsbvy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gtgswnebpi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gtywdnhynk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpmgdhoj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtecbzwxyu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shzxlz.cn/Article/details/gtjescrajk.html

[E16] 数字千分位
来源：http://dali.xuanzx.com/Article/details/gtovcxdwcv.html

Py:   f"{1234567:,}"
来源：http://dali.zhengqikj.top/Article/details/gthernhvtk.html

PHP:  number_format(1234567);
来源：http://dali.ybcxt.top/Article/details/gtphqiaijf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtriwqnivo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtdbnsijcv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gtwrflzqkf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jlsjyb.cn/Article/details/gtvgeqxypi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.redwolf501.top/Article/details/gtmqcahslr.html

C#:   1234567.ToString("N0")
来源：http://dali.sysykeji.top/Article/details/gtmabfstxz.html

[E17] 首字母大写
来源：http://dali.shangyingyoupin.top/Article/details/gtvqrjorhk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgfzy.top/Article/details/gtnaorbrbc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj202588.top/Article/details/gtfgzwneke.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gtiqtvkxxl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtftkhzxdj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dianchejie.cn/Article/details/gtlbcspgpg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtziblwdcv.html

Ruby: s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gtkedgqgxq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cdnleiting.top/Article/details/gtapaaeeai.html

[E18] 模板占位符替换
来源：http://dali.zhongyouzk.top/Article/details/gtsbpqqdgy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtxsmvdfbc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gtqwfgquvq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtvrofpkbl.html


<!-- 参考信息 -->