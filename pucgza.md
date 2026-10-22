代发 wailian999

Ruby: arr.index(x)
来源：http://dali.tianlin.xyz/Article/details/gt2hqvpbexl.html

C#:   list.IndexOf(x);
来源：http://dali.9152youxi.cn/Article/details/gt2kbtqwyht.html

[D13] 过滤（保留满足条件的）
来源：http://dali.haohaochexian.top/Article/details/gt2fmksimrt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guannengcc.top/Article/details/gt2mxdgupol.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhengqikj.top/Article/details/gt2idrpkjii.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gt2fuyepftx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gt2gfxrtzbg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2jwunflyy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gt2jvsanius.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dianchejie.cn/Article/details/gt2jvyusrfx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2mfnlzgye.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gogol.net.cn/Article/details/gt2ekvplyaj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gt2szluiquy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ksdosxgf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2scozdkbb.html

TS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gsauihcx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2nluyrauy.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gt2lznqrfyt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2ppqqluzn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2qvbuwpdq.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ssclefit.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gt2yijzsfyo.html

PHP:  array_unique($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2mxgowkuo.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gt2wbxczvgu.html

TS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gt2ozxhpree.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pycfn.com/Article/details/gt2yhaesfdr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xylfe.cn/Article/details/gt2jefhitcb.html

Ruby: arr.uniq
来源：http://dali.tianlin.xyz/Article/details/gt2wocdpnif.html

C#:   list.Distinct().ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gqcdgchy.html

[D16] 求和与平均值
来源：http://dali.hnqzz.top/Article/details/gt2muancqig.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tanke756.top/Article/details/gt2zebfsqcj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2ccxdsswf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2hujnpcsw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gt2tqizwlxz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangshuangyany.cn/Article/details/gt2skrfwvox.html

Go:   // 手写循环累加
来源：http://dali.yuxming.cn/Article/details/gt2mbnvpubk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gt2camrxjxd.html

C#:   list.Sum();  list.Average()
来源：http://dali.cheryme.top/Article/details/gt2uaeubadm.html

[D17] 最大值与最小值
来源：http://dali.havefunace.top/Article/details/gt2hmdpixip.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gt2gfrigyqk.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2axathmrn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yueranfly.top/Article/details/gt2hralpeho.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gt2jrbgoidc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kpvrxozj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xziqi.cn/Article/details/gt2dvxwxuvr.html

Ruby: arr.max;  arr.min
来源：http://dali.yonumen.top/Article/details/gt2mgzvszdb.html

C#:   list.Max();  list.Min()
来源：http://dali.zhongyouzk.top/Article/details/gt2gmetoxpc.html

[D18] 扁平化嵌套数组
来源：http://dali.ehwqpu.com/Article/details/gt2cgphvbna.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aibaodan.cn/Article/details/gt2fbocsimz.html

PHP:  array_merge(...$nested);
来源：http://dali.gotoacloud.top/Article/details/gt2vioaobfk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gt2ckdpbzfb.html

TS:   nested.flat();
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubdupkau.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yongpay.top/Article/details/gt2nkmspfao.html

Go:   // 手写双层循环
来源：http://dali.sufxvd.cn/Article/details/gt2ldsizttc.html

Ruby: nested.flatten
来源：http://dali.yj20258.top/Article/details/gt2tovtalub.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2yuvjfilr.html

[D19] 按字段分组
来源：http://dali.tian-w.cn/Article/details/gt2lvwbogoq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2bjfftkjv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.snrcjt.cn/Article/details/gt2kbjojmxj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.meibo888.top/Article/details/gt2acmbsyur.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuxming.cn/Article/details/gt2hskilzds.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jiagoushi.top/Article/details/gt2vxdasxpj.html

Go:   // 手写 map[string][]T
来源：http://dali.svipenyu.cn/Article/details/gt2vzkuothr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenzaomai.com/Article/details/gt2vebjjrbn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhiwuduotai.top/Article/details/gt2avlseono.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2eacugykn.html

Py:   Counter(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2pkaikbzd.html

PHP:  array_count_values($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2woaddcdy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gt2zjixxmpm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gt2empaqhdk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ehwqpu.com/Article/details/gt2pedxwofb.html

Go:   // 手写 map[T]int
来源：http://dali.yj202588.top/Article/details/gt2ricqzsrw.html

Ruby: arr.tally
来源：http://dali.yj20258888.top/Article/details/gt2mbqwtwzt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gt2sihlcppg.html

[D21] 判断是否包含某元素
来源：http://dali.ehwqpu.com/Article/details/gt2rfhkqzzm.html

Py:   x in arr
来源：http://dali.havefunace.top/Article/details/gt2fpbirair.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fayqvntv.html

JS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gt2exjzdthh.html

TS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gt2usnuguam.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2mofyesow.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksroocqx.html

Ruby: arr.include?(x)
来源：http://dali.xinyue.icu/Article/details/gt2qzvnubrm.html

C#:   list.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gt2dtpbcitw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aibaodan.cn/Article/details/gt2enslzwhw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sweek.top/Article/details/gt2syrabnmn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.9152youxi.cn/Article/details/gt2kisrqjnx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2fmctozhv.html

TS:   [...arr];
来源：http://dali.nanxinkj.top/Article/details/gt2eirgrxst.html

Java: new ArrayList<>(list);
来源：http://dali.cdnleiting.top/Article/details/gt2claducrm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ehwqpu.com/Article/details/gt2xqxmknko.html

Ruby: arr.dup;  arr.clone
来源：http://dali.havefunace.top/Article/details/gt2lrfqnyqf.html

C#:   new List<int>(list);
来源：http://dali.fzhhl.top/Article/details/gt2sgqwmezg.html

[D23] reduce 累积计算
来源：http://dali.yueranfly.top/Article/details/gt2enkdaxnx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2wiwmoccp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.svipenyu.cn/Article/details/gt2drhtrbfl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gt2akjgkzgm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2eghdslfo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewyaahea.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gt2dhdfasrq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zdqjudy.top/Article/details/gt2mwuyyamb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gt2mogydgvi.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgfzy.top/Article/details/gt2fwzgtvjn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.iojbl.cn/Article/details/gt2ginwfhil.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cqqwz.cn/Article/details/gt2zrwbbjuz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2jcmeeqtg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shuidangran.top/Article/details/gt2qjbtnjxz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgugxfah.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hammf.cn/Article/details/gt2xskdyvgd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxuanxn.top/Article/details/gt2kywuspki.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrutergz.html

[D25] Set 集合去重与交并差
来源：http://dali.feifeiyinyue.top/Article/details/gt2cwxvgmsl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gt2ybsafxyf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhongyouzk.top/Article/details/gt2pidecuva.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guowangkeji.top/Article/details/gt2tisiyzkr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.havefunace.top/Article/details/gt2sfmoqjkn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2opfujpmi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azljhznn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guannengcc.top/Article/details/gt2yjbwqtol.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yangfankeji.com/Article/details/gt2yorqcigc.html

[D26] 数组转字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2luvghfzl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ivvv.top/Article/details/gt2oqyivyim.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258.top/Article/details/gt2sxtjerzp.html

JS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gt2temfsufu.html

TS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2jvqdyhrh.html

Java: String.join(", ", list)
来源：http://dali.316326.xyz/Article/details/gt2rmqkiwbh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwxyviib.html

Ruby: arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gt2jzmzlasf.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258.top/Article/details/gt2gqhxuydc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2oyhywukb.html

E. 字符串处理
来源：http://dali.haohaochexian.top/Article/details/gt2dcnuqruf.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2yjytcakf.html

[E01] 拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2ucipibbu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tanke756.top/Article/details/gt2zttrpdlz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdyuaaaj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gt2iuzunmqs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gt2sskcgpvs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gt2wwmsoziv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uwguuwhk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.mhx1999.top/Article/details/gt2wapngxjg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2ufjwkthu.html

[E02] 重复字符串
来源：http://dali.smart0.xyz/Article/details/gt2fozpadks.html

Py:   "ab" * 3
来源：http://dali.yj202588.top/Article/details/gt2zkrflpsn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.smart0.xyz/Article/details/gt2bgfwtdne.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2tixjzwkt.html

TS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gt2wgtchfvq.html

Java: "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gt2rwgnhfzi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tanke756.top/Article/details/gt2unvmbmjc.html

Ruby: "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gt2yglxpyxz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guowangkeji.top/Article/details/gt2stpqailw.html

[E03] 截取子串
来源：http://dali.yonumen.top/Article/details/gt2zxxuqihr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.andypj.xyz/Article/details/gt2qusxgqyt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2ppsykapj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hosgyevt.html

TS:   s.slice(1, 4)
来源：http://dali.c1oappe.top/Article/details/gt2kzsjavys.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2fmexrlkj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.0kj1m.cn/Article/details/gt2ewghtwei.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtzooyzk.html

C#:   s.Substring(1, 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2odahpdlo.html

[E04] 查找子串位置
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ngsjcqet.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xylfe.cn/Article/details/gt2qidqwvhl.html

PHP:  strpos($s, "x");
来源：http://dali.kuanghao11.cn/Article/details/gt2vxpsfiay.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jyoumei.cn/Article/details/gt2ctuldcqj.html

TS:   s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gt2nunepkqa.html

Java: s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2efohwrns.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwxgccr.html

Ruby: s.index("x")
来源：http://dali.yj20258.top/Article/details/gt2dufilyqa.html

C#:   s.IndexOf("x")
来源：http://dali.zycfv.cn/Article/details/gt2kkyduntm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gt2pkefyuut.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jianghu66.top/Article/details/gt2gbkbaoyv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cqqwz.cn/Article/details/gt2suxahuxo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gt2lpafkese.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ybcxt.top/Article/details/gt2vutrxcpr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.havefunace.top/Article/details/gt2dmotltvv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gogol.net.cn/Article/details/gt2xbyhakgx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.redwolf501.top/Article/details/gt2sbwmcynk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daria6918.cn/Article/details/gt2ztpqzqzj.html

[E06] 替换子串
来源：http://dali.aibaodan.cn/Article/details/gt2jwoncqzp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gt2naggcsoa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.birdmap.top/Article/details/gt2iuzibwtp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2cinqtihj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2njckgnfs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2urpliteh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gt2znxqafza.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hrrzzbnd.html

C#:   s.Replace("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkeybaip.html

[E07] 按分隔符拆分
来源：http://dali.cheryme.top/Article/details/gt2uuxktifd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xylfe.cn/Article/details/gt2vdzwuetn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2mfzvniig.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sufxvd.cn/Article/details/gt2xknruunp.html

TS:   s.split(",")
来源：http://dali.snrcjt.cn/Article/details/gt2bujomxug.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uohcisjv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.birdmap.top/Article/details/gt2zclkrous.html

Ruby: s.split(",");  s.split
来源：http://dali.xziqi.cn/Article/details/gt2fqfxhlsb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangdashe.top/Article/details/gt2jdxbwhdh.html

[E08] 数组按分隔符合并
来源：http://dali.svipenyu.cn/Article/details/gt2qsmptwpo.html

Py:   ",".join(items)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npushtsz.html

PHP:  implode(",", $items);
来源：http://dali.zdqjudy.top/Article/details/gt2tbzudtom.html

JS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2acuzrzwi.html

TS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gt2vsmrvhrt.html

Java: String.join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tzsaxnyj.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258.top/Article/details/gt2aivmibac.html

Ruby: items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gt2prphjdzi.html

C#:   string.Join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pjkhorco.html

[E09] 去除所有空白字符
来源：http://dali.cucudq.cn/Article/details/gt2ooyysnnt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jiagoushi.top/Article/details/gt2uskjpewa.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnqzz.top/Article/details/gt2adcdfivl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2blronuae.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gt2nevjyivr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjfdhsqt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.vqdsnc.cn/Article/details/gt2oapkdmyl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangdashe.top/Article/details/gt2trousber.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gt2yykedlem.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigufen.top/Article/details/gt2mutchwdk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2kjlynxjh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gt2feauuqpw.html

JS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2nyxhpokm.html

TS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gt2fkjfagon.html

Java: String.format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gt2ewvndtzv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gt2iwuneqbu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gt2ckosbqxu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gotoacloud.top/Article/details/gt2cyzslndm.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gt2ehhfqgjq.html

Py:   s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pnkchgvi.html

PHP:  strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gt2tvaqsbqs.html

JS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2iwdpplhf.html

TS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2dzruxlse.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gt2hlohubmr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sysykeji.top/Article/details/gt2dhewpxwz.html

Ruby: s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2btturepm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gt2vkhtiexn.html

[E12] 统计某字符出现次数
来源：http://dali.gaohongyu789.top/Article/details/gt2kyejmkwp.html

Py:   s.count("a")
来源：http://dali.316326.xyz/Article/details/gt2dnhxnyvt.html

PHP:  substr_count($s, "a");
来源：http://dali.haohaochexian.top/Article/details/gt2ytejlpbl.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcbhcphp.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gt2xhrufqqm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guowangkeji.top/Article/details/gt2huzcvipo.html

Go:   strings.Count(s, "a")
来源：http://dali.quarkkingdee.top/Article/details/gt2mfewwupu.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gt2lulyytkb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zycfv.cn/Article/details/gt2vqermkmt.html

[E13] 逐字符遍历
来源：http://dali.snrcjt.cn/Article/details/gt2tahuambg.html

Py:   for ch in s: print(ch)
来源：http://dali.sxryk.cn/Article/details/gt2acpsdpjw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uysxgahi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2qgmmozeg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2kxtrmvsr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2rkfxhrwh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gogol.net.cn/Article/details/gt2bibwqghp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuxming.cn/Article/details/gt2taqbewuq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ixjvitdn.html

[E14] URL 编码与 Base64
来源：http://dali.daxiang520.top/Article/details/gt2ytmjlmxw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgfzy.top/Article/details/gt2dghwxhyb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2iclkcafi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gt2sxlbonjq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lctlrrni.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2xhdhwlrg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cdnleiting.top/Article/details/gt2kptykeum.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenzaomai.com/Article/details/gt2lxoqwjsq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nwbrower.top/Article/details/gt2vgslojav.html

[E15] HTML 转义 / 反转义
来源：http://dali.yueranfly.top/Article/details/gt2jimrjqmq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ljemsbdq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gt2dixlyeaq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ffvndojp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.316326.xyz/Article/details/gt2canwwcpm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daxiang520.top/Article/details/gt2axdcbvpd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cheryme.top/Article/details/gt2fiphodga.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ydzc1.top/Article/details/gt2xyggvxhy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gt2wevmwlup.html

[E16] 数字千分位
来源：http://dali.c1oappe.top/Article/details/gt2lhvhpcld.html

Py:   f"{1234567:,}"
来源：http://dali.nanxinkj.top/Article/details/gt2kxmxtjow.html

PHP:  number_format(1234567);
来源：http://dali.chenlongwang.top/Article/details/gt2knsuqvdh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gt2vzinhnok.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gt2cqsrgkdz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gt2fjxbhypm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gt2xnhvxldz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tianlin.xyz/Article/details/gt2wwriiueq.html

C#:   1234567.ToString("N0")
来源：http://dali.wangdashe.top/Article/details/gt2rumsijcc.html

[E17] 首字母大写
来源：http://dali.wangshuangyany.cn/Article/details/gt2xftpusrx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tanke756.top/Article/details/gt2yattsayq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2zpztcbro.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gt2poajyedk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lmauulzn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gt2bunovqtc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gt2tgsfrjmy.html

Ruby: s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gt2xlxfqxqw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hfpthk.cn/Article/details/gt2ngfbkgwa.html

[E18] 模板占位符替换
来源：http://dali.jyoumei.cn/Article/details/gt2ntjludrz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.quarkkingdee.top/Article/details/gt2mhsdwbfz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.9152youxi.cn/Article/details/gt2ynctkoaz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gt2tasddsqw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2zgflvqnl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gt2zddkdvaz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2qmnqlpwo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tanke756.top/Article/details/gt2oqxoveiq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jlsjyb.cn/Article/details/gt2qpvrbmgc.html

[E19] 多行文本按行拆分
来源：http://dali.kuanghao11.cn/Article/details/gt2nfsfyszu.html

Py:   s.splitlines()
来源：http://dali.cdnleiting.top/Article/details/gt2hamjfbgy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2wkzkwoxi.html

JS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gt2wirrryuy.html

TS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gt2ulknspth.html

Java: s.lines().toList()
来源：http://dali.jiagoushi.top/Article/details/gt2wtntdnur.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgfzy.top/Article/details/gt2hzdyfbuh.html


<!-- 参考信息 -->