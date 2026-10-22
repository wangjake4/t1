代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gt2gjtynthl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258.top/Article/details/gt2lfvwwwyf.html

Go:   // 手写 map[string][]T
来源：http://dali.shangyingyoupin.top/Article/details/gt2tfyjuiyr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.meibo888.top/Article/details/gt2arptzenh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigufen.top/Article/details/gt2bnynhzqf.html

[D20] 统计每个元素出现次数
来源：http://dali.pycfn.com/Article/details/gt2tiucnxld.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ulkstqym.html

PHP:  array_count_values($arr);
来源：http://dali.sysykeji.top/Article/details/gt2ydyyfcxb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gt2dvjlnkyd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gt2tizsdqqu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ppjwa.cn/Article/details/gt2himajtqz.html

Go:   // 手写 map[T]int
来源：http://dali.cucudq.cn/Article/details/gt2ntnrndgx.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gt2spglryzx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.quarkkingdee.top/Article/details/gt2uklrqnrj.html

[D21] 判断是否包含某元素
来源：http://dali.hnqzz.top/Article/details/gt2zfemvjxf.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gt2altgbsmo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjeqttgu.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gt2suufkyot.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2uekpseve.html

Java: list.contains(x)
来源：http://dali.redwolf501.top/Article/details/gt2jgxrwjyb.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzmkqmxt.html

Ruby: arr.include?(x)
来源：http://dali.316326.xyz/Article/details/gt2pvqaalle.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2reunjmdh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj202588.top/Article/details/gt2cybyvwsk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xlmilccr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gt2eueecabx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2luoothpc.html

TS:   [...arr];
来源：http://dali.sufxvd.cn/Article/details/gt2rkrfucrn.html

Java: new ArrayList<>(list);
来源：http://dali.gogol.net.cn/Article/details/gt2uesnubkv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gt2qfcnoeag.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tian-w.cn/Article/details/gt2gdpgytxe.html

C#:   new List<int>(list);
来源：http://dali.snrcjt.cn/Article/details/gt2rcxwzwwa.html

[D23] reduce 累积计算
来源：http://dali.ppjwa.cn/Article/details/gt2kcixqvrf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangdashe.top/Article/details/gt2dxsjiski.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.iojbl.cn/Article/details/gt2fnfsyiqn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2vxxmfvls.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2pdwnvnjs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bikeaamj.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gt2vxdzhhei.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhiwuduotai.top/Article/details/gt2xhswootn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.havefunace.top/Article/details/gt2wmyfwwyw.html

[D24] 字典 / Map 基本操作
来源：http://dali.316326.xyz/Article/details/gt2coxgacix.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nwbrower.top/Article/details/gt2xuevqite.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tiymtjaf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigufen.top/Article/details/gt2melvnzfr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ybcxt.top/Article/details/gt2iryprpcq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ydzc1.top/Article/details/gt2vpyjyvgz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fengsongda.top/Article/details/gt2jyqimisl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daria6918.cn/Article/details/gt2dhfxqjwx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rsfqhepw.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gt2lgjpcidi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tian-w.cn/Article/details/gt2axytnqug.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tianlin.xyz/Article/details/gt2xfsqxeru.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.meibo888.top/Article/details/gt2htkvtpal.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuanzx.com/Article/details/gt2djmptlto.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cheryme.top/Article/details/gt2txhbecjz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bpkmjomg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258888.top/Article/details/gt2elcwlnvc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shuidangran.top/Article/details/gt2kcdyfisr.html

[D26] 数组转字符串
来源：http://dali.nanxinkj.top/Article/details/gt2tzfjuxoj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2ukdittct.html

