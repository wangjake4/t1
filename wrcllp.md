代发 wailian999

Ruby: arr.index(x)
来源：http://dali.jinqigufen.top/Article/details/gtcjccxpvu.html

C#:   list.IndexOf(x);
来源：http://dali.havefunace.top/Article/details/gtjwbpknxf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daria6918.cn/Article/details/gtefnfvgfr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aizwys.cn/Article/details/gtkugnsbqr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shzxlz.cn/Article/details/gtiirixdkk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtmkbmwmbe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gtqwfyhqlj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahsiiohp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.havefunace.top/Article/details/gtqsjvydae.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sxryk.cn/Article/details/gttbidicyk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gtpajglxdi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gtsimlbgcw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtzpzcmfms.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tian-w.cn/Article/details/gtkeygnxam.html

JS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gtvtuqtwyb.html

TS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gtwnuxawlt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtmmfqcysm.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gtvuxiiras.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtpuasecfp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtdulonsff.html

[D15] 去重
来源：http://dali.yvedp.cn/Article/details/gtklxqgbpt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gtbfhvzcvn.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gthlqktzjh.html

JS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gtgvtfmikl.html

TS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtzvelxrdq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cdnleiting.top/Article/details/gtncnggssk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gtqtaxfcha.html

Ruby: arr.uniq
来源：http://dali.ehwqpu.com/Article/details/gtkgezbvfz.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gtpewicllj.html

[D16] 求和与平均值
来源：http://dali.jinghuilouyu.cn/Article/details/gtbphwqdph.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.havefunace.top/Article/details/gtndpotiqv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtsddipuzu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gtvxmziyqh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtsfejmdvy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.snrcjt.cn/Article/details/gtddzcymoy.html

Go:   // 手写循环累加
来源：http://dali.meibo888.top/Article/details/gtrpignmlo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhengqikj.top/Article/details/gtojdbjthl.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhixingplan.top/Article/details/gtxfmhnwnz.html

[D17] 最大值与最小值
来源：http://dali.yvedp.cn/Article/details/gttqoczoms.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtweqjgdub.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gtezuipokq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gtutjdibxt.html

TS:   Math.max(...arr);
来源：http://dali.tianlin.xyz/Article/details/gtdrttlgrt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gtxjuobepg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtrgebagwh.html

Ruby: arr.max;  arr.min
来源：http://dali.kuanghao11.cn/Article/details/gthylrtjpf.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gtqrakhivy.html

[D18] 扁平化嵌套数组
来源：http://dali.dashuyun.cn/Article/details/gtnwliinho.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.haohaochexian.top/Article/details/gtnscmfbjy.html

PHP:  array_merge(...$nested);
来源：http://dali.chenjidiqi.icu/Article/details/gtphbpmirm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xylfe.cn/Article/details/gtxzovofhu.html

TS:   nested.flat();
来源：http://dali.mhx1999.top/Article/details/gtdbfwydbi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pycfn.com/Article/details/gtnatmsqdn.html

Go:   // 手写双层循环
来源：http://dali.hnqzz.top/Article/details/gtywmwxpct.html

Ruby: nested.flatten
来源：http://dali.jianghu66.top/Article/details/gtbljgcbqp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtdjqpffif.html

[D19] 按字段分组
来源：http://dali.yuxming.cn/Article/details/gtffgcrgkh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xinyue.icu/Article/details/gtmcwgjgpz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gzhubu.top/Article/details/gtbhhcaoto.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hywenlv.cn/Article/details/gtoimpbjue.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhongyouzk.top/Article/details/gtjcnlopsj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgfzy.top/Article/details/gtxsnvhdhx.html

Go:   // 手写 map[string][]T
来源：http://dali.zhiwuduotai.top/Article/details/gtvejyhwnw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.quarkkingdee.top/Article/details/gtzogglffh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hysaishi.cn/Article/details/gteewrgawa.html

[D20] 统计每个元素出现次数
来源：http://dali.svipenyu.cn/Article/details/gtatcbmiaa.html

