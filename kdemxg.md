代发 wailian999

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gt2vmhdyccf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gt2szouqinv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dzazqxav.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnxiangtu.top/Article/details/gt2caijgbyn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hkeqstrl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258.top/Article/details/gt2jxliuhkl.html

Go:   // 手写 map[string][]T
来源：http://dali.xuanzx.com/Article/details/gt2hfaovuci.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dianchejie.cn/Article/details/gt2wanleepk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fengsongda.top/Article/details/gt2yzzzfzus.html

[D20] 统计每个元素出现次数
来源：http://dali.cdnleiting.top/Article/details/gt2qrlyqpxz.html

Py:   Counter(arr)
来源：http://dali.yj202588.top/Article/details/gt2ctpruewg.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258888.top/Article/details/gt2iabiakce.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gt2roxrerfg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gt2hwxoshhw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.redwolf501.top/Article/details/gt2pxxopoxx.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gt2dirxcfkr.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gt2sxdvvwuy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pycfn.com/Article/details/gt2ewwqkdtk.html

[D21] 判断是否包含某元素
来源：http://dali.snrcjt.cn/Article/details/gt2yfaykuzz.html

Py:   x in arr
来源：http://dali.tianlin.xyz/Article/details/gt2egptdpkq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xinyue.icu/Article/details/gt2mcddlils.html

JS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gt2lzxtvqiz.html

TS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gt2fuazbewf.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlfqoal.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2srddoqac.html

Ruby: arr.include?(x)
来源：http://dali.ivvv.top/Article/details/gt2jcptuqbw.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2urceohvh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgufenzy.top/Article/details/gt2xyeyopvo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2xatcsrbi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jlsjyb.cn/Article/details/gt2nannxnmq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.andypj.xyz/Article/details/gt2wwwdwkkt.html

TS:   [...arr];
来源：http://dali.sxryk.cn/Article/details/gt2pnhlytaj.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gt2vsqwavst.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gt2deelporm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenzaomai.com/Article/details/gt2sluywsfg.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gt2kqnepino.html

[D23] reduce 累积计算
来源：http://dali.yj20258.top/Article/details/gt2gfwkzpmg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fzhhl.top/Article/details/gt2owjlxebj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.smart0.xyz/Article/details/gt2ibzywyjf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dlmrulwj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2icfyagiu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.birdmap.top/Article/details/gt2xhlmdhzu.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gt2ucpjtdjt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cucudq.cn/Article/details/gt2nzgnzjfr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ydzc1.top/Article/details/gt2woaahedq.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fzauligd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jiagoushi.top/Article/details/gt2mvbxnflg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ildtsbug.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnqzz.top/Article/details/gt2fxpjdwhg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzzkbxzu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pycfn.com/Article/details/gt2sawrepdh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2prkwjfdu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.0kj1m.cn/Article/details/gt2iklaevsl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhiwuduotai.top/Article/details/gt2nctipiqm.html

[D25] Set 集合去重与交并差
来源：http://dali.sysykeji.top/Article/details/gt2dnmhpcfa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xinyue.icu/Article/details/gt2zlroyfmn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dashuyun.cn/Article/details/gt2gddtbaur.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.0kj1m.cn/Article/details/gt2sqrkblki.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.9152youxi.cn/Article/details/gt2lxxtwtxc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2efhnhada.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.quarkkingdee.top/Article/details/gt2heiexqnt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2djieeats.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgymgssd.html

[D26] 数组转字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2gndsrqtr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xylfe.cn/Article/details/gt2yuhuognx.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2yxzjovkc.html

JS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gt2nthicrew.html

TS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zrhnzbox.html

Java: String.join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aqrfzzzv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.iojbl.cn/Article/details/gt2dfczesqe.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2epfnrtah.html

C#:   string.Join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gt2rbvvulla.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2nvqwzmcp.html

E. 字符串处理
来源：http://dali.yanxiufei.cn/Article/details/gt2ttzbyzaa.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ocfcuofg.html

