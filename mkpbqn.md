代发 wailian999

C#:   list.Reverse();
来源：http://dali.sufxvd.cn/Article/details/gt2cqfunulf.html

[D12] 查找元素下标
来源：http://dali.wangdashe.top/Article/details/gt2gqcskzuy.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgfzy.top/Article/details/gt2acbbreks.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yvedp.cn/Article/details/gt2zxhmfwjx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2vwtknmjz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2ckadgkbw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gt2geyzdvgw.html

Go:   slices.Index(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zewhnbsj.html

Ruby: arr.index(x)
来源：http://dali.fengsongda.top/Article/details/gt2kdnocnbp.html

C#:   list.IndexOf(x);
来源：http://dali.9152youxi.cn/Article/details/gt2eauktyhz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cucudq.cn/Article/details/gt2ioimgpsa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gotoacloud.top/Article/details/gt2wjprmxok.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2bdudhntf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gt2bldmyerd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2zttlwifx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2cwtvszvj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yangfankeji.com/Article/details/gt2imuwtems.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daxiang520.top/Article/details/gt2idylezoa.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtqkkdwl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnxiangtu.top/Article/details/gt2rdlqgbnw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258.top/Article/details/gt2fnxurhqi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pycfn.com/Article/details/gt2fkpjndnc.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gt2mpcaxkin.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gt2wocbmjkq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.316326.xyz/Article/details/gt2zftzdjjo.html

Go:   // 手写循环
来源：http://dali.aizwys.cn/Article/details/gt2zaqewymh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daria6918.cn/Article/details/gt2yxvblcjr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2vnhbilyu.html

[D15] 去重
来源：http://dali.jiagoushi.top/Article/details/gt2nngpnbqu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljlgfqgi.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pgvmwkoi.html

JS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gt2scsuqtmx.html

TS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gt2ivvannnq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.iojbl.cn/Article/details/gt2nogezjls.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yflawqdh.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gt2garbyjcm.html

C#:   list.Distinct().ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kggblenj.html

[D16] 求和与平均值
来源：http://dali.nwbrower.top/Article/details/gt2saklegyf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gasapxgl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tanke756.top/Article/details/gt2oaapxiwk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gt2igebepqb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gt2iilrwnty.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zdqjudy.top/Article/details/gt2ysyxpucp.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rezlwgzp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigufen.top/Article/details/gt2ozgveapp.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ianofpjo.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gt2kebybqsq.html

Py:   max(arr);  min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ehgmdtxs.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2zblzvaxr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenlongwang.top/Article/details/gt2njfyyfpy.html

TS:   Math.max(...arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2fsolgfcv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.0kj1m.cn/Article/details/gt2tqjulsqn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuxming.cn/Article/details/gt2ncmuvlco.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gt2imvjzsuc.html

C#:   list.Max();  list.Min()
来源：http://dali.aizwys.cn/Article/details/gt2ekroocca.html

[D18] 扁平化嵌套数组
来源：http://dali.haohaochexian.top/Article/details/gt2uuyulfsj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gotoacloud.top/Article/details/gt2fqierxwq.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gt2wuxvutrt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.bjfxy.top/Article/details/gt2ymvablhr.html

TS:   nested.flat();
来源：http://dali.iojbl.cn/Article/details/gt2urfzxdar.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cucudq.cn/Article/details/gt2awsrhdxa.html

Go:   // 手写双层循环
来源：http://dali.sufxvd.cn/Article/details/gt2onxbjstc.html

Ruby: nested.flatten
来源：http://dali.yangfankeji.com/Article/details/gt2ntwcklrw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vthlejxb.html

[D19] 按字段分组
来源：http://dali.chenzaomai.com/Article/details/gt2pkuybxxq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.meibo888.top/Article/details/gt2qlwhvpul.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.316326.xyz/Article/details/gt2zxgfjcgi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yanxiufei.cn/Article/details/gt2iwrucpiq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aizwys.cn/Article/details/gt2qchrspoj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cdnleiting.top/Article/details/gt2pfzwkdww.html

Go:   // 手写 map[string][]T
来源：http://dali.wangshuangyany.cn/Article/details/gt2lidcppyd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gt2gbndxdmm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangshuangyany.cn/Article/details/gt2tavrjhhb.html

[D20] 统计每个元素出现次数
来源：http://dali.fengsongda.top/Article/details/gt2mfkyixar.html

Py:   Counter(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2knbometp.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2uixtjqjf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gt2lmnhawwl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gt2unwwmlww.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gt2dpfcaqsd.html

Go:   // 手写 map[T]int
来源：http://dali.guowangkeji.top/Article/details/gt2riyatkjy.html

Ruby: arr.tally
来源：http://dali.vqdsnc.cn/Article/details/gt2oggyzohd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jfqzedvb.html

[D21] 判断是否包含某元素
来源：http://dali.daxiang520.top/Article/details/gt2yhgtaimz.html

Py:   x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpdnfxkw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgfzy.top/Article/details/gt2lwxmshwb.html

JS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gt2opglddmr.html

TS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2teuzkazs.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2tatyjifs.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2tvkkvcbw.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gt2troknzoq.html

C#:   list.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gt2fxlpacdg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aibaodan.cn/Article/details/gt2trmzyuxx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jianghu66.top/Article/details/gt2jryfbtcp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gt2veufcion.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2bylcmwgt.html

TS:   [...arr];
来源：http://dali.0kj1m.cn/Article/details/gt2ibzjhbfu.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gt2vlolbaig.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ppjwa.cn/Article/details/gt2qbmtplcq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hywenlv.cn/Article/details/gt2axnqoxmo.html

C#:   new List<int>(list);
来源：http://dali.bjfxy.top/Article/details/gt2gsbekjwa.html

[D23] reduce 累积计算
来源：http://dali.ybcxt.top/Article/details/gt2lyybmrhu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dtnaodzv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxmoityv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2ynhggccn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gt2hnhayelf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yvedp.cn/Article/details/gt2iigjnbef.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gt2jynytbqq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ehwqpu.com/Article/details/gt2egpnwyfn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xziqi.cn/Article/details/gt2pxitlzar.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gt2qlgynrxg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.9152youxi.cn/Article/details/gt2ylsalpsw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cheryme.top/Article/details/gt2zdnmhbdh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.snrcjt.cn/Article/details/gt2oohlyldy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2eqmdfwxt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258888.top/Article/details/gt2vdqzjvnk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.meibo888.top/Article/details/gt2jhlcbega.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.kuanghao11.cn/Article/details/gt2mfutwnej.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dianchejie.cn/Article/details/gt2alsgtbtx.html

[D25] Set 集合去重与交并差
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfbmuadb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgfzy.top/Article/details/gt2minmqmbv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gt2llzajgfo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daria6918.cn/Article/details/gt2vejkboqu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gt2wwbsfjop.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gt2uucoyobg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ashrnzjv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aizwys.cn/Article/details/gt2ubzppykb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guannengcc.top/Article/details/gt2pkilmtbb.html

[D26] 数组转字符串
来源：http://dali.jianghu66.top/Article/details/gt2yetmbwkl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.0kj1m.cn/Article/details/gt2qeaeaisk.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uasqrpis.html

JS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2chwcoard.html

TS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gt2rckndesa.html

Java: String.join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gt2spgrfelv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtfbyhgx.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2zhtqyryp.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gt2opooklpx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2dedwoqoh.html

E. 字符串处理
来源：http://dali.xinyue.icu/Article/details/gt2hifhvlqz.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2qbkglywe.html

[E01] 拼接字符串
来源：http://dali.andypj.xyz/Article/details/gt2fzffwoff.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hfpthk.cn/Article/details/gt2yuqunijk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2owegbutv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gt2rvbassqu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gt2gpyzpvee.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sysykeji.top/Article/details/gt2ksmxszdb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cqqwz.cn/Article/details/gt2krzaapei.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gotoacloud.top/Article/details/gt2wdfopfki.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2dlsocnvc.html

[E02] 重复字符串
来源：http://dali.cucudq.cn/Article/details/gt2abyepxhk.html

Py:   "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gt2kuqlnsmk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gt2dnuyzqqa.html

JS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2hhgbldyv.html

TS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2gibnquah.html

Java: "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gt2kdvcujpe.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yangfankeji.com/Article/details/gt2ggasbret.html

Ruby: "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gt2moeahfcw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwouqngn.html

[E03] 截取子串
来源：http://dali.ybcxt.top/Article/details/gt2hukpfjoq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjhgljoo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2nxvjtpax.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gt2yxynidcg.html

TS:   s.slice(1, 4)
来源：http://dali.iojbl.cn/Article/details/gt2vanlmutp.html

Java: s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gt2orymalon.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hnlazcrw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yvedp.cn/Article/details/gt2vjdhkcto.html

C#:   s.Substring(1, 3)
来源：http://dali.daxiang520.top/Article/details/gt2oivzemyc.html

[E04] 查找子串位置
来源：http://dali.zhixingplan.top/Article/details/gt2kaczrlum.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sxryk.cn/Article/details/gt2lhtqfxez.html

PHP:  strpos($s, "x");
来源：http://dali.hammf.cn/Article/details/gt2qucdlfhm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgfzy.top/Article/details/gt2poilbqlr.html

TS:   s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jsvclgzb.html

Java: s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eniqrnsg.html

Go:   strings.Index(s, "x")
来源：http://dali.gaohongyu789.top/Article/details/gt2echzhcev.html

Ruby: s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gt2nfzuqisb.html

C#:   s.IndexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gt2lcmyuthp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hammf.cn/Article/details/gt2vjdkyiwv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2blnuqflf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dianchejie.cn/Article/details/gt2qghgrjfx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gt2sfnfkmtl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yueranfly.top/Article/details/gt2ttbwrefa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwhtinfp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fzhhl.top/Article/details/gt2njcbpalm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jianghu66.top/Article/details/gt2peqapvdz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gt2newtslih.html

[E06] 替换子串
来源：http://dali.gogol.net.cn/Article/details/gt2welgvysw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gt2kjdydczg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ydzc1.top/Article/details/gt2ogxijtkw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2tpsaoztm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2vpkhxhmj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2qofhrzkk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gt2onzyctpw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2osxbkspr.html

C#:   s.Replace("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2asydfhhv.html

[E07] 按分隔符拆分
来源：http://dali.sufxvd.cn/Article/details/gt2nqhnnjtm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqnfbkj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yonumen.top/Article/details/gt2emzjhvtd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2irjlznqr.html

TS:   s.split(",")
来源：http://dali.aibaodan.cn/Article/details/gt2gxaxhjky.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daria6918.cn/Article/details/gt2jryrpxoc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2gahiyydo.html

Ruby: s.split(",");  s.split
来源：http://dali.kuanghao11.cn/Article/details/gt2opkgfoys.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjabquuv.html

[E08] 数组按分隔符合并
来源：http://dali.vqdsnc.cn/Article/details/gt2uzeghjwf.html

Py:   ",".join(items)
来源：http://dali.hywenlv.cn/Article/details/gt2ratzjicv.html

PHP:  implode(",", $items);
来源：http://dali.quarkkingdee.top/Article/details/gt2dbhvoneb.html

JS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gt2bveekvck.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gt2hychlyvg.html

Java: String.join(",", items)
来源：http://dali.sysykeji.top/Article/details/gt2ebgodcio.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigufen.top/Article/details/gt2efxwrsny.html

Ruby: items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzaoecex.html

C#:   string.Join(",", items)
来源：http://dali.birdmap.top/Article/details/gt2hwnufaaz.html

[E09] 去除所有空白字符
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwupyize.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gt2hnufwxyf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2alaywcjl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mikqglxq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbqgainz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gt2vftpfkbx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aibaodan.cn/Article/details/gt2edjooeoq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2qlxrovdl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.meibo888.top/Article/details/gt2svmbmjxv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.smart0.xyz/Article/details/gt2sasryxvx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2jpcnrepn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.svipenyu.cn/Article/details/gt2iumicewc.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gt2jzdbhxjj.html

TS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gt2czkzjcwy.html

Java: String.format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gt2disinlas.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2xseupobl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gt2znxqspcr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gt2sxlkxkkg.html

[E11] 反转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2jwdtxskz.html

Py:   s[::-1]
来源：http://dali.yj20258888.top/Article/details/gt2jfhcqsyg.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjvhiptj.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2jgagcrwe.html

TS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvnymols.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xziqi.cn/Article/details/gt2npoyiswf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gt2vyyjjjmo.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gt2arlbkgnb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gt2fbaefjux.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gt2jzqxyslg.html

Py:   s.count("a")
来源：http://dali.cashguo.top/Article/details/gt2jbivwcth.html

PHP:  substr_count($s, "a");
来源：http://dali.cashguo.top/Article/details/gt2wloqaiba.html

JS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gt2jrkkjbrr.html

TS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gt2loybblwi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzfbfwzp.html

Go:   strings.Count(s, "a")
来源：http://dali.bjfxy.top/Article/details/gt2brfgyuiw.html

Ruby: s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gt2yjxzpwob.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yanxiufei.cn/Article/details/gt2hxelogma.html

[E13] 逐字符遍历
来源：http://dali.yonumen.top/Article/details/gt2onkvwizs.html

Py:   for ch in s: print(ch)
来源：http://dali.ybcxt.top/Article/details/gt2gguoeode.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gt2toogbpqs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gt2ljutheui.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2dznsbcbt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2mznkbhjy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gt2ffyrdovy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.mhx1999.top/Article/details/gt2szuyfdpe.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2withmvaz.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gt2mbcixyhq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yongpay.top/Article/details/gt2bpdkybgb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2pskibtio.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gt2schfmvuj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2ddtejkpt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ivvv.top/Article/details/gt2hzcwhlzz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shzxlz.cn/Article/details/gt2kucadgyd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.kuanghao11.cn/Article/details/gt2txtbltct.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fbtmqbfa.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hosockfs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dianchejie.cn/Article/details/gt2folepmqd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gt2fqdclomp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.iojbl.cn/Article/details/gt2bortifgn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gt2yplraycb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yvedp.cn/Article/details/gt2bwevjkdw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuanzx.com/Article/details/gt2qivpiplw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkydgci.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.haohaochexian.top/Article/details/gt2iiecabkb.html

[E16] 数字千分位
来源：http://dali.snrcjt.cn/Article/details/gt2tuhgrxjh.html

Py:   f"{1234567:,}"
来源：http://dali.c1oappe.top/Article/details/gt2bkmjyxir.html

PHP:  number_format(1234567);
来源：http://dali.hnxiangtu.top/Article/details/gt2kgctpqeu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gt2wibnjncf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gt2nkgirxsx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.havefunace.top/Article/details/gt2rrufrnlu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sxryk.cn/Article/details/gt2sbedxics.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmolaaof.html

C#:   1234567.ToString("N0")
来源：http://dali.316326.xyz/Article/details/gt2dinfwefp.html

[E17] 首字母大写
来源：http://dali.jyoumei.cn/Article/details/gt2zhpsyysj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.c1oappe.top/Article/details/gt2xlzpqeay.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pycfn.com/Article/details/gt2hzcuvncy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2fcxokpck.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2yjfkkgwq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258.top/Article/details/gt2ibqydhha.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pycfn.com/Article/details/gt2ezouamye.html

Ruby: s.capitalize
来源：http://dali.andypj.xyz/Article/details/gt2fukrifhg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gt2yqpcsasq.html

[E18] 模板占位符替换
来源：http://dali.c1oappe.top/Article/details/gt2ltuzdzlc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gt2coacluoh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigufen.top/Article/details/gt2yildayio.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gt2adluxcyq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2kqauhhqd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2klssaoai.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2zfenyhow.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sxryk.cn/Article/details/gt2tyyolzyk.html


<!-- 参考信息 -->