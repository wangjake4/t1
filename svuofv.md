代发 wailian999

[D15] 去重
来源：http://dali.316326.xyz/Article/details/gtxsmfwrks.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gtottcjiml.html

PHP:  array_unique($arr);
来源：http://dali.yongpay.top/Article/details/gtwpdvnmiv.html

JS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtqhiidazo.html

TS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtqgkiwbxe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.smart0.xyz/Article/details/gtfwykgncr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fengsongda.top/Article/details/gtmnanljum.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gtrtwsvnxn.html

C#:   list.Distinct().ToList()
来源：http://dali.ivvv.top/Article/details/gtnosotfal.html

[D16] 求和与平均值
来源：http://dali.316326.xyz/Article/details/gtsegnmipa.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gtkupqncel.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.andypj.xyz/Article/details/gtvznjmdwp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gtkzzbgltq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gtiyacjerb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.c1oappe.top/Article/details/gtphbflkwe.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gtmmudxnpz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gtnbpatkvl.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gtxphanoik.html

[D17] 最大值与最小值
来源：http://dali.jianghu66.top/Article/details/gtauekrbej.html

Py:   max(arr);  min(arr)
来源：http://dali.cucudq.cn/Article/details/gtxhfuthfl.html

PHP:  max($arr);  min($arr);
来源：http://dali.tanke756.top/Article/details/gtrumulppa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aibaodan.cn/Article/details/gtshnxetpu.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gtlqyjzaem.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.c1oappe.top/Article/details/gtybbdarrm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfehvkkv.html

Ruby: arr.max;  arr.min
来源：http://dali.quarkkingdee.top/Article/details/gtrdojmlmr.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gtpkvelwrw.html

[D18] 扁平化嵌套数组
来源：http://dali.zhoulong.xyz/Article/details/gtqzhhhctd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yvedp.cn/Article/details/gtmggplvhp.html

PHP:  array_merge(...$nested);
来源：http://dali.gotoacloud.top/Article/details/gtkktwcjge.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuimnqxui.html

TS:   nested.flat();
来源：http://dali.yj20258888.top/Article/details/gtlgqpbyrn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.birdmap.top/Article/details/gtpqfauhah.html

Go:   // 手写双层循环
来源：http://dali.aibaodan.cn/Article/details/gttvzzrcuj.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxgvgslv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tanke756.top/Article/details/gtibofrotk.html

[D19] 按字段分组
来源：http://dali.c1oappe.top/Article/details/gtlmvwaacp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.havefunace.top/Article/details/gtxvkrewuq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cashguo.top/Article/details/gtgrcewrbg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxinkj.top/Article/details/gtakwzmdch.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gtrrxaffbx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgbuarlc.html

Go:   // 手写 map[string][]T
来源：http://dali.chenlongwang.top/Article/details/gtavnipfcw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypzbymjk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebdkiyzc.html

[D20] 统计每个元素出现次数
来源：http://dali.hammf.cn/Article/details/gtgucukzaa.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqvvyxtn.html

PHP:  array_count_values($arr);
来源：http://dali.redwolf501.top/Article/details/gtgpgeezfu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtcgniaqkq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtzqetmdgx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jianghu66.top/Article/details/gtufouskdd.html

Go:   // 手写 map[T]int
来源：http://dali.aibaodan.cn/Article/details/gtyztxqhzw.html

Ruby: arr.tally
来源：http://dali.chenzaomai.com/Article/details/gttucqjmkj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gtgpvudzqd.html

[D21] 判断是否包含某元素
来源：http://dali.ehwqpu.com/Article/details/gtpigrhhrn.html

Py:   x in arr
来源：http://dali.ydzc1.top/Article/details/gtsllxfkoi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fzhhl.top/Article/details/gtiujppgoc.html

JS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gtfgbpvgjl.html

TS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gtdnjxgusw.html

Java: list.contains(x)
来源：http://dali.zycfv.cn/Article/details/gtlihtndxm.html

Go:   slices.Contains(arr, x)
来源：http://dali.cashguo.top/Article/details/gtizcwdjio.html

Ruby: arr.include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtembxdpfe.html

