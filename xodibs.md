代发 wailian999

C#:   list.Reverse();
来源：http://dali.ydzc1.top/Article/details/gtshhoecee.html

[D12] 查找元素下标
来源：http://dali.jianghu66.top/Article/details/gtdovauupt.html

Py:   arr.index(x);  x in arr
来源：http://dali.tanke756.top/Article/details/gtjglxntas.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtcfqlbnqd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gtzvjyaink.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtrnxsjscn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sweek.top/Article/details/gtcvzgzvgv.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtepwrsgbo.html

Ruby: arr.index(x)
来源：http://dali.jinqigufen.top/Article/details/gtpxudrcud.html

C#:   list.IndexOf(x);
来源：http://dali.quarkkingdee.top/Article/details/gtmbrnyrmc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hammf.cn/Article/details/gtpiosrdxw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgmfescp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yvedp.cn/Article/details/gtblbqcwih.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtlxwisjcq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gtjtiaiylr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtcfznkwjo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gogol.net.cn/Article/details/gtvdqguuxu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shangyingyoupin.top/Article/details/gtuizugozb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jianghu66.top/Article/details/gtajwilogg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tianlin.xyz/Article/details/gtbgiqfyjy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xinyue.icu/Article/details/gtnnzxzsyy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenlongwang.top/Article/details/gttyqrloqp.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtkczcofev.html

TS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gttqfgqnuf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ivvv.top/Article/details/gthxftjzxt.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtabfdpwtu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sysykeji.top/Article/details/gtdwcvqtoz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sysykeji.top/Article/details/gtgndqtmwe.html

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gtimqsbzhn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gtrjattvci.html

