代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.smart0.xyz/Article/details/gt2xtjxhjha.html

Ruby: arr.max;  arr.min
来源：http://dali.zhongyouzk.top/Article/details/gt2yrrqnozl.html

C#:   list.Max();  list.Min()
来源：http://dali.9152youxi.cn/Article/details/gt2fnrtntcs.html

[D18] 扁平化嵌套数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tepklrqt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.316326.xyz/Article/details/gt2eqjwwkgf.html

PHP:  array_merge(...$nested);
来源：http://dali.yongpay.top/Article/details/gt2lzzumxop.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yueranfly.top/Article/details/gt2cvwaotyf.html

TS:   nested.flat();
来源：http://dali.chenzaomai.com/Article/details/gt2yomourja.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cucudq.cn/Article/details/gt2gshxghdn.html

Go:   // 手写双层循环
来源：http://dali.chenzaomai.com/Article/details/gt2icqwkppz.html

Ruby: nested.flatten
来源：http://dali.c1oappe.top/Article/details/gt2bfkkwjdv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2aotidbln.html

[D19] 按字段分组
来源：http://dali.yj20258.top/Article/details/gt2uptjlrvb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ivvv.top/Article/details/gt2vvgiwvpn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbmncyhs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.c1oappe.top/Article/details/gt2axhygtuh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gt2eiwcsbvu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgufenzy.top/Article/details/gt2kltimqlq.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gt2muxbtvyx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.iojbl.cn/Article/details/gt2zobmavgv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohswvsnz.html

[D20] 统计每个元素出现次数
来源：http://dali.tanke756.top/Article/details/gt2fqnppmuz.html

Py:   Counter(arr)
来源：http://dali.yueranfly.top/Article/details/gt2mdppgkzb.html

