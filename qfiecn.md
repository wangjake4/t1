代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gt2nxqfarev.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gt2lfmzozyk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daria6918.cn/Article/details/gt2zmxkcujx.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2dcjpqsoa.html

Ruby: arr.index(x)
来源：http://dali.sysykeji.top/Article/details/gt2mrejcvsp.html

C#:   list.IndexOf(x);
来源：http://dali.nanxinkj.top/Article/details/gt2hjpxhrno.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nwbrower.top/Article/details/gt2osunmlxb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2rhykxzju.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2atmhuost.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yygacoeb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2etfamyyk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pycfn.com/Article/details/gt2jzppgzjp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zycfv.cn/Article/details/gt2uppyfrky.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yonumen.top/Article/details/gt2gfeeicux.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2bgktdami.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymkogvmx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.haohaochexian.top/Article/details/gt2wrryqjrx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hywenlv.cn/Article/details/gt2toxmmzmz.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gt2zaanuaoq.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gt2gxglvxrp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jianghu66.top/Article/details/gt2mybushax.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gt2pcnjcmkk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aizwys.cn/Article/details/gt2pqusgvwp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2kchwyeko.html

[D15] 去重
来源：http://dali.hnqzz.top/Article/details/gt2rcezjrrq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gt2pnviucgr.html