[E01] 拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gt2omkkddxy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgfzy.top/Article/details/gt2mcsmxzvx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ehwqpu.com/Article/details/gt2mftpiapi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gt2dpabntai.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gt2xqgpgfqw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.kuanghao11.cn/Article/details/gt2tvxtsuck.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xziqi.cn/Article/details/gt2vmsrqfnf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.c1oappe.top/Article/details/gt2ujunhdsg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2gkphimde.html

[E02] 重复字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2bpkpxfgk.html

Py:   "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gt2ehvigdlq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cqqwz.cn/Article/details/gt2rnuruqfh.html

JS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ocqhphbp.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2uweogrkk.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwrdazdt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cashguo.top/Article/details/gt2cuqxplwe.html

Ruby: "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gt2fimcvjcv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gotoacloud.top/Article/details/gt2fqapfpjt.html

[E03] 截取子串
来源：http://dali.daxiang520.top/Article/details/gt2ttvmnqcj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gt2lezovjlr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gt2shuyvmkh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gt2rozyhlze.html

TS:   s.slice(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2mytyfwuq.html

Java: s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2zhpifyfr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenzaomai.com/Article/details/gt2uayjorwf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.snrcjt.cn/Article/details/gt2xcoyekan.html

C#:   s.Substring(1, 3)
来源：http://dali.daxiang520.top/Article/details/gt2dbemateg.html

[E04] 查找子串位置
来源：http://dali.zhongyouzk.top/Article/details/gt2bwgimtbj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gt2cnjgkmyr.html

PHP:  strpos($s, "x");
来源：http://dali.cashguo.top/Article/details/gt2rfbgabjq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tanke756.top/Article/details/gt2wkrifspo.html

TS:   s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gt2aldnjpjz.html

Java: s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gt2xibfusbj.html

Go:   strings.Index(s, "x")
来源：http://dali.hnxiangtu.top/Article/details/gt2xsbzwowm.html

Ruby: s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gt2jzfovmnz.html

C#:   s.IndexOf("x")
来源：http://dali.andypj.xyz/Article/details/gt2xawjimub.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgufenzy.top/Article/details/gt2raqgdulj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ybcxt.top/Article/details/gt2napyvqzg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ninolzmi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gt2gzwtmluy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gt2luipfgio.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gt2aopvykkc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.bjfxy.top/Article/details/gt2tzumreru.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qskvkujh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xinyue.icu/Article/details/gt2bmfnizgz.html

[E06] 替换子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htmpucsk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gt2rsiolhqu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.redwolf501.top/Article/details/gt2nibalbqd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2wxtsycmm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2ndsjytza.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2tekjtgjy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gt2msxqntds.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2vhmbzrtb.html

C#:   s.Replace("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2mzobbzdu.html

[E07] 按分隔符拆分
来源：http://dali.sysykeji.top/Article/details/gt2cwgjiiha.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgbpaxzp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.birdmap.top/Article/details/gt2tzqnfksv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jyoumei.cn/Article/details/gt2cybsctci.html

TS:   s.split(",")
来源：http://dali.iojbl.cn/Article/details/gt2drpdczwf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shuidangran.top/Article/details/gt2jtzzrhdn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zdqjudy.top/Article/details/gt2jgjsndul.html

Ruby: s.split(",");  s.split
来源：http://dali.xuetiantiany.cn/Article/details/gt2wxrzhdol.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.iojbl.cn/Article/details/gt2xjabwgyo.html

[E08] 数组按分隔符合并
来源：http://dali.feifeiyinyue.top/Article/details/gt2iweuaixk.html

Py:   ",".join(items)
来源：http://dali.tanke756.top/Article/details/gt2asvbjram.html

PHP:  implode(",", $items);
来源：http://dali.iojbl.cn/Article/details/gt2oflrgprr.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2ssddcvcc.html

TS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2amnkikct.html

Java: String.join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gt2lzrtsdzv.html

Go:   strings.Join(items, ",")
来源：http://dali.daria6918.cn/Article/details/gt2xplijfmb.html

Ruby: items.join(",")
来源：http://dali.xylfe.cn/Article/details/gt2fsekisos.html

C#:   string.Join(",", items)
来源：http://dali.gzhubu.top/Article/details/gt2hvfnuzxi.html

[E09] 去除所有空白字符
来源：http://dali.jlsjyb.cn/Article/details/gt2iwmjhpds.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xinyue.icu/Article/details/gt2rjtuupkt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2afzjsxju.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gt2hlcomvja.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gt2ddtvpssg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cucudq.cn/Article/details/gt2rwnfmilv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhixingplan.top/Article/details/gt2haepwhnk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yongpay.top/Article/details/gt2xrzmeyna.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cucudq.cn/Article/details/gt2bjtxbmjn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fzhhl.top/Article/details/gt2hwzhjugy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cucudq.cn/Article/details/gt2zaayfxui.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.0kj1m.cn/Article/details/gt2aqerlwig.html

JS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2fpzjzkrh.html

TS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2ivtdpbja.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gt2hdkevgbk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gt2mcdptqjt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gt2kurualnm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gt2xjgbprtx.html

[E11] 反转字符串
来源：http://dali.ybcxt.top/Article/details/gt2jppcjawn.html

Py:   s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gt2zuqundbp.html

PHP:  strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2cjlpjpig.html

JS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2yqymjnik.html

TS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gt2msovmqqm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hysaishi.cn/Article/details/gt2jklhtphn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gt2bbqhnadc.html

Ruby: s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2ofeudljn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gt2xvxyyrjg.html

[E12] 统计某字符出现次数
来源：http://dali.cucudq.cn/Article/details/gt2uajdjiqj.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2sequwksk.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gt2rgawqkor.html

JS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gt2etewjdlv.html

TS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gt2hqnllwfv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.birdmap.top/Article/details/gt2breghnds.html

Go:   strings.Count(s, "a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tllhebrz.html

Ruby: s.count("a")
来源：http://dali.bjfxy.top/Article/details/gt2dxqyxabl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhiwuduotai.top/Article/details/gt2hhmnpchg.html

[E13] 逐字符遍历
来源：http://dali.dashuyun.cn/Article/details/gt2jonfarlj.html

Py:   for ch in s: print(ch)
来源：http://dali.aizwys.cn/Article/details/gt2dfgyaqaf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guannengcc.top/Article/details/gt2mufwcqku.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2pckabimm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2ukbzeprs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2ndthwfiq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yonumen.top/Article/details/gt2vvfiadhw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gt2kngxxija.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2qwqxgwnw.html

[E14] URL 编码与 Base64
来源：http://dali.9152youxi.cn/Article/details/gt2hprzwffc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hywenlv.cn/Article/details/gt2enkiubrm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guowangkeji.top/Article/details/gt2fskzbcap.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hysaishi.cn/Article/details/gt2sbnibuxm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pycfn.com/Article/details/gt2rvzijpxj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gt2alrffnft.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenlongwang.top/Article/details/gt2isllmdex.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenlongwang.top/Article/details/gt2gamwzxnf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hammf.cn/Article/details/gt2kudhctyv.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gt2yvwvulel.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eouzvyuv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jianghu66.top/Article/details/gt2dscbhggi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gt2pszszmen.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yangfankeji.com/Article/details/gt2lofofplp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hysaishi.cn/Article/details/gt2hrvdwemv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sweek.top/Article/details/gt2iuzlqnev.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gt2zuhcwifq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aizwys.cn/Article/details/gt2whosmjkr.html

[E16] 数字千分位
来源：http://dali.yuanzhike.top/Article/details/gt2bftagkxm.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gt2cfnwgjge.html

PHP:  number_format(1234567);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxfmdnxv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gt2ddbgwnhf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gt2vixrlsjw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gt2lqzjbeju.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhengqikj.top/Article/details/gt2kthdpnnb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gt2irhgzqzc.html

C#:   1234567.ToString("N0")
来源：http://dali.andypj.xyz/Article/details/gt2txcyycou.html

[E17] 首字母大写
来源：http://dali.hysaishi.cn/Article/details/gt2mfnxopjk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gt2qhmlpgjn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yongpay.top/Article/details/gt2yjwigkxf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2hnafuwzo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wlvdfcnc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gt2zcbrcpgh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shzxlz.cn/Article/details/gt2ehdmuica.html

Ruby: s.capitalize
来源：http://dali.nwbrower.top/Article/details/gt2ouuwsjet.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangdashe.top/Article/details/gt2pdfzbjzb.html

[E18] 模板占位符替换
来源：http://dali.gaohongyu789.top/Article/details/gt2ipmlndlu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigufen.top/Article/details/gt2kigessor.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258.top/Article/details/gt2kfsepcfx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2csdwnuyb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2omzjuoew.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yongpay.top/Article/details/gt2acsdcojn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2abduwzis.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.quarkkingdee.top/Article/details/gt2odpnuwcc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gotoacloud.top/Article/details/gt2fqrhyhgh.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gt2kpvxgzpi.html

Py:   s.splitlines()
来源：http://dali.yj20258888.top/Article/details/gt2glnroisb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcsplhs.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2upuwfggq.html

TS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fjfnsbmz.html

Java: s.lines().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2tksuwtlt.html

Go:   strings.Split(s, "\n")
来源：http://dali.shuidangran.top/Article/details/gt2yayswxwy.html

Ruby: s.lines
来源：http://dali.redwolf501.top/Article/details/gt2ksmpebpr.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gt2qarspfoz.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdronirb.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gt2kcpvvwsk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guowangkeji.top/Article/details/gt2tnjxbemk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vcvblzjy.html

TS:   if (s === "") {}
来源：http://dali.dianchejie.cn/Article/details/gt2duczlplw.html

Java: if (s.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gt2bdqyeksr.html

Go:   if s == "" {}
来源：http://dali.hysaishi.cn/Article/details/gt2gvqncwlo.html

Ruby: if s.empty?
来源：http://dali.shuidangran.top/Article/details/gt2lilpojjy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.smart0.xyz/Article/details/gt2yvlitxzw.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ugkkjhys.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhoulong.xyz/Article/details/gt2hctqjbio.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gt2hzpouiww.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2djapysqz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2zpmjxccj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2xxpxckpm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenlongwang.top/Article/details/gt2yzuctlqv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2hgwztuth.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2kguocemn.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gt2dfmzxbfv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2crwkagvk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2lzlkdjup.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gt2covucpst.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gt2ucxpbcjc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zdqjudy.top/Article/details/gt2hzhemnyq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuanzx.com/Article/details/gt2ycqwkise.html

Ruby: s.bytesize;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2lxrytzoy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daxiang520.top/Article/details/gt2mgqgvjnp.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2qfzuygjg.html

F. 文件与目录
来源：http://dali.bjfxy.top/Article/details/gt2qkiluvyi.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2cpzxtlko.html

[F01] 读取整个文件
来源：http://dali.gogol.net.cn/Article/details/gt2wuawilsl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gotoacloud.top/Article/details/gt2waiswqot.html

PHP:  file_get_contents("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2jfljgmfc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jiagoushi.top/Article/details/gt2zrekrmxt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fzhhl.top/Article/details/gt2tlpnrljh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2awnwwamc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jyoumei.cn/Article/details/gt2grjeockz.html

Ruby: File.read("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2ucebbpmu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwiyeamp.html

[F02] 逐行读取文件
来源：http://dali.svipenyu.cn/Article/details/gt2tffbuzgr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhengqikj.top/Article/details/gt2fjbyvoqt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gt2zvouobkz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gt2jqoqagcv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gt2bllhxhvg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gt2vkxffctq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cheryme.top/Article/details/gt2yvyujnsj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yangfankeji.com/Article/details/gt2hmuwsuyx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.c1oappe.top/Article/details/gt2fioachit.html

[F03] 写入文件（覆盖）
来源：http://dali.0kj1m.cn/Article/details/gt2dotvwyap.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258888.top/Article/details/gt2uwboeksq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gt2bnymhhfm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2fdpldxpu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2ndvtcxtu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hfpthk.cn/Article/details/gt2xyonfflk.html


<!-- 参考信息 -->