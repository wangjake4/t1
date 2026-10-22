代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nwbrower.top/Article/details/gt2cfxyuqua.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2zkbifkbx.html

JS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gt2iydmgzbf.html

TS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gt2csfjkwza.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.andypj.xyz/Article/details/gt2fyhjxfph.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gt2bbvbqzsz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ylmyakhe.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2qcihrjlh.html

[D15] 去重
来源：http://dali.jqgfzy.top/Article/details/gt2pkdkqock.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gt2brlomcyj.html

PHP:  array_unique($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2larezeil.html

JS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gt2kchttjeh.html

TS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2uvhwlrhx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gt2jthsvwkx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jlsjyb.cn/Article/details/gt2lptsqaek.html

Ruby: arr.uniq
来源：http://dali.chenlongwang.top/Article/details/gt2wfilvlkb.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2qmssdqlp.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gt2thyarhod.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2jqinshoi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2qxrqoatc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2lokpgrzw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gt2xjwgnwfk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yanxiufei.cn/Article/details/gt2kxuhfojc.html

Go:   // 手写循环累加
来源：http://dali.xinyue.icu/Article/details/gt2akblvrio.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj202588.top/Article/details/gt2gttmymba.html

C#:   list.Sum();  list.Average()
来源：http://dali.iojbl.cn/Article/details/gt2cooeangr.html

[D17] 最大值与最小值
来源：http://dali.zhoulong.xyz/Article/details/gt2kfcggqgm.html

Py:   max(arr);  min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2najicanx.html

PHP:  max($arr);  min($arr);
来源：http://dali.iojbl.cn/Article/details/gt2fmliraol.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.svipenyu.cn/Article/details/gt2gxvzvqnf.html

TS:   Math.max(...arr);
来源：http://dali.gzhubu.top/Article/details/gt2scogfhnu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.meibo888.top/Article/details/gt2zdkeabpp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2ohplkqqr.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258.top/Article/details/gt2tidlmpbv.html

C#:   list.Max();  list.Min()
来源：http://dali.tanke756.top/Article/details/gt2vyrlwqjm.html

[D18] 扁平化嵌套数组
来源：http://dali.yanxiufei.cn/Article/details/gt2xlfoqaaa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zycfv.cn/Article/details/gt2opqbnsqp.html

PHP:  array_merge(...$nested);
来源：http://dali.havefunace.top/Article/details/gt2pfchzrlq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tian-w.cn/Article/details/gt2kyrxekks.html

TS:   nested.flat();
来源：http://dali.zhixingplan.top/Article/details/gt2owdxlsmb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ydzc1.top/Article/details/gt2nkpnlvdo.html

Go:   // 手写双层循环
来源：http://dali.zdqjudy.top/Article/details/gt2gkalltni.html

Ruby: nested.flatten
来源：http://dali.nwbrower.top/Article/details/gt2oprgopwk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2niatagqu.html

[D19] 按字段分组
来源：http://dali.aizwys.cn/Article/details/gt2ibnldpss.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gzhubu.top/Article/details/gt2zyyyusyw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.smart0.xyz/Article/details/gt2obpqatyn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gt2cgwdtpek.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cashguo.top/Article/details/gt2mrqoceqs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.quarkkingdee.top/Article/details/gt2oejaocrw.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangtech.top/Article/details/gt2igzgrgzy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cashguo.top/Article/details/gt2rfrzahqy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ptpfabjj.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoljwgk.html

Py:   Counter(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2hmujoykq.html

PHP:  array_count_values($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2kcqvffwv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gt2bsxnqvzr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gt2xcomyfog.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenlongwang.top/Article/details/gt2vichkfrn.html

Go:   // 手写 map[T]int
来源：http://dali.daxiang520.top/Article/details/gt2hbocecql.html

Ruby: arr.tally
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odwtpgpo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pycfn.com/Article/details/gt2xomzrkmi.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gt2pzrqxpxd.html

Py:   x in arr
来源：http://dali.yj20258.top/Article/details/gt2wnqlpexw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ybcxt.top/Article/details/gt2icururgm.html

JS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gt2vncdmfzg.html

TS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gt2guufndxd.html

Java: list.contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2uoigbisd.html

Go:   slices.Contains(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2yhuesafv.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gt2ozshjutn.html

C#:   list.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gt2lasblpqa.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhongyouzk.top/Article/details/gt2shndseok.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ydzc1.top/Article/details/gt2srrsfxwn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258888.top/Article/details/gt2nltfxasx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2blxumddb.html

TS:   [...arr];
来源：http://dali.aizwys.cn/Article/details/gt2eenbjezk.html

Java: new ArrayList<>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dyhxbtwz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhengqikj.top/Article/details/gt2gvmnytec.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zycfv.cn/Article/details/gt2svfxoqci.html

C#:   new List<int>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xowipsbq.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rtivmqlo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2gncpxrdu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2rtnibrvw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2lzofijen.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gt2rzphqopn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2exbtxfrx.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gt2lhnidalc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gt2vbftzlgs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ivvv.top/Article/details/gt2yrznccij.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gt2armonlhw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2eikfedxm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dvmaxsfp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xylfe.cn/Article/details/gt2euosnwsk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2kzzqhhxd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gt2tpwlchmt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qxaaykyb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.316326.xyz/Article/details/gt2hlfgpdgu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aejdreou.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gt2lorusdav.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gt2gwziutxt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjdgovqv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2frumidyy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnxiangtu.top/Article/details/gt2sjbxkgrw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tojvppop.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.quarkkingdee.top/Article/details/gt2meykocew.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gt2aqgjlgir.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gt2mqmibybx.html

[D26] 数组转字符串
来源：http://dali.ehwqpu.com/Article/details/gt2cfrlxjqt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2rcrlybsz.html

PHP:  implode(", ", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fvxkhxij.html

JS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cenjhwhf.html

TS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qcdzhuhk.html

Java: String.join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gt2npqyqtgo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.snrcjt.cn/Article/details/gt2nfefmgow.html

Ruby: arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gt2vqwjjbqg.html

C#:   string.Join(", ", list)
来源：http://dali.havefunace.top/Article/details/gt2nxdtmwef.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2yqwajihj.html

E. 字符串处理
来源：http://dali.fengsongda.top/Article/details/gt2lthjghth.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2smwgzebq.html

[E01] 拼接字符串
来源：http://dali.fzhhl.top/Article/details/gt2wdwndbyu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gotoacloud.top/Article/details/gt2xqltinpn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cjemycld.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gt2lhsswrjr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gt2wzgybswl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2plvubeyh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2jhehnqrm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gt2iobxpdqe.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2akabbalg.html

[E02] 重复字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aredhfea.html

Py:   "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gt2jfvwbkfe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gt2zppaqgql.html

JS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gt2pzyovqzb.html

TS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gt2ifsaxrbf.html

Java: "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gt2yvetwgmg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.andypj.xyz/Article/details/gt2cynqemhf.html

Ruby: "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gt2ixdlsnjm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yvedp.cn/Article/details/gt2bvaimiik.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gt2pmdzaejm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gt2vljasjwu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gt2ppzmhzls.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gt2ahztganf.html

TS:   s.slice(1, 4)
来源：http://dali.daria6918.cn/Article/details/gt2vokfmaul.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oxszjjao.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xinyue.icu/Article/details/gt2pcsfhrii.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.meibo888.top/Article/details/gt2oaemmkbk.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ycwwmmwd.html

[E04] 查找子串位置
来源：http://dali.gaohongyu789.top/Article/details/gt2pmydppkf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gt2rbjcpkzv.html

PHP:  strpos($s, "x");
来源：http://dali.cashguo.top/Article/details/gt2eghthovy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gt2xtovrsvt.html

TS:   s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdvqbmhh.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gt2qexvlhak.html

Go:   strings.Index(s, "x")
来源：http://dali.cqqwz.cn/Article/details/gt2cbzajctg.html

Ruby: s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gt2pqupiybf.html

C#:   s.IndexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gt2vstfyrab.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.mhx1999.top/Article/details/gt2hqpxezrf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.snrcjt.cn/Article/details/gt2utrcvwfr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gogol.net.cn/Article/details/gt2djxakyrt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gt2pgotwwvc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gt2kylksfjj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gt2sbmlcfpv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntghlelr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sxryk.cn/Article/details/gt2rpoobskx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2ylyeophr.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gt2gvnnkbyt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gt2mmkvwcnh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2hqtdmxxk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2vnkicfoh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fdwuetht.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2finjxdqq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gt2ttksezfq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2vklvspwj.html

C#:   s.Replace("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2kicftyta.html

[E07] 按分隔符拆分
来源：http://dali.daria6918.cn/Article/details/gt2xprnhety.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cucudq.cn/Article/details/gt2adnqpzxe.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2jlomouff.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cucudq.cn/Article/details/gt2ayfbtnci.html

TS:   s.split(",")
来源：http://dali.chenzaomai.com/Article/details/gt2ioqaqqcy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ppjwa.cn/Article/details/gt2mthicnle.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.bjfxy.top/Article/details/gt2cimyhzuo.html

Ruby: s.split(",");  s.split
来源：http://dali.gotoacloud.top/Article/details/gt2txkwcpyh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xziqi.cn/Article/details/gt2bpbrcpae.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gt2noxdbajf.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gt2ihjihsrz.html

PHP:  implode(",", $items);
来源：http://dali.shzxlz.cn/Article/details/gt2pnmudyzu.html

JS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gt2qmueomtm.html

TS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2xomywxfz.html

Java: String.join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gt2tacywgzd.html

Go:   strings.Join(items, ",")
来源：http://dali.316326.xyz/Article/details/gt2cnucynrd.html

Ruby: items.join(",")
来源：http://dali.iojbl.cn/Article/details/gt2pcwyhdkp.html

C#:   string.Join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kptqfscn.html

[E09] 去除所有空白字符
来源：http://dali.yonumen.top/Article/details/gt2lyrccder.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gt2vzazzzmk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nwbrower.top/Article/details/gt2nvusaiwf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gt2rmchlwzb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gt2mwfmfnwl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gt2vvcuoede.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cqqwz.cn/Article/details/gt2hikqjthw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gt2pzqbjank.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ivvv.top/Article/details/gt2padjzuuk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj202588.top/Article/details/gt2eeetjlvx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.c1oappe.top/Article/details/gt2bmnupwpi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gt2anlduyri.html

JS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gt2whzshzro.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2copzfccw.html

Java: String.format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2flkniwji.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gt2jlnwftgg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gt2lqwwgyza.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gt2ughwfrro.html

[E11] 反转字符串
来源：http://dali.0kj1m.cn/Article/details/gt2bnfrqmgv.html

Py:   s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gt2bhjmklod.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vngdqcpi.html

JS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2lstehrmx.html

TS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xhpxkexf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.iojbl.cn/Article/details/gt2pbhnjjym.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.mhx1999.top/Article/details/gt2hvgqhfsj.html

Ruby: s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2euayfgtf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gt2qaixmeaf.html

[E12] 统计某字符出现次数
来源：http://dali.ehwqpu.com/Article/details/gt2bytzzson.html

Py:   s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gt2pnuaktlg.html

PHP:  substr_count($s, "a");
来源：http://dali.hysaishi.cn/Article/details/gt2ayhutkvv.html

JS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2slgcmjra.html

TS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gt2uvvuvfws.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ppjwa.cn/Article/details/gt2bnjkmvtx.html

Go:   strings.Count(s, "a")
来源：http://dali.jianghu66.top/Article/details/gt2dkqiszfz.html

Ruby: s.count("a")
来源：http://dali.pycfn.com/Article/details/gt2lempnqgj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.9152youxi.cn/Article/details/gt2zbbkrlgr.html

[E13] 逐字符遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2upebjckj.html

Py:   for ch in s: print(ch)
来源：http://dali.yvedp.cn/Article/details/gt2mdpyksyh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fzhhl.top/Article/details/gt2opjlhufj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2dgkdujjk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oznabmas.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yonumen.top/Article/details/gt2idaokuds.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgfzy.top/Article/details/gt2oiplokjo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jyoumei.cn/Article/details/gt2owmatail.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxinkj.top/Article/details/gt2xxtezoky.html

[E14] URL 编码与 Base64
来源：http://dali.mhx1999.top/Article/details/gt2tyyuhknr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pycfn.com/Article/details/gt2vdudrehx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dvcwijir.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tianlin.xyz/Article/details/gt2ojpwxdfw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guannengcc.top/Article/details/gt2tngvfwqb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yangfankeji.com/Article/details/gt2xwiffjnk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gt2rporxynk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.mhx1999.top/Article/details/gt2iofxnsxk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ehwqpu.com/Article/details/gt2gcfbibaa.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj202588.top/Article/details/gt2lodeprpb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.andypj.xyz/Article/details/gt2tlwlkbsp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gt2emzswbfq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.9152youxi.cn/Article/details/gt2sacvounb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2jslxzhel.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhiwuduotai.top/Article/details/gt2tpvrcuwr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gt2qvuxqjdd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbvxaqgx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2ismnpzos.html

[E16] 数字千分位
来源：http://dali.redwolf501.top/Article/details/gt2ywrfjazh.html

Py:   f"{1234567:,}"
来源：http://dali.guowangkeji.top/Article/details/gt2xkiorwio.html

PHP:  number_format(1234567);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bsxatptx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gt2jqmebevw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gt2olwgqsxf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhengqikj.top/Article/details/gt2ugzrllro.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sweek.top/Article/details/gt2earamrcm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigfzy.top/Article/details/gt2kuwfshbj.html

C#:   1234567.ToString("N0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2npsahjmb.html

[E17] 首字母大写
来源：http://dali.jinqigfzy.top/Article/details/gt2bcekegqq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ybcxt.top/Article/details/gt2waknoojh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yangfankeji.com/Article/details/gt2uxlchxwr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gt2nruoaapm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gt2mqnrdzov.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2mupdyeif.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vsjxbyvi.html

Ruby: s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gt2yphbieqm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjfxxuid.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gt2fbhpgfex.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ybcxt.top/Article/details/gt2mwlhyovq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xinyue.icu/Article/details/gt2xrmvuygd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2qqlwbzli.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2pcyupaqv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2weyorgsg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2lmzrfkbp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2vgdaylic.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cashguo.top/Article/details/gt2ezfsqara.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gt2qmpszjnd.html

Py:   s.splitlines()
来源：http://dali.dashuyun.cn/Article/details/gt2vcpoalus.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2biihktoh.html

JS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gt2zxeakfyl.html

TS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gt2xruwigyf.html

Java: s.lines().toList()
来源：http://dali.sxryk.cn/Article/details/gt2vsbudnvh.html

Go:   strings.Split(s, "\n")
来源：http://dali.xinyue.icu/Article/details/gt2scmhkfzz.html

Ruby: s.lines
来源：http://dali.xinyue.icu/Article/details/gt2khrnmbxc.html

C#:   s.Split('\n')
来源：http://dali.tanke756.top/Article/details/gt2fhrognhq.html

[E20] 判断字符串是否为空
来源：http://dali.vqdsnc.cn/Article/details/gt2clzzcmue.html

Py:   if not s:
来源：http://dali.smart0.xyz/Article/details/gt2vbolmzsq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gt2ugynohzc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2qnlprpjo.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gt2bhhtfvhz.html

Java: if (s.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gt2dimfoqgd.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gt2ntkxyoqd.html

Ruby: if s.empty?
来源：http://dali.yj20258888.top/Article/details/gt2pfvewhno.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sxryk.cn/Article/details/gt2yvlvtavl.html

[E21] 超长截断加省略号
来源：http://dali.guowangkeji.top/Article/details/gt2vjvkkgxn.html


<!-- 参考信息 -->