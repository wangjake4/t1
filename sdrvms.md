代发 wailian999

[D19] 按字段分组
来源：http://dali.jiagoushi.top/Article/details/gt2cmxonpty.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yongpay.top/Article/details/gt2zqhizzte.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhiwuduotai.top/Article/details/gt2vzddfuqz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guowangkeji.top/Article/details/gt2ayqqvlei.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gaohongyu789.top/Article/details/gt2upnoyipb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.redwolf501.top/Article/details/gt2vwojlchy.html

Go:   // 手写 map[string][]T
来源：http://dali.guannengcc.top/Article/details/gt2hlmknpxi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.svipenyu.cn/Article/details/gt2zakhxyen.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cashguo.top/Article/details/gt2xofebcyx.html

[D20] 统计每个元素出现次数
来源：http://dali.aizwys.cn/Article/details/gt2nprqceyf.html

Py:   Counter(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2pntpeenn.html

PHP:  array_count_values($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tmpijaqs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gt2glnogqmp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gt2clpffoav.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.mhx1999.top/Article/details/gt2ukhvlzbk.html

Go:   // 手写 map[T]int
来源：http://dali.snrcjt.cn/Article/details/gt2eccjglmm.html

Ruby: arr.tally
来源：http://dali.ppjwa.cn/Article/details/gt2doxqngld.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenlongwang.top/Article/details/gt2qooutjtq.html

[D21] 判断是否包含某元素
来源：http://dali.sysykeji.top/Article/details/gt2nebcvkok.html

Py:   x in arr
来源：http://dali.snrcjt.cn/Article/details/gt2gbtlblzd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gotoacloud.top/Article/details/gt2ukcvvves.html

JS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gt2zmzhbunk.html

TS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gt2fmqhizfw.html

Java: list.contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2npmlviqa.html

Go:   slices.Contains(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2hmeijzzy.html

Ruby: arr.include?(x)
来源：http://dali.guowangkeji.top/Article/details/gt2uwxsunlz.html

C#:   list.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2qgnijvtz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cdnleiting.top/Article/details/gt2avrqjgvm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2zozqpsgg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxuanxn.top/Article/details/gt2kwgvevid.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2djmbqbzg.html

TS:   [...arr];
来源：http://dali.meibo888.top/Article/details/gt2giwvnigw.html

Java: new ArrayList<>(list);
来源：http://dali.meibo888.top/Article/details/gt2xuurackn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gt2ydxjgayu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tanke756.top/Article/details/gt2zqotrctk.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gt2nzrlowng.html

[D23] reduce 累积计算
来源：http://dali.ydzc1.top/Article/details/gt2tyqemqgx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnqzz.top/Article/details/gt2cnxsmeyz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jianghu66.top/Article/details/gt2kxqkjyca.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2uxlnktqr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2fnocpmol.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tianlin.xyz/Article/details/gt2alarvzkl.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gt2mnhawokj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gt2itzzedzv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gt2mdeujxln.html

[D24] 字典 / Map 基本操作
来源：http://dali.ivvv.top/Article/details/gt2cpqprtdc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shuidangran.top/Article/details/gt2fftrjqax.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2rsushpof.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gt2jyzvtcyt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2xlebvbsy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ivvv.top/Article/details/gt2pjlmncsm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xziqi.cn/Article/details/gt2ligjkvfp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ppmqmchu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhongyouzk.top/Article/details/gt2hnrewfyj.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bohfuuho.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cqqwz.cn/Article/details/gt2ojmzxdbe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xziqi.cn/Article/details/gt2jfzpmpsy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gt2tgxqhbwk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shzxlz.cn/Article/details/gt2nwawxvuf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangdashe.top/Article/details/gt2mlbvnuta.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xziqi.cn/Article/details/gt2oaqldpqi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2fvtxrpiy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yangfankeji.com/Article/details/gt2curegslu.html

[D26] 数组转字符串
来源：http://dali.yj20258888.top/Article/details/gt2vdldgell.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guannengcc.top/Article/details/gt2xtlkgtqx.html

PHP:  implode(", ", $arr);
来源：http://dali.zycfv.cn/Article/details/gt2nvoeopao.html

JS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gt2zluuilzl.html

TS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gt2oyxaaeyj.html

Java: String.join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gt2kjbgnmws.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gt2yahwgkas.html

Ruby: arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2jfhsufbj.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gt2ktqhgeko.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2arhndqad.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuqksud.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvkkmpua.html

[E01] 拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gt2vpvjnwud.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sweek.top/Article/details/gt2ghwafdxt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gt2xnffhviz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gt2xceskjog.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2tiasioof.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.vqdsnc.cn/Article/details/gt2bukgwotq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fengsongda.top/Article/details/gt2fijjwzxj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yangfankeji.com/Article/details/gt2fjaamxba.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2rvigiqdb.html

[E02] 重复字符串
来源：http://dali.sysykeji.top/Article/details/gt2sgrctyyv.html

Py:   "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gt2ytnkqzkz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ehwqpu.com/Article/details/gt2zcdpfolb.html

JS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gt2qktdwwul.html

TS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gt2lyoovhor.html

Java: "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gt2mszyceax.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2khlrqyfn.html

Ruby: "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gt2exepqcqo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tanke756.top/Article/details/gt2xyyiqzml.html

[E03] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gt2fggemfzv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fzhhl.top/Article/details/gt2qmkmwqgr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2ojrangau.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gt2rgqobtli.html

TS:   s.slice(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2fcjmjoyj.html

Java: s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gt2sovmagwu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2tphtpkns.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pengpengdd.cyou/Article/details/gt2yutfiknt.html

C#:   s.Substring(1, 3)
来源：http://dali.hammf.cn/Article/details/gt2zqqmqrac.html

[E04] 查找子串位置
来源：http://dali.yongpay.top/Article/details/gt2rheqiwou.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sysykeji.top/Article/details/gt2umuuuhmb.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixcjmewb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yanxiufei.cn/Article/details/gt2dodlvngj.html

TS:   s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gt2kiooesgg.html

Java: s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gt2yhksorex.html

Go:   strings.Index(s, "x")
来源：http://dali.jiagoushi.top/Article/details/gt2svaokdxp.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbygtdz.html

C#:   s.IndexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ojcitfww.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.316326.xyz/Article/details/gt2vwktlwuc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2hqsrjljj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sxryk.cn/Article/details/gt2avbojrvv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gt2zwbokgyi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fzhhl.top/Article/details/gt2cydsopbr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xuxkuzzv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.svipenyu.cn/Article/details/gt2rfshywcp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2adjhmgeq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gayvkdnv.html

[E06] 替换子串
来源：http://dali.sxryk.cn/Article/details/gt2soeismgd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gt2joinrgba.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nwbrower.top/Article/details/gt2qsvmhtta.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2dsbjwwom.html

TS:   s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2rkpzinio.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2dbfkexeh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2osnqsrsx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wevtyivm.html

C#:   s.Replace("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2rzuzokik.html

[E07] 按分隔符拆分
来源：http://dali.jqgfzy.top/Article/details/gt2secyfngl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yangfankeji.com/Article/details/gt2nookhvkq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2vtxhhlta.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gt2kecjgbiw.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2jbmcpifa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258888.top/Article/details/gt2nwxgwkrz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.9152youxi.cn/Article/details/gt2fmsxiplm.html

Ruby: s.split(",");  s.split
来源：http://dali.cashguo.top/Article/details/gt2envzthqr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hfpthk.cn/Article/details/gt2wuyxgdio.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigufen.top/Article/details/gt2mmsinnjv.html

Py:   ",".join(items)
来源：http://dali.smart0.xyz/Article/details/gt2ffmhfmsv.html

PHP:  implode(",", $items);
来源：http://dali.daria6918.cn/Article/details/gt2zumuhnlu.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2gvccqkpa.html

TS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gt2oznojvgu.html

Java: String.join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gt2oujxofdq.html

Go:   strings.Join(items, ",")
来源：http://dali.andypj.xyz/Article/details/gt2ihqairwj.html

Ruby: items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgdojrew.html

C#:   string.Join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gt2xsefqori.html

[E09] 去除所有空白字符
来源：http://dali.tian-w.cn/Article/details/gt2jtydlwhh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuxming.cn/Article/details/gt2xzsaqapb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2kgspadeu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dihvrnqk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gt2wzuwweky.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gt2tgwrwslq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.quarkkingdee.top/Article/details/gt2zcipueiw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guannengcc.top/Article/details/gt2phefjsmu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gt2wgoqlzjq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.316326.xyz/Article/details/gt2ibezzepv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2dufuvyzt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sxryk.cn/Article/details/gt2lpqpudts.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gt2yoqffwht.html

TS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2qwvmbklc.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iaijixju.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gt2zicssnzn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jllmtben.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hywenlv.cn/Article/details/gt2xtranuhv.html

[E11] 反转字符串
来源：http://dali.dianchejie.cn/Article/details/gt2sonnvfga.html

Py:   s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gt2chrdfsua.html

PHP:  strrev($s);
来源：http://dali.gzhubu.top/Article/details/gt2xancahrh.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2bjqvbvhx.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2ggrcxqkp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.0kj1m.cn/Article/details/gt2zknyvqkn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2lpdfrggj.html

Ruby: s.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2gohipgho.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gt2xmwmmvfl.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gt2fuoibkmz.html

Py:   s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2mpmqpxvj.html

PHP:  substr_count($s, "a");
来源：http://dali.nwbrower.top/Article/details/gt2ddrbjche.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fnuscwfs.html

TS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gt2lmxqqazx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yongpay.top/Article/details/gt2ypeypfxx.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxinkj.top/Article/details/gt2quthslnr.html

Ruby: s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2oopqfxrh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gt2phitzpfz.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2srxsodmo.html

Py:   for ch in s: print(ch)
来源：http://dali.havefunace.top/Article/details/gt2wpehpfes.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fzhhl.top/Article/details/gt2ydvibfdj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gt2scaxpcre.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwchslhx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2qwhidpak.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gt2qnnthpyb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgufenzy.top/Article/details/gt2knbbfino.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gt2kjboxfal.html

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gt2swtyrdyr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gt2dfteiwlh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuxming.cn/Article/details/gt2ytndfgfk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aibaodan.cn/Article/details/gt2pqsgvwma.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xziqi.cn/Article/details/gt2hidgdrak.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gt2dtotnbbo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sxryk.cn/Article/details/gt2wjvbvjmc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hfpthk.cn/Article/details/gt2ukvnsten.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daxiang520.top/Article/details/gt2ijkymimh.html

[E15] HTML 转义 / 反转义
来源：http://dali.hysaishi.cn/Article/details/gt2pizuhysb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cashguo.top/Article/details/gt2oqhvdxel.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2yompuphz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cdnleiting.top/Article/details/gt2qsecqdgd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2gzbekfmv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gt2enooszpp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gt2qkfrwzki.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxinkj.top/Article/details/gt2tocupvkn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daxiang520.top/Article/details/gt2ereyznel.html

[E16] 数字千分位
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xwsnwxne.html

Py:   f"{1234567:,}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2adyiyhng.html

PHP:  number_format(1234567);
来源：http://dali.cdnleiting.top/Article/details/gt2pyshcbsu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gt2hjxoeqtw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gt2twmhccio.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gt2yzdkiwoc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jianghu66.top/Article/details/gt2bfaifqqs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.birdmap.top/Article/details/gt2zpjfzvim.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gt2glmgcvqj.html

[E17] 首字母大写
来源：http://dali.haohaochexian.top/Article/details/gt2ipcqzkai.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258888.top/Article/details/gt2coxngdse.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2wjiifdys.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gt2hyhctxvy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gt2qavdatwi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gt2kndwkrsl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2cwmffnpy.html

Ruby: s.capitalize
来源：http://dali.yj202588.top/Article/details/gt2axycfgva.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daria6918.cn/Article/details/gt2elbrzspt.html

[E18] 模板占位符替换
来源：http://dali.yonumen.top/Article/details/gt2flhdfhxo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zycfv.cn/Article/details/gt2mrshfswv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwecytzs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2pvizosor.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gt2tcnjppvc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2amanygne.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gt2nzuqfxtl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gt2mratlnqq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.birdmap.top/Article/details/gt2stuwavsd.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gt2okxaqtll.html

Py:   s.splitlines()
来源：http://dali.quarkkingdee.top/Article/details/gt2pfjlgfxr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2dfwfinaw.html

JS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gt2iydexbas.html

TS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gt2ihiwuqhd.html

Java: s.lines().toList()
来源：http://dali.birdmap.top/Article/details/gt2ngbgqnji.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdzmqkto.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gt2udxymlub.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gt2srpurnci.html

[E20] 判断字符串是否为空
来源：http://dali.cdnleiting.top/Article/details/gt2yfwkxtfj.html

Py:   if not s:
来源：http://dali.yj202588.top/Article/details/gt2hlpxghul.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenzaomai.com/Article/details/gt2jqpzjrod.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fzhhl.top/Article/details/gt2rqbzueqt.html

TS:   if (s === "") {}
来源：http://dali.yanxiufei.cn/Article/details/gt2iayfqosf.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tfoahvph.html

Go:   if s == "" {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2nbcodced.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gt2rabihdpx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gt2fntbfgqx.html

[E21] 超长截断加省略号
来源：http://dali.wangshuangyany.cn/Article/details/gt2htmrjzxz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ehwqpu.com/Article/details/gt2qkhlpblr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gt2dayighao.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2smwepxsp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvroicar.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2exzmxlqa.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gt2xwzkqutr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2khullmuy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2eyegeozy.html

[E22] 字节长度与字符长度
来源：http://dali.yvedp.cn/Article/details/gt2mufnvhvo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gt2miziodhr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gt2klifjmli.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gt2llpfwfmg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gt2nlwqbojo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigufen.top/Article/details/gt2aflnhixp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxznfrb.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ptsladqw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dashuyun.cn/Article/details/gt2zsvvtcee.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2enngrwxd.html

F. 文件与目录
来源：http://dali.hywenlv.cn/Article/details/gt2ymcxemqb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2stvbusfe.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gt2wkpgcsaf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gaohongyu789.top/Article/details/gt2uhspkkbj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efsfbesz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqpdlnnk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2horlpfjq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gt2lokcpiel.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gt2pozgdrpz.html

Ruby: File.read("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2mipfodbr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2cpohnuwx.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gt2rtjgarcc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gt2ayqjjggq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.andypj.xyz/Article/details/gt2yzpgdvbr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gt2njcogzao.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gt2yylbiuwn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pivjxcjw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tuppifco.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gt2rnfkqxsk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhongyouzk.top/Article/details/gt2efysbdmq.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxinkj.top/Article/details/gt2bzznrgec.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gt2jswdncsk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gt2dfucjtbj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qrtajjle.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gt2jotenguv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2cfgqzrfc.html


<!-- 参考信息 -->