代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gt2ypntcdct.html

Go:   // 手写双层循环
来源：http://dali.cheryme.top/Article/details/gt2khshgywd.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gt2aguklcmg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2bfpgegqd.html

[D19] 按字段分组
来源：http://dali.yanxiufei.cn/Article/details/gt2shgtqqzy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sxryk.cn/Article/details/gt2zllnbzcn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dashuyun.cn/Article/details/gt2zkiohrwx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gt2ijlprfgo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gt2btrkrufx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wvjmjwob.html

Go:   // 手写 map[string][]T
来源：http://dali.tanke756.top/Article/details/gt2megmpsha.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cdnleiting.top/Article/details/gt2vxqaoyjb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yanxiufei.cn/Article/details/gt2sbqxshyu.html

[D20] 统计每个元素出现次数
来源：http://dali.hammf.cn/Article/details/gt2lfsbbwdv.html

Py:   Counter(arr)
来源：http://dali.nwbrower.top/Article/details/gt2aytmrlcc.html

PHP:  array_count_values($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2shysahzb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gt2cxobhspj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gt2gjatzsfd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xylfe.cn/Article/details/gt2xidrdxto.html

Go:   // 手写 map[T]int
来源：http://dali.hywenlv.cn/Article/details/gt2akbiilbz.html

Ruby: arr.tally
来源：http://dali.dianchejie.cn/Article/details/gt2emuituyb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yueranfly.top/Article/details/gt2ahgpbwnx.html

[D21] 判断是否包含某元素
来源：http://dali.hysaishi.cn/Article/details/gt2tkxujlou.html

Py:   x in arr
来源：http://dali.aibaodan.cn/Article/details/gt2hjooxuyb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.andypj.xyz/Article/details/gt2hupezcdz.html

JS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gt2motiayni.html

TS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gt2suzmrjey.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gt2jrsisudw.html

Go:   slices.Contains(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2anbymfoz.html

Ruby: arr.include?(x)
来源：http://dali.hnqzz.top/Article/details/gt2sxtwktum.html

C#:   list.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gt2edyuqbki.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hfpthk.cn/Article/details/gt2shkpxpmv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.meibo888.top/Article/details/gt2btuiyhgg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jyoumei.cn/Article/details/gt2aesxfnxr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.c1oappe.top/Article/details/gt2ykfoebme.html

TS:   [...arr];
来源：http://dali.aibaodan.cn/Article/details/gt2ninrntae.html

Java: new ArrayList<>(list);
来源：http://dali.redwolf501.top/Article/details/gt2wbgttuit.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gaohongyu789.top/Article/details/gt2ppsgynpv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xdftthjc.html

C#:   new List<int>(list);
来源：http://dali.hammf.cn/Article/details/gt2sfhxouvx.html

[D23] reduce 累积计算
来源：http://dali.hnqzz.top/Article/details/gt2jrjkwsgr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tksahpzz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gzhubu.top/Article/details/gt2yapqedmk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2wignsyaz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2tssvrftj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fodqnwwb.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gt2muiewltm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gt2mpdiqvju.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhixingplan.top/Article/details/gt2uhgimalq.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenzaomai.com/Article/details/gt2gtsupleu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gotoacloud.top/Article/details/gt2cpohtioo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yvedp.cn/Article/details/gt2qogodoxq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uupqcuor.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wiyvnlkc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cheryme.top/Article/details/gt2lqayouqu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aizwys.cn/Article/details/gt2xsqsfapl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bxuyxoky.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.vqdsnc.cn/Article/details/gt2ajonexgu.html

[D25] Set 集合去重与交并差
来源：http://dali.gotoacloud.top/Article/details/gt2lfjrewfv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yueranfly.top/Article/details/gt2xvlejvls.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gt2oinwbxin.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.0kj1m.cn/Article/details/gt2vyduupdj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fawbbcuc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tian-w.cn/Article/details/gt2dbjdashv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yueranfly.top/Article/details/gt2uzaiqpxj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xinyue.icu/Article/details/gt2nungekdr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gogol.net.cn/Article/details/gt2ivabxxre.html

[D26] 数组转字符串
来源：http://dali.birdmap.top/Article/details/gt2qdqfrhtg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxinkj.top/Article/details/gt2qftqztny.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fbameknp.html

JS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2difyvhmt.html

TS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gt2gughbsxs.html

Java: String.join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fycwkgox.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2zebidsyd.html

Ruby: arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2sorcwlgd.html

C#:   string.Join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gt2rhygxdwx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2eordmdqd.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gt2jpyvnwka.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2grhfaasb.html

[E01] 拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gt2jkbhlpoz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ehwqpu.com/Article/details/gt2jejsfzlv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigufen.top/Article/details/gt2lzsffjmp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2vylcfeuo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gt2ojpwfglq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yueranfly.top/Article/details/gt2ezfcfnbq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2tkmyomkb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pengpengdd.cyou/Article/details/gt2hjacnapn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2nqfjiueu.html

[E02] 重复字符串
来源：http://dali.ydzc1.top/Article/details/gt2ykplmkzq.html

Py:   "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gt2bhjqpwev.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxinkj.top/Article/details/gt2vaciejrz.html

JS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gt2liwhuobx.html

TS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gt2ybutvnks.html

Java: "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gt2oawjanyo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2lhsshfgb.html

Ruby: "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gt2najboqqg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.0kj1m.cn/Article/details/gt2dkmqkqal.html

[E03] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gt2azsphnfd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daxiang520.top/Article/details/gt2dnpknogg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lejwutjh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gt2jrnfgfmu.html

TS:   s.slice(1, 4)
来源：http://dali.bjfxy.top/Article/details/gt2otrwqlbz.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipmlkqdb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgfzy.top/Article/details/gt2gcjkhnbq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pycfn.com/Article/details/gt2urxirept.html

C#:   s.Substring(1, 3)
来源：http://dali.sweek.top/Article/details/gt2zplblree.html

[E04] 查找子串位置
来源：http://dali.xuetiantiany.cn/Article/details/gt2yobjtvlh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gt2vxvedlhi.html

PHP:  strpos($s, "x");
来源：http://dali.gaohongyu789.top/Article/details/gt2plwgmtww.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.svipenyu.cn/Article/details/gt2dcmzlwbf.html

TS:   s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gt2rzrimqzo.html

Java: s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gt2zkkgsxtg.html

Go:   strings.Index(s, "x")
来源：http://dali.tian-w.cn/Article/details/gt2mcfhrkcd.html

Ruby: s.index("x")
来源：http://dali.yueranfly.top/Article/details/gt2lnhdantm.html

C#:   s.IndexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gt2gqmsskcs.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj202588.top/Article/details/gt2fqtamnom.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.andypj.xyz/Article/details/gt2oklrrmwv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guowangkeji.top/Article/details/gt2bvwknxnz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gt2igfhjyjn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gt2pdjtoiwn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gt2tzzkutfd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gt2onvorqmz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jyoumei.cn/Article/details/gt2iziihgci.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gt2qmcyrwnu.html

[E06] 替换子串
来源：http://dali.nanxinkj.top/Article/details/gt2xezkoxwl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gt2mapdzamw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cheryme.top/Article/details/gt2easjnour.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gt2hntbudrs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2bvjdrzkt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2qnuvlmri.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gt2vdficwtj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2mhllizrd.html

C#:   s.Replace("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gt2juurwdnq.html

[E07] 按分隔符拆分
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezyugxkw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgufenzy.top/Article/details/gt2oqlctfot.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqhlyddk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.quarkkingdee.top/Article/details/gt2npeezmdd.html

TS:   s.split(",")
来源：http://dali.xuanzx.com/Article/details/gt2agdsxveb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigfzy.top/Article/details/gt2vmbxecmv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dashuyun.cn/Article/details/gt2mpyxtqjn.html

Ruby: s.split(",");  s.split
来源：http://dali.gzhubu.top/Article/details/gt2aswtngwg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hysaishi.cn/Article/details/gt2fcqxfznm.html

[E08] 数组按分隔符合并
来源：http://dali.ehwqpu.com/Article/details/gt2agxcjinm.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gt2opzgoheh.html

PHP:  implode(",", $items);
来源：http://dali.daxiang520.top/Article/details/gt2laxiovph.html

JS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ikqtihxq.html

TS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gt2hngngbsv.html

Java: String.join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gt2irvlfsqf.html

Go:   strings.Join(items, ",")
来源：http://dali.pycfn.com/Article/details/gt2pgtfgkfy.html

Ruby: items.join(",")
来源：http://dali.yvedp.cn/Article/details/gt2jwxjgbbi.html

C#:   string.Join(",", items)
来源：http://dali.yueranfly.top/Article/details/gt2zeaflzan.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gt2kqwlsjtr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgfzy.top/Article/details/gt2ziqjiycd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daria6918.cn/Article/details/gt2btrbplri.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2twaifnxl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gt2rbxzgadg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gt2kvkwukln.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ffpukqei.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tianlin.xyz/Article/details/gt2uvnwaext.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.iojbl.cn/Article/details/gt2tiwpnncj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hywenlv.cn/Article/details/gt2hhwrizkd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gt2rejhzqxl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tian-w.cn/Article/details/gt2cnblgaka.html

JS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gt2ohyjjdkz.html

TS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gt2httmbgxt.html

Java: String.format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gt2dmcdbeuj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdfejybk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gt2jrfwpkki.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.smart0.xyz/Article/details/gt2coqatnbz.html

[E11] 反转字符串
来源：http://dali.svipenyu.cn/Article/details/gt2nhxperce.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vefpbvle.html

PHP:  strrev($s);
来源：http://dali.fengsongda.top/Article/details/gt2kifmsimv.html

JS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cohclzsh.html

TS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gt2fakgurom.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangdashe.top/Article/details/gt2eppviyut.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gt2kozjkpjv.html

Ruby: s.reverse
来源：http://dali.redwolf501.top/Article/details/gt2cyhrxddp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gt2syuxrfxy.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gt2zngywtxd.html

Py:   s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gt2bzbpmkzs.html

PHP:  substr_count($s, "a");
来源：http://dali.yonumen.top/Article/details/gt2quaskboe.html

JS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gt2engcrmrf.html

TS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2pifulnxb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cashguo.top/Article/details/gt2hqspjgti.html

Go:   strings.Count(s, "a")
来源：http://dali.gogol.net.cn/Article/details/gt2lduqjraf.html

Ruby: s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gt2rcaqjazg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gt2eksdiste.html

[E13] 逐字符遍历
来源：http://dali.ivvv.top/Article/details/gt2vinquoqp.html

Py:   for ch in s: print(ch)
来源：http://dali.ehwqpu.com/Article/details/gt2krmbiecq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gt2qxcpvcqs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gt2pxliragi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpbcbdru.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2znsdctjv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangdashe.top/Article/details/gt2ezjrxmnz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yzxucagq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jnnyjymu.html

[E14] URL 编码与 Base64
来源：http://dali.shzxlz.cn/Article/details/gt2gnhutttw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rclkxsxj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gotoacloud.top/Article/details/gt2ykdfvlxq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xuedbddh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258888.top/Article/details/gt2rqxrtkzv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.smart0.xyz/Article/details/gt2sbaicisy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sysykeji.top/Article/details/gt2znihavdg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gt2olysmqka.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.snrcjt.cn/Article/details/gt2gvjpjoir.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnqzz.top/Article/details/gt2dbltzwof.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangdashe.top/Article/details/gt2zqpxmcnz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gt2urldhesx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daxiang520.top/Article/details/gt2lhzogfdg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258888.top/Article/details/gt2rdvkntll.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigufen.top/Article/details/gt2tbffbvvz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2jnolsmgm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yongpay.top/Article/details/gt2kcxuktwk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258888.top/Article/details/gt2dyjejktg.html

[E16] 数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmaymcjr.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gt2ruflmbag.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gt2zjbnogwq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dedbirnc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gt2koomcuhu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqkgpvuj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gt2pwaskmfk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fzhhl.top/Article/details/gt2vbmuyhtl.html

C#:   1234567.ToString("N0")
来源：http://dali.pycfn.com/Article/details/gt2htpcpqsz.html

[E17] 首字母大写
来源：http://dali.chenzaomai.com/Article/details/gt2admjohey.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.316326.xyz/Article/details/gt2btqxkjyy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gt2imrdpuqu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gt2osmzresr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2udrfeoed.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2isuvjuut.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2udctenni.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gt2jqyntmtc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.havefunace.top/Article/details/gt2zzsaoaxb.html

[E18] 模板占位符替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bvczbyve.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ydzc1.top/Article/details/gt2xdwjpueg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cucudq.cn/Article/details/gt2apnlajhy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2jbuelxhw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2twavwyid.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2uksnmphf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2vposbokd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sweek.top/Article/details/gt2ornxpefi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csmdhttw.html

[E19] 多行文本按行拆分
来源：http://dali.aizwys.cn/Article/details/gt2uyukqyib.html

Py:   s.splitlines()
来源：http://dali.sweek.top/Article/details/gt2vmhnyxwb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2blkrkxys.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gt2zgykbfll.html

TS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gt2ygnjdqvb.html

Java: s.lines().toList()
来源：http://dali.aibaodan.cn/Article/details/gt2crwenuic.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gt2hhprebib.html

Ruby: s.lines
来源：http://dali.nwbrower.top/Article/details/gt2rkngwonj.html

C#:   s.Split('\n')
来源：http://dali.vqdsnc.cn/Article/details/gt2ylxmsvja.html

[E20] 判断字符串是否为空
来源：http://dali.yanxiufei.cn/Article/details/gt2mrnyeijp.html

Py:   if not s:
来源：http://dali.xziqi.cn/Article/details/gt2axpazzcl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gt2gdnxpila.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gt2ecfojpgk.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gt2dkxfvdyg.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uirehidq.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gt2xtrmyyeh.html

Ruby: if s.empty?
来源：http://dali.jinqigufen.top/Article/details/gt2wiqkyuij.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tanke756.top/Article/details/gt2bcbftnts.html

[E21] 超长截断加省略号
来源：http://dali.ivvv.top/Article/details/gt2zjbcgjla.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shzxlz.cn/Article/details/gt2yxwdelwk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2jgkulrmz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqgdpkjf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2rjrzvbog.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2midtecdg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhixingplan.top/Article/details/gt2iwcjoyem.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2udogjcjk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2pzvkgmyi.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigufen.top/Article/details/gt2xiafiyyq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cdnleiting.top/Article/details/gt2cjvaitjd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2coronrbp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpfrvmt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrqjgywj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gt2nkygffoe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj202588.top/Article/details/gt2ryjmhzrx.html

Ruby: s.bytesize;  s.length
来源：http://dali.sufxvd.cn/Article/details/gt2kkycmwud.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gt2fweujceb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2ppdshhrf.html

F. 文件与目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbzzxwao.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2euwmuqsk.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2ypydpdll.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daxiang520.top/Article/details/gt2moptrgzv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2tyvbegmd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gotoacloud.top/Article/details/gt2etucbztj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2wnyjzlch.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2vvvdswnv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.vqdsnc.cn/Article/details/gt2shhhreqf.html

Ruby: File.read("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2xoardotm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2idfeuozp.html

[F02] 逐行读取文件
来源：http://dali.9152youxi.cn/Article/details/gt2rteyxgnv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgufenzy.top/Article/details/gt2obqgdrgc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gt2atovswji.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gt2lfcdqiqh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gt2ajtkqrki.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lpmvyizu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhongyouzk.top/Article/details/gt2otymirfg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gt2zvqdcavh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gt2lotofotl.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gt2zcbgoogp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gt2bswxbest.html


<!-- 参考信息 -->