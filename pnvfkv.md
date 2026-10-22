代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gt2fmnzyrlv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kcueajwn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sweek.top/Article/details/gt2nihigalp.html

Go:   // 手写循环累加
来源：http://dali.jianghu66.top/Article/details/gt2ouueruyz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nwbrower.top/Article/details/gt2lctsjrxa.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangshuangyany.cn/Article/details/gt2rrjodhjr.html

[D17] 最大值与最小值
来源：http://dali.xinyue.icu/Article/details/gt2kmgopqrp.html

Py:   max(arr);  min(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2bxyyirjs.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gt2gbolhvkz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenzaomai.com/Article/details/gt2mnqvflil.html

TS:   Math.max(...arr);
来源：http://dali.chenlongwang.top/Article/details/gt2esvwsred.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zycfv.cn/Article/details/gt2hyxozdcs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2ytcqfwrg.html

Ruby: arr.max;  arr.min
来源：http://dali.andypj.xyz/Article/details/gt2xnmpxhbv.html

C#:   list.Max();  list.Min()
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmsdhqas.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigfzy.top/Article/details/gt2sqacjnbm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sweek.top/Article/details/gt2cpueuwrd.html

PHP:  array_merge(...$nested);
来源：http://dali.guowangkeji.top/Article/details/gt2coxgwhra.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangdashe.top/Article/details/gt2gvtcyynx.html

TS:   nested.flat();
来源：http://dali.nanxuanxn.top/Article/details/gt2mkuovrsw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.svipenyu.cn/Article/details/gt2ytzuttcr.html

Go:   // 手写双层循环
来源：http://dali.316326.xyz/Article/details/gt2zwncmxjb.html

Ruby: nested.flatten
来源：http://dali.fzhhl.top/Article/details/gt2pxqzfmia.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2tlyvhkib.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gt2lbuwixig.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dianchejie.cn/Article/details/gt2zqljjjot.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sysykeji.top/Article/details/gt2wzsmypnt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hysaishi.cn/Article/details/gt2qnlmjfqv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gt2unwoagyx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gt2sflsxdok.html

Go:   // 手写 map[string][]T
来源：http://dali.316326.xyz/Article/details/gt2tmjgpxfk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigfzy.top/Article/details/gt2jrinpdss.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guannengcc.top/Article/details/gt2ydvhbgcn.html

[D20] 统计每个元素出现次数
来源：http://dali.zhengqikj.top/Article/details/gt2imdmmxnm.html

Py:   Counter(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2sbzqosok.html

PHP:  array_count_values($arr);
来源：http://dali.fzhhl.top/Article/details/gt2hiaanpok.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gt2dvzthlqg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gt2ukfpxkeg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yanxiufei.cn/Article/details/gt2tvrbglme.html

Go:   // 手写 map[T]int
来源：http://dali.haohaochexian.top/Article/details/gt2rimlswvh.html

Ruby: arr.tally
来源：http://dali.shuidangran.top/Article/details/gt2wbiufhri.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gt2jhuqrdmu.html

[D21] 判断是否包含某元素
来源：http://dali.aizwys.cn/Article/details/gt2pltkslig.html

Py:   x in arr
来源：http://dali.guowangkeji.top/Article/details/gt2jkahwlvo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxacfptm.html

JS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gt2btmldtma.html

TS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2aaoxsojz.html

Java: list.contains(x)
来源：http://dali.guowangkeji.top/Article/details/gt2mucxbbfq.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bayshhor.html

Ruby: arr.include?(x)
来源：http://dali.sysykeji.top/Article/details/gt2gghwzugd.html

C#:   list.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gt2zvdtyiqt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258888.top/Article/details/gt2ntqrozos.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2binncrdk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aibaodan.cn/Article/details/gt2ospufzxl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shuidangran.top/Article/details/gt2odosfyxi.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gt2jruzexay.html

Java: new ArrayList<>(list);
来源：http://dali.svipenyu.cn/Article/details/gt2naqczzjv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.mhx1999.top/Article/details/gt2amgazden.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zycfv.cn/Article/details/gt2pjycseeu.html

C#:   new List<int>(list);
来源：http://dali.zdqjudy.top/Article/details/gt2mwylzyqt.html

[D23] reduce 累积计算
来源：http://dali.shangyingyoupin.top/Article/details/gt2jycnwneo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2wvznzysi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dykbqkhb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2jltuprqq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rfdkkoep.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ydzc1.top/Article/details/gt2oelynhtw.html

Go:   // 手写循环
来源：http://dali.snrcjt.cn/Article/details/gt2ruiuavir.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shangyingyoupin.top/Article/details/gt2pnwugbto.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.meibo888.top/Article/details/gt2zqhbzylg.html

[D24] 字典 / Map 基本操作
来源：http://dali.316326.xyz/Article/details/gt2jcqgmwwu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gt2rsslaonm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ydzc1.top/Article/details/gt2dgznquwy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jlntunkw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2fxzxucjx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cashguo.top/Article/details/gt2exhgtfyh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gt2qmiddjut.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sweek.top/Article/details/gt2blthdvrg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuanzx.com/Article/details/gt2jkoaefnd.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gt2vjqlhrly.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dashuyun.cn/Article/details/gt2gsuhkpti.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zycfv.cn/Article/details/gt2budgzmbs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yonumen.top/Article/details/gt2nhotmkiy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.smart0.xyz/Article/details/gt2myhnmxvm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhengqikj.top/Article/details/gt2jyeovtku.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yongpay.top/Article/details/gt2ujuxvwsd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.haohaochexian.top/Article/details/gt2czgbwjhf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gt2vlwdmlqo.html

[D26] 数组转字符串
来源：http://dali.chenzaomai.com/Article/details/gt2zukdwkew.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2pwhwwkyi.html

PHP:  implode(", ", $arr);
来源：http://dali.zhixingplan.top/Article/details/gt2kajksscy.html

JS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gt2xquktfoj.html

TS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2dilkjhtz.html

Java: String.join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gt2vtteyqtk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jltwwawf.html

Ruby: arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2iqkdufuy.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gt2humxzkdx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2gapeizbc.html

E. 字符串处理
来源：http://dali.tianlin.xyz/Article/details/gt2birodoiw.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ctwllnea.html

[E01] 拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2ssbehcfw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnqzz.top/Article/details/gt2hjoridit.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2enqildjk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gt2bastzjwx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gt2byvliytb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnxiangtu.top/Article/details/gt2yexkpsjh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hammf.cn/Article/details/gt2uuvksxeu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shuidangran.top/Article/details/gt2urxocbqf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2ozovddzx.html

[E02] 重复字符串
来源：http://dali.xuanzx.com/Article/details/gt2ojaexuuo.html

Py:   "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gt2enpazodp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ecppeuxj.html

JS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gt2dooleyzx.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gt2neuksdft.html

Java: "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gt2fciqrqms.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jiagoushi.top/Article/details/gt2jsommlhr.html

Ruby: "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gt2xcyjvloq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gt2fedttguy.html

[E03] 截取子串
来源：http://dali.xylfe.cn/Article/details/gt2wmlpjdtp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cdnleiting.top/Article/details/gt2zcxlqccx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gt2ejrpvgvf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gt2sjggppvk.html

TS:   s.slice(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2bepwcirq.html

Java: s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gt2xodfegxi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnqzz.top/Article/details/gt2xqsqgawh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuanzhike.top/Article/details/gt2uowisamn.html

C#:   s.Substring(1, 3)
来源：http://dali.xziqi.cn/Article/details/gt2abcngwic.html

[E04] 查找子串位置
来源：http://dali.yuxming.cn/Article/details/gt2iconnfbm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gt2ejklpbow.html

PHP:  strpos($s, "x");
来源：http://dali.jyoumei.cn/Article/details/gt2zzjletoj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhixingplan.top/Article/details/gt2tkoqacip.html

TS:   s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lksgdtku.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gt2vkohlxbr.html

Go:   strings.Index(s, "x")
来源：http://dali.zycfv.cn/Article/details/gt2gnlaxxab.html

Ruby: s.index("x")
来源：http://dali.yj20258888.top/Article/details/gt2jhfpxsrq.html

C#:   s.IndexOf("x")
来源：http://dali.bjfxy.top/Article/details/gt2chxdwjni.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dashuyun.cn/Article/details/gt2cfptriqo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aibaodan.cn/Article/details/gt2jvnkkcsn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhixingplan.top/Article/details/gt2nftrmqpa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxfixafr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fengsongda.top/Article/details/gt2hgtgkfgi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2acuuroxw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.meibo888.top/Article/details/gt2rknlidtj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkgskdf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hammf.cn/Article/details/gt2eqgwtvov.html

[E06] 替换子串
来源：http://dali.tian-w.cn/Article/details/gt2ojaepoqd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ecaxeouo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ehwqpu.com/Article/details/gt2wxllawbb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tqnqdzxy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2rsqyjjnh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2xmbfjdrn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gt2ykqstlgp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2ookdyhyt.html

C#:   s.Replace("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2fgedzhjr.html

[E07] 按分隔符拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkhxevpe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cashguo.top/Article/details/gt2utvehnlm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2ruursrgw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gotoacloud.top/Article/details/gt2nilxvqza.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gt2zicpgoew.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jiagoushi.top/Article/details/gt2pxpcmxfc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cheryme.top/Article/details/gt2atyhqbqr.html

Ruby: s.split(",");  s.split
来源：http://dali.cheryme.top/Article/details/gt2wsjvlxjr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.andypj.xyz/Article/details/gt2dzigivla.html

[E08] 数组按分隔符合并
来源：http://dali.wangdashe.top/Article/details/gt2necrwxmw.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fvhlvcqj.html

PHP:  implode(",", $items);
来源：http://dali.iojbl.cn/Article/details/gt2phvnjgdv.html

JS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2jjxoknbu.html

TS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gt2qvazipcd.html

Java: String.join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gt2xgkjbhko.html

Go:   strings.Join(items, ",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dfsnltmi.html

Ruby: items.join(",")
来源：http://dali.yuxming.cn/Article/details/gt2ygolufwb.html

C#:   string.Join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gt2hbqhnrms.html

[E09] 去除所有空白字符
来源：http://dali.guannengcc.top/Article/details/gt2enlfaauo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ppjwa.cn/Article/details/gt2xxixujog.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2cdrfjmlw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jorithay.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gt2cfthkmiw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gt2xqqfjdox.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.svipenyu.cn/Article/details/gt2quvtbpkh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2agdhdkoe.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ybcxt.top/Article/details/gt2xqjaqple.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ehwqpu.com/Article/details/gt2gxskfjer.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xylfe.cn/Article/details/gt2alqaieoi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangdashe.top/Article/details/gt2ezwqcntk.html

JS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gt2havlecio.html

TS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2ocprkoxy.html

Java: String.format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gt2xygjghsi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gt2tapprtok.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gt2makiyuff.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gt2wrcxebly.html

[E11] 反转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2sfjrqxvm.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gt2dmeofctk.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbnvdtii.html

JS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gt2tkdllgkk.html

TS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2xzarxiwh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.0kj1m.cn/Article/details/gt2gbtbfjmw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.9152youxi.cn/Article/details/gt2wujtznwy.html

Ruby: s.reverse
来源：http://dali.hfpthk.cn/Article/details/gt2qhcvzycv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gt2zxqwdeon.html

[E12] 统计某字符出现次数
来源：http://dali.jiagoushi.top/Article/details/gt2tnquapmv.html

Py:   s.count("a")
来源：http://dali.daria6918.cn/Article/details/gt2ndepkpsl.html

PHP:  substr_count($s, "a");
来源：http://dali.wangdashe.top/Article/details/gt2wwoaqfct.html

JS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gt2jdvmpwsz.html

TS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gt2iwgihggs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gt2mekabtaw.html

Go:   strings.Count(s, "a")
来源：http://dali.hammf.cn/Article/details/gt2clinviet.html

Ruby: s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2nwjfmwzo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gotoacloud.top/Article/details/gt2ewouncjg.html

[E13] 逐字符遍历
来源：http://dali.tianlin.xyz/Article/details/gt2ejuggduf.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gt2lrzaqvug.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhixingplan.top/Article/details/gt2eznqlbyo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xylgsgti.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gt2smxdyuxc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2fcmrvovd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shuidangran.top/Article/details/gt2ysoisopd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.svipenyu.cn/Article/details/gt2rngqtxny.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2vjxnysjm.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gt2ahlodrzr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.havefunace.top/Article/details/gt2qyatmjqa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sxryk.cn/Article/details/gt2rgoscxje.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258.top/Article/details/gt2pohtihdt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xurnivdi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2wddvyuki.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yangfankeji.com/Article/details/gt2hpwxdkpu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kyzlkidh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cheryme.top/Article/details/gt2zxfrfzmh.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj202588.top/Article/details/gt2thrsnrid.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gzhubu.top/Article/details/gt2degzkunv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.0kj1m.cn/Article/details/gt2pbaqeyvw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2uwetqofl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ppjwa.cn/Article/details/gt2xqwrmgsg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gt2rnovfpid.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gt2guyevjlz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dashuyun.cn/Article/details/gt2iqdsdqvv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gt2oaxmqgww.html

[E16] 数字千分位
来源：http://dali.yuxming.cn/Article/details/gt2cxkltciw.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gt2bgwnyjkt.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gt2iienbqjj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gt2fyrwsrdj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gt2uutipulx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258.top/Article/details/gt2zwmlrkjk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.havefunace.top/Article/details/gt2sjjdbqip.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yueranfly.top/Article/details/gt2lmrxobzw.html

C#:   1234567.ToString("N0")
来源：http://dali.kuanghao11.cn/Article/details/gt2eskgpldc.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ycyocrxg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gt2uksnztsu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgfzy.top/Article/details/gt2wlwjmmog.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gt2lmazrbka.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gt2sexhiuua.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenzaomai.com/Article/details/gt2ogshcydh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xinyue.icu/Article/details/gt2isofpkke.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gt2mivcctjd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhoulong.xyz/Article/details/gt2kqctdvbh.html

[E18] 模板占位符替换
来源：http://dali.dashuyun.cn/Article/details/gt2jmcnqzjx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fzhhl.top/Article/details/gt2wcabwtso.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aizwys.cn/Article/details/gt2kciitdsq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2zhsuecxj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2viquslqh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2kxoceubm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gt2ggoxvesp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shuidangran.top/Article/details/gt2btfnrulw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gt2qclszahs.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gt2hhrzxymy.html

Py:   s.splitlines()
来源：http://dali.fzhhl.top/Article/details/gt2cfruhsuh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2fskfrsnf.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tdgsjldh.html

TS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gt2dxfqdsks.html

Java: s.lines().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mytqthtw.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nfqmadfz.html

Ruby: s.lines
来源：http://dali.pycfn.com/Article/details/gt2rwvtannc.html

C#:   s.Split('\n')
来源：http://dali.nanxinkj.top/Article/details/gt2dkbofhgf.html

[E20] 判断字符串是否为空
来源：http://dali.yanxiufei.cn/Article/details/gt2olyvcbsn.html

Py:   if not s:
来源：http://dali.pycfn.com/Article/details/gt2rtvkjaba.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hysaishi.cn/Article/details/gt2dchatgkp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ydzc1.top/Article/details/gt2wgglxgzd.html

TS:   if (s === "") {}
来源：http://dali.ydzc1.top/Article/details/gt2hpgwxlkv.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gt2blehihmo.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gt2vtkvysoz.html

Ruby: if s.empty?
来源：http://dali.zhiwuduotai.top/Article/details/gt2mahvcbip.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ybcxt.top/Article/details/gt2gkwgmoku.html

[E21] 超长截断加省略号
来源：http://dali.guowangkeji.top/Article/details/gt2avabndaw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sysykeji.top/Article/details/gt2wbtxkmnr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2odiyfuem.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2qalgkevi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2rutfkbxm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2qwecykjy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gt2xldpoyzp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2igysgkld.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2mjygqbfz.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dhzsegti.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2fqdkorwj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2ubtlhyxk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gt2acnubusy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gt2cuhhzjbf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sufxvd.cn/Article/details/gt2rbhzdckx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.haohaochexian.top/Article/details/gt2ophzrgjg.html

Ruby: s.bytesize;  s.length
来源：http://dali.hywenlv.cn/Article/details/gt2jehmhmoz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xinyue.icu/Article/details/gt2ghehmcne.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2jnqrttnf.html

F. 文件与目录
来源：http://dali.ybcxt.top/Article/details/gt2fhppopth.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2moenerhq.html


<!-- 参考信息 -->