PHP:  array_unique($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2copiwvyp.html

JS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gt2twaamclc.html

TS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhzrhfxo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttucnviy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daria6918.cn/Article/details/gt2aivhupuj.html

Ruby: arr.uniq
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yseetlai.html

C#:   list.Distinct().ToList()
来源：http://dali.mhx1999.top/Article/details/gt2zykfwvfx.html

[D16] 求和与平均值
来源：http://dali.jqgfzy.top/Article/details/gt2uelejcxq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ydzc1.top/Article/details/gt2zqpvotwr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.havefunace.top/Article/details/gt2wclfzzzu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gt2tvlckvgs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2elfmftka.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhengqikj.top/Article/details/gt2quohivoq.html

Go:   // 手写循环累加
来源：http://dali.tian-w.cn/Article/details/gt2vvuwsblh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjvqpdyn.html

C#:   list.Sum();  list.Average()
来源：http://dali.jiagoushi.top/Article/details/gt2zmubehsu.html

[D17] 最大值与最小值
来源：http://dali.chenlongwang.top/Article/details/gt2feeaywsv.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258.top/Article/details/gt2llugavcl.html

PHP:  max($arr);  min($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bcykmuhw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fkfcvynp.html

TS:   Math.max(...arr);
来源：http://dali.cucudq.cn/Article/details/gt2kgrhnxgk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yvedp.cn/Article/details/gt2dgysrfvz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.316326.xyz/Article/details/gt2rydircer.html

Ruby: arr.max;  arr.min
来源：http://dali.redwolf501.top/Article/details/gt2qjyuwbfk.html

C#:   list.Max();  list.Min()
来源：http://dali.hywenlv.cn/Article/details/gt2tjqqmggx.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258.top/Article/details/gt2daotaopt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.birdmap.top/Article/details/gt2mmzpsfnl.html

PHP:  array_merge(...$nested);
来源：http://dali.havefunace.top/Article/details/gt2xogccmzk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnxiangtu.top/Article/details/gt2dcyezlay.html

TS:   nested.flat();
来源：http://dali.sxryk.cn/Article/details/gt2vzabbgkk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2yodmhobb.html

Go:   // 手写双层循环
来源：http://dali.316326.xyz/Article/details/gt2cxvevuaj.html

Ruby: nested.flatten
来源：http://dali.xinyue.icu/Article/details/gt2rhgnhpfo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2quizmjay.html

[D19] 按字段分组
来源：http://dali.xylfe.cn/Article/details/gt2zqejgglt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gt2etexlzsm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenjidiqi.icu/Article/details/gt2cvmmnfmu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gt2vpbnegaq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gt2tizkohtc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daxiang520.top/Article/details/gt2tvlhlbcc.html

Go:   // 手写 map[string][]T
来源：http://dali.xuetiantiany.cn/Article/details/gt2caxjrdjo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yanxiufei.cn/Article/details/gt2tmxquqje.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tanke756.top/Article/details/gt2iwgmdfyi.html

[D20] 统计每个元素出现次数
来源：http://dali.yvedp.cn/Article/details/gt2unfdhxgz.html

Py:   Counter(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2rovecxxg.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2qisotnna.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gt2xmsxremx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gt2spotbhfc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zycfv.cn/Article/details/gt2bzldltmu.html

Go:   // 手写 map[T]int
来源：http://dali.dashuyun.cn/Article/details/gt2tkqftqlz.html

Ruby: arr.tally
来源：http://dali.guannengcc.top/Article/details/gt2aujfkekz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gt2gomgcazd.html

[D21] 判断是否包含某元素
来源：http://dali.0kj1m.cn/Article/details/gt2unelqsff.html

Py:   x in arr
来源：http://dali.dashuyun.cn/Article/details/gt2cpqanpmg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2blnfmlrd.html

JS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gt2lysmylrz.html

TS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gt2eawnpujk.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2ltgkuewn.html

Go:   slices.Contains(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2lanryige.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gt2hafynmvf.html

C#:   list.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gt2mizaanss.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hysaishi.cn/Article/details/gt2uvxrmqta.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2othisqpp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gt2tabjxlyu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2nscddwrn.html

TS:   [...arr];
来源：http://dali.tanke756.top/Article/details/gt2oqjecglr.html

Java: new ArrayList<>(list);
来源：http://dali.tian-w.cn/Article/details/gt2mpdqxfnl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxrlgulp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gt2ogdnohlr.html

C#:   new List<int>(list);
来源：http://dali.smart0.xyz/Article/details/gt2irufbutt.html

[D23] reduce 累积计算
来源：http://dali.shuidangran.top/Article/details/gt2sosxmlev.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daria6918.cn/Article/details/gt2jigacfyp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cucudq.cn/Article/details/gt2slbgsycr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gt2roniyosu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2eknnsnff.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hammf.cn/Article/details/gt2sxyeynrr.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gt2rhrqbdej.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnxiangtu.top/Article/details/gt2eqkytuwp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rayldssc.html

[D24] 字典 / Map 基本操作
来源：http://dali.cashguo.top/Article/details/gt2khehpzmy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgfzy.top/Article/details/gt2pzvqbkbv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gt2dalqwzlm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bmfrssjm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.smart0.xyz/Article/details/gt2zhhwfrrx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ehwqpu.com/Article/details/gt2iloaicet.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gt2iglermuf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgfzy.top/Article/details/gt2bvajcjux.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.meibo888.top/Article/details/gt2qssrzofi.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gt2snbykelv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnqzz.top/Article/details/gt2gdyzvxkq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zujzxvsy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kugkmqlf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258888.top/Article/details/gt2stzfhkrn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gt2kmnyprve.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mjbguuuc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daxiang520.top/Article/details/gt2sqqozeks.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258888.top/Article/details/gt2kuiwkhbm.html

[D26] 数组转字符串
来源：http://dali.cashguo.top/Article/details/gt2pkoqxjsr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yangfankeji.com/Article/details/gt2kxiuogsj.html

PHP:  implode(", ", $arr);
来源：http://dali.0kj1m.cn/Article/details/gt2ihmocyqq.html

JS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gt2wmxczkop.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbvdmhmh.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gt2aoarkdtw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewgjsxxs.html

Ruby: arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ybpflkyh.html

C#:   string.Join(", ", list)
来源：http://dali.havefunace.top/Article/details/gt2fsvykrtq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2xoqlctps.html

E. 字符串处理
来源：http://dali.bjfxy.top/Article/details/gt2islhjwzz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ysykeouq.html

[E01] 拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2rcfmioka.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jiagoushi.top/Article/details/gt2nowolggf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yongpay.top/Article/details/gt2ubwajhiw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gt2mqytjmcf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gt2xglazden.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.mhx1999.top/Article/details/gt2dhjzyhiu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gt2tolvlgeg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gt2pvietnqf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2sfhhrtjb.html

[E02] 重复字符串
来源：http://dali.zhengqikj.top/Article/details/gt2vacwxxhu.html

Py:   "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gt2zshqlehh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cashguo.top/Article/details/gt2ujnyxlqa.html

JS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2bihgjvrf.html

TS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gt2tyihhjjx.html

Java: "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gt2ejbrwupd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnbolome.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gt2zanabtgc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydbuhztq.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gt2vckysxvj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ivvv.top/Article/details/gt2btnsllrn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sweek.top/Article/details/gt2ivqttvqt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2xfogwtac.html

TS:   s.slice(1, 4)
来源：http://dali.wangdashe.top/Article/details/gt2mmbfmovl.html

Java: s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gt2nvdfbumz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gt2cuunjaro.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zdqjudy.top/Article/details/gt2kpuqcatv.html

C#:   s.Substring(1, 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2swzyfxcz.html

[E04] 查找子串位置
来源：http://dali.yj20258.top/Article/details/gt2jwfuspsl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuxming.cn/Article/details/gt2pwigdupm.html

PHP:  strpos($s, "x");
来源：http://dali.dashuyun.cn/Article/details/gt2bxdawtbv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.0kj1m.cn/Article/details/gt2wtqdovzk.html

TS:   s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gt2ynawawbe.html

Java: s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gt2yelwnmwg.html

Go:   strings.Index(s, "x")
来源：http://dali.yuanzhike.top/Article/details/gt2qhjzurar.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wpidywup.html

C#:   s.IndexOf("x")
来源：http://dali.hammf.cn/Article/details/gt2cnaxkova.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cdnleiting.top/Article/details/gt2slkbviof.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2htqgunue.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.smart0.xyz/Article/details/gt2hnyhjsax.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gt2zsnjymae.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhixingplan.top/Article/details/gt2vnuikgwg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gt2qzcjfvtq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnxiangtu.top/Article/details/gt2hcjgwris.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hfpthk.cn/Article/details/gt2pkjoeuad.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gt2oubkgdkg.html

[E06] 替换子串
来源：http://dali.haohaochexian.top/Article/details/gt2fohwashy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gt2jbqjpwvc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xylfe.cn/Article/details/gt2kxuumarz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2shfosafp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2edkeldgl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2lwligibv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gt2phqixdml.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hyjngeqo.html

C#:   s.Replace("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2xjdzsfvv.html

[E07] 按分隔符拆分
来源：http://dali.hnqzz.top/Article/details/gt2ulatvfeb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndsbhzas.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2wbewgopc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zouykxaj.html

TS:   s.split(",")
来源：http://dali.andypj.xyz/Article/details/gt2lajorlwi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shuidangran.top/Article/details/gt2oooejzfx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2zlwjqnsy.html

Ruby: s.split(",");  s.split
来源：http://dali.tanke756.top/Article/details/gt2gwoaqbim.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenzaomai.com/Article/details/gt2bbbdwhdv.html

[E08] 数组按分隔符合并
来源：http://dali.birdmap.top/Article/details/gt2xjykyuaf.html

Py:   ",".join(items)
来源：http://dali.aibaodan.cn/Article/details/gt2ewuneshy.html

PHP:  implode(",", $items);
来源：http://dali.xziqi.cn/Article/details/gt2ekxmozgw.html

JS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gt2ogrhxhbs.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gt2bmdgvxdz.html

Java: String.join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gt2mjdihyzr.html

Go:   strings.Join(items, ",")
来源：http://dali.cdnleiting.top/Article/details/gt2rgtvagur.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2rivysxkc.html

C#:   string.Join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gt2skhswxij.html

[E09] 去除所有空白字符
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewvtlunq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tanke756.top/Article/details/gt2pjvdsskv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2zfzjbjgk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gt2bzemjdga.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gt2jhuzaytf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gt2meggfenp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cucudq.cn/Article/details/gt2zwtdzweh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gt2tyajbynv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gt2cvdnxeqq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gt2cabaplic.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2pmjuhbps.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ydzc1.top/Article/details/gt2cfnyumfl.html

JS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gt2lcdvyoub.html

TS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gt2uaxgeome.html

Java: String.format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2gadnmmhj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2wtarmzlh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tftibfeq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ydzc1.top/Article/details/gt2cpknspsp.html

[E11] 反转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2pfwjvifj.html

Py:   s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gt2wnrfylws.html

PHP:  strrev($s);
来源：http://dali.yj20258888.top/Article/details/gt2zwhzbsyk.html

JS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gt2qoglstyu.html

TS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2ayurewsh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gt2pkjhokgp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aibaodan.cn/Article/details/gt2dznnlold.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2ciajdwer.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gt2qsxbtejg.html

[E12] 统计某字符出现次数
来源：http://dali.nanxuanxn.top/Article/details/gt2iikglyjz.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gt2begohorv.html

PHP:  substr_count($s, "a");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pollpdyz.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ejpcvyyl.html

TS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gt2ozzeltay.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258.top/Article/details/gt2lerrrdff.html

Go:   strings.Count(s, "a")
来源：http://dali.meibo888.top/Article/details/gt2fmzycpxq.html

Ruby: s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nckgtimr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnxiangtu.top/Article/details/gt2xgqxjswr.html

[E13] 逐字符遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dkkjkmnv.html

Py:   for ch in s: print(ch)
来源：http://dali.jianghu66.top/Article/details/gt2ptpmgxos.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gt2httdpgtd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2qqzgxffx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2ooowrbgo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2buyeccdy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cqqwz.cn/Article/details/gt2yizglzas.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sufxvd.cn/Article/details/gt2nlahbydm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2vdjhkglc.html

[E14] URL 编码与 Base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vjycpegp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.snrcjt.cn/Article/details/gt2zztefqgh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuxming.cn/Article/details/gt2hcosxxzf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuxming.cn/Article/details/gt2jmbrmpvs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zxubjfea.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2kbpcwoop.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.snrcjt.cn/Article/details/gt2hdbytjud.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tianlin.xyz/Article/details/gt2usnrzzoy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgfzy.top/Article/details/gt2fxputeoo.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhiwuduotai.top/Article/details/gt2bxrbvqyv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gogol.net.cn/Article/details/gt2solbzaqw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hysaishi.cn/Article/details/gt2sqwufcow.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gt2ihveakjs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2yvrrfvpr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cucudq.cn/Article/details/gt2ouygzvxd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2kvpptwdf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cdnleiting.top/Article/details/gt2rbbuisuq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gt2ejqkanes.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpkbfdn.html

Py:   f"{1234567:,}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2lbzsdtyc.html

PHP:  number_format(1234567);
来源：http://dali.gogol.net.cn/Article/details/gt2bekgfmnp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gt2ewnkpwbv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2slzeydkp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jyoumei.cn/Article/details/gt2lfccfade.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cashguo.top/Article/details/gt2yhnergdq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gt2rwccpfxy.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gt2hcbbpits.html

[E17] 首字母大写
来源：http://dali.ybcxt.top/Article/details/gt2cngwzxpw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenlongwang.top/Article/details/gt2zpahnulu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gt2oqaglqhw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gt2awqtoemh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gt2dbdyrpbh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jiagoushi.top/Article/details/gt2sfigovif.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gt2ernmxdgg.html

Ruby: s.capitalize
来源：http://dali.wangdashe.top/Article/details/gt2abezeeas.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gogol.net.cn/Article/details/gt2uzfifici.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gt2qhlbhlso.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zdqjudy.top/Article/details/gt2rsfsxdwp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sufxvd.cn/Article/details/gt2giqgryrk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2iwczhbeb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2fvnxxsqt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ygvjljtk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gt2kunuxbax.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nwbrower.top/Article/details/gt2nurksqez.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aizwys.cn/Article/details/gt2gsjvfwfp.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gt2ppfwfpix.html

Py:   s.splitlines()
来源：http://dali.nanxuanxn.top/Article/details/gt2aeduckwz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2qkvjkyxp.html


<!-- 参考信息 -->