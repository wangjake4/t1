代发 wailian999

[D19] 按字段分组
来源：http://dali.nanxuanxn.top/Article/details/gtzwncadgs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gtomyrrskd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gogol.net.cn/Article/details/gtdibkbdmw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hysaishi.cn/Article/details/gtxtztmwut.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gtgfgfkxxj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.redwolf501.top/Article/details/gtjweevcai.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gtfclpuvkh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxinkj.top/Article/details/gtvzeqwxpw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.iojbl.cn/Article/details/gtdazgteco.html

[D20] 统计每个元素出现次数
来源：http://dali.yj202588.top/Article/details/gtgwvbtreb.html

Py:   Counter(arr)
来源：http://dali.9152youxi.cn/Article/details/gttgftwonc.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gtvbfnvxgf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gtrtkbhmmy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gthrynxtfr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenjidiqi.icu/Article/details/gtaubfsmin.html

Go:   // 手写 map[T]int
来源：http://dali.tian-w.cn/Article/details/gtvfcdtowt.html

Ruby: arr.tally
来源：http://dali.fzhhl.top/Article/details/gtqelxnddx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.kuanghao11.cn/Article/details/gtrwalxmtz.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gtgybhxnas.html

Py:   x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpcrppxr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gtlrsdywql.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtljgjwysz.html

TS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtyribptvh.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtbydaepzt.html

