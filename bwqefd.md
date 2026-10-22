代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2mxmymvgr.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxuanxn.top/Article/details/gt2vyondhgx.html

C#:   list.Max();  list.Min()
来源：http://dali.cdnleiting.top/Article/details/gt2fhpabgmi.html

[D18] 扁平化嵌套数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwihichy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pengpengdd.cyou/Article/details/gt2hbyghzub.html

PHP:  array_merge(...$nested);
来源：http://dali.0kj1m.cn/Article/details/gt2lhitempf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guowangkeji.top/Article/details/gt2khkeeffm.html

TS:   nested.flat();
来源：http://dali.feifeiyinyue.top/Article/details/gt2vvovwyvx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tianlin.xyz/Article/details/gt2owfojuov.html

Go:   // 手写双层循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbhgkemc.html

Ruby: nested.flatten
来源：http://dali.aibaodan.cn/Article/details/gt2ykfntmor.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2mfiwekbz.html

[D19] 按字段分组
来源：http://dali.jinqigufen.top/Article/details/gt2htnhgxtt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.redwolf501.top/Article/details/gt2snqkgvoz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.havefunace.top/Article/details/gt2bahfshac.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.c1oappe.top/Article/details/gt2qlsbtynk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gt2owxabnjo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gt2lfsddzjt.html

Go:   // 手写 map[string][]T
来源：http://dali.svipenyu.cn/Article/details/gt2eymogwbp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydpupfay.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxinkj.top/Article/details/gt2pkhcwdwm.html

[D20] 统计每个元素出现次数
来源：http://dali.jiagoushi.top/Article/details/gt2wnvphotu.html

