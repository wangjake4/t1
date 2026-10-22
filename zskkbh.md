代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.c1oappe.top/Article/details/gt2vfnfuvrw.html

Ruby: arr.max;  arr.min
来源：http://dali.hfpthk.cn/Article/details/gt2zfrkaffo.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zawaerja.html

[D18] 扁平化嵌套数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhroiljy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258888.top/Article/details/gt2jrgeaqaz.html

PHP:  array_merge(...$nested);
来源：http://dali.tian-w.cn/Article/details/gt2jdygoseg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fafqhafd.html

TS:   nested.flat();
来源：http://dali.jqgfzy.top/Article/details/gt2apefliby.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2dgngsomm.html

Go:   // 手写双层循环
来源：http://dali.havefunace.top/Article/details/gt2czyryqfu.html

Ruby: nested.flatten
来源：http://dali.gogol.net.cn/Article/details/gt2mpctozyl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2zdatglud.html

[D19] 按字段分组
来源：http://dali.havefunace.top/Article/details/gt2iztenluf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sufxvd.cn/Article/details/gt2wqxqxoyk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258888.top/Article/details/gt2drpupbgt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gt2ownztxxh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gt2ffktpegq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qkojoyfx.html

Go:   // 手写 map[string][]T
来源：http://dali.cashguo.top/Article/details/gt2ehyoiydx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.bjfxy.top/Article/details/gt2bhyklhqh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zdqjudy.top/Article/details/gt2plfeojgg.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gt2efynqiaz.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ftfmjchf.html

