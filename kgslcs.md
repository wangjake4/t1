代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2igvgtkru.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2eycogroy.html

TS:   Math.max(...arr);
来源：http://dali.svipenyu.cn/Article/details/gt2okccdxfv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hywenlv.cn/Article/details/gt2nsqnrkbf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2ednubheu.html

Ruby: arr.max;  arr.min
来源：http://dali.yangfankeji.com/Article/details/gt2gfosxcaa.html

C#:   list.Max();  list.Min()
来源：http://dali.birdmap.top/Article/details/gt2pvywvjow.html

[D18] 扁平化嵌套数组
来源：http://dali.nwbrower.top/Article/details/gt2mlhcadvq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gt2jpkxfmco.html

PHP:  array_merge(...$nested);
来源：http://dali.quarkkingdee.top/Article/details/gt2lenccckr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.birdmap.top/Article/details/gt2asxbqsby.html

TS:   nested.flat();
来源：http://dali.zhoulong.xyz/Article/details/gt2babpfxxy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yongpay.top/Article/details/gt2zfcqzefy.html

Go:   // 手写双层循环
来源：http://dali.jinqigfzy.top/Article/details/gt2rsvlvddl.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gt2clfocawk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2gudhubpz.html

[D19] 按字段分组
来源：http://dali.redwolf501.top/Article/details/gt2ugllnahc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jyoumei.cn/Article/details/gt2qfbdgpcp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cqqwz.cn/Article/details/gt2eupzfnmx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.vqdsnc.cn/Article/details/gt2rozvznxa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gt2llyahhjk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cucudq.cn/Article/details/gt2xdjqsckk.html

Go:   // 手写 map[string][]T
来源：http://dali.shzxlz.cn/Article/details/gt2cxzmuigc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258.top/Article/details/gt2xvdxaczq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwozvnlv.html

[D20] 统计每个元素出现次数
来源：http://dali.tanke756.top/Article/details/gt2jbxjrlyr.html