C#:   list.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gttofabqwp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenzaomai.com/Article/details/gtjcdmyzpv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtqtehqouw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gtzgvqhlfg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gtqazhwdxv.html

TS:   [...arr];
来源：http://dali.yangfankeji.com/Article/details/gtoowdttoz.html

Java: new ArrayList<>(list);
来源：http://dali.zhoulong.xyz/Article/details/gtnfiexxjf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hfpthk.cn/Article/details/gtsqbaewsf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.kuanghao11.cn/Article/details/gtjohewlyg.html

C#:   new List<int>(list);
来源：http://dali.yueranfly.top/Article/details/gtkftvgkvf.html

[D23] reduce 累积计算
来源：http://dali.wangshuangyany.cn/Article/details/gtohrtkqaa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.redwolf501.top/Article/details/gtciyzrlqf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqbgqarn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gtajqnbkvj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtyopxgocu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gtoppebvaw.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gtkrhormrr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gtptswrtun.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdavhqgvz.html

[D24] 字典 / Map 基本操作
来源：http://dali.cashguo.top/Article/details/gtqbxcihjy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guannengcc.top/Article/details/gtkilnyria.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gtplyiamtf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yongpay.top/Article/details/gtquhepmjt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtmuutgivu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtlsnaicqu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gtazndbwfb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhongyouzk.top/Article/details/gtwavhprdd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangshuangyany.cn/Article/details/gtibchvxpk.html

[D25] Set 集合去重与交并差
来源：http://dali.shuidangran.top/Article/details/gtyblyygqb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ppjwa.cn/Article/details/gtpicolnsw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuanzhike.top/Article/details/gthauysorv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jianghu66.top/Article/details/gtaowgyfzz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhiwuduotai.top/Article/details/gteiodsjmb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guannengcc.top/Article/details/gtamuiwiyz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xinyue.icu/Article/details/gtzjxxgnsw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangdashe.top/Article/details/gtzruwpqle.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gtdhhxjpzj.html

[D26] 数组转字符串
来源：http://dali.zhixingplan.top/Article/details/gtawcbraht.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cashguo.top/Article/details/gtutcsofft.html