Py:   Counter(arr)
来源：http://dali.yuxming.cn/Article/details/gtnlbtetyf.html

PHP:  array_count_values($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtsxlzupwq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gtuutfoipp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gtratwqlrg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jiagoushi.top/Article/details/gtwtjkvetb.html

Go:   // 手写 map[T]int
来源：http://dali.xziqi.cn/Article/details/gtsiaozmtz.html

Ruby: arr.tally
来源：http://dali.tianlin.xyz/Article/details/gtifgvycit.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.svipenyu.cn/Article/details/gtuaxioakq.html

[D21] 判断是否包含某元素
来源：http://dali.chenlongwang.top/Article/details/gtqxihytji.html

Py:   x in arr
来源：http://dali.cdnleiting.top/Article/details/gtoxxsvxad.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtkcyzmtvv.html

JS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gtpmelgumv.html

TS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gtiqieqxwz.html

Java: list.contains(x)
来源：http://dali.sysykeji.top/Article/details/gtjfgyhbbb.html

Go:   slices.Contains(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtzhjyturp.html

Ruby: arr.include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gteagtfkgf.html

C#:   list.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gtwwzbghfd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sweek.top/Article/details/gtgyvqdtcw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yvedp.cn/Article/details/gtccgpjrww.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenlongwang.top/Article/details/gtzpoogacb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtkrcvlzsf.html

TS:   [...arr];
来源：http://dali.shangyingyoupin.top/Article/details/gtnjehlffa.html

Java: new ArrayList<>(list);
来源：http://dali.bjfxy.top/Article/details/gtrfxmvpbt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenlongwang.top/Article/details/gtufxxdchb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gtyitxqizz.html

C#:   new List<int>(list);
来源：http://dali.zhengqikj.top/Article/details/gtfbiktqdx.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gtwnosfnru.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ehwqpu.com/Article/details/gtjmbslauq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gtnyxmfayg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gtlzecqpts.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtxszbwdhe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.quarkkingdee.top/Article/details/gtsjmluhqn.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gtuupzkzek.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nwbrower.top/Article/details/gtsqzltual.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtohhdqxal.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258.top/Article/details/gtivwiuryk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gtyrupekxt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aibaodan.cn/Article/details/gtanmjerkj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sysykeji.top/Article/details/gtejjxngyj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.mhx1999.top/Article/details/gthtaxetin.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtaamzyayw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pycfn.com/Article/details/gtuxvgehuj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.smart0.xyz/Article/details/gtkcaxdtan.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgfzy.top/Article/details/gttfekrnpi.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlfhathp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ppjwa.cn/Article/details/gtepsvnmuj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gtbbhilamv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cashguo.top/Article/details/gtcwjsvqgw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shangyingyoupin.top/Article/details/gtxzxmhgkv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xinyue.icu/Article/details/gtqhbxtxrx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gtawiboxyx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.bjfxy.top/Article/details/gtccdhdcim.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtrmnlhjfe.html

[D26] 数组转字符串
来源：http://dali.cheryme.top/Article/details/gtkhsootjo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hywenlv.cn/Article/details/gttgkbkwry.html

PHP:  implode(", ", $arr);
来源：http://dali.yongpay.top/Article/details/gtooescizf.html

JS:   arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtnkbdaqlh.html

TS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtpznzcdxg.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtecnkhukc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gtfokbaflk.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtzhyoyywt.html

C#:   string.Join(", ", list)
来源：http://dali.hfpthk.cn/Article/details/gtenrnerth.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gthkcktlgd.html

E. 字符串处理
来源：http://dali.yj20258888.top/Article/details/gtaljctsiw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtlwoyctpm.html

[E01] 拼接字符串
来源：http://dali.zycfv.cn/Article/details/gttjaovisi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cucudq.cn/Article/details/gtsbgzrpzn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tianlin.xyz/Article/details/gtdaptalss.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtnbmvbfne.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gtfkmjhmia.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnekxhkca.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuanzx.com/Article/details/gtglamptkm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xinyue.icu/Article/details/gtckfabljy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtfazrobks.html

[E02] 重复字符串
来源：http://dali.gogol.net.cn/Article/details/gttuzvahjx.html

Py:   "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gtvgpuuwmn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.iojbl.cn/Article/details/gtxduydfet.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtmghffitm.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gteaprturb.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtnetwotgo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gtrcbrawfg.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtmvhejusb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sysykeji.top/Article/details/gtntsoubko.html

[E03] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtntkgaxza.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hfpthk.cn/Article/details/gtsmvifqbt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtndlaribn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtrbbczpnd.html

TS:   s.slice(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvemwoxhb.html

Java: s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtuvepjiyl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sweek.top/Article/details/gtchmlverr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fengsongda.top/Article/details/gtdcrqlwks.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258.top/Article/details/gtrawxjoir.html

[E04] 查找子串位置
来源：http://dali.gzhubu.top/Article/details/gtapnpglms.html

Py:   s.find("x");  s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gtllhmzaze.html

PHP:  strpos($s, "x");
来源：http://dali.andypj.xyz/Article/details/gtydfhmajx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shuidangran.top/Article/details/gtozrfckrz.html

TS:   s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtdkpmvqtn.html

Java: s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtzjoasmnn.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gtynkzkyls.html

Ruby: s.index("x")
来源：http://dali.tanke756.top/Article/details/gtbvreohrs.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gtrxatbxhh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjrcaxxs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonnwlylw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sufxvd.cn/Article/details/gtuklmtsbv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttffznxwf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigufen.top/Article/details/gtslbswbjw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtnxddabqd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gtbuvcnuaf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.andypj.xyz/Article/details/gthprzxkdb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtbtsxdrtm.html

[E06] 替换子串
来源：http://dali.ydzc1.top/Article/details/gtbpixlnwa.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtannbpbhq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gtuviddnjv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtclfonjoz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtzqpghfei.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtfkrklfra.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gthachmmlp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtwlzgbjye.html

C#:   s.Replace("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtfvatukkx.html

[E07] 按分隔符拆分
来源：http://dali.xuanzx.com/Article/details/gtdnlvcwgs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenzaomai.com/Article/details/gtgzdyqnzl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtapkoxanu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fzhhl.top/Article/details/gtendfcqzx.html

TS:   s.split(",")
来源：http://dali.ppjwa.cn/Article/details/gtnclxoupq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixkidrgm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gtfzpsfohg.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigfzy.top/Article/details/gtbmgelmib.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pengpengdd.cyou/Article/details/gtwobocvmt.html

[E08] 数组按分隔符合并
来源：http://dali.chenjidiqi.icu/Article/details/gtclonxhye.html

Py:   ",".join(items)
来源：http://dali.hnqzz.top/Article/details/gtcpdkhxss.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gtqvsxnjpr.html

JS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtjmhprqha.html

TS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtcrkrsueu.html

Java: String.join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtmzamxswv.html

Go:   strings.Join(items, ",")
来源：http://dali.yangfankeji.com/Article/details/gtacfrqpel.html

Ruby: items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtiumveict.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtvdzvrtgb.html

[E09] 去除所有空白字符
来源：http://dali.birdmap.top/Article/details/gtonqwkqmw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xylfe.cn/Article/details/gtarvnokmj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pycfn.com/Article/details/gtobphgncd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gtvofietof.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtuwxmazxp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cheryme.top/Article/details/gthzdtgfrb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuanzhike.top/Article/details/gtjmntguuu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xuanzx.com/Article/details/gtgisxvrxk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtkskjmucl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.redwolf501.top/Article/details/gtdwpwkesk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtpxoayvrk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmesmouyf.html

JS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtrjfjuyzb.html

TS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtqlpnizwi.html

Java: String.format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtcvgzzexf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtbkhmljpl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtstbkuhvl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xziqi.cn/Article/details/gtefqwafpq.html

[E11] 反转字符串
来源：http://dali.jqgfzy.top/Article/details/gtbctzxmuo.html

Py:   s[::-1]
来源：http://dali.yvedp.cn/Article/details/gthbgnntjs.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gthjqqacrs.html

JS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtxgbdqvrc.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtswnzpyht.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ppjwa.cn/Article/details/gtnmwgyrgu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuanzx.com/Article/details/gtparrsdsh.html

Ruby: s.reverse
来源：http://dali.c1oappe.top/Article/details/gtqvqzzudo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtzzngcadc.html

[E12] 统计某字符出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtdumfpsbm.html

Py:   s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtkokaizzo.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gtlydocglt.html

JS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrhsdjzh.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtkgcfbamn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gtgscgjqkb.html

Go:   strings.Count(s, "a")
来源：http://dali.yangfankeji.com/Article/details/gtwsnsivzt.html

Ruby: s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtbejpcktp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.snrcjt.cn/Article/details/gtbrgdatzp.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gtejxqhxmj.html

Py:   for ch in s: print(ch)
来源：http://dali.smart0.xyz/Article/details/gtnqlogyzj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.meibo888.top/Article/details/gttxrrklze.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtwbcjwpij.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gtqcbozbgw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuanzx.com/Article/details/gtisuwzrnf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuanzx.com/Article/details/gtjojoiyho.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pengpengdd.cyou/Article/details/gtoamblucw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jianghu66.top/Article/details/gtygnlyiav.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258888.top/Article/details/gtkoprgocs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangshuangyany.cn/Article/details/gtgwvwtyhc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gtjgmwswjc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hfpthk.cn/Article/details/gtgushfusf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gtmohqtkoj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gtsdvomhxa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sysykeji.top/Article/details/gtaflwffgs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gtvmfaxzjk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtisuwermj.html

[E15] HTML 转义 / 反转义
来源：http://dali.shangyingyoupin.top/Article/details/gtgqryuqvg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtalkxjylm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gogol.net.cn/Article/details/gtpxbyarop.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tian-w.cn/Article/details/gtfcucwqnt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gtvkvidivj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gtogoyyikf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgyznnpw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.vqdsnc.cn/Article/details/gtpzphbxkc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.quarkkingdee.top/Article/details/gtxohmabiz.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgmwbris.html

Py:   f"{1234567:,}"
来源：http://dali.zhongyouzk.top/Article/details/gtzsqfbowt.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gtfvmrlnxd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtqjvhpdko.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtxgnwokba.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.bjfxy.top/Article/details/gtfepeooou.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jyoumei.cn/Article/details/gtfvklijfc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258888.top/Article/details/gtsmgpxogj.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gtgggxjuzu.html

[E17] 首字母大写
来源：http://dali.feifeiyinyue.top/Article/details/gtfkntvfei.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gtfgnjbpid.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gogol.net.cn/Article/details/gtjseggdgh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gtbdhyjntm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gtmfgkvzha.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dashuyun.cn/Article/details/gtbhhmfqej.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cdnleiting.top/Article/details/gtmaieeivz.html

Ruby: s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gtstdmjnou.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.snrcjt.cn/Article/details/gtckietuvm.html

[E18] 模板占位符替换
来源：http://dali.nanxuanxn.top/Article/details/gthwmuujec.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj202588.top/Article/details/gthptrtlrj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cqqwz.cn/Article/details/gtlkqldyft.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysnimrbl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtmbbqxpzs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtneumekyo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258.top/Article/details/gtapqwkeuw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ppjwa.cn/Article/details/gtjcvtvlid.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yonumen.top/Article/details/gtxdxbxvos.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gtyaxuzwjc.html

Py:   s.splitlines()
来源：http://dali.chenzaomai.com/Article/details/gtxfipzklu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtindgfrcj.html

JS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtdyyituaw.html

TS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtcxusxzfa.html

Java: s.lines().toList()
来源：http://dali.dianchejie.cn/Article/details/gtivllwzwq.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtotewsres.html


<!-- 参考信息 -->