代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sweek.top/Article/details/gt2uuqhrlap.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangshuangyany.cn/Article/details/gt2mlnmmsas.html

[D17] 最大值与最小值
来源：http://dali.cdnleiting.top/Article/details/gt2hjbjmoqk.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gt2jwtmpwwp.html

PHP:  max($arr);  min($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2usnqbakx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2araoknfh.html

TS:   Math.max(...arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2hdqyehmb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shuidangran.top/Article/details/gt2pafxshsu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zycfv.cn/Article/details/gt2pdcclixf.html

Ruby: arr.max;  arr.min
来源：http://dali.pengpengdd.cyou/Article/details/gt2oktkogmr.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gt2wxkqdkvl.html

[D18] 扁平化嵌套数组
来源：http://dali.xziqi.cn/Article/details/gt2rqvttmew.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cashguo.top/Article/details/gt2hcqzkmro.html

PHP:  array_merge(...$nested);
来源：http://dali.zdqjudy.top/Article/details/gt2cgdafere.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pgiosqrq.html

TS:   nested.flat();
来源：http://dali.tianlin.xyz/Article/details/gt2dvwcxlsi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cucudq.cn/Article/details/gt2admrvsfk.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gt2ikhqtjin.html

Ruby: nested.flatten
来源：http://dali.andypj.xyz/Article/details/gt2zvxgqtnx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gt2wmquesrg.html

[D19] 按字段分组
来源：http://dali.hammf.cn/Article/details/gt2kdozzryj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.9152youxi.cn/Article/details/gt2bvhejhfe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cqqwz.cn/Article/details/gt2geqncrbl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhixingplan.top/Article/details/gt2jczopxnn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gt2aordzjhg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258.top/Article/details/gt2fucalpsa.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xwjgppss.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fzhhl.top/Article/details/gt2kuviqcrs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ehwqpu.com/Article/details/gt2bswkztdq.html

[D20] 统计每个元素出现次数
来源：http://dali.cqqwz.cn/Article/details/gt2pyitnvee.html

Py:   Counter(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ecsgmqvk.html

PHP:  array_count_values($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2fmroqmre.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gt2lxjdchym.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gt2frigbfhs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ivvv.top/Article/details/gt2jrxbxsbf.html

Go:   // 手写 map[T]int
来源：http://dali.tian-w.cn/Article/details/gt2lufgrcxw.html

Ruby: arr.tally
来源：http://dali.hnqzz.top/Article/details/gt2izliiqwl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tian-w.cn/Article/details/gt2ssbzuthr.html

[D21] 判断是否包含某元素
来源：http://dali.hfpthk.cn/Article/details/gt2hewwcitu.html

Py:   x in arr
来源：http://dali.aibaodan.cn/Article/details/gt2ndcqzoog.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj202588.top/Article/details/gt2pnvorjiq.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gt2tfodorqg.html

TS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gt2goknkvtk.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2ddnekybu.html

Go:   slices.Contains(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2xpddhdqi.html

Ruby: arr.include?(x)
来源：http://dali.tanke756.top/Article/details/gt2nkbeattn.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfpxjtl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cashguo.top/Article/details/gt2gqlhgcos.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gddorjid.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhongyouzk.top/Article/details/gt2aduiljwo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.birdmap.top/Article/details/gt2zgvcvbas.html

TS:   [...arr];
来源：http://dali.kuanghao11.cn/Article/details/gt2chgrvdnj.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdwnanpy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tian-w.cn/Article/details/gt2zexyccjh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ydzc1.top/Article/details/gt2guvimpcu.html

C#:   new List<int>(list);
来源：http://dali.xinyue.icu/Article/details/gt2zoomasjz.html

[D23] reduce 累积计算
来源：http://dali.vqdsnc.cn/Article/details/gt2ugfmvfcp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vosdulpy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2dguvixgi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gt2ddykbotu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gt2zlynhiww.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xinyue.icu/Article/details/gt2qrnhobum.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gt2owgkujym.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gaohongyu789.top/Article/details/gt2nsywrqku.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gzhubu.top/Article/details/gt2stgrgane.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2dnsghwrs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.snrcjt.cn/Article/details/gt2npghxtbp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aizwys.cn/Article/details/gt2kjpfowkd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aizwys.cn/Article/details/gt2cozufbkd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shuidangran.top/Article/details/gt2wzhmxwex.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ehwqpu.com/Article/details/gt2rzcyncwt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.316326.xyz/Article/details/gt2efiwphzx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guannengcc.top/Article/details/gt2uyeoiuoa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sweek.top/Article/details/gt2ewjskvti.html

[D25] Set 集合去重与交并差
来源：http://dali.redwolf501.top/Article/details/gt2wpdtgveu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gt2pkiigahu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cashguo.top/Article/details/gt2yabpagvo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gogol.net.cn/Article/details/gt2xqbtlyfe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xziqi.cn/Article/details/gt2hfxlquhu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yongpay.top/Article/details/gt2ikorbxkm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.iojbl.cn/Article/details/gt2kjzfleyn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenzaomai.com/Article/details/gt2jiaavwow.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dhtknshr.html

[D26] 数组转字符串
来源：http://dali.wangdashe.top/Article/details/gt2njmwqxss.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gogol.net.cn/Article/details/gt2oqbvphmx.html

PHP:  implode(", ", $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2dyflcjvt.html

JS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2lslabpox.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gt2siqnuekl.html

Java: String.join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gt2uccabxfr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuxming.cn/Article/details/gt2qptshgql.html

Ruby: arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gt2gzwoiwxx.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2muurbazg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2wkgmditb.html

E. 字符串处理
来源：http://dali.sweek.top/Article/details/gt2rjuoienh.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2jzqtfkvw.html

[E01] 拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gt2hpnpslcg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yongpay.top/Article/details/gt2cifkdwfg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guannengcc.top/Article/details/gt2iludbooi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nneivtwn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gt2wkhqqbwz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.svipenyu.cn/Article/details/gt2nkeucrba.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sufxvd.cn/Article/details/gt2yarzfmlr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gt2qiebubpl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2aiqtedxc.html

[E02] 重复字符串
来源：http://dali.svipenyu.cn/Article/details/gt2qdjfxwhh.html

Py:   "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zmidknfy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuanzhike.top/Article/details/gt2cudiknvq.html

JS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gt2jgopwhbi.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2ehqlkwkz.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gt2unovpccu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gt2nbcamqbp.html

Ruby: "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gt2vpdfxvph.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shuidangran.top/Article/details/gt2ekmupxjv.html

[E03] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gt2kfjhtywa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guowangkeji.top/Article/details/gt2ucyyglgu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2qcllbjtp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gt2uctjqzsm.html

TS:   s.slice(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gt2zkjfdoag.html

Java: s.substring(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gt2tlwqoani.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.smart0.xyz/Article/details/gt2xesjbirw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gt2gkntnnwm.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2tqxaqdir.html

[E04] 查找子串位置
来源：http://dali.nwbrower.top/Article/details/gt2lmwwphuw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gt2yihutont.html

PHP:  strpos($s, "x");
来源：http://dali.svipenyu.cn/Article/details/gt2cxlvpqnr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pvqbwuhw.html

TS:   s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gt2tdjfbnfo.html

Java: s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gt2kiwtbzwk.html

Go:   strings.Index(s, "x")
来源：http://dali.jlsjyb.cn/Article/details/gt2ihidjvns.html

Ruby: s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gt2ubazrzqy.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gt2texqrcrs.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhixingplan.top/Article/details/gt2ooawaxci.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2dhrsjmvq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gotoacloud.top/Article/details/gt2nwuwpvuf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2vaiicwkq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2eepbjbpt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2wrpgctse.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.mhx1999.top/Article/details/gt2fgmahvip.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2srfbtbss.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.andypj.xyz/Article/details/gt2thhaliwo.html

[E06] 替换子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dfklvkix.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gt2zbfikhnv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2acysazfz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2xgjzfjia.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2eiiowgmh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2shhivusj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gt2vbwqlplo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2gbhugvxx.html

C#:   s.Replace("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zrtmvajv.html

[E07] 按分隔符拆分
来源：http://dali.snrcjt.cn/Article/details/gt2qzugjyeh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guannengcc.top/Article/details/gt2iwdoeczg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2polcbcdh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hfpthk.cn/Article/details/gt2sqhozufd.html

TS:   s.split(",")
来源：http://dali.ppjwa.cn/Article/details/gt2xnzzgout.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yueranfly.top/Article/details/gt2grcsgxml.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnzvmnzh.html

Ruby: s.split(",");  s.split
来源：http://dali.kuanghao11.cn/Article/details/gt2wwopubzv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guannengcc.top/Article/details/gt2dfzzjnhs.html

[E08] 数组按分隔符合并
来源：http://dali.sufxvd.cn/Article/details/gt2gtkvafla.html

Py:   ",".join(items)
来源：http://dali.gotoacloud.top/Article/details/gt2exutlsjf.html

PHP:  implode(",", $items);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dzjgulqv.html

JS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gt2hzpfdyuj.html

TS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2bybkhtom.html

Java: String.join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gt2ojlvkqrw.html

Go:   strings.Join(items, ",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmrlbidq.html

Ruby: items.join(",")
来源：http://dali.yongpay.top/Article/details/gt2jvwyubnx.html

C#:   string.Join(",", items)
来源：http://dali.guannengcc.top/Article/details/gt2jeywcdcc.html

[E09] 去除所有空白字符
来源：http://dali.tianlin.xyz/Article/details/gt2vacnqgxy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shuidangran.top/Article/details/gt2zpbbrxzn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2lmodeyvz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gt2jfyusnbw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lulgyuen.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gt2afroqmly.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xinyue.icu/Article/details/gt2wykqwnzq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wlnsvpam.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gt2myrecywt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pazixgbb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daxiang520.top/Article/details/gt2nedkeigh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cdnleiting.top/Article/details/gt2frsfcojc.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nautghkf.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2ukbxsbhd.html

Java: String.format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2wncnzpld.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2vkkzyodo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gt2kfmffwrf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuanzx.com/Article/details/gt2yglnwnbi.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gt2knzapmjb.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gt2auehjzau.html

PHP:  strrev($s);
来源：http://dali.ybcxt.top/Article/details/gt2jkspxnvu.html

JS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2sacotdgd.html

TS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gt2xbhaqtvf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2qtuflkzf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gt2yobjbiko.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gt2dhvtykun.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gt2tatyxeyq.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gt2olrdiwqe.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gt2uuxwgfmv.html

PHP:  substr_count($s, "a");
来源：http://dali.shzxlz.cn/Article/details/gt2vjzcqaxx.html

JS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gt2dipyzzvq.html

TS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gt2mwnjrrqe.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nwbrower.top/Article/details/gt2nekbbnfa.html

Go:   strings.Count(s, "a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jbzaruyo.html

Ruby: s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwxncejy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.feifeiyinyue.top/Article/details/gt2kglnmclp.html

[E13] 逐字符遍历
来源：http://dali.haohaochexian.top/Article/details/gt2tgyjlnli.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gt2mgmruyyo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gt2xkqwxyim.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2krgvqxnk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gt2ygpnpjaj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wumksitc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.bjfxy.top/Article/details/gt2borauyvf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigufen.top/Article/details/gt2fsnfxmel.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ybcxt.top/Article/details/gt2hxejqktv.html

[E14] URL 编码与 Base64
来源：http://dali.chenjidiqi.icu/Article/details/gt2dbnwwplk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2fflavgvi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhixingplan.top/Article/details/gt2tgriuvec.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cucudq.cn/Article/details/gt2xybpizcf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuxming.cn/Article/details/gt2arlorzse.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daxiang520.top/Article/details/gt2seijwacy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aizwys.cn/Article/details/gt2roqnuvpw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.mhx1999.top/Article/details/gt2nhzbxklp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gt2rraqprrk.html

[E15] HTML 转义 / 反转义
来源：http://dali.cheryme.top/Article/details/gt2fjadsuhn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhixingplan.top/Article/details/gt2wutokutk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.0kj1m.cn/Article/details/gt2hvprhzpz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gotoacloud.top/Article/details/gt2cdqmnivi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nwbrower.top/Article/details/gt2wyvchftr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.andypj.xyz/Article/details/gt2qhwknias.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenzaomai.com/Article/details/gt2qacfkcdi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2tujlzggr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gt2wjgleyrj.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hmebjovb.html

Py:   f"{1234567:,}"
来源：http://dali.guannengcc.top/Article/details/gt2kdydoysy.html

PHP:  number_format(1234567);
来源：http://dali.tian-w.cn/Article/details/gt2xfqzgnzl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gt2sdqhidmk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gt2ecwjqace.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.havefunace.top/Article/details/gt2aahdmyrg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daria6918.cn/Article/details/gt2ddpulegx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hfpthk.cn/Article/details/gt2xtdaaxru.html

C#:   1234567.ToString("N0")
来源：http://dali.gaohongyu789.top/Article/details/gt2wqnybnpf.html

[E17] 首字母大写
来源：http://dali.birdmap.top/Article/details/gt2pgwwiogh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gt2ugicrdxu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnqzz.top/Article/details/gt2cbrrrtpu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wrpacrik.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gt2qshnkgik.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gt2bwknqdao.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlcnyztc.html

Ruby: s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gt2mkmohwdx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.haohaochexian.top/Article/details/gt2zkchgvgh.html

[E18] 模板占位符替换
来源：http://dali.tanke756.top/Article/details/gt2bececclg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yongpay.top/Article/details/gt2irxodopf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gt2jsvvxzpq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2ibicmbmb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2jvyfobon.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2drdgtele.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2oeoetvim.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gt2aqakcrku.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gt2xzpggrdp.html

[E19] 多行文本按行拆分
来源：http://dali.tian-w.cn/Article/details/gt2opcvlbdh.html

Py:   s.splitlines()
来源：http://dali.hysaishi.cn/Article/details/gt2ydyzkpfe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2iuqbqukm.html

JS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gt2jpeywlgc.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gt2qwzpwzti.html

Java: s.lines().toList()
来源：http://dali.jqgfzy.top/Article/details/gt2kivfqxtl.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xlobvqvx.html

Ruby: s.lines
来源：http://dali.smart0.xyz/Article/details/gt2wphwxaja.html

C#:   s.Split('\n')
来源：http://dali.0kj1m.cn/Article/details/gt2ewhayqsh.html

[E20] 判断字符串是否为空
来源：http://dali.guowangkeji.top/Article/details/gt2lalrdugt.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gt2xuindefg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ehwqpu.com/Article/details/gt2bcfkbuqh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iwvbhynj.html

TS:   if (s === "") {}
来源：http://dali.sweek.top/Article/details/gt2jidifcme.html

Java: if (s.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gt2tjnwocxj.html

Go:   if s == "" {}
来源：http://dali.gotoacloud.top/Article/details/gt2ptlhopai.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqhgyigu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fengsongda.top/Article/details/gt2ytrmhosb.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gt2vbfkxqwl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kbpcghni.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2vgzjbkwn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2eedrajzc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2vmxbybwm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2bxsclppo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gt2qtmuelwy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zkzdhvne.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gt2qslbtvxf.html

[E22] 字节长度与字符长度
来源：http://dali.haohaochexian.top/Article/details/gt2tqocdlfa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mymisiza.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gt2gpjetyzq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2mgdrphef.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gt2kueqzign.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jiagoushi.top/Article/details/gt2pmxmhqye.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ydzc1.top/Article/details/gt2lmjcsvig.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gt2zdwuqkag.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gt2ebqwfapk.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2cvofpjbj.html

F. 文件与目录
来源：http://dali.pengpengdd.cyou/Article/details/gt2uambgjko.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2cofkfkww.html

[F01] 读取整个文件
来源：http://dali.xuanzx.com/Article/details/gt2zjyjwkhc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yvedp.cn/Article/details/gt2jejfqkxp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2qfpyftta.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gzhubu.top/Article/details/gt2rlxuguze.html


<!-- 参考信息 -->