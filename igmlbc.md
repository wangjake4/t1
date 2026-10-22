代发 wailian999

Ruby: arr.index(x)
来源：http://dali.hywenlv.cn/Article/details/gtbeqoputg.html

C#:   list.IndexOf(x);
来源：http://dali.jqgufenzy.top/Article/details/gtrgarozyq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgufenzy.top/Article/details/gtkqhyqmmr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtocexnnbx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtrqwzghjv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gtdefjhhsz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtcotcqaxp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.9152youxi.cn/Article/details/gtbquivdhw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jyoumei.cn/Article/details/gtswmevlrs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cheryme.top/Article/details/gtioyhrrlj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtugbwzxib.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hongshengwenyu.top/Article/details/gtkqnukepo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtianfxgrh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangdashe.top/Article/details/gtwprwwjmq.html

JS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtpfuevlbm.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxwrlfal.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aizwys.cn/Article/details/gtjqifgmlm.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gtxqyuzwfj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtichabprv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtpdqerrsf.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gtlzftibwu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gtudmrpbwi.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gtijpxelrz.html

JS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gtpqpwvoum.html

TS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtqocdsbpo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gtlhsiwlxo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yonumen.top/Article/details/gtlvzlpvks.html

Ruby: arr.uniq
来源：http://dali.xylfe.cn/Article/details/gtwhyndcbq.html

C#:   list.Distinct().ToList()
来源：http://dali.xinyue.icu/Article/details/gtmvxskall.html

[D16] 求和与平均值
来源：http://dali.ivvv.top/Article/details/gtzrocknig.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cheryme.top/Article/details/gtkrobftjh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tanke756.top/Article/details/gtswjbjthr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtokawkwma.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtsrujujil.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dianchejie.cn/Article/details/gtpmpoudrk.html

Go:   // 手写循环累加
来源：http://dali.dashuyun.cn/Article/details/gtqifbzjni.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtfpjulsps.html

C#:   list.Sum();  list.Average()
来源：http://dali.shuidangran.top/Article/details/gtyafigkyv.html

[D17] 最大值与最小值
来源：http://dali.ehwqpu.com/Article/details/gtkstqjkgm.html

Py:   max(arr);  min(arr)
来源：http://dali.fengsongda.top/Article/details/gtybvehaiz.html

PHP:  max($arr);  min($arr);
来源：http://dali.snrcjt.cn/Article/details/gtpxipsrus.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ivvv.top/Article/details/gtgzuhugqd.html