PHP:  array_count_values($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2qvgyqpuu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tlbvumrw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gt2mumgiunp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jiagoushi.top/Article/details/gt2xtfzkstf.html

Go:   // 手写 map[T]int
来源：http://dali.ydzc1.top/Article/details/gt2dudfsngs.html

Ruby: arr.tally
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bzwtfgso.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ppjwa.cn/Article/details/gt2urmrlcfk.html

[D21] 判断是否包含某元素
来源：http://dali.cashguo.top/Article/details/gt2xdbucgkm.html

Py:   x in arr
来源：http://dali.gaohongyu789.top/Article/details/gt2scgleqyz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sysykeji.top/Article/details/gt2kafcmikg.html

JS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2cpxpsscy.html

TS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2wrgmcpwy.html

Java: list.contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2fegnrcui.html

Go:   slices.Contains(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2hcswcydh.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gt2unbhbaks.html

C#:   list.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gt2dfryxsgx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dianchejie.cn/Article/details/gt2glxxcfwy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqnmgpcp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gt2agvmnwea.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gt2ibdyafbv.html

TS:   [...arr];
来源：http://dali.yvedp.cn/Article/details/gt2nwtzbfyr.html

Java: new ArrayList<>(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2gngpgftd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgfzy.top/Article/details/gt2uojluhmm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gt2cvtyalpu.html

C#:   new List<int>(list);
来源：http://dali.tianlin.xyz/Article/details/gt2fljmweex.html

[D23] reduce 累积计算
来源：http://dali.redwolf501.top/Article/details/gt2ymfrgbsd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpknnat.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xylfe.cn/Article/details/gt2ifanmcqd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vggfqcvw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gt2aocyvwzd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gogol.net.cn/Article/details/gt2ikobqbgk.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gt2siusoukd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gt2akrlpfgc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gt2ntddbycu.html

[D24] 字典 / Map 基本操作
来源：http://dali.aizwys.cn/Article/details/gt2llyyhmth.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gotoacloud.top/Article/details/gt2wdcnzepo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ppjwa.cn/Article/details/gt2nvmmiluo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tian-w.cn/Article/details/gt2lxvjgxej.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2xxswfljt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dashuyun.cn/Article/details/gt2ozpgqbwn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenzaomai.com/Article/details/gt2iiycmslp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yangfankeji.com/Article/details/gt2cdijguev.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xinyue.icu/Article/details/gt2fzlhhjpt.html

[D25] Set 集合去重与交并差
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nemkwqzf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuanzx.com/Article/details/gt2iolufegw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gaohongyu789.top/Article/details/gt2yghnpvuz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.mhx1999.top/Article/details/gt2ncuxydgp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhongyouzk.top/Article/details/gt2ofptkzen.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sweek.top/Article/details/gt2upekfceb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenzaomai.com/Article/details/gt2nvpymoty.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuxming.cn/Article/details/gt2iimmehyl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2kcxaxqho.html

[D26] 数组转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzjjwbgr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hysaishi.cn/Article/details/gt2qyzzeibf.html

PHP:  implode(", ", $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2srtvmpxn.html

JS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gt2xgfwpejy.html

TS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2azhtmjch.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gt2risxqzgj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gt2xkvkzavl.html

Ruby: arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gt2vgszdyxv.html

C#:   string.Join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gt2ecqeitge.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2nfxwobff.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gt2gjeuxvxw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2desbqsks.html

[E01] 拼接字符串
来源：http://dali.pycfn.com/Article/details/gt2mlewsffp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yongpay.top/Article/details/gt2ebfczokx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2blqjonpq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gt2iuihvygk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gt2rwyycoyi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daxiang520.top/Article/details/gt2xhsyvmto.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yueranfly.top/Article/details/gt2gsailjub.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gotoacloud.top/Article/details/gt2xlwnzyjn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2felvuuvt.html

[E02] 重复字符串
来源：http://dali.yvedp.cn/Article/details/gt2zmstewko.html

Py:   "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gt2yfubwtly.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gt2plvrzgxe.html

JS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gt2cvkndowf.html

TS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gt2cqnsgtud.html

Java: "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2xvpeequw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rywltgiz.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gt2apiytsfb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gogol.net.cn/Article/details/gt2mdnbgzha.html

[E03] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gt2pzkabcnf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ivvv.top/Article/details/gt2iapikfty.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2bigemrce.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2iililfnm.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtqwtpwu.html

Java: s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2msdijpmq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ybcxt.top/Article/details/gt2twkgrsnp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.bjfxy.top/Article/details/gt2sxhhygrl.html

C#:   s.Substring(1, 3)
来源：http://dali.cucudq.cn/Article/details/gt2geflhvui.html

[E04] 查找子串位置
来源：http://dali.cashguo.top/Article/details/gt2zkllljwv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zycfv.cn/Article/details/gt2htrkpabs.html

PHP:  strpos($s, "x");
来源：http://dali.cucudq.cn/Article/details/gt2bqjxgoom.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xylfe.cn/Article/details/gt2unkavisk.html

TS:   s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gt2seonxsfz.html

Java: s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gt2oxgbrhbh.html

Go:   strings.Index(s, "x")
来源：http://dali.gotoacloud.top/Article/details/gt2vufutmnr.html

Ruby: s.index("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2mdkzpech.html

C#:   s.IndexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gt2ucjmxqvb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gt2tkaznykx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj202588.top/Article/details/gt2kstryeum.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nwbrower.top/Article/details/gt2lkmpntrh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gt2cxptyqio.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yvedp.cn/Article/details/gt2dlltvcan.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2qsgludwd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.mhx1999.top/Article/details/gt2amzzjatt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzefaxea.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.redwolf501.top/Article/details/gt2shgdusel.html

[E06] 替换子串
来源：http://dali.tianlin.xyz/Article/details/gt2pictjsib.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gt2gbbwihji.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aizwys.cn/Article/details/gt2faizzjiy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2quqkknid.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2muuvdrao.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2jinntyss.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gt2rwhnduku.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2bqygqsbp.html

C#:   s.Replace("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2chhsaghr.html

[E07] 按分隔符拆分
来源：http://dali.jiagoushi.top/Article/details/gt2tcsivepl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.havefunace.top/Article/details/gt2nnslrbay.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2zriepwok.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sxryk.cn/Article/details/gt2cfzvyfsp.html

TS:   s.split(",")
来源：http://dali.yuanzhike.top/Article/details/gt2nxibydtc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zycfv.cn/Article/details/gt2ovwmxlob.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cqqwz.cn/Article/details/gt2khjvioyh.html

Ruby: s.split(",");  s.split
来源：http://dali.xylfe.cn/Article/details/gt2kycisvli.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xylfe.cn/Article/details/gt2beqxyrxt.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gt2rkijlexf.html

Py:   ",".join(items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwnkjhar.html

PHP:  implode(",", $items);
来源：http://dali.sweek.top/Article/details/gt2fabsjrzq.html

JS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gt2fygjnnhd.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2idfcixxd.html

Java: String.join(",", items)
来源：http://dali.smart0.xyz/Article/details/gt2rwzowvtq.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mesritsp.html

Ruby: items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gt2rjvfltzx.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gt2ohwwfmcv.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gt2ybwllzzx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hysaishi.cn/Article/details/gt2waefayns.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dscfygyo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gt2xdwoubtt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gt2glcuadvj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gt2vrydgqku.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gt2frujhiub.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gt2vprjabzk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gt2ewuvequa.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dashuyun.cn/Article/details/gt2zywmlpmn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2dwazzulf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sweek.top/Article/details/gt2wnxiwzxp.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gt2yhrsayyk.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2vdovvpfh.html

Java: String.format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gt2ojiislqi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tgyirnkq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gt2txskuist.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hysaishi.cn/Article/details/gt2paoqsjgi.html

[E11] 反转字符串
来源：http://dali.fzhhl.top/Article/details/gt2vasfvdip.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gt2wugxfkhv.html

PHP:  strrev($s);
来源：http://dali.hammf.cn/Article/details/gt2fesworoa.html

JS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2reeahozw.html

TS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2spdzneoa.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yvedp.cn/Article/details/gt2kqtbovwl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zdqjudy.top/Article/details/gt2uimzjuyr.html

Ruby: s.reverse
来源：http://dali.zhixingplan.top/Article/details/gt2vknhgzfh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gt2aihryzua.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gt2imisytdt.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2uebfxfkb.html

PHP:  substr_count($s, "a");
来源：http://dali.yuxming.cn/Article/details/gt2yozlkhfu.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gt2hnhyaxoc.html

TS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gt2qpriouzq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pycfn.com/Article/details/gt2rdzdlabg.html

Go:   strings.Count(s, "a")
来源：http://dali.vqdsnc.cn/Article/details/gt2wlfonkkq.html

Ruby: s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gt2xxuyqaqa.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xziqi.cn/Article/details/gt2pcyrrikm.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2otqrvknr.html

Py:   for ch in s: print(ch)
来源：http://dali.yueranfly.top/Article/details/gt2imnvjygd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.snrcjt.cn/Article/details/gt2tucgsbkj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opxnkkhb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gt2xfmhcuot.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gzhubu.top/Article/details/gt2mtlmnkjr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nwbrower.top/Article/details/gt2ijbwaexh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj202588.top/Article/details/gt2evmvtgov.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj202588.top/Article/details/gt2hdirhlcn.html

[E14] URL 编码与 Base64
来源：http://dali.daxiang520.top/Article/details/gt2jvfnzscx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cdnleiting.top/Article/details/gt2oaazqaek.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jianghu66.top/Article/details/gt2svyzasqy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cqqwz.cn/Article/details/gt2yuzvytwk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ybcxt.top/Article/details/gt2bsydbfjj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gt2vymmztex.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.quarkkingdee.top/Article/details/gt2clnufuqs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hfpthk.cn/Article/details/gt2xxeixprn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zdqjudy.top/Article/details/gt2jjajoirq.html

[E15] HTML 转义 / 反转义
来源：http://dali.guowangkeji.top/Article/details/gt2calgyjln.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sufxvd.cn/Article/details/gt2lftecqnz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.smart0.xyz/Article/details/gt2lwffktfj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gt2vmslybar.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2pgohdhbk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jianghu66.top/Article/details/gt2kszpdgoy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gt2dazjgzmc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2lrfnzsfq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.smart0.xyz/Article/details/gt2efemfieb.html

[E16] 数字千分位
来源：http://dali.wangdashe.top/Article/details/gt2nphlngmb.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwdfmsmo.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtujexxq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gt2twqxxeaw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gt2mekhhefk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.smart0.xyz/Article/details/gt2iwlofcoi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gt2zikuwuto.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2txnioqov.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gt2xgjtumcr.html

[E17] 首字母大写
来源：http://dali.shangyingyoupin.top/Article/details/gt2adprncly.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guowangkeji.top/Article/details/gt2vyhquqeo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenzaomai.com/Article/details/gt2vkwirbxl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gt2wfidruac.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gt2srjngjcr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cavyxxxw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.meibo888.top/Article/details/gt2vlgvlsnx.html

Ruby: s.capitalize
来源：http://dali.yonumen.top/Article/details/gt2fytlbjha.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxqonjmu.html

[E18] 模板占位符替换
来源：http://dali.svipenyu.cn/Article/details/gt2snoncfze.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hfpthk.cn/Article/details/gt2qmofpcmm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.smart0.xyz/Article/details/gt2kidqvqyj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2hlztlipq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vugvqlox.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2sfnrsdfk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2fozflfxi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ppjwa.cn/Article/details/gt2sxzaxnky.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bexyxehc.html

[E19] 多行文本按行拆分
来源：http://dali.xinyue.icu/Article/details/gt2rxkhraya.html

Py:   s.splitlines()
来源：http://dali.andypj.xyz/Article/details/gt2mtbjrnfv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cheryme.top/Article/details/gt2vbjebmwk.html

JS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gt2rdowyqnh.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gt2sahdpdan.html

Java: s.lines().toList()
来源：http://dali.jinqigufen.top/Article/details/gt2vkfmmhik.html

Go:   strings.Split(s, "\n")
来源：http://dali.fzhhl.top/Article/details/gt2uryjtugg.html

Ruby: s.lines
来源：http://dali.shzxlz.cn/Article/details/gt2hcvzphis.html

C#:   s.Split('\n')
来源：http://dali.sxryk.cn/Article/details/gt2zuaofcji.html

[E20] 判断字符串是否为空
来源：http://dali.hnxiangtu.top/Article/details/gt2jplhncfx.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gt2hqcwlqhv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jlsjyb.cn/Article/details/gt2mevqqgpp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gt2reqjlzsg.html

TS:   if (s === "") {}
来源：http://dali.yueranfly.top/Article/details/gt2lnidrjgm.html

Java: if (s.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gt2xybugodn.html

Go:   if s == "" {}
来源：http://dali.fengsongda.top/Article/details/gt2ioescttn.html

Ruby: if s.empty?
来源：http://dali.xuanzx.com/Article/details/gt2klumtbdc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yvedp.cn/Article/details/gt2qrtolqoq.html

[E21] 超长截断加省略号
来源：http://dali.yanxiufei.cn/Article/details/gt2tgziprah.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gt2ywovupre.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gt2tcuhijsd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2sypkapgn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2yalwlzce.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2pdipwits.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gt2atbtmkkn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2tukofmka.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gt2jeqbjnuj.html

[E22] 字节长度与字符长度
来源：http://dali.meibo888.top/Article/details/gt2kmzdlhwr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aibaodan.cn/Article/details/gt2tsppzkxt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2fnipkzjr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gt2vscazirb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gt2hdetszxa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.andypj.xyz/Article/details/gt2qhrtgjeo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nwbrower.top/Article/details/gt2qghthbeh.html

Ruby: s.bytesize;  s.length
来源：http://dali.ppjwa.cn/Article/details/gt2sqypwzkh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.0kj1m.cn/Article/details/gt2lhltcjrn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2feicrwke.html

F. 文件与目录
来源：http://dali.dashuyun.cn/Article/details/gt2jcqofmbc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2mxnhahij.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gt2ueohaskz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gt2dtcslgca.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2kgltbbwp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhengqikj.top/Article/details/gt2zyjljhjs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ebidtjbg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gt2tletfrqx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuanzx.com/Article/details/gt2idvwidkq.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2xwbkvpte.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2hoybcxtu.html

[F02] 逐行读取文件
来源：http://dali.daxiang520.top/Article/details/gt2mojzklfk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.redwolf501.top/Article/details/gt2yiaqkewp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fengsongda.top/Article/details/gt2optssbxa.html


<!-- 参考信息 -->