Go:   slices.Contains(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtitiqfpfj.html

Ruby: arr.include?(x)
来源：http://dali.xziqi.cn/Article/details/gtngoqcncn.html

C#:   list.Contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtsmcmgjzz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cucudq.cn/Article/details/gtysceykxv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwsolllf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258.top/Article/details/gtmtpqvfkr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shzxlz.cn/Article/details/gtlimaqgjc.html

TS:   [...arr];
来源：http://dali.ybcxt.top/Article/details/gtlqvjtjhv.html

Java: new ArrayList<>(list);
来源：http://dali.ydzc1.top/Article/details/gtqrnmqfga.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xinyue.icu/Article/details/gtxkcotlyh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dianchejie.cn/Article/details/gtqaukcsqu.html

C#:   new List<int>(list);
来源：http://dali.cheryme.top/Article/details/gtygtvyqks.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gtlxlqwjcr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtsvgxqftl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gtajbwwmld.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gtcygfjbal.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtmbfncqsl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ydzc1.top/Article/details/gtlmmbvqmg.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gtlvjdxxum.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gtyrsfttkh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.kuanghao11.cn/Article/details/gtmzyxmavz.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxuanxn.top/Article/details/gthndvvcfl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aizwys.cn/Article/details/gtwzrbhfbp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhengqikj.top/Article/details/gtlxqjzhvk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zycfv.cn/Article/details/gtrbuncpeo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gteaikgbsl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jianghu66.top/Article/details/gtodwqbqcj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.quarkkingdee.top/Article/details/gtgrqctjpu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daxiang520.top/Article/details/gtuogpplje.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgfzy.top/Article/details/gtuxywubuv.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigfzy.top/Article/details/gtkbmhcmnj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gtcmobqwks.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.mhx1999.top/Article/details/gtqcyowapq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gtlbpjpdrs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gtmxydwqop.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtqiwiokdf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gtypjjqxtf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgufenzy.top/Article/details/gthqajtgzr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtomkdvdme.html

[D26] 数组转字符串
来源：http://dali.yuxming.cn/Article/details/gtthfbhdan.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dashuyun.cn/Article/details/gtoakiwvyi.html

PHP:  implode(", ", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtyrvnvpnb.html

JS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtkgldjdrx.html

TS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxkwmhnw.html

Java: String.join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtfnsyrukv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.316326.xyz/Article/details/gtrglmkict.html

Ruby: arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtyrspslyb.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtzmtyzmkc.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtnzzwnwjd.html

E. 字符串处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtnetppxbu.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtagotfbst.html

[E01] 拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtecxcnhgd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.feifeiyinyue.top/Article/details/gterbdxgdw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.c1oappe.top/Article/details/gtvqdbeccw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtrcktwhyn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtqomvrspy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yangfankeji.com/Article/details/gtbkkoaxhy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gtpcqhobvu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gtjhkryhwj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlaemmqqi.html

[E02] 重复字符串
来源：http://dali.zhengqikj.top/Article/details/gtdziwpdkt.html

Py:   "ab" * 3
来源：http://dali.yj20258888.top/Article/details/gtltinoiof.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhengqikj.top/Article/details/gtinpwrbdc.html

JS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtmahbgzsh.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtcuunpjxr.html

Java: "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtlwqavlbp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ydzc1.top/Article/details/gtqnakcxrb.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtkelukwpm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtwnoydysv.html

[E03] 截取子串
来源：http://dali.yj20258888.top/Article/details/gtmbbzkqor.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pycfn.com/Article/details/gteszxzekf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtbjvecisy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtmewcdagc.html

TS:   s.slice(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gtpdtdonww.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtawvleijw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258888.top/Article/details/gthqjyrozc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sxryk.cn/Article/details/gtxjokfpkp.html

C#:   s.Substring(1, 3)
来源：http://dali.haohaochexian.top/Article/details/gtrtfonyyt.html

[E04] 查找子串位置
来源：http://dali.haohaochexian.top/Article/details/gtszkiabap.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ydzc1.top/Article/details/gtsvmbuhwl.html

PHP:  strpos($s, "x");
来源：http://dali.dashuyun.cn/Article/details/gtmysthayu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daxiang520.top/Article/details/gtvbkaiywl.html

TS:   s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsrhzyjg.html

Java: s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtclxddxoc.html

Go:   strings.Index(s, "x")
来源：http://dali.yuxming.cn/Article/details/gtghcsothe.html

Ruby: s.index("x")
来源：http://dali.shuidangran.top/Article/details/gtuxdtmoek.html

C#:   s.IndexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtsyrgrnsg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258.top/Article/details/gtudyyqhqh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.mhx1999.top/Article/details/gtaoiuxiry.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aibaodan.cn/Article/details/gtpuolluht.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtpqoegcwg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.9152youxi.cn/Article/details/gtklgoozcy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtlibfjngz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyetqmybz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258888.top/Article/details/gtsqywctis.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtnnfcfkgg.html

[E06] 替换子串
来源：http://dali.chenzaomai.com/Article/details/gtkhfetnzg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtotucshgq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.svipenyu.cn/Article/details/gtwlwgvbjl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtojxtsnul.html

TS:   s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtjkgtwjug.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtmpdjcael.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.birdmap.top/Article/details/gtixkhdfqw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtnnbpibew.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtmuljbyny.html

[E07] 按分隔符拆分
来源：http://dali.iojbl.cn/Article/details/gtstqrxoqm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigfzy.top/Article/details/gtwlubfqjx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtpneseyap.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ppjwa.cn/Article/details/gtbsmsbifv.html

TS:   s.split(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtfondqjjx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenjidiqi.icu/Article/details/gtaxfngojr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dianchejie.cn/Article/details/gtljmgusdq.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gtyilwylzx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yangfankeji.com/Article/details/gtjktnrkbn.html

[E08] 数组按分隔符合并
来源：http://dali.guowangkeji.top/Article/details/gtivjzrhqg.html

Py:   ",".join(items)
来源：http://dali.yanxiufei.cn/Article/details/gtasohyawd.html

PHP:  implode(",", $items);
来源：http://dali.aizwys.cn/Article/details/gtvcfnzmka.html

JS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtokpltgxx.html

TS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gthkytteiv.html

Java: String.join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gtznhexlco.html

Go:   strings.Join(items, ",")
来源：http://dali.feifeiyinyue.top/Article/details/gtjczamkzc.html

Ruby: items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdlmhqly.html

C#:   string.Join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtopgtmpia.html

[E09] 去除所有空白字符
来源：http://dali.dashuyun.cn/Article/details/gtdwcdoybq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gtrdvdqijh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jyoumei.cn/Article/details/gtusxzllxf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbthzyza.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gtdvaqenqy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gtotydbqej.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fzhhl.top/Article/details/gtokbmawyf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuxming.cn/Article/details/gtdfrxjleh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtldywekvj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gtkqgabmga.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ivvv.top/Article/details/gtqzebharz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gogol.net.cn/Article/details/gtxugpdfkc.html

JS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtbwsfffvl.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtwifmmqov.html

Java: String.format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtctvsywqm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gthykdtnvo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtyuotymzj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gteoasthgs.html

[E11] 反转字符串
来源：http://dali.dashuyun.cn/Article/details/gtadruavex.html

Py:   s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtmhvuuckq.html

PHP:  strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtuznaxtfy.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtjeruymxe.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtqxcfgjqq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sufxvd.cn/Article/details/gthwbauyer.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtyreqlxbw.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gtbhlabzbq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtcjbeyjte.html

[E12] 统计某字符出现次数
来源：http://dali.sufxvd.cn/Article/details/gtidosvirr.html

Py:   s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gtngjlfsmt.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gtfcknwwbz.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gtnhlwfkxg.html

TS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtxitkufcq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xziqi.cn/Article/details/gtnoautgvr.html

Go:   strings.Count(s, "a")
来源：http://dali.zhoulong.xyz/Article/details/gtoypqhhal.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteeatvaro.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gtkmhnosph.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtegmpszlx.html

Py:   for ch in s: print(ch)
来源：http://dali.gaohongyu789.top/Article/details/gtcopgowhi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sufxvd.cn/Article/details/gttkyfouym.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtsahzncdl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gtcmmjjyfm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xylfe.cn/Article/details/gtepfbkrtk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.0kj1m.cn/Article/details/gtowzrsmyh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jlsjyb.cn/Article/details/gtsfzpoplf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yvedp.cn/Article/details/gtvxihsbvx.html

[E14] URL 编码与 Base64
来源：http://dali.mhx1999.top/Article/details/gtalyduzxj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ydzc1.top/Article/details/gtbfbgpwkg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gthjxqqyal.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gtfjclisda.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gtycwkcybg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtadwnjeuy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yvedp.cn/Article/details/gtnfpwepnq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ehwqpu.com/Article/details/gtzeycxwfm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cheryme.top/Article/details/gtjifikakc.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gtfkhgzsvj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xinyue.icu/Article/details/gtispmfrra.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrvwksju.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hysaishi.cn/Article/details/gtwgdlfufk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtuylsrtlc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.bjfxy.top/Article/details/gtlnemiarn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gttqirzmpt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gtcjdysuly.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gtsnhikjzx.html

[E16] 数字千分位
来源：http://dali.sysykeji.top/Article/details/gtfwphihwz.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gttlligvkg.html

PHP:  number_format(1234567);
来源：http://dali.9152youxi.cn/Article/details/gtvrskvgiw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtcxnktbff.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkvtjiil.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gtganucnth.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258.top/Article/details/gtguxzwnkn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gtuswpmcod.html

C#:   1234567.ToString("N0")
来源：http://dali.dianchejie.cn/Article/details/gtsebcyams.html

[E17] 首字母大写
来源：http://dali.shzxlz.cn/Article/details/gtrmwtwymd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwttwdms.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.vqdsnc.cn/Article/details/gtczxleyip.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gthtxrwqwu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gtxzzaqnfn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmliizcav.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pycfn.com/Article/details/gtctqonxer.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gtistkbvrt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gttgzggkoc.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gtmjoblesf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fengsongda.top/Article/details/gtpaaxqgop.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangdashe.top/Article/details/gtpzbqlbla.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtxnecasvq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpxqllkz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtvzrjyurr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtzfzxxlxu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gtpsfabycp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guannengcc.top/Article/details/gtqgcpinir.html

[E19] 多行文本按行拆分
来源：http://dali.hammf.cn/Article/details/gtqymqrykh.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiakzbezd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gtbhtwyvyv.html

JS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtjzipdsaa.html

TS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtohzxidmq.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gtjzfezvni.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsihpksjc.html

Ruby: s.lines
来源：http://dali.yongpay.top/Article/details/gtshikzxbj.html

C#:   s.Split('\n')
来源：http://dali.xuetiantiany.cn/Article/details/gtupahzhap.html

[E20] 判断字符串是否为空
来源：http://dali.zhixingplan.top/Article/details/gtkwpxzfbu.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwymrwzmn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cqqwz.cn/Article/details/gteeitorjs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gtvqtiglrm.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gtivukuqqq.html

Java: if (s.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gtsbxdhidp.html

Go:   if s == "" {}
来源：http://dali.nanxuanxn.top/Article/details/gttkbnfwzm.html

Ruby: if s.empty?
来源：http://dali.dashuyun.cn/Article/details/gtksjsozbe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gzhubu.top/Article/details/gtbujxvvvy.html

[E21] 超长截断加省略号
来源：http://dali.jqgfzy.top/Article/details/gtqosbtcyc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.316326.xyz/Article/details/gtmbyoglsg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtrmqwpfxd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gttfcwdgkc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvssvumqn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtjkxczrso.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daria6918.cn/Article/details/gtpyaqxgpl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtpwfingdf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtacqjavnd.html

[E22] 字节长度与字符长度
来源：http://dali.haohaochexian.top/Article/details/gtkatdgnkp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hywenlv.cn/Article/details/gtsaocueng.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtopzzkxjf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gtrbaclyvu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtildcmtby.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cucudq.cn/Article/details/gtlwjlfapr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxuanxn.top/Article/details/gtgfubobou.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gtqzeblosb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ydzc1.top/Article/details/gtbqemaglu.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtoogyggbu.html

F. 文件与目录
来源：http://dali.zhoulong.xyz/Article/details/gthgqvvhwv.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtqibnxiix.html

[F01] 读取整个文件
来源：http://dali.fzhhl.top/Article/details/gtyxfuhbtv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tianlin.xyz/Article/details/gtikeqivwk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtobjbichy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gtldfccgnp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtquwzkhhi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtxiwewrfj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gttnkqmdby.html

Ruby: File.read("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtbyiupsci.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtrwfhrvve.html

[F02] 逐行读取文件
来源：http://dali.zhoulong.xyz/Article/details/gtcadkxpje.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ydzc1.top/Article/details/gtcmivjdvf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gtnjwawdda.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gtogwghimd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gthoqrllxp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gtwcbuafyk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuetiantiany.cn/Article/details/gtciwitlwc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gotoacloud.top/Article/details/gtwcqdseii.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gtnxplswoe.html

[F03] 写入文件（覆盖）
来源：http://dali.yanxiufei.cn/Article/details/gtxragmcgu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigfzy.top/Article/details/gtgbzuuato.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtijacival.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtzhdhukzt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtigweyukj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gtbedsvjwa.html


<!-- 参考信息 -->