PHP:  implode(", ", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tixctojy.html

JS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2oefkfxki.html

TS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gt2loschntm.html

Java: String.join(", ", list)
来源：http://dali.meibo888.top/Article/details/gt2htpcnqzw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.meibo888.top/Article/details/gt2eixsvsmm.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gt2jsqiefsk.html

C#:   string.Join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pcdtwkxl.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xafuixlv.html

E. 字符串处理
来源：http://dali.redwolf501.top/Article/details/gt2ysworzjk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2ynqhljsp.html

[E01] 拼接字符串
来源：http://dali.sxryk.cn/Article/details/gt2nyndbhkb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gt2luwjmpnm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gt2fnnrglyy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gt2enekwcoo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2imdltaqn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gzhubu.top/Article/details/gt2qfhxbmhc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gogol.net.cn/Article/details/gt2lpbuuutb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sxryk.cn/Article/details/gt2jdnbxubc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aizwys.cn/Article/details/gt2ajlvzfyc.html

[E02] 重复字符串
来源：http://dali.shzxlz.cn/Article/details/gt2oufveiwr.html

Py:   "ab" * 3
来源：http://dali.pycfn.com/Article/details/gt2dtevlmlm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jianghu66.top/Article/details/gt2bugljfbr.html

JS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gt2cbtafrov.html

TS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2sqnbejrp.html

Java: "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gt2cqmmhjxy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzzraln.html

Ruby: "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gt2gyvknfnl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gzhubu.top/Article/details/gt2epxiysez.html

[E03] 截取子串
来源：http://dali.yj202588.top/Article/details/gt2wriedkjx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fengsongda.top/Article/details/gt2ouzovqdo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2cdwhrdbt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gt2jjrhnrmv.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2rolnuaqi.html

Java: s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2zkufhcan.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fzhhl.top/Article/details/gt2ytvwzqrv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhoulong.xyz/Article/details/gt2wqldsqnd.html

C#:   s.Substring(1, 3)
来源：http://dali.fengsongda.top/Article/details/gt2hxfsiqst.html

[E04] 查找子串位置
来源：http://dali.c1oappe.top/Article/details/gt2blkrnxqw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gzhubu.top/Article/details/gt2shztfrsh.html

PHP:  strpos($s, "x");
来源：http://dali.snrcjt.cn/Article/details/gt2lqioirhs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ivvv.top/Article/details/gt2zfqgkycz.html

TS:   s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gt2erqoopni.html

Java: s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gt2tkkrxogv.html

Go:   strings.Index(s, "x")
来源：http://dali.shzxlz.cn/Article/details/gt2lsftbaao.html

Ruby: s.index("x")
来源：http://dali.havefunace.top/Article/details/gt2rcfxuqmp.html

C#:   s.IndexOf("x")
来源：http://dali.yongpay.top/Article/details/gt2mdaqttgy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ppjwa.cn/Article/details/gt2cystzcuy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aibaodan.cn/Article/details/gt2uspduyuw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnxiangtu.top/Article/details/gt2wduuxirr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2xdzuyvag.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangdashe.top/Article/details/gt2lojbmmrr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gt2huybglvy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sysykeji.top/Article/details/gt2iuaaqhsm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gotoacloud.top/Article/details/gt2mytykqat.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gwbxkkaf.html

[E06] 替换子串
来源：http://dali.cucudq.cn/Article/details/gt2hggvvelx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gt2fnmllvow.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dashuyun.cn/Article/details/gt2cibycamu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2jsdhhlnj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2hbnjkssu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptmospsx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gt2xowfydgw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2zhujojys.html

C#:   s.Replace("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2xtzrtgov.html

[E07] 按分隔符拆分
来源：http://dali.nanxinkj.top/Article/details/gt2uzskudtn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sweek.top/Article/details/gt2hlgasqbb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2dyuqljbc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hywenlv.cn/Article/details/gt2xdosusoz.html

TS:   s.split(",")
来源：http://dali.redwolf501.top/Article/details/gt2feknvgfo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jiagoushi.top/Article/details/gt2gcfqqrgq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenlongwang.top/Article/details/gt2sokyriiq.html

Ruby: s.split(",");  s.split
来源：http://dali.shuidangran.top/Article/details/gt2wpqpcerj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gt2bgbknmin.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnntmxi.html

Py:   ",".join(items)
来源：http://dali.smart0.xyz/Article/details/gt2dszscscl.html

PHP:  implode(",", $items);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ouulrulg.html

JS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gt2udutsrsc.html

TS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gt2qheetvvv.html

Java: String.join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ugzgcntq.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gt2ldntqfax.html

Ruby: items.join(",")
来源：http://dali.smart0.xyz/Article/details/gt2bjlgsxfy.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gt2uaqdrypw.html

[E09] 去除所有空白字符
来源：http://dali.bjfxy.top/Article/details/gt2rylypxnp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shzxlz.cn/Article/details/gt2pwzdatgv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hammf.cn/Article/details/gt2nokrcpbc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gt2ulyfxgdq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gt2lpodapvf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gt2okaibthz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sufxvd.cn/Article/details/gt2phgrjuik.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xuanzx.com/Article/details/gt2spvckmkc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.c1oappe.top/Article/details/gt2loahgawi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ybcxt.top/Article/details/gt2owubbgab.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gt2ucroeukg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2kudnvreo.html

JS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gt2matnqyna.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2gvoxfjff.html

Java: String.format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gt2nhzcjpwe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gt2qujdsxin.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gt2snnuhxya.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.smart0.xyz/Article/details/gt2mpxdctpf.html

[E11] 反转字符串
来源：http://dali.guannengcc.top/Article/details/gt2lhhzhxwt.html

Py:   s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gt2jygvrhmu.html

PHP:  strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2szpwjszt.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtuubhzb.html

TS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gt2bfwwsdsn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2dbapprmi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nwbrower.top/Article/details/gt2ymtnzqan.html

Ruby: s.reverse
来源：http://dali.yj202588.top/Article/details/gt2gfcyqxna.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gt2ajwdkdxx.html

[E12] 统计某字符出现次数
来源：http://dali.haohaochexian.top/Article/details/gt2unlpaadp.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gt2dgwafowa.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgufenzy.top/Article/details/gt2gtkpdnxh.html

JS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gt2njwqsyut.html

TS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gt2ggcmbjju.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxuanxn.top/Article/details/gt2fayflbny.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxuanxn.top/Article/details/gt2fmdubgxq.html

Ruby: s.count("a")
来源：http://dali.iojbl.cn/Article/details/gt2hcfakizm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuetiantiany.cn/Article/details/gt2jisuexou.html

[E13] 逐字符遍历
来源：http://dali.jinqigufen.top/Article/details/gt2vyoqonio.html

Py:   for ch in s: print(ch)
来源：http://dali.meibo888.top/Article/details/gt2ocqtmnpv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.mhx1999.top/Article/details/gt2vuqyqjfb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2bsxqhqrv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gt2vjbopyqn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2nceomjzw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.c1oappe.top/Article/details/gt2qelpdpmz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xylfe.cn/Article/details/gt2wkmdnxbi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fmrtnzvd.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigufen.top/Article/details/gt2ylhwuosp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hfpthk.cn/Article/details/gt2cjofnghi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gt2ucsyyhaz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shzxlz.cn/Article/details/gt2figrqnka.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jyoumei.cn/Article/details/gt2jtbriudp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjekaqxj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guowangkeji.top/Article/details/gt2brtlroex.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.bjfxy.top/Article/details/gt2hoilnlar.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kbowtivo.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gt2jmscvgzc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ivvv.top/Article/details/gt2fgscabip.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.mhx1999.top/Article/details/gt2kpdnnncf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cashguo.top/Article/details/gt2vvdlupdp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ybcxt.top/Article/details/gt2zpagwyue.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gt2vvhssqqi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gt2gcbvykzf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wudckkos.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gt2fpfspvkx.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gt2dhnjbzbw.html

Py:   f"{1234567:,}"
来源：http://dali.vqdsnc.cn/Article/details/gt2ssxqyvgu.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gt2mpkaqnok.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gt2tcicvdho.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gt2wydtmlza.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odugdhlx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.bjfxy.top/Article/details/gt2rczdvwzo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gt2kwnfxywb.html

C#:   1234567.ToString("N0")
来源：http://dali.cashguo.top/Article/details/gt2tuntlfom.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gt2fnhgwcsu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gt2pnlggvcc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hywenlv.cn/Article/details/gt2fdekiutg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gt2axqcyngi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gt2rarviufv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnqzz.top/Article/details/gt2eojgwpca.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hysaishi.cn/Article/details/gt2pavgmtvo.html

Ruby: s.capitalize
来源：http://dali.hnqzz.top/Article/details/gt2gxgcbmje.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cdnleiting.top/Article/details/gt2vgmsxvsn.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gt2hmbwscfo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sxryk.cn/Article/details/gt2xywmcfln.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tanke756.top/Article/details/gt2pfoevris.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2ymrcmzxw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2zkjeoimp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gt2xoedtsqv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2zytndycz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gt2msndzbzv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdehnhio.html

[E19] 多行文本按行拆分
来源：http://dali.haohaochexian.top/Article/details/gt2ioxkrrze.html

Py:   s.splitlines()
来源：http://dali.hysaishi.cn/Article/details/gt2nnjcpukd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2vfxgwaml.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gt2fxnrfgsf.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gt2ydylsydn.html

Java: s.lines().toList()
来源：http://dali.dianchejie.cn/Article/details/gt2offdocva.html

Go:   strings.Split(s, "\n")
来源：http://dali.sysykeji.top/Article/details/gt2qlfqicnu.html

Ruby: s.lines
来源：http://dali.zhoulong.xyz/Article/details/gt2ahzogvsz.html

C#:   s.Split('\n')
来源：http://dali.tian-w.cn/Article/details/gt2lglboaws.html

[E20] 判断字符串是否为空
来源：http://dali.hammf.cn/Article/details/gt2twpbqbok.html

Py:   if not s:
来源：http://dali.chenjidiqi.icu/Article/details/gt2hdcixfgu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gt2ehieioiv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gt2umxctsin.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gt2qcilkoab.html

Java: if (s.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gt2vdksnjom.html

Go:   if s == "" {}
来源：http://dali.316326.xyz/Article/details/gt2xbsfjxca.html

Ruby: if s.empty?
来源：http://dali.zhongyouzk.top/Article/details/gt2ydwtxwlt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qknwxuqz.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gt2dohoyedw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aibaodan.cn/Article/details/gt2xvlukhkx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwrxpgxa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2nimyvyvj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2oepbzpwv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2gxgbrkwe.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258.top/Article/details/gt2eexcxvme.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2afskmjqb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2ubjgwzal.html

[E22] 字节长度与字符长度
来源：http://dali.yj202588.top/Article/details/gt2nkujtqfp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigufen.top/Article/details/gt2jiutlluo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gt2rkfyjkfx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gt2tezzhuae.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gt2izaifrxb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gt2ozmujgql.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ngtcwbss.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2oolduqau.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.iojbl.cn/Article/details/gt2pygauyzy.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2aajlkkfd.html

F. 文件与目录
来源：http://dali.hfpthk.cn/Article/details/gt2kphfigcx.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2ibswbhfn.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gt2xwnlxfip.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gt2leqrxnlg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2kugcvbhd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gt2qgqrxzxy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gt2xldlqire.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2iitetrul.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangdashe.top/Article/details/gt2vndceedq.html

Ruby: File.read("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndzbnnsd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2tujyfflv.html

[F02] 逐行读取文件
来源：http://dali.316326.xyz/Article/details/gt2ebttrait.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.birdmap.top/Article/details/gt2tgqnbmbf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gogol.net.cn/Article/details/gt2dtrceiik.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2bmxoyfqj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gt2riavgdkd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avygfyet.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.haohaochexian.top/Article/details/gt2etrxynyx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhixingplan.top/Article/details/gt2vntsqlvo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgfzy.top/Article/details/gt2gbdkkoio.html

[F03] 写入文件（覆盖）
来源：http://dali.zhixingplan.top/Article/details/gt2quumecsw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gt2gdndqser.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gt2ebcwxgxk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gt2bhenlviw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gt2jexdmyzu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ubhyatgj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gt2edfuzmkw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hywenlv.cn/Article/details/gt2xgauykru.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gt2fvxmfngu.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gt2cnnjodht.html


<!-- 参考信息 -->