Py:   Counter(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2ecleluls.html

PHP:  array_count_values($arr);
来源：http://dali.meibo888.top/Article/details/gt2bxpuzzfb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iytazgjk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gt2mclnqrpi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.smart0.xyz/Article/details/gt2lnnmlglp.html

Go:   // 手写 map[T]int
来源：http://dali.hongshengwenyu.top/Article/details/gt2rjjhzbvy.html

Ruby: arr.tally
来源：http://dali.yj20258888.top/Article/details/gt2cikolxrr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gt2wbtvgvrp.html

[D21] 判断是否包含某元素
来源：http://dali.nanxuanxn.top/Article/details/gt2emuxrzjx.html

Py:   x in arr
来源：http://dali.0kj1m.cn/Article/details/gt2nigncbke.html

PHP:  in_array($x, $arr, true);
来源：http://dali.birdmap.top/Article/details/gt2uixfwchw.html

JS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2cxzplajf.html

TS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gt2lmjgpbly.html

Java: list.contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2nxyetxcp.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2dmpzrxdm.html

Ruby: arr.include?(x)
来源：http://dali.jqgfzy.top/Article/details/gt2unvblarx.html

C#:   list.Contains(x)
来源：http://dali.havefunace.top/Article/details/gt2eokjayjn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gt2esgkoqtr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.birdmap.top/Article/details/gt2tdmchthl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.kuanghao11.cn/Article/details/gt2igbkcawd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2sqqlrgtj.html

TS:   [...arr];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khmtvdnk.html

Java: new ArrayList<>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ahbgdsfu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgufenzy.top/Article/details/gt2aufmfcae.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yonumen.top/Article/details/gt2dpdbfxwz.html

C#:   new List<int>(list);
来源：http://dali.haohaochexian.top/Article/details/gt2vqgpapus.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wbyhjwcy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zxvsolfu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.smart0.xyz/Article/details/gt2tjtlrkza.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2cmrmiehd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gt2hwshhekg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gzhubu.top/Article/details/gt2mpsjxvnj.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gt2djvvdfsh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.snrcjt.cn/Article/details/gt2humhwzcq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gt2qatiatmh.html

[D24] 字典 / Map 基本操作
来源：http://dali.cashguo.top/Article/details/gt2abovmlqu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhixingplan.top/Article/details/gt2wlrbngbd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.havefunace.top/Article/details/gt2aqivbiql.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.0kj1m.cn/Article/details/gt2jednncsx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2mnnrsuvf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pycfn.com/Article/details/gt2yexxqcxh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hammf.cn/Article/details/gt2pqpadlzh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gt2anzmkpfz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fzhhl.top/Article/details/gt2mgwodqxz.html

[D25] Set 集合去重与交并差
来源：http://dali.yonumen.top/Article/details/gt2wninjdsu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangshuangyany.cn/Article/details/gt2xijhrbsg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guowangkeji.top/Article/details/gt2xkjddffe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aipainjb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgfzy.top/Article/details/gt2xeutedrk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.316326.xyz/Article/details/gt2lvdifxfd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sufxvd.cn/Article/details/gt2evhgkjmj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sufxvd.cn/Article/details/gt2mvudanqj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sysykeji.top/Article/details/gt2zaoyrqof.html

[D26] 数组转字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2ldhhitdx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shuidangran.top/Article/details/gt2dfvwjqri.html

PHP:  implode(", ", $arr);
来源：http://dali.snrcjt.cn/Article/details/gt2anobqbxx.html

JS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gt2lffzlqka.html

TS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gt2qrcmouer.html

Java: String.join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gt2chqosxkv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ydzc1.top/Article/details/gt2kzrunwmb.html

Ruby: arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gt2ojdpohey.html

C#:   string.Join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gt2uzuxstcl.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2afnjkmry.html

E. 字符串处理
来源：http://dali.yj20258888.top/Article/details/gt2pnkuylrh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2aujsgkhl.html

[E01] 拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2jscnvtgh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daxiang520.top/Article/details/gt2tovrrpvg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2igxwesoe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gt2ermmmmtp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jyoumei.cn/Article/details/gt2tembwulh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxinkj.top/Article/details/gt2bihntthw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.iojbl.cn/Article/details/gt2fqxemsmk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.kuanghao11.cn/Article/details/gt2tybluspc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2bwnamuus.html

[E02] 重复字符串
来源：http://dali.meibo888.top/Article/details/gt2mztvflvu.html

Py:   "ab" * 3
来源：http://dali.yj202588.top/Article/details/gt2mmgeezft.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenlongwang.top/Article/details/gt2zerbucwg.html

JS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gt2aoufffzl.html

TS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gt2hqcwwshw.html

Java: "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hretzxwe.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfvqiveg.html

Ruby: "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gt2etjayjts.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daxiang520.top/Article/details/gt2usmjprww.html

[E03] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xzxwpdkn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ppjwa.cn/Article/details/gt2uqtuglvp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mefvhtmf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ephxfmfy.html

TS:   s.slice(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkgbzmwv.html

Java: s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqjkvuap.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aibaodan.cn/Article/details/gt2jgkdjayi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhongyouzk.top/Article/details/gt2qmphgfzb.html

C#:   s.Substring(1, 3)
来源：http://dali.havefunace.top/Article/details/gt2rcambrcd.html

[E04] 查找子串位置
来源：http://dali.nanxinkj.top/Article/details/gt2cuzyffla.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqtasipg.html

PHP:  strpos($s, "x");
来源：http://dali.bjfxy.top/Article/details/gt2oezejbnw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.havefunace.top/Article/details/gt2xcdmquqd.html

TS:   s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2evjcyxyk.html

Java: s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gt2lpswvqhn.html

Go:   strings.Index(s, "x")
来源：http://dali.snrcjt.cn/Article/details/gt2psaoytyl.html

Ruby: s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gt2rqzkhdfn.html

C#:   s.IndexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gt2lfdkxekr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenzaomai.com/Article/details/gt2dytdoxgi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zycfv.cn/Article/details/gt2nbjfifjg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.iojbl.cn/Article/details/gt2uvajcyod.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrjcbopd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ivvv.top/Article/details/gt2vjegchlo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2axfdfaot.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgufenzy.top/Article/details/gt2kofzrydi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aizwys.cn/Article/details/gt2tzygnsoa.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gt2rmbfgavk.html

[E06] 替换子串
来源：http://dali.cashguo.top/Article/details/gt2xtveipsz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gt2nyljywow.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hywenlv.cn/Article/details/gt2musceulh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2oqfnhvcn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2boyjsjeh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2mabsigug.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gt2fksqezkd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sweek.top/Article/details/gt2dexgehko.html

C#:   s.Replace("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2nimxnlxo.html

[E07] 按分隔符拆分
来源：http://dali.sysykeji.top/Article/details/gt2ixjceikl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ydzc1.top/Article/details/gt2ugujpagz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2uohajijy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gotoacloud.top/Article/details/gt2mjxzmkzh.html

TS:   s.split(",")
来源：http://dali.chenlongwang.top/Article/details/gt2zhdhbimr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgfzy.top/Article/details/gt2gzqwynjq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jianghu66.top/Article/details/gt2bvuisbin.html

Ruby: s.split(",");  s.split
来源：http://dali.xylfe.cn/Article/details/gt2hxthcafp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hysaishi.cn/Article/details/gt2oikakxqc.html

[E08] 数组按分隔符合并
来源：http://dali.hysaishi.cn/Article/details/gt2ezyadmbq.html

Py:   ",".join(items)
来源：http://dali.hysaishi.cn/Article/details/gt2btfqaxqj.html

PHP:  implode(",", $items);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rdghawlz.html

JS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gt2dhzctaaj.html

TS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gt2jbvfmokw.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gt2ubtakbcv.html

Go:   strings.Join(items, ",")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjssslut.html

Ruby: items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gt2dtzjiaqq.html

C#:   string.Join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gt2koztgiym.html

[E09] 去除所有空白字符
来源：http://dali.tian-w.cn/Article/details/gt2nwtctnpw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pycfn.com/Article/details/gt2mpnsyzwn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2izfljthp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2tagfrjvj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gt2xtqfenci.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gt2lswpqmqm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgfzy.top/Article/details/gt2esbbzvyf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dexdhphg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gt2wzcpabtn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pycfn.com/Article/details/gt2yiqinoey.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2seokbcgy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gogol.net.cn/Article/details/gt2vstbazrt.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2tcgzrdnj.html

TS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2ygvxweop.html

Java: String.format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2seyjhuqz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gt2xuzhqzgr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2vefirsga.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cashguo.top/Article/details/gt2arbxfbnn.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gt2duupebth.html

Py:   s[::-1]
来源：http://dali.ybcxt.top/Article/details/gt2kcusegpu.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gt2zexzfiqm.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gt2jwodysec.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2jwgzlbwu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2cugzkcuq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gt2hstzbghm.html

Ruby: s.reverse
来源：http://dali.cdnleiting.top/Article/details/gt2ohjwsfbg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gt2fyimqhod.html

[E12] 统计某字符出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gt2wjkoudkj.html

Py:   s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gt2dlzqstbu.html

PHP:  substr_count($s, "a");
来源：http://dali.xylfe.cn/Article/details/gt2ysjvwonh.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abjcrmms.html

TS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gt2icffomcd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcnkkyrf.html

Go:   strings.Count(s, "a")
来源：http://dali.gzhubu.top/Article/details/gt2qgotmqra.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gt2kavbulku.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yonumen.top/Article/details/gt2xkasnekn.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2yuuajxuj.html

Py:   for ch in s: print(ch)
来源：http://dali.meibo888.top/Article/details/gt2gptiknkv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yonumen.top/Article/details/gt2qublzspy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2webgdkqy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gt2yjbxixxc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gt2mqqnmsge.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgfzy.top/Article/details/gt2bcgychss.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangdashe.top/Article/details/gt2gzaqcdkk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gt2vepbjaaw.html

[E14] URL 编码与 Base64
来源：http://dali.yueranfly.top/Article/details/gt2ketmicbi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gt2hzargaog.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gt2eulnuztp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gt2hfiwixtr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenzaomai.com/Article/details/gt2yngwwbuz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gt2jcvxirzm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fzhhl.top/Article/details/gt2fdielpuz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gzhubu.top/Article/details/gt2fyxpgggm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2hueiobqj.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2prtggxfp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2azrhpgus.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jsajkans.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhengqikj.top/Article/details/gt2mnfcgicx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yongpay.top/Article/details/gt2nmesdadd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tianlin.xyz/Article/details/gt2gbmkpeqv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guannengcc.top/Article/details/gt2rmtcqvgs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gt2yvlfbwvf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfhdvduf.html

[E16] 数字千分位
来源：http://dali.cdnleiting.top/Article/details/gt2ssjeqxtk.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258.top/Article/details/gt2xahomtxx.html

PHP:  number_format(1234567);
来源：http://dali.yonumen.top/Article/details/gt2dllfaydj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gt2lobaenhr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gt2nsrcjfrf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gt2cokswzxj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fzhhl.top/Article/details/gt2nnpshnrt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gt2fnwsxwkm.html

C#:   1234567.ToString("N0")
来源：http://dali.wangdashe.top/Article/details/gt2chtjaeme.html

[E17] 首字母大写
来源：http://dali.birdmap.top/Article/details/gt2lppxwudb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xziqi.cn/Article/details/gt2jmozjbkm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tian-w.cn/Article/details/gt2fydqjpba.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybkxwmgl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2vhprllpl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2mrepaxdk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxooagsd.html

Ruby: s.capitalize
来源：http://dali.iojbl.cn/Article/details/gt2yzfblsre.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuanzx.com/Article/details/gt2eeugvxgb.html

[E18] 模板占位符替换
来源：http://dali.ehwqpu.com/Article/details/gt2dbzzhmrk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tuxhgpig.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhixingplan.top/Article/details/gt2pssjibea.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jzrtcfei.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gt2wkftzgkl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2hyhixbgd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2wtqkenjp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gt2bbwwlhmg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdbmhjbs.html

[E19] 多行文本按行拆分
来源：http://dali.tian-w.cn/Article/details/gt2cgpilwsg.html

Py:   s.splitlines()
来源：http://dali.chenlongwang.top/Article/details/gt2kpekusew.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tndiewin.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gt2rxwqdpjx.html

TS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hijjpnii.html

Java: s.lines().toList()
来源：http://dali.jyoumei.cn/Article/details/gt2pyqyglzy.html

Go:   strings.Split(s, "\n")
来源：http://dali.yonumen.top/Article/details/gt2kgyjerjk.html

Ruby: s.lines
来源：http://dali.yj202588.top/Article/details/gt2xvbkuohb.html

C#:   s.Split('\n')
来源：http://dali.chenzaomai.com/Article/details/gt2rlhtrfke.html

[E20] 判断字符串是否为空
来源：http://dali.haohaochexian.top/Article/details/gt2cgrtzhcv.html

Py:   if not s:
来源：http://dali.cheryme.top/Article/details/gt2wfywatqx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aibaodan.cn/Article/details/gt2mlihnjqp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cucudq.cn/Article/details/gt2lmsrzmok.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gt2lqtjtolg.html

Java: if (s.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gt2ircitpgy.html

Go:   if s == "" {}
来源：http://dali.gotoacloud.top/Article/details/gt2zgqfussq.html

Ruby: if s.empty?
来源：http://dali.iojbl.cn/Article/details/gt2uamylloo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2ychwmenv.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gt2jexuzudr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aizwys.cn/Article/details/gt2uozmdjdt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2jthpovax.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wtungwxn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2epbfjbgy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2trvqjslh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigufen.top/Article/details/gt2zqrjnhzc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2chcmtgfv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2pswqfhhy.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2totxbedj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2dcifdhjm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gt2pjiazkdo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gt2eotmmqpx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2voykuubj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cktsudpy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gogol.net.cn/Article/details/gt2zpvknyjh.html

Ruby: s.bytesize;  s.length
来源：http://dali.yonumen.top/Article/details/gt2botlplvq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ydzc1.top/Article/details/gt2gwalbqlc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2btzplcff.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gt2mrkbhehb.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2rppyttys.html

[F01] 读取整个文件
来源：http://dali.zhengqikj.top/Article/details/gt2lodhsxhg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnxiangtu.top/Article/details/gt2eiqpkjex.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2rndprktg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lrnnhcpr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gt2nlzqzcia.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2duowrmmp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.andypj.xyz/Article/details/gt2fgaslkza.html

Ruby: File.read("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2wwyvwlud.html


<!-- 参考信息 -->