PHP:  array_count_values($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2nonsehtr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gt2jkvhqhgk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gt2vwuigigy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxuanxn.top/Article/details/gt2ykehaklf.html

Go:   // 手写 map[T]int
来源：http://dali.jiagoushi.top/Article/details/gt2dkvowqpu.html

Ruby: arr.tally
来源：http://dali.dianchejie.cn/Article/details/gt2jcgigjyr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.0kj1m.cn/Article/details/gt2muezyjen.html

[D21] 判断是否包含某元素
来源：http://dali.ppjwa.cn/Article/details/gt2dvzzntgs.html

Py:   x in arr
来源：http://dali.havefunace.top/Article/details/gt2wooooocn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.meibo888.top/Article/details/gt2rdsmeeoc.html

JS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2owivmglo.html

TS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gt2qquhegxr.html

Java: list.contains(x)
来源：http://dali.yvedp.cn/Article/details/gt2zwbwopps.html

Go:   slices.Contains(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kpyxbpvs.html

Ruby: arr.include?(x)
来源：http://dali.redwolf501.top/Article/details/gt2fhseyixp.html

C#:   list.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cdzundlk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.redwolf501.top/Article/details/gt2asshrpce.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ivvv.top/Article/details/gt2cpdsvczc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yangfankeji.com/Article/details/gt2lcwazhbs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uwntixhz.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gt2tnuhixrl.html

Java: new ArrayList<>(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2bkyxobge.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gt2xpenxned.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258888.top/Article/details/gt2tfgqnsnu.html

C#:   new List<int>(list);
来源：http://dali.hywenlv.cn/Article/details/gt2uqycuayu.html

[D23] reduce 累积计算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rqkyyedq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gt2ulcsrehf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangdashe.top/Article/details/gt2jdhtxxfu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2xepppcrl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2gytqidon.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uyttbatm.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gt2iunofxyd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.meibo888.top/Article/details/gt2jlezxlpe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rfxlcdhi.html

[D24] 字典 / Map 基本操作
来源：http://dali.shuidangran.top/Article/details/gt2dxnozfvf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.haohaochexian.top/Article/details/gt2sqhoywae.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shuidangran.top/Article/details/gt2ubyvcyfa.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.meibo888.top/Article/details/gt2mbgfadnx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2xpborydp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zzhpvgek.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gzhubu.top/Article/details/gt2dbpayxkc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ydzc1.top/Article/details/gt2mueznffh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenlongwang.top/Article/details/gt2xcaybfwl.html

[D25] Set 集合去重与交并差
来源：http://dali.yueranfly.top/Article/details/gt2zbjshwrj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tianlin.xyz/Article/details/gt2fjfhdgld.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sufxvd.cn/Article/details/gt2gijtzjrg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sysykeji.top/Article/details/gt2blzwgoez.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.birdmap.top/Article/details/gt2lulutlvw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ypubazex.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.havefunace.top/Article/details/gt2istqpqsc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2igyexodz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tanke756.top/Article/details/gt2xdnhkali.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkyopbop.html

Py:   ", ".join(map(str, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2etfabmrf.html

PHP:  implode(", ", $arr);
来源：http://dali.yj202588.top/Article/details/gt2wcpljbob.html

JS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gt2sylqjtfe.html

TS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2qovesagy.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gt2ebnbrksj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kduqgasa.html

Ruby: arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2qtcsqxjr.html

C#:   string.Join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gt2rabapbyo.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ltgylyib.html

E. 字符串处理
来源：http://dali.ehwqpu.com/Article/details/gt2eotyplsh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2cmfqwcki.html

[E01] 拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gt2ilvuycxj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.redwolf501.top/Article/details/gt2ankbyjre.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2qiknxzmn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gt2lyhrndfk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gt2ujatzvwx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.bjfxy.top/Article/details/gt2okzokioz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sufxvd.cn/Article/details/gt2nwkdnzzf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhoulong.xyz/Article/details/gt2nknmczxw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2pggqibsc.html

[E02] 重复字符串
来源：http://dali.guannengcc.top/Article/details/gt2zjbhubgn.html

Py:   "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gt2yunmkjen.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vkihcmts.html

JS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gt2oygfxiba.html

TS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gt2kppgucsz.html

Java: "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2lmszbovp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hammf.cn/Article/details/gt2bqftafqo.html

Ruby: "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gt2cniwcrtq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxinkj.top/Article/details/gt2kvnpzqlf.html

[E03] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gt2ettdaujb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dashuyun.cn/Article/details/gt2ghrtudag.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gt2rnllmfgu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bopjrnig.html

TS:   s.slice(1, 4)
来源：http://dali.316326.xyz/Article/details/gt2sszffujc.html

Java: s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gt2kbcxmrzp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tianlin.xyz/Article/details/gt2ruopmopk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gt2ppzyygnq.html

C#:   s.Substring(1, 3)
来源：http://dali.yuanzhike.top/Article/details/gt2rbkjdfej.html

[E04] 查找子串位置
来源：http://dali.sufxvd.cn/Article/details/gt2iypfmwij.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2ljokminy.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigfzy.top/Article/details/gt2zxnqwdrw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.bjfxy.top/Article/details/gt2drouwkyn.html

TS:   s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gt2ivlzplcr.html

Java: s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gt2niwatczz.html

Go:   strings.Index(s, "x")
来源：http://dali.hnqzz.top/Article/details/gt2imnkjxjy.html

Ruby: s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gt2ipabwhzl.html

C#:   s.IndexOf("x")
来源：http://dali.hnqzz.top/Article/details/gt2whossmis.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.iojbl.cn/Article/details/gt2pdvpfwfp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jianghu66.top/Article/details/gt2sneuvdgs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnqzz.top/Article/details/gt2ducfptqn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gt2vptoyypo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tanke756.top/Article/details/gt2gnsxnoic.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gt2drpguuca.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gaohongyu789.top/Article/details/gt2wwkiexgp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2sayduoti.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yonumen.top/Article/details/gt2ibpldcjf.html

[E06] 替换子串
来源：http://dali.dianchejie.cn/Article/details/gt2tdanqsjs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2imvkvdor.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ydzc1.top/Article/details/gt2ycahvyjo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2mvespqiq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2gxcbdqnm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2ztproxdw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2ssvmkmnj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2gairsppg.html

C#:   s.Replace("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhohrihg.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gt2pqxudivz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.quarkkingdee.top/Article/details/gt2vpfctytz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2lejnbcfr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gt2jpmfwvyd.html

TS:   s.split(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2krcrcrtt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hysaishi.cn/Article/details/gt2souebgwy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sxryk.cn/Article/details/gt2zxuehlhb.html

Ruby: s.split(",");  s.split
来源：http://dali.vqdsnc.cn/Article/details/gt2ibscrfqj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gt2ilpwgysn.html

[E08] 数组按分隔符合并
来源：http://dali.gotoacloud.top/Article/details/gt2ejxadeep.html

Py:   ",".join(items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fabwmrss.html

PHP:  implode(",", $items);
来源：http://dali.yonumen.top/Article/details/gt2ciezfonz.html

JS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrtjnaie.html

TS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gt2gxwwwqtj.html

Java: String.join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnvcqenj.html

Go:   strings.Join(items, ",")
来源：http://dali.fengsongda.top/Article/details/gt2ayyiaomb.html

Ruby: items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qztgflyz.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gt2xdqwhnhe.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gt2pudmdtek.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2peyhgyse.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cucudq.cn/Article/details/gt2nysjdfbq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gt2opiasdkj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2slnfqkmj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xylfe.cn/Article/details/gt2mayovsit.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuxming.cn/Article/details/gt2mmqrwdam.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cucudq.cn/Article/details/gt2hickmgpe.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cheryme.top/Article/details/gt2aljyvlvr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.kuanghao11.cn/Article/details/gt2iicqqmhk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgpthohv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wvaylfaa.html

JS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2xtthnocx.html

TS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2lwzxigke.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2sixihywz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gt2ecboyfpb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gt2cnumyxcl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aibaodan.cn/Article/details/gt2vlqaqmwr.html

[E11] 反转字符串
来源：http://dali.cucudq.cn/Article/details/gt2jzcjyoef.html

Py:   s[::-1]
来源：http://dali.hammf.cn/Article/details/gt2yknjhfne.html

PHP:  strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2prpargfm.html

JS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2mwlchygf.html

TS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2oocqxdug.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cucudq.cn/Article/details/gt2wqnipwas.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuxming.cn/Article/details/gt2bxgjyczv.html

Ruby: s.reverse
来源：http://dali.shzxlz.cn/Article/details/gt2tbblwyto.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gt2wpglhlhe.html

[E12] 统计某字符出现次数
来源：http://dali.9152youxi.cn/Article/details/gt2nlygoaud.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mlkivloz.html

PHP:  substr_count($s, "a");
来源：http://dali.gaohongyu789.top/Article/details/gt2fbmulxjv.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gt2vuamrrqx.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gt2pypwcmfy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cashguo.top/Article/details/gt2iuerhnrz.html

Go:   strings.Count(s, "a")
来源：http://dali.pycfn.com/Article/details/gt2euotvzfr.html

Ruby: s.count("a")
来源：http://dali.iojbl.cn/Article/details/gt2uejdwbzt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aibaodan.cn/Article/details/gt2fexusrew.html

[E13] 逐字符遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2rpqteoea.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gt2ahbexlcz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gt2kogwifbf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2vkevvokc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2yojcddhy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2tzsyuenw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gt2gtjmlzeh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gt2pnaykqjl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2ezmnfjud.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gt2jlcetlaj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfozawid.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2jsuwaprw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpotwnih.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gt2uebbzxii.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gt2kaelilsw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuanzx.com/Article/details/gt2yxesmjhw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.haohaochexian.top/Article/details/gt2azotwweg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2ibiphvbk.html

[E15] HTML 转义 / 反转义
来源：http://dali.svipenyu.cn/Article/details/gt2ochzaekn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2ylburmiy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ppjwa.cn/Article/details/gt2sdphgwsq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2ibydktex.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ikixgkrz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.haohaochexian.top/Article/details/gt2bckjpkyu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guannengcc.top/Article/details/gt2xzuxrftg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.meibo888.top/Article/details/gt2tbtfcdpv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ivvv.top/Article/details/gt2huwgbjcv.html

[E16] 数字千分位
来源：http://dali.daxiang520.top/Article/details/gt2uxefkzwu.html

Py:   f"{1234567:,}"
来源：http://dali.zhongyouzk.top/Article/details/gt2cgvkdeot.html

PHP:  number_format(1234567);
来源：http://dali.c1oappe.top/Article/details/gt2jdvsdvkh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gt2hdyqlgoj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gt2ylyxcazu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gt2ohynpgfp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.mhx1999.top/Article/details/gt2tfqziemo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txezncob.html

C#:   1234567.ToString("N0")
来源：http://dali.zdqjudy.top/Article/details/gt2sycncgso.html

[E17] 首字母大写
来源：http://dali.pengpengdd.cyou/Article/details/gt2puflfhpr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gt2jqytulrc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lmsfucru.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gt2cdcvsqkq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gt2azrhfkid.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aizwys.cn/Article/details/gt2owycsmkx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cqqwz.cn/Article/details/gt2tdmfgrbo.html

Ruby: s.capitalize
来源：http://dali.wangshuangyany.cn/Article/details/gt2kxxrpmyp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.redwolf501.top/Article/details/gt2qenfcvsy.html

[E18] 模板占位符替换
来源：http://dali.fzhhl.top/Article/details/gt2fugrxqif.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gt2blxigqsv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.redwolf501.top/Article/details/gt2ymauxyds.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2cwdidhoh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gt2gjnqsbwz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2znrjglpr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2saluzaps.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gt2ejylmhnc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ydzc1.top/Article/details/gt2tobcoaps.html

[E19] 多行文本按行拆分
来源：http://dali.gaohongyu789.top/Article/details/gt2xvzbjymq.html

Py:   s.splitlines()
来源：http://dali.yongpay.top/Article/details/gt2ftqaivfk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2osdgbtsp.html

JS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gt2zioecqfu.html

TS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gt2prnbbcjm.html

Java: s.lines().toList()
来源：http://dali.yj20258888.top/Article/details/gt2vayjcbuz.html

Go:   strings.Split(s, "\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2caqrzffm.html

Ruby: s.lines
来源：http://dali.chenzaomai.com/Article/details/gt2kkmtnoai.html

C#:   s.Split('\n')
来源：http://dali.yj20258888.top/Article/details/gt2wdngnbww.html

[E20] 判断字符串是否为空
来源：http://dali.tanke756.top/Article/details/gt2pyelpsvd.html

Py:   if not s:
来源：http://dali.jinqigfzy.top/Article/details/gt2fpxlccsc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gt2vpgvczln.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xylfe.cn/Article/details/gt2tavtzcyi.html

TS:   if (s === "") {}
来源：http://dali.sysykeji.top/Article/details/gt2yolzlonj.html

Java: if (s.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gt2zbyuunvv.html

Go:   if s == "" {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2dezendqu.html

Ruby: if s.empty?
来源：http://dali.tianlin.xyz/Article/details/gt2rnbksvql.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gt2szvcmjzs.html

[E21] 超长截断加省略号
来源：http://dali.jyoumei.cn/Article/details/gt2hxxnbzho.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shuidangran.top/Article/details/gt2xnklkuiq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gt2kvdejqag.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gt2ivlwojgb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpogzpv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2kwmzrbtw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nwbrower.top/Article/details/gt2bxzrjstd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2bnmsgsvv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2ubihxnxs.html

[E22] 字节长度与字符长度
来源：http://dali.jqgufenzy.top/Article/details/gt2zpzumjfk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2ubkwribk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2hyzyqgxr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gt2euabjbqa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gt2wdosjbtr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gt2wykiohfs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gt2knhvrawc.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gt2acgdbjjf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gt2djlcozhy.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssrmzldg.html

F. 文件与目录
来源：http://dali.xinyue.icu/Article/details/gt2vodbfinb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2tssbybfi.html

[F01] 读取整个文件
来源：http://dali.aizwys.cn/Article/details/gt2hewcrecf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvoywpjt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2vduttoke.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gt2zdzrlylg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gt2xxhdzado.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2uftukcyk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnxiangtu.top/Article/details/gt2dqvlracg.html

Ruby: File.read("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2duzokcrs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2xyveaayq.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gt2ratnjqty.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daxiang520.top/Article/details/gt2iehsbasc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xsykwnlj.html


<!-- 参考信息 -->