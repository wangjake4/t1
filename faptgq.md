代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jianghu66.top/Article/details/gt2vxlvktnu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhiwuduotai.top/Article/details/gt2xoqgkznc.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gt2jmrcwfdz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.0kj1m.cn/Article/details/gt2mtyptref.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnqzz.top/Article/details/gt2qsyohsls.html

[D20] 统计每个元素出现次数
来源：http://dali.0kj1m.cn/Article/details/gt2vrudzqfq.html

Py:   Counter(arr)
来源：http://dali.andypj.xyz/Article/details/gt2lmvwcnwx.html

PHP:  array_count_values($arr);
来源：http://dali.cheryme.top/Article/details/gt2xxemoarf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gt2dodidfnj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gt2giznarht.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpmooytr.html

Go:   // 手写 map[T]int
来源：http://dali.yonumen.top/Article/details/gt2jaxliowk.html

Ruby: arr.tally
来源：http://dali.gaohongyu789.top/Article/details/gt2mfpxdesn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gt2ltnvlegb.html

[D21] 判断是否包含某元素
来源：http://dali.bjfxy.top/Article/details/gt2lvkkgaiv.html

Py:   x in arr
来源：http://dali.jqgfzy.top/Article/details/gt2ozpjlfvi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangdashe.top/Article/details/gt2ahdwwqei.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgjnnud.html

TS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2grfrgzuq.html

Java: list.contains(x)
来源：http://dali.wangdashe.top/Article/details/gt2erwfwplu.html