Py:   Counter(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2dersptxr.html

PHP:  array_count_values($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ulfbdcgn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gt2dsfqogfq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gt2itdvdwwt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kpktuwqn.html

Go:   // 手写 map[T]int
来源：http://dali.meibo888.top/Article/details/gt2rezlqfvt.html

Ruby: arr.tally
来源：http://dali.quarkkingdee.top/Article/details/gt2igyyoctd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.smart0.xyz/Article/details/gt2ehxmxnmu.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gt2nitzhfmq.html

Py:   x in arr
来源：http://dali.bjfxy.top/Article/details/gt2nzendyyi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hammf.cn/Article/details/gt2tqcvgzvf.html

JS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gt2mwhgyoka.html

TS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gt2lnmvehdr.html

Java: list.contains(x)
来源：http://dali.yj20258888.top/Article/details/gt2dgqucscp.html

Go:   slices.Contains(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2wkxizewp.html

Ruby: arr.include?(x)
来源：http://dali.yj20258888.top/Article/details/gt2zfxqqzqp.html

C#:   list.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2enphgtiv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sufxvd.cn/Article/details/gt2dnsimtfi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2lualqbsh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guannengcc.top/Article/details/gt2wkzpluze.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cucudq.cn/Article/details/gt2corfmidf.html

TS:   [...arr];
来源：http://dali.xinyue.icu/Article/details/gt2jwjwfefr.html

Java: new ArrayList<>(list);
来源：http://dali.ppjwa.cn/Article/details/gt2hlgzrsem.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenzaomai.com/Article/details/gt2szqnhndd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hammf.cn/Article/details/gt2knmxsseb.html

C#:   new List<int>(list);
来源：http://dali.hfpthk.cn/Article/details/gt2hfphgzio.html

[D23] reduce 累积计算
来源：http://dali.yueranfly.top/Article/details/gt2mqwtwtkn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2kxfgksft.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2mplunkkl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2vwcwwppo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gt2fulfzlmh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daxiang520.top/Article/details/gt2qjnfhxre.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gt2ugttofpt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yongpay.top/Article/details/gt2xijrpujv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jlsjyb.cn/Article/details/gt2qwgfbxrj.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenlongwang.top/Article/details/gt2gqjcupax.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ydgxaqxk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gt2ddexloof.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2htaphxiv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2tueldxwl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ydzc1.top/Article/details/gt2qfcdxtux.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yangfankeji.com/Article/details/gt2pujpsmhf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sysykeji.top/Article/details/gt2elcudkiw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigufen.top/Article/details/gt2gyfapnys.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gt2parqnaek.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnqzz.top/Article/details/gt2pheljhfs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gt2rsjchsqe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ivvv.top/Article/details/gt2cvtkchpn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gt2fyncozwo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2bbydgtnf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gt2qycsoqhh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xylfe.cn/Article/details/gt2ffrrjiuf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xylfe.cn/Article/details/gt2arcpblsq.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2adezkmca.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dianchejie.cn/Article/details/gt2yxmihueb.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sblgysxm.html

JS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bggwmddu.html

TS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gt2cqokvald.html

Java: String.join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gt2bulsobbp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ehwqpu.com/Article/details/gt2qsnzgyls.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gt2tywakeya.html

C#:   string.Join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gt2utlxgyvd.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2hdhvppoe.html

E. 字符串处理
来源：http://dali.chenlongwang.top/Article/details/gt2laordhol.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2lxcfvfup.html

[E01] 拼接字符串
来源：http://dali.yuxming.cn/Article/details/gt2ycfwdhda.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cheryme.top/Article/details/gt2niljhejm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ybcxt.top/Article/details/gt2gdfcvsmd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2igrzmcvm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2qewaxolt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdhdwdda.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hysaishi.cn/Article/details/gt2spbwvsdr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbvtkezo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2aaiavcau.html

[E02] 重复字符串
来源：http://dali.nanxinkj.top/Article/details/gt2zbynibca.html

Py:   "ab" * 3
来源：http://dali.yj20258.top/Article/details/gt2gwicjsbl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.316326.xyz/Article/details/gt2uzalvklz.html

JS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gt2foadeuqd.html

TS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2kwmnjeah.html

Java: "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2frjnpshw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ivvv.top/Article/details/gt2xmttefko.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofktzona.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnqzz.top/Article/details/gt2pzqbycrr.html

[E03] 截取子串
来源：http://dali.ivvv.top/Article/details/gt2sqkbfrdc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gt2akwjpqmj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2vpwqcpvm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gt2ljbefjvq.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gt2rwkiftdw.html

Java: s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2siocirgt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258.top/Article/details/gt2ftiqnyiz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2chiionea.html

C#:   s.Substring(1, 3)
来源：http://dali.aibaodan.cn/Article/details/gt2vqpkonjx.html

[E04] 查找子串位置
来源：http://dali.yueranfly.top/Article/details/gt2zxsuxnoa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gt2wlqcveuh.html

PHP:  strpos($s, "x");
来源：http://dali.iojbl.cn/Article/details/gt2ggwmtzxu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nwbrower.top/Article/details/gt2qkdeaenk.html

TS:   s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gt2llyolcsl.html

Java: s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gt2xjpldbbg.html

Go:   strings.Index(s, "x")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kypylvas.html

Ruby: s.index("x")
来源：http://dali.yj202588.top/Article/details/gt2qaurjajn.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gt2wacjkiby.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dianchejie.cn/Article/details/gt2uvvtcfes.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yongpay.top/Article/details/gt2vpwunznx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangdashe.top/Article/details/gt2lccssoxl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2wbiodnyb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gzhubu.top/Article/details/gt2qarobzxw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gt2ownbtgff.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.smart0.xyz/Article/details/gt2jzmfojdp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gt2lbhiahzv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shuidangran.top/Article/details/gt2kpvbtmox.html

[E06] 替换子串
来源：http://dali.ydzc1.top/Article/details/gt2ijmommfv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gt2pwjhorhm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zjgachzl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sffetebc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2osxywwmx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2kvfwivko.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gt2kdfmzwic.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2szijtxck.html

C#:   s.Replace("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2idwtbzjx.html

[E07] 按分隔符拆分
来源：http://dali.xinyue.icu/Article/details/gt2rbdysgxt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangdashe.top/Article/details/gt2yzmzhfei.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2kvotebbz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.0kj1m.cn/Article/details/gt2nvfebvlr.html

TS:   s.split(",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejkeqyho.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuanzx.com/Article/details/gt2ffmgroxo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.haohaochexian.top/Article/details/gt2plmiaqhc.html

Ruby: s.split(",");  s.split
来源：http://dali.redwolf501.top/Article/details/gt2qnhgzixz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guannengcc.top/Article/details/gt2bgyvwghf.html

[E08] 数组按分隔符合并
来源：http://dali.smart0.xyz/Article/details/gt2eprxbgye.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gt2miohglno.html

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gt2uukcteqo.html

JS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2gkuoiput.html

TS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gt2kdovncrc.html

Java: String.join(",", items)
来源：http://dali.sxryk.cn/Article/details/gt2qkwveoip.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2upmxtfhe.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2jsecuqon.html

C#:   string.Join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gt2qywnuidb.html

[E09] 去除所有空白字符
来源：http://dali.ehwqpu.com/Article/details/gt2ogtszqwb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hysaishi.cn/Article/details/gt2qdirrmlz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangdashe.top/Article/details/gt2rhmtywrb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gt2dkkmgwhx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gt2jmyyveop.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gt2prxgropf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cucudq.cn/Article/details/gt2aswvuopn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.bjfxy.top/Article/details/gt2aqznidpo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gt2thygpwks.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jlsjyb.cn/Article/details/gt2qyhwyqje.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2klkyouts.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gt2nvjltuxk.html

JS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2riaqaofc.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2hyinftej.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2udhluaab.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gt2zccmvqwq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gt2hvaaqzeg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gt2imebrilm.html

[E11] 反转字符串
来源：http://dali.yj20258888.top/Article/details/gt2dnsqwein.html

Py:   s[::-1]
来源：http://dali.xziqi.cn/Article/details/gt2hhzntfiq.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsngxkin.html

JS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2vjyhscah.html

TS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gt2ivkiogeq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxxbfnan.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2npehtzey.html

Ruby: s.reverse
来源：http://dali.zhixingplan.top/Article/details/gt2zhrwxnol.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gt2bnvcyxlo.html

[E12] 统计某字符出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gt2thlpwyed.html

Py:   s.count("a")
来源：http://dali.cucudq.cn/Article/details/gt2tbjshhfb.html

PHP:  substr_count($s, "a");
来源：http://dali.mhx1999.top/Article/details/gt2lbnmgetv.html

JS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gt2zngdvemw.html

TS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gt2qeomtvcz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gaohongyu789.top/Article/details/gt2ebjodmfh.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxinkj.top/Article/details/gt2kzwyfmxc.html

Ruby: s.count("a")
来源：http://dali.meibo888.top/Article/details/gt2nkacrwbz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guannengcc.top/Article/details/gt2umsbqxti.html

[E13] 逐字符遍历
来源：http://dali.andypj.xyz/Article/details/gt2ejrorebn.html

Py:   for ch in s: print(ch)
来源：http://dali.zhengqikj.top/Article/details/gt2eozcjcdn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gt2ccizwpwa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2nnzaaibf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2qskpbeyn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gt2gztjxdqt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.havefunace.top/Article/details/gt2xcfkrwkx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ebbjkoae.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2oggozltu.html

[E14] URL 编码与 Base64
来源：http://dali.yvedp.cn/Article/details/gt2glslfzlp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sxryk.cn/Article/details/gt2yaamqayp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxzcpehs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuanzhike.top/Article/details/gt2bynqtmii.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.haohaochexian.top/Article/details/gt2aqqqjojt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhengqikj.top/Article/details/gt2alipoxtu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jyoumei.cn/Article/details/gt2azvqtzgq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ivvv.top/Article/details/gt2yurhgrlc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yonumen.top/Article/details/gt2ovgyyraq.html

[E15] HTML 转义 / 反转义
来源：http://dali.svipenyu.cn/Article/details/gt2ajvftvpu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gzhubu.top/Article/details/gt2cfjlmwue.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.andypj.xyz/Article/details/gt2xdnpdxrh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2npvonpja.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.meibo888.top/Article/details/gt2ntjhmymi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.svipenyu.cn/Article/details/gt2nxalspxn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fengsongda.top/Article/details/gt2akjqhcqs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wzxwtzma.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gt2mbuxbecz.html

[E16] 数字千分位
来源：http://dali.cdnleiting.top/Article/details/gt2jpinchya.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigfzy.top/Article/details/gt2hrzvzkir.html

PHP:  number_format(1234567);
来源：http://dali.yonumen.top/Article/details/gt2zslpuemh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gt2mcvgttdl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gt2nqxxxryp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gt2sjgwtxqo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ybcxt.top/Article/details/gt2nogsdiro.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hysaishi.cn/Article/details/gt2zexqfaxw.html

C#:   1234567.ToString("N0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmqwevzd.html

[E17] 首字母大写
来源：http://dali.jianghu66.top/Article/details/gt2akdmwygl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gt2oqsaoquq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.mhx1999.top/Article/details/gt2fetstswu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2bpacwtfq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gt2vppcvgbh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gt2cddlpqit.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj202588.top/Article/details/gt2pswgtfjz.html

Ruby: s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gt2geillhia.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.svipenyu.cn/Article/details/gt2rwgpwfns.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gt2envmmemw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yonumen.top/Article/details/gt2gksqioef.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gt2cuapwsog.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gt2ckhutgms.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gt2rafwzpnq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2obeqvydn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2arankiab.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ehwqpu.com/Article/details/gt2tnzeokzb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dcvtfedt.html

[E19] 多行文本按行拆分
来源：http://dali.wangshuangyany.cn/Article/details/gt2gzjcoznc.html

Py:   s.splitlines()
来源：http://dali.sxryk.cn/Article/details/gt2owwbxnsn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2fvvlcmsc.html

JS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gt2qyfgbaxs.html

TS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gt2mbysqdgh.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrsqnls.html

Go:   strings.Split(s, "\n")
来源：http://dali.gzhubu.top/Article/details/gt2sizwcgww.html

Ruby: s.lines
来源：http://dali.nwbrower.top/Article/details/gt2osnibxjt.html

C#:   s.Split('\n')
来源：http://dali.smart0.xyz/Article/details/gt2diiqxjgq.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gt2tjqxbuce.html

Py:   if not s:
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwvcaqdh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fzhhl.top/Article/details/gt2jtykuvdi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gt2rknevugl.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gt2pxettlqi.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2jpicscte.html

Go:   if s == "" {}
来源：http://dali.cqqwz.cn/Article/details/gt2kyuubggj.html

Ruby: if s.empty?
来源：http://dali.mhx1999.top/Article/details/gt2xvkgivua.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bldbrsmc.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gt2tnkposaj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xylfe.cn/Article/details/gt2nnzqfkim.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yongpay.top/Article/details/gt2qaucazrf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2ghsmlhca.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2yrfmwsjn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gt2qehnggla.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zycfv.cn/Article/details/gt2qdejsjmf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2ruevmqjf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2eaubpobo.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2czxywfzr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ivvv.top/Article/details/gt2tlzzbmue.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2yifhbies.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gt2jqcmnjqx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gt2bvhdfqem.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cucudq.cn/Article/details/gt2ytcwnfrv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sysykeji.top/Article/details/gt2gkubzmlc.html

Ruby: s.bytesize;  s.length
来源：http://dali.ivvv.top/Article/details/gt2rxydeccn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gt2aamcdydh.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2wodnfotf.html

F. 文件与目录
来源：http://dali.cheryme.top/Article/details/gt2qsrsoxkk.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjxwxttj.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gt2xchecrfa.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sysykeji.top/Article/details/gt2wvibvqqs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2zbjsbywr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sweek.top/Article/details/gt2ilcnqwpe.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gt2axuzzsqj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gt2czlsdtny.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gt2mlxciloj.html

Ruby: File.read("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2uqoirldg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2zlgetvpe.html

[F02] 逐行读取文件
来源：http://dali.zhongyouzk.top/Article/details/gt2munjksgv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2dsenvzwv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yueranfly.top/Article/details/gt2qnxqgucj.html


<!-- 参考信息 -->