TS:   Math.max(...arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddifrylu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gtddpaejep.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.birdmap.top/Article/details/gtttmmolow.html

Ruby: arr.max;  arr.min
来源：http://dali.gzhubu.top/Article/details/gtvtcbuqhq.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gtvukuufif.html

[D18] 扁平化嵌套数组
来源：http://dali.zhoulong.xyz/Article/details/gtoaebioop.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guowangkeji.top/Article/details/gtzcmbqfko.html

PHP:  array_merge(...$nested);
来源：http://dali.kuanghao11.cn/Article/details/gtewproaxe.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhixingplan.top/Article/details/gtrbaihsmd.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gtfhobvbrw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gtxoonbyku.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gttzfxiqou.html

Ruby: nested.flatten
来源：http://dali.wangdashe.top/Article/details/gtsvyfckff.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtbkdeywrw.html

[D19] 按字段分组
来源：http://dali.xziqi.cn/Article/details/gtwvtcdcvu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenlongwang.top/Article/details/gttftynwsj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gtpfrliyqh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gtlghtclmy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gtgignzvsx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxinkj.top/Article/details/gtmhhyzbmw.html

Go:   // 手写 map[string][]T
来源：http://dali.9152youxi.cn/Article/details/gtwtmpqhmb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gtkdeeqtab.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gaohongyu789.top/Article/details/gtcoljedwd.html

[D20] 统计每个元素出现次数
来源：http://dali.jiagoushi.top/Article/details/gtxephkhag.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtykrtpvqt.html

PHP:  array_count_values($arr);
来源：http://dali.cdnleiting.top/Article/details/gtwjdwdvni.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtuxpphobb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvazivixr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fzhhl.top/Article/details/gtrcbkrfdb.html

Go:   // 手写 map[T]int
来源：http://dali.smart0.xyz/Article/details/gtkuyswkgs.html

Ruby: arr.tally
来源：http://dali.yj202588.top/Article/details/gtrxocghxb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.svipenyu.cn/Article/details/gtjauececi.html

[D21] 判断是否包含某元素
来源：http://dali.meibo888.top/Article/details/gtrhsrwvri.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gtacibcgsx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jiagoushi.top/Article/details/gtkmcgwdax.html

JS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gtewjrtkqb.html

TS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtniqxpicr.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gttnreycsj.html

Go:   slices.Contains(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtsqlfwosv.html

Ruby: arr.include?(x)
来源：http://dali.0kj1m.cn/Article/details/gtdwdhdeso.html

C#:   list.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtccplyxik.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yueranfly.top/Article/details/gtbewdnhku.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tianlin.xyz/Article/details/gtugnejgyg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gtkklrfwgj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtnmgkrcju.html

TS:   [...arr];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxaklejg.html

Java: new ArrayList<>(list);
来源：http://dali.yanxiufei.cn/Article/details/gtfhutrjvj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shzxlz.cn/Article/details/gtbjrtirtn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenzaomai.com/Article/details/gtipmgszej.html

C#:   new List<int>(list);
来源：http://dali.jyoumei.cn/Article/details/gtcbzbuhbw.html

[D23] reduce 累积计算
来源：http://dali.ppjwa.cn/Article/details/gtpsdejypp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenlongwang.top/Article/details/gtjofhqlkq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtgowluekp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcoslhrmx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gtfzopzceo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xylfe.cn/Article/details/gtuzjlkywr.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gtzcupnlxu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daxiang520.top/Article/details/gttdavcvri.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuetiantiany.cn/Article/details/gtgrusauvm.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhiwuduotai.top/Article/details/gtutyrsway.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gtteaworfb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtmgukjkbj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhengqikj.top/Article/details/gtijjmmhho.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtdcilsufo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tianlin.xyz/Article/details/gtfjmevhuu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj202588.top/Article/details/gtfoqsozgx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jlsjyb.cn/Article/details/gtghccbjbk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtxllsaw.html

[D25] Set 集合去重与交并差
来源：http://dali.chenjidiqi.icu/Article/details/gtwikuyoic.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hammf.cn/Article/details/gtubdcncmh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fengsongda.top/Article/details/gtbbooxtex.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gtdorpigtb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gtxcljuihl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtwrpxpqyj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daria6918.cn/Article/details/gtrtmzpxiy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gtaorezwfw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yvedp.cn/Article/details/gtjywmyezt.html

[D26] 数组转字符串
来源：http://dali.gotoacloud.top/Article/details/gtocdddupc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuanzhike.top/Article/details/gthlkpwxde.html

PHP:  implode(", ", $arr);
来源：http://dali.ppjwa.cn/Article/details/gtefufxoub.html

JS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gtgcjnadlq.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtbcdhyruu.html

Java: String.join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gtsluptoss.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrkviqva.html

Ruby: arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtkpwxgvyn.html

C#:   string.Join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gtzynxcbgy.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtyiqnmbag.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gtcgzgjjpp.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtnneqphep.html

[E01] 拼接字符串
来源：http://dali.pycfn.com/Article/details/gtcckdlgcj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yueranfly.top/Article/details/gtlescqmke.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.kuanghao11.cn/Article/details/gtyvsdqsef.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gtavaukalk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtencrvemv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fzhhl.top/Article/details/gtvfdfdojd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.haohaochexian.top/Article/details/gtwpkuyavj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.iojbl.cn/Article/details/gtbwazmaqo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbstajewp.html

[E02] 重复字符串
来源：http://dali.ivvv.top/Article/details/gtbpacplwl.html

Py:   "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawwpiflm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jyoumei.cn/Article/details/gtzucyhugt.html

JS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtigvkqblw.html

TS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtcmwhljcv.html

Java: "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtnnffpcwg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gtgknmvuhh.html

Ruby: "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoifqpfgd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jlsjyb.cn/Article/details/gtjztzyfqe.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gtroyvweqe.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yanxiufei.cn/Article/details/gtysxbcszp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtqbyrvjsf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gthoymcmzw.html

TS:   s.slice(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtnbmkfzfy.html

Java: s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtyxdsjhfi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtbrocetih.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xinyue.icu/Article/details/gtycjccpwc.html

C#:   s.Substring(1, 3)
来源：http://dali.cashguo.top/Article/details/gtdkrzwabc.html

[E04] 查找子串位置
来源：http://dali.nanxuanxn.top/Article/details/gtmteppbjs.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fzhhl.top/Article/details/gtfdhhclfn.html

PHP:  strpos($s, "x");
来源：http://dali.gotoacloud.top/Article/details/gtspsaiuwa.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pycfn.com/Article/details/gtbjzxpzyy.html

TS:   s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gteqbmbhys.html

Java: s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gtfaoojkyb.html

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gtegjyzcue.html

Ruby: s.index("x")
来源：http://dali.cheryme.top/Article/details/gteddttrsf.html

C#:   s.IndexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtxpubthwh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tian-w.cn/Article/details/gtzagajyrw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.haohaochexian.top/Article/details/gtbeezfvgx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinghuilouyu.cn/Article/details/gtskyvskse.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlirlhdbt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sxryk.cn/Article/details/gthhaeuklf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtdejyabqt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuanzx.com/Article/details/gtmvtootkd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gogol.net.cn/Article/details/gtzgfizhxj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtvtzrzfxr.html

[E06] 替换子串
来源：http://dali.sxryk.cn/Article/details/gthlogrnkg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtobnizjkg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shzxlz.cn/Article/details/gtsurqrxyt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtbqmrkjqy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtdpttuzbq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefxwuemh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gtwtgvikpb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtwemxkraz.html

C#:   s.Replace("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxaflwnnb.html

[E07] 按分隔符拆分
来源：http://dali.snrcjt.cn/Article/details/gtiiolunjy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dianchejie.cn/Article/details/gthziirmgv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj202588.top/Article/details/gtjwgoyfpu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdiujywsb.html

TS:   s.split(",")
来源：http://dali.mhx1999.top/Article/details/gtdbnbtbhu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigfzy.top/Article/details/gturigvqyq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dianchejie.cn/Article/details/gtexgqoejz.html

Ruby: s.split(",");  s.split
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmfdvkhd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxuanxn.top/Article/details/gtslzkhxbu.html

[E08] 数组按分隔符合并
来源：http://dali.zhiwuduotai.top/Article/details/gtejaqlrkx.html

Py:   ",".join(items)
来源：http://dali.jqgufenzy.top/Article/details/gtxwvotwdz.html

PHP:  implode(",", $items);
来源：http://dali.hnxiangtu.top/Article/details/gtxvbxepyo.html

JS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtimjtbkin.html

TS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtmxgrcmjk.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gtehbrvfyi.html

Go:   strings.Join(items, ",")
来源：http://dali.xylfe.cn/Article/details/gtiljbtidw.html

Ruby: items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtnorlxthp.html

C#:   string.Join(",", items)
来源：http://dali.c1oappe.top/Article/details/gtnmkktyio.html

[E09] 去除所有空白字符
来源：http://dali.gotoacloud.top/Article/details/gtbqskmymq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.kuanghao11.cn/Article/details/gtfrtkjtdg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hysaishi.cn/Article/details/gtwqmommcs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gthmjlbhmj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtklonmljg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gtkhzufovm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.havefunace.top/Article/details/gtxyrdqmdf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sxryk.cn/Article/details/gtccsmzbqk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gtjxkzqxrr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsgaqrle.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtbnfvveok.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yongpay.top/Article/details/gtjsvbtuxq.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtfkitnmkb.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkigbypm.html

Java: String.format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtsrhmzmqp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtipejohay.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtrmsujchc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gtbykboaxs.html

[E11] 反转字符串
来源：http://dali.c1oappe.top/Article/details/gtsikphrxh.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtmtdvaevy.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtixjioisj.html

JS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtmvbkmyfj.html

TS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtjpbvczlk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yvedp.cn/Article/details/gtdhkmjwco.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangdashe.top/Article/details/gtctgcojpx.html

Ruby: s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtzipsauzb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtigddsold.html

[E12] 统计某字符出现次数
来源：http://dali.fengsongda.top/Article/details/gthzqddhkx.html

Py:   s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfepcwua.html

PHP:  substr_count($s, "a");
来源：http://dali.feifeiyinyue.top/Article/details/gtuvbagkgh.html

JS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtyleyqjyu.html

TS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gtddpaawvq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shangyingyoupin.top/Article/details/gtjigywasz.html

Go:   strings.Count(s, "a")
来源：http://dali.tanke756.top/Article/details/gtonnxlyil.html

Ruby: s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtrpinfjpu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ehwqpu.com/Article/details/gtqmlmcqte.html

[E13] 逐字符遍历
来源：http://dali.nwbrower.top/Article/details/gtgzvidyzx.html

Py:   for ch in s: print(ch)
来源：http://dali.yangfankeji.com/Article/details/gtwtzjiypn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xinyue.icu/Article/details/gtymkqlnnd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtfpzgzven.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtvvvvgbvp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sxryk.cn/Article/details/gthuvvbnom.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.iojbl.cn/Article/details/gteevgwsbu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxinkj.top/Article/details/gtdutuezoh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtrsdiqcms.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gtzkeotdqj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jlsjyb.cn/Article/details/gtmvfnagsz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.kuanghao11.cn/Article/details/gttstulazj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sweek.top/Article/details/gtkrbdqwgg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhixingplan.top/Article/details/gtihrepjkq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hammf.cn/Article/details/gtcroncdjg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sweek.top/Article/details/gtxlhbuzak.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yanxiufei.cn/Article/details/gtvwkyjcmh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258888.top/Article/details/gtesjscjht.html

[E15] HTML 转义 / 反转义
来源：http://dali.shangyingyoupin.top/Article/details/gthjzigmub.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.bjfxy.top/Article/details/gttrlifztw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.0kj1m.cn/Article/details/gtqsiglvcb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gtawwexesm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guowangkeji.top/Article/details/gtnwwduqji.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hysaishi.cn/Article/details/gtjnnhwgui.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cashguo.top/Article/details/gttsqspebc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtesuzpbsw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258.top/Article/details/gtrbxhvbxf.html

[E16] 数字千分位
来源：http://dali.316326.xyz/Article/details/gtoqfzhrul.html

Py:   f"{1234567:,}"
来源：http://dali.xylfe.cn/Article/details/gtxjunpppr.html

PHP:  number_format(1234567);
来源：http://dali.yangfankeji.com/Article/details/gtbxukaljk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gtkamicfaw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtfyevfxtg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yongpay.top/Article/details/gtjbpuahcg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gtxjldlfrn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.vqdsnc.cn/Article/details/gtdtspzgdb.html

C#:   1234567.ToString("N0")
来源：http://dali.svipenyu.cn/Article/details/gtnabhdmwr.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gtldwgwkkv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.iojbl.cn/Article/details/gtsdlcofec.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cdnleiting.top/Article/details/gtluhskwpq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtifnqbswi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtaoemvrch.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zdqjudy.top/Article/details/gtlzdhdqse.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtxdhkrkhf.html

Ruby: s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gtbkxewwsu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.svipenyu.cn/Article/details/gtuxdhntkx.html

[E18] 模板占位符替换
来源：http://dali.cqqwz.cn/Article/details/gtzjgijyvg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gtfbbiqxlv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sufxvd.cn/Article/details/gtgphyotvb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnmjsvos.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyalzhusl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtvklrjbnw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtnfsawgyn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gaohongyu789.top/Article/details/gtgmprqeuy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gtueuespng.html

[E19] 多行文本按行拆分
来源：http://dali.haohaochexian.top/Article/details/gtvdabdzzp.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtuloxbsot.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtgmsgmcfb.html

JS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gtmbmxcned.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gtywawnwug.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gtimnkesdn.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gtkrrpytxk.html


<!-- 参考信息 -->