Go:   slices.Contains(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2uynyyavm.html

Ruby: arr.include?(x)
来源：http://dali.birdmap.top/Article/details/gt2blynbcdz.html

C#:   list.Contains(x)
来源：http://dali.dianchejie.cn/Article/details/gt2oqpmnphc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gt2ttsedyrl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2kbfezpvl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sweek.top/Article/details/gt2lgramnbx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dkkcqeuf.html

TS:   [...arr];
来源：http://dali.jqgufenzy.top/Article/details/gt2kowdudvb.html

Java: new ArrayList<>(list);
来源：http://dali.0kj1m.cn/Article/details/gt2yziwkgbs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pycfn.com/Article/details/gt2wpuexhvx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnxiangtu.top/Article/details/gt2nopybsgf.html

C#:   new List<int>(list);
来源：http://dali.hnqzz.top/Article/details/gt2okgdrpjw.html

[D23] reduce 累积计算
来源：http://dali.gogol.net.cn/Article/details/gt2gpdtuqvc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daria6918.cn/Article/details/gt2rlmurqpj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2ikktrnoe.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gt2xchufhrd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gt2yovgylwv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gt2osczifla.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gt2rrmcbuxo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tian-w.cn/Article/details/gt2dumnctpp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vyrrdwih.html

[D24] 字典 / Map 基本操作
来源：http://dali.xziqi.cn/Article/details/gt2ankrwhca.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.c1oappe.top/Article/details/gt2baokrdmm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gt2kbvxwlzb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnqzz.top/Article/details/gt2pitlqakl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2kncjfwdc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj202588.top/Article/details/gt2nzqblkjn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ehwqpu.com/Article/details/gt2whulmvmp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gt2pryuqeew.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuetiantiany.cn/Article/details/gt2shammhya.html

[D25] Set 集合去重与交并差
来源：http://dali.jiagoushi.top/Article/details/gt2tryqqmys.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gt2eofqkidg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuanzhike.top/Article/details/gt2rxjouict.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yangfankeji.com/Article/details/gt2mgsjvfvv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhongyouzk.top/Article/details/gt2fbppdzvd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gt2qdbivapw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sweek.top/Article/details/gt2yscvoipw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuanzhike.top/Article/details/gt2ktfraxnl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guowangkeji.top/Article/details/gt2oczkapoh.html

[D26] 数组转字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2xrbegrzo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2qspkwzzf.html

PHP:  implode(", ", $arr);
来源：http://dali.yongpay.top/Article/details/gt2ycbmzsxv.html

JS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gt2lqqtksih.html

TS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2tsvocghn.html

Java: String.join(", ", list)
来源：http://dali.hfpthk.cn/Article/details/gt2jfumdkoi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yonumen.top/Article/details/gt2fqsxazxa.html

Ruby: arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gt2lutomxpn.html

C#:   string.Join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjtlfidc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2krzfbnin.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gt2krumwfsm.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2navhfslm.html

[E01] 拼接字符串
来源：http://dali.fzhhl.top/Article/details/gt2favfdsrm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gt2ryanmrts.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hfpthk.cn/Article/details/gt2bpjkjqhe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gt2jngumybn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gt2eptvzvox.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nwbrower.top/Article/details/gt2hoebqail.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dashuyun.cn/Article/details/gt2kqvdyxrv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxuanxn.top/Article/details/gt2ynkzlzmn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2dwktrlgd.html

[E02] 重复字符串
来源：http://dali.ppjwa.cn/Article/details/gt2vlurkact.html

Py:   "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gt2smmotbaa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uohdmaxl.html

JS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gt2yyztfnbd.html

TS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gt2ajeiuiqn.html

Java: "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2igwqgujz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ydzc1.top/Article/details/gt2uhsxzmax.html

Ruby: "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gt2peezhvef.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rgfcakwp.html

[E03] 截取子串
来源：http://dali.yvedp.cn/Article/details/gt2vqddnkud.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cheryme.top/Article/details/gt2mgjmjjky.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gt2smsctoat.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2eprcrdbg.html

TS:   s.slice(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vhtpepww.html

Java: s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gt2ooskijfa.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2socmbzea.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ivvv.top/Article/details/gt2efkqjlxs.html

C#:   s.Substring(1, 3)
来源：http://dali.sufxvd.cn/Article/details/gt2wlilsjik.html

[E04] 查找子串位置
来源：http://dali.cucudq.cn/Article/details/gt2rpbwsxxw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gt2dwpdbiix.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gt2eijvccth.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gt2phnpjjqg.html

TS:   s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gt2czumhyku.html

Java: s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gt2tucysrxe.html

Go:   strings.Index(s, "x")
来源：http://dali.jlsjyb.cn/Article/details/gt2oycblzin.html

Ruby: s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gt2xksjovoz.html

C#:   s.IndexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2bnhjhnmf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pengpengdd.cyou/Article/details/gt2kiuhzezo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tian-w.cn/Article/details/gt2cqvprckf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dashuyun.cn/Article/details/gt2izscovsj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2yevgblmz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aizwys.cn/Article/details/gt2echkieyt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2zxapeejg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jiagoushi.top/Article/details/gt2eqsxvhev.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2eftuojcu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2vqhfkztx.html

[E06] 替换子串
来源：http://dali.jiagoushi.top/Article/details/gt2wiuisgnu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xtevdfea.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2qdrkfxei.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2vxpljcjr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2xjnsklks.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2saoxxead.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uklpiuwr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2cxhcnojf.html

C#:   s.Replace("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2vvbbwxgm.html

[E07] 按分隔符拆分
来源：http://dali.dianchejie.cn/Article/details/gt2lycatmxb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjsgnela.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2evykhgwi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pycfn.com/Article/details/gt2emrakfei.html

TS:   s.split(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2ucvjjzmv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cucudq.cn/Article/details/gt2facviubi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgfzy.top/Article/details/gt2iurpohms.html

Ruby: s.split(",");  s.split
来源：http://dali.cqqwz.cn/Article/details/gt2hwersusn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gt2vwqwbjda.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gt2kcwgrsaz.html

Py:   ",".join(items)
来源：http://dali.shzxlz.cn/Article/details/gt2atiuhxuz.html

PHP:  implode(",", $items);
来源：http://dali.sxryk.cn/Article/details/gt2ocxazhgz.html

JS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2mwwdaqyn.html

TS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gt2xgymakjm.html

Java: String.join(",", items)
来源：http://dali.meibo888.top/Article/details/gt2cbxskdhd.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gt2eikontbl.html

Ruby: items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gt2ofshhmyp.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2famdijbz.html

[E09] 去除所有空白字符
来源：http://dali.ydzc1.top/Article/details/gt2upzkldwg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yueranfly.top/Article/details/gt2pwqokape.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2glupnncb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gt2qpiqvvak.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gt2glsdykqg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zxmndars.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gogol.net.cn/Article/details/gt2cybpzids.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.redwolf501.top/Article/details/gt2pvtstbbq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangdashe.top/Article/details/gt2suiowhhw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yongpay.top/Article/details/gt2zhxjlhgh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gt2tedmmcuq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aizwys.cn/Article/details/gt2wngmdbkz.html

JS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gt2rnuaqrvj.html

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gt2tevtgqqt.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gt2gfyqfgfo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gt2wrrcvsjl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2kuzuzphd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gt2otcsicjg.html

[E11] 反转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uyxphmxh.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gt2xgcllvnm.html

PHP:  strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gt2hfylsjqz.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcylcft.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2exvoxogp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tianlin.xyz/Article/details/gt2eeqobzyh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.9152youxi.cn/Article/details/gt2taudfqxa.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gt2sdgicdbk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gt2yqrimvjb.html

[E12] 统计某字符出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gt2riwvbrpy.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gt2mgdxfxlf.html

PHP:  substr_count($s, "a");
来源：http://dali.yonumen.top/Article/details/gt2mdayrvie.html

JS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gt2lettzcgh.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxgrkwcp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hywenlv.cn/Article/details/gt2osqudfsq.html

Go:   strings.Count(s, "a")
来源：http://dali.dianchejie.cn/Article/details/gt2ncdtchle.html

Ruby: s.count("a")
来源：http://dali.fengsongda.top/Article/details/gt2wzclhqxl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gt2xyhhiepv.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gt2znhseblb.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gt2kcpudnxd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.andypj.xyz/Article/details/gt2nvljcumb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gt2pwccxcbw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gt2ippbsifg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gt2cmvqwnko.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2mnyimele.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnqzz.top/Article/details/gt2jawfyeji.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gt2uskgiwyn.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigufen.top/Article/details/gt2cdbbfzqt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.andypj.xyz/Article/details/gt2mmtmewnt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.iojbl.cn/Article/details/gt2vrqwjqab.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sufxvd.cn/Article/details/gt2hwcxkilz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gt2fqyqcqqn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.316326.xyz/Article/details/gt2narbaufa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ivvv.top/Article/details/gt2aeizyiab.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pycfn.com/Article/details/gt2jtgfxabo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shzxlz.cn/Article/details/gt2smsbabkb.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuanzx.com/Article/details/gt2vvwvcjkn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tianlin.xyz/Article/details/gt2fdljmssv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2opsakcxz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bzhxkcue.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gt2evbvmtbu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cdnleiting.top/Article/details/gt2uhqcvtvl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cucudq.cn/Article/details/gt2vtiffpwn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj202588.top/Article/details/gt2itlgjycb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2xzdggjaa.html

[E16] 数字千分位
来源：http://dali.jinqigufen.top/Article/details/gt2dgvmktkc.html

Py:   f"{1234567:,}"
来源：http://dali.bjfxy.top/Article/details/gt2sdaydozr.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hzpvutec.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gt2xlekbiok.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gt2cojjjxns.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tian-w.cn/Article/details/gt2mcudbnkv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hammf.cn/Article/details/gt2wpgygpun.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jyoumei.cn/Article/details/gt2txbvclwf.html

C#:   1234567.ToString("N0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hmhfwimo.html

[E17] 首字母大写
来源：http://dali.jinqigufen.top/Article/details/gt2znmhlesr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.c1oappe.top/Article/details/gt2urvdkoee.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gt2tkwgpcdu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tixelejb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gt2srljksxf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2ddtlbojf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gt2vhqsbvxp.html

Ruby: s.capitalize
来源：http://dali.mhx1999.top/Article/details/gt2nwjdkppp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yangfankeji.com/Article/details/gt2pkivuqjz.html

[E18] 模板占位符替换
来源：http://dali.hfpthk.cn/Article/details/gt2cpyycjug.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gt2kftuzsdk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jyoumei.cn/Article/details/gt2cwscluxp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2wrhfjzki.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2jovlbhea.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yypfodjp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vbjgiqjw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gotoacloud.top/Article/details/gt2rsnmywft.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aizwys.cn/Article/details/gt2lswnwinc.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gt2nwnsvbkk.html

Py:   s.splitlines()
来源：http://dali.jqgufenzy.top/Article/details/gt2ykomjvcx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2zjhkquor.html

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gt2fufdktfq.html

TS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gt2diuxmxfd.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekgzfidz.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2fdwoyfgc.html

Ruby: s.lines
来源：http://dali.yj20258888.top/Article/details/gt2ljhirmlg.html

C#:   s.Split('\n')
来源：http://dali.cqqwz.cn/Article/details/gt2rivagdgr.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gt2rcxctbsf.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gt2yqtkvrzp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenlongwang.top/Article/details/gt2cljzbyjl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gogol.net.cn/Article/details/gt2aqrvtsnu.html

TS:   if (s === "") {}
来源：http://dali.meibo888.top/Article/details/gt2avqqbnuj.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gt2isoerlqt.html

Go:   if s == "" {}
来源：http://dali.haohaochexian.top/Article/details/gt2wcqmgptu.html

Ruby: if s.empty?
来源：http://dali.jlsjyb.cn/Article/details/gt2mygpdrco.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2putyaycb.html

[E21] 超长截断加省略号
来源：http://dali.yongpay.top/Article/details/gt2tslolhih.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gt2dmymdnqo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gt2kegsxzqn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2njbscmyu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2ftskxeok.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2ijbgufni.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenzaomai.com/Article/details/gt2nzumhkio.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2pbfpgsyp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2pndnhnln.html

[E22] 字节长度与字符长度
来源：http://dali.shzxlz.cn/Article/details/gt2adiklyul.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gt2cxialhem.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gt2kctmgkne.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2qubvylgx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2mytntyek.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sufxvd.cn/Article/details/gt2ypbofmzv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gt2ezejrvlc.html

Ruby: s.bytesize;  s.length
来源：http://dali.pycfn.com/Article/details/gt2towvjyzu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qmccihrk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2geerkphi.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gt2lxuatuia.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2bvcdfeah.html

[F01] 读取整个文件
来源：http://dali.iojbl.cn/Article/details/gt2ulookejq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gt2cdfdbfos.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2uxmdyphm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sweek.top/Article/details/gt2exopvvpu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gt2sxzaorrx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2oswalgzx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nwbrower.top/Article/details/gt2ltqorhxz.html

Ruby: File.read("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2hhtwbbro.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2rgcoyeor.html

[F02] 逐行读取文件
来源：http://dali.redwolf501.top/Article/details/gt2jfoigxnn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gt2biaetkwf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aibaodan.cn/Article/details/gt2jmmmtxrh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2czitiywd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkbtbmhk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gt2eyzafqxz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gt2xbztlpvh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigfzy.top/Article/details/gt2wbexvdcd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydllzzow.html

[F03] 写入文件（覆盖）
来源：http://dali.shzxlz.cn/Article/details/gt2ltysqprh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hywenlv.cn/Article/details/gt2qcylbvyv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxvqbsua.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqumpdye.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gt2snvnkfag.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.bjfxy.top/Article/details/gt2ziddvhcr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tanke756.top/Article/details/gt2xxnggiub.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258.top/Article/details/gt2sovjkflr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2pfdocksk.html

[F04] 追加写入文件
来源：http://dali.pycfn.com/Article/details/gt2nfatxayx.html


<!-- 参考信息 -->