代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.gzhubu.top/Article/details/gt2oalawyft.html

Java: Collections.reverse(list);
来源：http://dali.jlsjyb.cn/Article/details/gt2esnmigco.html

Go:   slices.Reverse(arr)
来源：http://dali.fengsongda.top/Article/details/gt2qqsozqxt.html

Ruby: arr.reverse
来源：http://dali.zhixingplan.top/Article/details/gt2geujqczn.html

C#:   list.Reverse();
来源：http://dali.wangdashe.top/Article/details/gt2jsjehzdc.html

[D12] 查找元素下标
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eqrmdvuu.html

Py:   arr.index(x);  x in arr
来源：http://dali.fengsongda.top/Article/details/gt2prtnskmq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2fpeniuge.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2yqarndcn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ieytihbe.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xinyue.icu/Article/details/gt2ogrefqet.html

Go:   slices.Index(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2uumfvruk.html

Ruby: arr.index(x)
来源：http://dali.yj20258.top/Article/details/gt2hvboxtkl.html

C#:   list.IndexOf(x);
来源：http://dali.ppjwa.cn/Article/details/gt2gohqflxj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yueranfly.top/Article/details/gt2vsrqeeuq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwapsbfs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xziqi.cn/Article/details/gt2cmmqkeaj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2jhbvcezn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gt2kgddhoah.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2srglepfr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgfzy.top/Article/details/gt2kodcqdsp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hammf.cn/Article/details/gt2ovdkbtgs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2mqgfwodf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.haohaochexian.top/Article/details/gt2ubezxwob.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gt2sezpcgsg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnqzz.top/Article/details/gt2ftconukv.html

JS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2exjyoxsu.html

TS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gt2cicctkmr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2wokfdzvm.html

Go:   // 手写循环
来源：http://dali.yj202588.top/Article/details/gt2ijtycorr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangdashe.top/Article/details/gt2ugmbqzyw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2bjoblcqh.html

[D15] 去重
来源：http://dali.yanxiufei.cn/Article/details/gt2xgrmjaaz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daria6918.cn/Article/details/gt2xvjifxda.html

PHP:  array_unique($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2hhzvsdlv.html

JS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gt2pvyjrgze.html

TS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gt2mtbfajnm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shangyingyoupin.top/Article/details/gt2meczxsfm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.havefunace.top/Article/details/gt2ifdfivbz.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ezaqxchr.html

C#:   list.Distinct().ToList()
来源：http://dali.andypj.xyz/Article/details/gt2viexiddw.html

[D16] 求和与平均值
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldshpiud.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2uxhuguxl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2wgpdfpyx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2ounbvjwm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gt2gunlcrif.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhixingplan.top/Article/details/gt2ineysykg.html

Go:   // 手写循环累加
来源：http://dali.zhongyouzk.top/Article/details/gt2bufhxelz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gt2xtysevmc.html

C#:   list.Sum();  list.Average()
来源：http://dali.cashguo.top/Article/details/gt2fuymbxgg.html

[D17] 最大值与最小值
来源：http://dali.zycfv.cn/Article/details/gt2mvwzdqdk.html

Py:   max(arr);  min(arr)
来源：http://dali.yongpay.top/Article/details/gt2moibzgod.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gt2lsafwuge.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dashuyun.cn/Article/details/gt2jrikphnu.html

TS:   Math.max(...arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wgozfiek.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cucudq.cn/Article/details/gt2gzcvvuqg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2bwdhblnu.html

Ruby: arr.max;  arr.min
来源：http://dali.pengpengdd.cyou/Article/details/gt2tevsbnfz.html

C#:   list.Max();  list.Min()
来源：http://dali.9152youxi.cn/Article/details/gt2gjvginks.html

[D18] 扁平化嵌套数组
来源：http://dali.gzhubu.top/Article/details/gt2tjyrvbie.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.c1oappe.top/Article/details/gt2vcwzanee.html

PHP:  array_merge(...$nested);
来源：http://dali.fengsongda.top/Article/details/gt2hhmiyyoy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmsdilkt.html

TS:   nested.flat();
来源：http://dali.cheryme.top/Article/details/gt2chbttnbc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2wjvehgcp.html

Go:   // 手写双层循环
来源：http://dali.meibo888.top/Article/details/gt2gqsnbgjo.html

Ruby: nested.flatten
来源：http://dali.snrcjt.cn/Article/details/gt2mvbebhrx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2elqlaoni.html

[D19] 按字段分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2slihsrul.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.redwolf501.top/Article/details/gt2qktcfaxi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.iojbl.cn/Article/details/gt2itzqktxh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gaohongyu789.top/Article/details/gt2wdowwivk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gt2vgovkhfc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gaohongyu789.top/Article/details/gt2nyhjnvkc.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gt2yokzsbsc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gt2upgwishk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fzhhl.top/Article/details/gt2fmtshaeb.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxuanxn.top/Article/details/gt2zoyqbiii.html

Py:   Counter(arr)
来源：http://dali.aizwys.cn/Article/details/gt2zzhjlljz.html

PHP:  array_count_values($arr);
来源：http://dali.jianghu66.top/Article/details/gt2lrgksywt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gt2utlvkmsn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gt2dservotc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuetiantiany.cn/Article/details/gt2epthijsk.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vuljeojx.html

Ruby: arr.tally
来源：http://dali.jlsjyb.cn/Article/details/gt2qtefnnar.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gt2xhjkglab.html

[D21] 判断是否包含某元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2bwyfkhzw.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gt2gtvapomu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2pvleuytm.html

JS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gt2yfldimrn.html

TS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gt2apnazgro.html

Java: list.contains(x)
来源：http://dali.0kj1m.cn/Article/details/gt2tzdlhifm.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2aoexjszx.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gt2ilojsvai.html

C#:   list.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gt2dfwlfsuk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.kuanghao11.cn/Article/details/gt2cndikdxz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2bsrwdbqv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yueranfly.top/Article/details/gt2tridbfsn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2jtctobtp.html

TS:   [...arr];
来源：http://dali.c1oappe.top/Article/details/gt2bfqpcfpk.html

Java: new ArrayList<>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bltjnrbv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dashuyun.cn/Article/details/gt2kabjeksa.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xylfe.cn/Article/details/gt2kuicaaaj.html

C#:   new List<int>(list);
来源：http://dali.andypj.xyz/Article/details/gt2ntgkoijm.html

[D23] reduce 累积计算
来源：http://dali.gaohongyu789.top/Article/details/gt2baqbturp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yonumen.top/Article/details/gt2rkdpvhzd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.havefunace.top/Article/details/gt2hdbhiaxk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gt2ndhuqhpq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2fphoupfq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gt2qrnrilhc.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gt2bsxzxekl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hywenlv.cn/Article/details/gt2fptqqfaa.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tanke756.top/Article/details/gt2vcaskegm.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhiwuduotai.top/Article/details/gt2faivahsf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cashguo.top/Article/details/gt2yukqgzsy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.birdmap.top/Article/details/gt2fbwponfn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2wayzspas.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnqzz.top/Article/details/gt2dydtnlst.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daria6918.cn/Article/details/gt2rvxpwztb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daxiang520.top/Article/details/gt2snrwofaq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhzlqsmk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cucudq.cn/Article/details/gt2vwtbtxpz.html

[D25] Set 集合去重与交并差
来源：http://dali.gotoacloud.top/Article/details/gt2rfjkoirf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yueranfly.top/Article/details/gt2nhpmwhtv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxinkj.top/Article/details/gt2wqgmvpam.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ruivjxmi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gt2ngawnlte.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dianchejie.cn/Article/details/gt2fjvaaszb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenzaomai.com/Article/details/gt2rkfaictv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj202588.top/Article/details/gt2clwzjmxh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqdxlkll.html

[D26] 数组转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2qtifzkjz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigufen.top/Article/details/gt2wjajzbpu.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gt2sxvvwuvg.html

JS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gt2mmojicdr.html

TS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fajnuira.html

Java: String.join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhmdwhij.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cdnleiting.top/Article/details/gt2hcxmiwer.html

Ruby: arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gt2klgexntq.html

C#:   string.Join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gt2btphemwi.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2fjixksva.html

E. 字符串处理
来源：http://dali.bjfxy.top/Article/details/gt2vyecrehw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2sigdyczl.html

[E01] 拼接字符串
来源：http://dali.xylfe.cn/Article/details/gt2vgluelcl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258888.top/Article/details/gt2xumyumjw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pycfn.com/Article/details/gt2fvdaxtno.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gt2sghvhpqy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gt2dthcxcxt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gt2otmegcfw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jiagoushi.top/Article/details/gt2syelmgwo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuetiantiany.cn/Article/details/gt2vceqbshu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2suufbjld.html

[E02] 重复字符串
来源：http://dali.jinqigufen.top/Article/details/gt2nmzfznbb.html

Py:   "ab" * 3
来源：http://dali.yj202588.top/Article/details/gt2rurowgon.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jianghu66.top/Article/details/gt2yezhzkcn.html

JS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gt2xjhjpyup.html

TS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gt2tshddeth.html

Java: "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gt2kdukmtkd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gt2pdtcouzl.html

Ruby: "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gt2zxeijqsi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgfzy.top/Article/details/gt2dubxjujn.html

[E03] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gt2arsjjcwm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pycfn.com/Article/details/gt2khwjdjgu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2huebqqve.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2dohjtuma.html

TS:   s.slice(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2spitpylx.html

Java: s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmqkqbxj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwqdwsta.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hysaishi.cn/Article/details/gt2jjjenytm.html

C#:   s.Substring(1, 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2roxciaos.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gt2zefxbqwx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sysykeji.top/Article/details/gt2hrragxpu.html

PHP:  strpos($s, "x");
来源：http://dali.smart0.xyz/Article/details/gt2ermngncb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxuanxn.top/Article/details/gt2gchbkupt.html

TS:   s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gt2hssnxxep.html

Java: s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gt2gdchatex.html

Go:   strings.Index(s, "x")
来源：http://dali.jiagoushi.top/Article/details/gt2cgztkuvx.html

Ruby: s.index("x")
来源：http://dali.mhx1999.top/Article/details/gt2tmtkxqom.html

C#:   s.IndexOf("x")
来源：http://dali.jianghu66.top/Article/details/gt2asjukiyb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.havefunace.top/Article/details/gt2ycietmsf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ydzc1.top/Article/details/gt2apjsexle.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgfzy.top/Article/details/gt2qukvsjii.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gt2zjfapvyt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhengqikj.top/Article/details/gt2fkjzoaxp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gt2wyxdbbmg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tianlin.xyz/Article/details/gt2efkbuwmy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigufen.top/Article/details/gt2nyclzafn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbovunjs.html

[E06] 替换子串
来源：http://dali.nanxinkj.top/Article/details/gt2jyokrujg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gt2qlqfmkzp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jyoumei.cn/Article/details/gt2qbuzkgrp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2dbppquth.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2tetddcxy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2ijuplvip.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vabfysyd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2dhxzqguy.html

C#:   s.Replace("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2jrxmnvzi.html

[E07] 按分隔符拆分
来源：http://dali.hongshengwenyu.top/Article/details/gt2knrdwkpu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhiwuduotai.top/Article/details/gt2nowluzgm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2lcgkhpnz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rsduotqo.html

TS:   s.split(",")
来源：http://dali.andypj.xyz/Article/details/gt2egnuuwge.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cheryme.top/Article/details/gt2fyyruqqa.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2iezpvcha.html

Ruby: s.split(",");  s.split
来源：http://dali.zhoulong.xyz/Article/details/gt2kyefhyqk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gt2zuyxgfow.html

[E08] 数组按分隔符合并
来源：http://dali.chenjidiqi.icu/Article/details/gt2qpnqapvg.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gt2xdintuey.html

PHP:  implode(",", $items);
来源：http://dali.hysaishi.cn/Article/details/gt2vqappyle.html

JS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gt2rvjenggd.html

TS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gt2eikoxsmz.html

Java: String.join(",", items)
来源：http://dali.fengsongda.top/Article/details/gt2wzeofjhr.html

Go:   strings.Join(items, ",")
来源：http://dali.ivvv.top/Article/details/gt2pxjrcsbb.html

Ruby: items.join(",")
来源：http://dali.andypj.xyz/Article/details/gt2rqntccvw.html

C#:   string.Join(",", items)
来源：http://dali.mhx1999.top/Article/details/gt2gqxlharv.html

[E09] 去除所有空白字符
来源：http://dali.yuxming.cn/Article/details/gt2ouphgpro.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2mzghjzzj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2ezvcajqo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2luobainp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gt2lrdllsqm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ybcxt.top/Article/details/gt2nbfkcnih.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gt2qzoujlna.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxsjlcrg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sysykeji.top/Article/details/gt2thjkwonb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.redwolf501.top/Article/details/gt2zcgfeinp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ybcxt.top/Article/details/gt2ahyxzjtc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yanxiufei.cn/Article/details/gt2wbikfitc.html

JS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gt2jidusxlc.html

TS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gt2gylhlupy.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gt2ivhkbrkj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gt2hldmuucg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2pfafyxmu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.svipenyu.cn/Article/details/gt2hruirfpv.html

[E11] 反转字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2qeelawqk.html

Py:   s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rchkgdkk.html

PHP:  strrev($s);
来源：http://dali.nwbrower.top/Article/details/gt2dbudwmdt.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2hiyxbkyc.html

TS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2bppxvlnx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gt2exqknawq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulqlxuby.html

Ruby: s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2dfhvkeou.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gt2dqklhscm.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvzrskmm.html

Py:   s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fwyfgnfk.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gt2zlzxeydb.html

JS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gt2hbzqoduh.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gt2lnsctjxi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gt2bbisvuub.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2virphfqa.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gt2xeirhkga.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gt2qcwuhufk.html

[E13] 逐字符遍历
来源：http://dali.jiagoushi.top/Article/details/gt2opwwklqv.html

Py:   for ch in s: print(ch)
来源：http://dali.cucudq.cn/Article/details/gt2uobekarp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhixingplan.top/Article/details/gt2lsvfniue.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2cntrtked.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gt2kvamughh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yangfankeji.com/Article/details/gt2lwvhslhw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2ymmvjwcq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jlsjyb.cn/Article/details/gt2csijcmes.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2tufextmc.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2llobtdgy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aizwys.cn/Article/details/gt2ylstmyib.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenzaomai.com/Article/details/gt2ubrcwesc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.svipenyu.cn/Article/details/gt2mpmbgnqq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2prrbrkpf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gt2ttdmndyt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.quarkkingdee.top/Article/details/gt2xovybija.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmrnuamj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hnnzhejs.html

[E15] HTML 转义 / 反转义
来源：http://dali.shzxlz.cn/Article/details/gt2bxogtuin.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mksualsv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2lkwlghvn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gt2iroauzzx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yvedp.cn/Article/details/gt2cwqcjazf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gt2nurmbajc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jyoumei.cn/Article/details/gt2qedoftjf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ksjhmrxb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cucudq.cn/Article/details/gt2kipvtfgh.html

[E16] 数字千分位
来源：http://dali.daria6918.cn/Article/details/gt2jtptijiy.html

Py:   f"{1234567:,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ytebqigf.html

PHP:  number_format(1234567);
来源：http://dali.zhixingplan.top/Article/details/gt2enrwnnuu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gt2qtcljffk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gt2elrjwbmq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gt2rqqlaegb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dianchejie.cn/Article/details/gt2jylixrtl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxcrtzoc.html

C#:   1234567.ToString("N0")
来源：http://dali.iojbl.cn/Article/details/gt2jvdptpcl.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gt2suvuoswa.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tianlin.xyz/Article/details/gt2idpapyiw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yongpay.top/Article/details/gt2dywgmdnu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2afpntgtm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gt2axsqrnum.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2tyqhqesr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2vtyammqq.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gt2kvzztikf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gt2ypbldsjl.html

[E18] 模板占位符替换
来源：http://dali.gogol.net.cn/Article/details/gt2vbsqsplv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangdashe.top/Article/details/gt2uebdzqrp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hammf.cn/Article/details/gt2zhcnnezc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2qfogojyu.html


<!-- 参考信息 -->