PHP:  array_unique($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtcuvlouwx.html

JS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gtgogteldc.html

TS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtbtljxkqo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gtxawfnffc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cdnleiting.top/Article/details/gttgrucqlg.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gttgbkwunl.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gtuiqqqvrd.html

[D16] 求和与平均值
来源：http://dali.zdqjudy.top/Article/details/gtrzpdhqtn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqlxgxhi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gzhubu.top/Article/details/gtxvevzrso.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtdsgvjnkk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtxvatdhxd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuanzhike.top/Article/details/gtvjgboulf.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gtwcowofmh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgfzy.top/Article/details/gtuewoburf.html

C#:   list.Sum();  list.Average()
来源：http://dali.jiagoushi.top/Article/details/gtlbekeuyn.html

[D17] 最大值与最小值
来源：http://dali.nanxuanxn.top/Article/details/gtgoehklwz.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtrbnmtran.html

PHP:  max($arr);  min($arr);
来源：http://dali.dianchejie.cn/Article/details/gtxxwefyfq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dianchejie.cn/Article/details/gtikdzqyoh.html

TS:   Math.max(...arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtvxidkxvj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hfpthk.cn/Article/details/gtfbcnwhjc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtburznvwv.html

Ruby: arr.max;  arr.min
来源：http://dali.aibaodan.cn/Article/details/gtktthhczx.html

C#:   list.Max();  list.Min()
来源：http://dali.nwbrower.top/Article/details/gtbehvwhpz.html

[D18] 扁平化嵌套数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsyhsfxh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.0kj1m.cn/Article/details/gtuibkvxko.html

PHP:  array_merge(...$nested);
来源：http://dali.tanke756.top/Article/details/gtzzhczkjf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuxming.cn/Article/details/gtuwpoybwu.html

TS:   nested.flat();
来源：http://dali.jinghuilouyu.cn/Article/details/gtpioefsiv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhixingplan.top/Article/details/gtsyktvejx.html

Go:   // 手写双层循环
来源：http://dali.snrcjt.cn/Article/details/gtcjelylbz.html

Ruby: nested.flatten
来源：http://dali.yvedp.cn/Article/details/gtrfycnghx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangdashe.top/Article/details/gtelqedetg.html

[D19] 按字段分组
来源：http://dali.guowangkeji.top/Article/details/gtfobbeawa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xziqi.cn/Article/details/gtqqbdguze.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tian-w.cn/Article/details/gthechalxg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daxiang520.top/Article/details/gtsrgjgnji.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ybcxt.top/Article/details/gtwrnsqdrs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcflwgyz.html

Go:   // 手写 map[string][]T
来源：http://dali.pengpengdd.cyou/Article/details/gtpnzkaxgj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shzxlz.cn/Article/details/gtskxskvvi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.feifeiyinyue.top/Article/details/gtwgwzozbi.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gtbggwflby.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtionyyeyg.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gtrmmzllvd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtziqegpot.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gtjpeltnsq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xinyue.icu/Article/details/gtefvhlaxh.html

Go:   // 手写 map[T]int
来源：http://dali.hnxiangtu.top/Article/details/gthkuoctut.html

Ruby: arr.tally
来源：http://dali.chenzaomai.com/Article/details/gtwuthzogj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jianghu66.top/Article/details/gtbeicyevz.html

[D21] 判断是否包含某元素
来源：http://dali.dashuyun.cn/Article/details/gtvrpedtwe.html

Py:   x in arr
来源：http://dali.haohaochexian.top/Article/details/gtsqttaxzu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jyoumei.cn/Article/details/gtqzzykezs.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtbdevjgau.html

TS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtswmphtyj.html

Java: list.contains(x)
来源：http://dali.aizwys.cn/Article/details/gtvvdvstqb.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtlmmpwxst.html

Ruby: arr.include?(x)
来源：http://dali.guowangkeji.top/Article/details/gtbivqiuhg.html

C#:   list.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtwnxijcfs.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nwbrower.top/Article/details/gtkgmhuqix.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgfzy.top/Article/details/gtrvicwzti.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aibaodan.cn/Article/details/gtcdeuhzwm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxuanxn.top/Article/details/gterrtiwvl.html

TS:   [...arr];
来源：http://dali.cashguo.top/Article/details/gtodkeyjaz.html

Java: new ArrayList<>(list);
来源：http://dali.dianchejie.cn/Article/details/gthhgiqbfg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sysykeji.top/Article/details/gtjngyfyot.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldkinzeu.html

C#:   new List<int>(list);
来源：http://dali.zhoulong.xyz/Article/details/gtrethwffv.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gtqmeqbrrs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ehwqpu.com/Article/details/gttzloqkdy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.316326.xyz/Article/details/gtcgcuazsa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pycfn.com/Article/details/gtaxergyvz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gtoogrxesb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gtukvmazrb.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gtroywmsii.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenzaomai.com/Article/details/gtrrpijcsb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gtzrcdhfsf.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxuanxn.top/Article/details/gtnooqcbvx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jiagoushi.top/Article/details/gtdtgtglbv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtjuommdpv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jyoumei.cn/Article/details/gtcljaxltg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtzatygchx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hfpthk.cn/Article/details/gtrffzyrdv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.0kj1m.cn/Article/details/gtordoxift.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guannengcc.top/Article/details/gtcfgewbct.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shuidangran.top/Article/details/gtefzqihnt.html

[D25] Set 集合去重与交并差
来源：http://dali.hnxiangtu.top/Article/details/gtatjpeqhu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj202588.top/Article/details/gtgixdlznf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.birdmap.top/Article/details/gtbwsismio.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtzfttpjtp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guannengcc.top/Article/details/gtngmbppyb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aibaodan.cn/Article/details/gtlajrobwm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ivvv.top/Article/details/gtmcvkfwnw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.smart0.xyz/Article/details/gtvpiynave.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yonumen.top/Article/details/gtdqveeggu.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtjruxvffq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yangfankeji.com/Article/details/gtgspstzah.html

PHP:  implode(", ", $arr);
来源：http://dali.dashuyun.cn/Article/details/gtjfdjlgny.html

JS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtgtopslsg.html

TS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtyubscuvl.html

Java: String.join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gtrxsymusg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daxiang520.top/Article/details/gtwjdvtlqk.html

Ruby: arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbkydvph.html

C#:   string.Join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gtckaahrzy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtuepmcxsf.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gtfbscpcqg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtdoypidrn.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtmvkpupga.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yueranfly.top/Article/details/gtvqibgfrc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxinkj.top/Article/details/gtifccuxaa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtirfscgrh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gtthpjrpkn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gtscnntpam.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gthlwcmmxn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.c1oappe.top/Article/details/gtzimuecjg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtgkglilrl.html

[E02] 重复字符串
来源：http://dali.yuanzhike.top/Article/details/gtvicdpjuf.html

Py:   "ab" * 3
来源：http://dali.hammf.cn/Article/details/gtobokdwgv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sysykeji.top/Article/details/gtuqhpdbbp.html

JS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvgeeyaz.html

TS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtoclrbojz.html

Java: "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtqrsgqmxx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gteudylpog.html

Ruby: "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gtiromyivx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gtbnnmbvuf.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gtpxaalzfg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gaohongyu789.top/Article/details/gtkrpxvuxp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlasqhsaf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuiqkwba.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtvighwjjd.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtfdfnxdmt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jianghu66.top/Article/details/gttxdfvpjl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.haohaochexian.top/Article/details/gtonxgzcmg.html

C#:   s.Substring(1, 3)
来源：http://dali.cashguo.top/Article/details/gtgsflnuso.html

[E04] 查找子串位置
来源：http://dali.jyoumei.cn/Article/details/gtfrqhweii.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aizwys.cn/Article/details/gttuctmzyi.html

PHP:  strpos($s, "x");
来源：http://dali.ivvv.top/Article/details/gtgakbfpwl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnqzz.top/Article/details/gtyoxsrpgs.html

TS:   s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtwylkchfb.html

Java: s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gthkrlkrup.html

Go:   strings.Index(s, "x")
来源：http://dali.daxiang520.top/Article/details/gtjfovvtmi.html

Ruby: s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gteotjbads.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gtvbzqjvtd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yonumen.top/Article/details/gtzywcdwfp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxuanxn.top/Article/details/gttvomyilu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yongpay.top/Article/details/gtqxvhypjy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtfvuifttt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.mhx1999.top/Article/details/gtrleslpjx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtejduzmlh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yvedp.cn/Article/details/gtxkvlqknr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258.top/Article/details/gtekxnqlad.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtoulirfdd.html

[E06] 替换子串
来源：http://dali.dashuyun.cn/Article/details/gtpgbrhmku.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gtizfezmgc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gtqvqeykxk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtkjizlbvl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjvcrbwi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtndxssfxh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtyucjbsts.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtghjednek.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtgblrabqp.html

[E07] 按分隔符拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtojrtphec.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhiwuduotai.top/Article/details/gtatmsiaqx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfqiohcd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtptpwwmdi.html

TS:   s.split(",")
来源：http://dali.gaohongyu789.top/Article/details/gtowacsbuf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigfzy.top/Article/details/gtuhhsuexm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gzhubu.top/Article/details/gtyzbsejeh.html

Ruby: s.split(",");  s.split
来源：http://dali.0kj1m.cn/Article/details/gttwibiryl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hongshengwenyu.top/Article/details/gtetrhehdk.html

[E08] 数组按分隔符合并
来源：http://dali.wangdashe.top/Article/details/gtugftigmx.html

Py:   ",".join(items)
来源：http://dali.yonumen.top/Article/details/gtkhwsijib.html

PHP:  implode(",", $items);
来源：http://dali.zhixingplan.top/Article/details/gtypphuxxb.html

JS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtztozstwf.html

TS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtomwoiaqw.html

Java: String.join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gtfmsgwerx.html

Go:   strings.Join(items, ",")
来源：http://dali.guannengcc.top/Article/details/gttnljdkrk.html

Ruby: items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtwgyburhh.html

C#:   string.Join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gtmrtuczzo.html

[E09] 去除所有空白字符
来源：http://dali.nanxinkj.top/Article/details/gtslozrdgr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthelvlalz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigufen.top/Article/details/gttembpqtr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpowvlrli.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gtppyntlbj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sxryk.cn/Article/details/gtmjrpfslv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ybcxt.top/Article/details/gttjtgscxp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yueranfly.top/Article/details/gtgfkhpcjv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtzhmqzplj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daxiang520.top/Article/details/gttbvdkqtg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqekotwh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomcmuiqd.html

JS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtlbfpsyvm.html

TS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtzdduucet.html

Java: String.format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtjfydkbvp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtqbkgqtgx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtbsdrirur.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.snrcjt.cn/Article/details/gtipputqqc.html

[E11] 反转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtbegovibe.html

Py:   s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtuqhaljin.html

PHP:  strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtlyofkqdi.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmrwiixx.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtboztyknr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jlsjyb.cn/Article/details/gtbekyzqse.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gtamuofyoj.html

Ruby: s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtbhzfebnw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gtidcxagfp.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkmnvasd.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtbebonrne.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcywdnxp.html

JS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gtuxyooxef.html

TS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtrcdcooim.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shzxlz.cn/Article/details/gtwaafdoes.html

Go:   strings.Count(s, "a")
来源：http://dali.cdnleiting.top/Article/details/gtaminthxn.html

Ruby: s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtnqnkoubs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yanxiufei.cn/Article/details/gtjdjkcowe.html

[E13] 逐字符遍历
来源：http://dali.shzxlz.cn/Article/details/gtfoxovyux.html

Py:   for ch in s: print(ch)
来源：http://dali.zycfv.cn/Article/details/gthtuudjma.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gthcxgvnpx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gtfgpqovdd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtkfsxehsf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gzhubu.top/Article/details/gtbuobeptk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtmskhudvo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gtivszufpk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.andypj.xyz/Article/details/gthtkrgrhp.html

[E14] URL 编码与 Base64
来源：http://dali.fengsongda.top/Article/details/gtwwsqrhmw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pycfn.com/Article/details/gtednhnhog.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gtistrrjfb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hongshengwenyu.top/Article/details/gtecyulgyc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cheryme.top/Article/details/gtpqggpeud.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258888.top/Article/details/gtqoxarxly.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gtchxdmbka.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gtpdotmfmm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnqzz.top/Article/details/gtrcyjktli.html

[E15] HTML 转义 / 反转义
来源：http://dali.mhx1999.top/Article/details/gttchqnucw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gtnzbzlfpr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hfpthk.cn/Article/details/gtfsgfmiof.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sysykeji.top/Article/details/gtvvxaihsg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shzxlz.cn/Article/details/gtqvlgltsi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.redwolf501.top/Article/details/gtfftakbrv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.iojbl.cn/Article/details/gtlmzopsin.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dianchejie.cn/Article/details/gtlyyeyloo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gtforlzolp.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gttauxmgyo.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gtyfaaxqee.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gtkhiqpczg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtcmhcrbid.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gthnebtphz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuanzx.com/Article/details/gtwgzwlzhj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenzaomai.com/Article/details/gtbxcuoukt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hfpthk.cn/Article/details/gtypvqqywk.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gtxydqmnvv.html

[E17] 首字母大写
来源：http://dali.birdmap.top/Article/details/gtgnwukbfs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigfzy.top/Article/details/gtkvcthpym.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhengqikj.top/Article/details/gtliprtwkd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtrwlkcmqp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtqqohwoqu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daxiang520.top/Article/details/gthnuplchp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigufen.top/Article/details/gtaxhaxgip.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gtggxruuqm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jlsjyb.cn/Article/details/gtxpkuazec.html

[E18] 模板占位符替换
来源：http://dali.xuetiantiany.cn/Article/details/gtmdshjroi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gtbxpbvzsx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.haohaochexian.top/Article/details/gtzsxczwne.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtbhjmxtkh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtcibvbaem.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtfaqryyok.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubnndesn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gtdqjnoipd.html


<!-- 参考信息 -->