PHP:  implode(", ", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gteueavxti.html

JS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtidnrigjg.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtldkjhpuo.html

Java: String.join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gtvclgesho.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aibaodan.cn/Article/details/gtzrgtupsf.html

Ruby: arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtqtfmalcz.html

C#:   string.Join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gtvtewpfsm.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtxxavmvec.html

E. 字符串处理
来源：http://dali.daria6918.cn/Article/details/gtixwsdazz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtbrpwbdpp.html

[E01] 拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtognsfzni.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sxryk.cn/Article/details/gtntmhxovi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.quarkkingdee.top/Article/details/gtqhcskmjm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtnaudcuvo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtgqvouaex.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jianghu66.top/Article/details/gtoweoeeke.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnxiangtu.top/Article/details/gthzevjifz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gtyavkmngb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtaddfqayx.html

[E02] 重复字符串
来源：http://dali.mhx1999.top/Article/details/gtzeyniyxh.html

Py:   "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gtojdaitdz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.feifeiyinyue.top/Article/details/gttemjmnpv.html

JS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtadkwkhcr.html

TS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjoxhhkxf.html

Java: "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtkvohdrdt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shuidangran.top/Article/details/gtcxnadvyh.html

Ruby: "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gtaosrtckb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenzaomai.com/Article/details/gttatnftjx.html

[E03] 截取子串
来源：http://dali.cashguo.top/Article/details/gtxpzcrvhz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pycfn.com/Article/details/gthsyyldew.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtducalxbk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtmcrnbncr.html

TS:   s.slice(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtqizbnowj.html

Java: s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtlkltyprh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gtclsixefo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gtxxldivui.html

C#:   s.Substring(1, 3)
来源：http://dali.pycfn.com/Article/details/gthvdqfcps.html

[E04] 查找子串位置
来源：http://dali.yj20258888.top/Article/details/gthehcnpfg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtooupmdtw.html

PHP:  strpos($s, "x");
来源：http://dali.hnqzz.top/Article/details/gtcqqtsxub.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jlsjyb.cn/Article/details/gtjtmvgdlf.html

TS:   s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtaabicerc.html

Java: s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtyemzlkhj.html

Go:   strings.Index(s, "x")
来源：http://dali.hammf.cn/Article/details/gtjfvcaybq.html

Ruby: s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtjncqaqbu.html

C#:   s.IndexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtzwqakutz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cucudq.cn/Article/details/gtbkkkmign.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtkixvggko.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gtfkglqack.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtbzfpidug.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gtmkzkawsv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtjirswtbx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.haohaochexian.top/Article/details/gtmqgncoof.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.snrcjt.cn/Article/details/gtdeywocpq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtiwfbizuh.html

[E06] 替换子串
来源：http://dali.yuxming.cn/Article/details/gtjdkckvvi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtoowyyoca.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sysykeji.top/Article/details/gtvrkbtrga.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtyjcuubnx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtgvrphqcu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtbsawvknx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gtygsmqtgp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtdiyvsfig.html

C#:   s.Replace("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtqtublxyq.html

[E07] 按分隔符拆分
来源：http://dali.hammf.cn/Article/details/gtozzuupna.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shangyingyoupin.top/Article/details/gtxyltnjlc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtirhadxrx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gtyrqgxdse.html

TS:   s.split(",")
来源：http://dali.chenzaomai.com/Article/details/gtmhmkiauf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhiwuduotai.top/Article/details/gtoobtcbdl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.meibo888.top/Article/details/gtrwigadvg.html

Ruby: s.split(",");  s.split
来源：http://dali.bjfxy.top/Article/details/gtgqiknvlw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tianlin.xyz/Article/details/gtmjoszyfp.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gtkrzzhfch.html

Py:   ",".join(items)
来源：http://dali.0kj1m.cn/Article/details/gtyhsbxdbf.html

PHP:  implode(",", $items);
来源：http://dali.chenzaomai.com/Article/details/gttqcaekrt.html

JS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtlewusrtk.html

TS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gttuozprhq.html

Java: String.join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gtisibnahd.html

Go:   strings.Join(items, ",")
来源：http://dali.yueranfly.top/Article/details/gtedxnldpf.html

Ruby: items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtjdhazokd.html

C#:   string.Join(",", items)
来源：http://dali.hnqzz.top/Article/details/gtwsywbcwc.html

[E09] 去除所有空白字符
来源：http://dali.xuanzx.com/Article/details/gtcwqghbhi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gzhubu.top/Article/details/gtrsfqhmio.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gtmztnwuyv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gtrzvnkdpt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gtwlqqugls.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtgklwoikw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.quarkkingdee.top/Article/details/gthjyrsbdk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ybcxt.top/Article/details/gtvomglvah.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtnfchnvkp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yvedp.cn/Article/details/gtnoyulbmt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtffvixtam.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj202588.top/Article/details/gtnswymlek.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtmysbvdxd.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgjtrove.html

Java: String.format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gttxbwcojv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtrrqbkilz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtbspykshc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hfpthk.cn/Article/details/gtqtlobcrk.html

[E11] 反转字符串
来源：http://dali.yonumen.top/Article/details/gtnlpwzaif.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtrlithhkw.html

PHP:  strrev($s);
来源：http://dali.pycfn.com/Article/details/gtybissycp.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtbuseaiot.html

TS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtuqqmbpkv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hysaishi.cn/Article/details/gtcquysfwu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.redwolf501.top/Article/details/gtccohrkyp.html

Ruby: s.reverse
来源：http://dali.wangdashe.top/Article/details/gtbctyyzym.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gtpiyixroz.html

[E12] 统计某字符出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gtvbofshel.html

Py:   s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gtixvukyzj.html

PHP:  substr_count($s, "a");
来源：http://dali.gogol.net.cn/Article/details/gteqggtwyp.html

JS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gtiynruwrt.html

TS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gtjidyslcd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shangyingyoupin.top/Article/details/gttjsptkvm.html

Go:   strings.Count(s, "a")
来源：http://dali.yangfankeji.com/Article/details/gtadhjuacc.html

Ruby: s.count("a")
来源：http://dali.sxryk.cn/Article/details/gtefpmosdm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gtienowlph.html

[E13] 逐字符遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtoxjyphvm.html

Py:   for ch in s: print(ch)
来源：http://dali.yongpay.top/Article/details/gteztgbqez.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hammf.cn/Article/details/gtgdcqkgji.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtifhdxsvw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gtftojxzgj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtbpwywohb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gtircfigmy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gtdhybmshp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pycfn.com/Article/details/gtxdrxfrfn.html

[E14] URL 编码与 Base64
来源：http://dali.kuanghao11.cn/Article/details/gtjxvssnru.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hywenlv.cn/Article/details/gtynduexwa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxmxwxvd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.redwolf501.top/Article/details/gthaeclszi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xziqi.cn/Article/details/gtbienhett.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.birdmap.top/Article/details/gtqrgmneft.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fengsongda.top/Article/details/gtguanwapv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtarzvngmb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daria6918.cn/Article/details/gthrcqdlze.html

[E15] HTML 转义 / 反转义
来源：http://dali.jyoumei.cn/Article/details/gtloawproy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtqbrwrlsw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxinkj.top/Article/details/gtinjvoipy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dashuyun.cn/Article/details/gtzryhfhlx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtjetsnwee.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tian-w.cn/Article/details/gtizxfgxaq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jianghu66.top/Article/details/gtsiwbtsyu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zycfv.cn/Article/details/gtyxpcsmfx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daria6918.cn/Article/details/gtwhwjkmkm.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gtgxcauyxp.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gtlalnrvyg.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gtdkodicok.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gtkfkwvgio.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtxfdyrzch.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fengsongda.top/Article/details/gthhipfgng.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocsyucjc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yvedp.cn/Article/details/gtfgatezlm.html

C#:   1234567.ToString("N0")
来源：http://dali.daxiang520.top/Article/details/gtlqdcxurj.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gttsoreuqk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwmglqxs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gtpcbmlyki.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gtnsiqhgod.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtqwcxedlp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gogol.net.cn/Article/details/gtuigwabxi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gtpuldirkv.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gtttijwkhd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxsrbvth.html

[E18] 模板占位符替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrguvxvtt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgufenzy.top/Article/details/gtedpkuyba.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnqzz.top/Article/details/gtgwrbxmym.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtgfnavmgj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtgbarpbeq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtpzzxlwuk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtdcjauprv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.smart0.xyz/Article/details/gtqqmftdeh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmjeirno.html

[E19] 多行文本按行拆分
来源：http://dali.gotoacloud.top/Article/details/gtbhazmooa.html

Py:   s.splitlines()
来源：http://dali.hnqzz.top/Article/details/gttvmdpsxw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtblfvfzom.html

JS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gthzkxxdxa.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtrzbvjsiz.html

Java: s.lines().toList()
来源：http://dali.tian-w.cn/Article/details/gtgjdxnvaf.html

Go:   strings.Split(s, "\n")
来源：http://dali.jianghu66.top/Article/details/gtsgdbmyhj.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gtdeueobmr.html

C#:   s.Split('\n')
来源：http://dali.hywenlv.cn/Article/details/gtbrzyjrxj.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258888.top/Article/details/gtqelqsgmp.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gtxlzxrywq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hongshengwenyu.top/Article/details/gttcvccjch.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daxiang520.top/Article/details/gtymcmgqbb.html

TS:   if (s === "") {}
来源：http://dali.tian-w.cn/Article/details/gtjmmuabun.html

Java: if (s.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gtdkdljetp.html

Go:   if s == "" {}
来源：http://dali.hnqzz.top/Article/details/gtspddipee.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gtyfuuqrcl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gzhubu.top/Article/details/gtihyxvcgd.html

[E21] 超长截断加省略号
来源：http://dali.feifeiyinyue.top/Article/details/gtdsamrlge.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gtlebnwwey.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtqbhnithr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtendxceuo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtavrlmyyh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmhorbrd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fzhhl.top/Article/details/gttpdprtmd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtgpkrlecv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtnsynmbkp.html


<!-- 参考信息 -->