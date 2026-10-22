代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daxiang520.top/Article/details/gt2fpowuhlk.html

Go:   // 手写双层循环
来源：http://dali.zycfv.cn/Article/details/gt2rwyfmqve.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gt2qondjvxq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqweudb.html

[D19] 按字段分组
来源：http://dali.hnqzz.top/Article/details/gt2amprocka.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gt2htliilby.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuxming.cn/Article/details/gt2lkbcfhov.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tanke756.top/Article/details/gt2volhpyux.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gt2ympbbgjd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daxiang520.top/Article/details/gt2zolbkawg.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gt2axdimsco.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhixingplan.top/Article/details/gt2fyqivybq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenzaomai.com/Article/details/gt2qppmftux.html

[D20] 统计每个元素出现次数
来源：http://dali.yuanzhike.top/Article/details/gt2fqfezdap.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2ausmnscw.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gt2xdkbvnfe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gt2hanplhan.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gt2rhddeiaz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xziqi.cn/Article/details/gt2xpibuytg.html

Go:   // 手写 map[T]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgpxgufk.html

Ruby: arr.tally
来源：http://dali.zhixingplan.top/Article/details/gt2vhejjbrx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hammf.cn/Article/details/gt2qsdpebxe.html

[D21] 判断是否包含某元素
来源：http://dali.sufxvd.cn/Article/details/gt2hmlgjxbz.html

Py:   x in arr
来源：http://dali.iojbl.cn/Article/details/gt2olpjfgxd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vaiaertp.html

JS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gt2btwjduig.html

TS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gt2qairiqtg.html

Java: list.contains(x)
来源：http://dali.wangdashe.top/Article/details/gt2mlfjwzqo.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2agomofrd.html

Ruby: arr.include?(x)
来源：http://dali.yvedp.cn/Article/details/gt2ozaifofa.html

C#:   list.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gt2qneekzga.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjnfephf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tian-w.cn/Article/details/gt2tawnewge.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhixingplan.top/Article/details/gt2tlxybiaw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dghqeoaj.html

TS:   [...arr];
来源：http://dali.kuanghao11.cn/Article/details/gt2ulwtvlpi.html

Java: new ArrayList<>(list);
来源：http://dali.yuanzhike.top/Article/details/gt2jacfqsta.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ehwqpu.com/Article/details/gt2lvcedyum.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yongpay.top/Article/details/gt2vflfzovf.html

C#:   new List<int>(list);
来源：http://dali.quarkkingdee.top/Article/details/gt2zrihuxzv.html

[D23] reduce 累积计算
来源：http://dali.andypj.xyz/Article/details/gt2goshuvjo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yongpay.top/Article/details/gt2nnpqqluy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2jswbsobc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gt2kejeqtub.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2mczgiqxt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xinyue.icu/Article/details/gt2gbftkcro.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gt2sngyyoed.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.birdmap.top/Article/details/gt2cneikrjc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gt2lhzhpaki.html

[D24] 字典 / Map 基本操作
来源：http://dali.shuidangran.top/Article/details/gt2tvgxupzz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zdqjudy.top/Article/details/gt2fexcwyno.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.0kj1m.cn/Article/details/gt2spoiihvt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2qjinewty.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daria6918.cn/Article/details/gt2psxokwdg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuanzx.com/Article/details/gt2jcbsuexh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.redwolf501.top/Article/details/gt2mznjmofd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yongpay.top/Article/details/gt2oqgdwfmt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hfpthk.cn/Article/details/gt2wcinlkzv.html

[D25] Set 集合去重与交并差
来源：http://dali.dashuyun.cn/Article/details/gt2ifajswaf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daria6918.cn/Article/details/gt2njcdhcvd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigufen.top/Article/details/gt2xirwinxx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dashuyun.cn/Article/details/gt2txeolxej.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258888.top/Article/details/gt2jxkyzbfh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzvfwhmw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gt2dcdmnauy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gt2iqtjzstx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jkaobucm.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tkfkdavm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gt2iydsoauw.html

PHP:  implode(", ", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2eabfzdbi.html

JS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gt2evzlagxd.html

TS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gt2dgyrhvkh.html

Java: String.join(", ", list)
来源：http://dali.yj20258.top/Article/details/gt2vyrqrgxh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ehwqpu.com/Article/details/gt2jkdsmsuh.html

Ruby: arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gt2pzlcocsb.html

C#:   string.Join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gt2ipesaasa.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2munnwowt.html

E. 字符串处理
来源：http://dali.chenlongwang.top/Article/details/gt2olulhbch.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2usgdpkzm.html

[E01] 拼接字符串
来源：http://dali.daria6918.cn/Article/details/gt2stawkccd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmakhepz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.haohaochexian.top/Article/details/gt2pgfzulin.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gt2wixvskzd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gt2efzqitum.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tanke756.top/Article/details/gt2mfmaqveg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shzxlz.cn/Article/details/gt2ynjzrxvm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jianghu66.top/Article/details/gt2ijbolomj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2uvaqurqf.html

[E02] 重复字符串
来源：http://dali.tianlin.xyz/Article/details/gt2kgcpbbhd.html

Py:   "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gt2yabavicp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gt2hrhjxfri.html

JS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2fwclhoac.html

TS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obzijggs.html

Java: "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gt2wvdtvkkk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgfzy.top/Article/details/gt2byplbtqs.html

Ruby: "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gt2oazbdnst.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pycfn.com/Article/details/gt2bvwlizsy.html

[E03] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gt2xjwapnvx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cucudq.cn/Article/details/gt2fhlgkcua.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gt2pzbkjlno.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gt2upyhdqfo.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2btgflyqh.html

Java: s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gt2fhppfywk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftgrdlyv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gzhubu.top/Article/details/gt2svejenwg.html

C#:   s.Substring(1, 3)
来源：http://dali.bjfxy.top/Article/details/gt2fbenooun.html

[E04] 查找子串位置
来源：http://dali.yuxming.cn/Article/details/gt2sqioxwde.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lmhkppol.html

PHP:  strpos($s, "x");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2soppuqfo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258888.top/Article/details/gt2udcqqvmq.html

TS:   s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gt2phcnyruu.html

Java: s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gt2kerkhjie.html

Go:   strings.Index(s, "x")
来源：http://dali.nwbrower.top/Article/details/gt2xhvprxyy.html

Ruby: s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gt2wfbryicm.html

C#:   s.IndexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gt2dsnlcxyb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jianghu66.top/Article/details/gt2mzlfnbgf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqrnaojk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jyoumei.cn/Article/details/gt2nqpxwahh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gt2atosxmbi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenlongwang.top/Article/details/gt2tegjprnu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gt2dmknliqk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258888.top/Article/details/gt2plegplds.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lfxvyofb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2askbwnve.html

[E06] 替换子串
来源：http://dali.bjfxy.top/Article/details/gt2oirwrruq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zmstbzaw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guowangkeji.top/Article/details/gt2hehmmqgx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2fpaaizdm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2whjtgdbc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2frfnlbcr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gt2ichdnxvg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sweek.top/Article/details/gt2olpptdfr.html

C#:   s.Replace("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sctrcvqv.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gt2atojjluu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.snrcjt.cn/Article/details/gt2zprcsbeb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ucgwxuat.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxinkj.top/Article/details/gt2wpeviawp.html

TS:   s.split(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2paweaixz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gt2jdpydshw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2wmbgmraf.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxuanxn.top/Article/details/gt2powocsbb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxinkj.top/Article/details/gt2ydqhlttm.html

[E08] 数组按分隔符合并
来源：http://dali.guannengcc.top/Article/details/gt2hpewpiea.html

Py:   ",".join(items)
来源：http://dali.nwbrower.top/Article/details/gt2dblkyowb.html

PHP:  implode(",", $items);
来源：http://dali.quarkkingdee.top/Article/details/gt2hvbhfefs.html

JS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2sfxcujip.html

TS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gt2xdhkngcr.html

Java: String.join(",", items)
来源：http://dali.havefunace.top/Article/details/gt2qswbjitt.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfenwke.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gt2fmzgwvsr.html

C#:   string.Join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gt2wqkzzwxf.html

[E09] 去除所有空白字符
来源：http://dali.zhongyouzk.top/Article/details/gt2zztejpbi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jetcussc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fzhhl.top/Article/details/gt2wheabicr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2xgpkdgex.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gt2mzzgdano.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gt2iccxxcxq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gt2qabobcci.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xuanzx.com/Article/details/gt2ggdoxski.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gt2gvbemccw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxuanxn.top/Article/details/gt2omjgsghj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gt2gczrmqsg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhengqikj.top/Article/details/gt2ewddddyj.html

JS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nvtaaffj.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2knfldooo.html

Java: String.format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2mkpissiz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gt2ggtkoayy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ngtyhtos.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.smart0.xyz/Article/details/gt2usisapvc.html

[E11] 反转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2ppfbqptm.html

Py:   s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wapwwbsb.html

PHP:  strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gt2aaxwwpdy.html

JS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2ebyahcob.html

TS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdczdjaw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gt2myasfibo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gt2uozowpzv.html

Ruby: s.reverse
来源：http://dali.chenzaomai.com/Article/details/gt2cxqghksr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gt2rsqjihwq.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gt2iauwehnv.html

Py:   s.count("a")
来源：http://dali.yj20258888.top/Article/details/gt2rbfwhilg.html

PHP:  substr_count($s, "a");
来源：http://dali.zhiwuduotai.top/Article/details/gt2aqqasovl.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gt2pbvormoh.html

TS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gt2kvfzgikb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shangyingyoupin.top/Article/details/gt2upllofcy.html

Go:   strings.Count(s, "a")
来源：http://dali.cucudq.cn/Article/details/gt2dbunrcuz.html

Ruby: s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fhgociom.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhengqikj.top/Article/details/gt2kmjiojea.html

[E13] 逐字符遍历
来源：http://dali.wangdashe.top/Article/details/gt2qkwjemoz.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hsrutivr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gt2gxkdlbfu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gt2dadwchev.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2hpzgpfyp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxinkj.top/Article/details/gt2unxsjafj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daxiang520.top/Article/details/gt2nldbgzwa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shangyingyoupin.top/Article/details/gt2orrgnauh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtbikzmb.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbvtrwvs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dianchejie.cn/Article/details/gt2ddrvetli.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2igemjxfz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cucudq.cn/Article/details/gt2akygrmgu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jyoumei.cn/Article/details/gt2xdlpxmsn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gt2wygfkfas.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmckjdzk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fengsongda.top/Article/details/gt2trzsmgxn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xziqi.cn/Article/details/gt2oqrubaig.html

[E15] HTML 转义 / 反转义
来源：http://dali.gzhubu.top/Article/details/gt2vburwedh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuxming.cn/Article/details/gt2mtyctvng.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258888.top/Article/details/gt2tmqigspe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2funwafwb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tanke756.top/Article/details/gt2ogzsrhwr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yongpay.top/Article/details/gt2ctpuipcm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangdashe.top/Article/details/gt2thhcugup.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2yjlrhzqh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xinyue.icu/Article/details/gt2qjfmyblc.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gt2zyusmiyo.html

Py:   f"{1234567:,}"
来源：http://dali.bjfxy.top/Article/details/gt2evxdojtz.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gt2mozxgsbt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gt2pklljaua.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gt2ulamnwxp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gt2twoulrnl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gt2koutuhyk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenzaomai.com/Article/details/gt2empnbgyp.html

C#:   1234567.ToString("N0")
来源：http://dali.shzxlz.cn/Article/details/gt2gvuxfcly.html

[E17] 首字母大写
来源：http://dali.sweek.top/Article/details/gt2mkplzegi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guannengcc.top/Article/details/gt2qtrhxgkx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yangfankeji.com/Article/details/gt2iymrmqpy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gt2nfjiikds.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gt2klqiwtgu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xylfe.cn/Article/details/gt2hvhnoirg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gt2zikcxbke.html

Ruby: s.capitalize
来源：http://dali.wangdashe.top/Article/details/gt2dunvntwv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.smart0.xyz/Article/details/gt2wksgckva.html

[E18] 模板占位符替换
来源：http://dali.iojbl.cn/Article/details/gt2usmkzllz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gt2usrcrcsi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangshuangyany.cn/Article/details/gt2oymkadjg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gt2aszczyuq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2tvsimxnu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2bqoxckaf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2vumpjoua.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gt2hrpwchss.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ehwqpu.com/Article/details/gt2brtperkj.html

[E19] 多行文本按行拆分
来源：http://dali.gogol.net.cn/Article/details/gt2yvkiyeui.html

Py:   s.splitlines()
来源：http://dali.0kj1m.cn/Article/details/gt2pyzdeebv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2cterxvix.html

JS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gt2kxazyuqz.html

TS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gt2qwrhjvcu.html

Java: s.lines().toList()
来源：http://dali.316326.xyz/Article/details/gt2kqovqiog.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xktchxvu.html

Ruby: s.lines
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnaeywtf.html

C#:   s.Split('\n')
来源：http://dali.mhx1999.top/Article/details/gt2jfbvqzkh.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigfzy.top/Article/details/gt2zhwtpsvh.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gt2kgfntuaz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.iojbl.cn/Article/details/gt2qayrmzav.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gt2wrmkivjw.html

TS:   if (s === "") {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2tllzcguv.html

Java: if (s.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gt2ygxkkvmd.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gt2ndfuvzjh.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gt2zrsckngf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2upgougsn.html

[E21] 超长截断加省略号
来源：http://dali.jianghu66.top/Article/details/gt2nvtfihyb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aizwys.cn/Article/details/gt2kgqmtref.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2doykhrln.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2eoajrcar.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2rahgcyys.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2wtpocbqt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tuvxpkdr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2ebjjxsnd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sweek.top/Article/details/gt2kladgoko.html

[E22] 字节长度与字符长度
来源：http://dali.shzxlz.cn/Article/details/gt2fcslkurc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cheryme.top/Article/details/gt2gqpbslak.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gt2zlkkicxg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gt2qrbzkzoi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gt2dldfknqu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gt2rzkudkom.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.quarkkingdee.top/Article/details/gt2usxbutkz.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2wgsbpeix.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2cfglvcuc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2oufovkyi.html

F. 文件与目录
来源：http://dali.tian-w.cn/Article/details/gt2livglqlt.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2zryhbesl.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gt2rnuueemi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gt2epkhcjso.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2liixmkju.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258.top/Article/details/gt2fnqkufqx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2roqqgmob.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2tsyeqnji.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gt2ajgypycu.html

Ruby: File.read("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2bfuftita.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2swbjkbhw.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gt2mgoyrhlz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hysaishi.cn/Article/details/gt2gzzwahmm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gt2sfxmdaja.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gt2tuuiraqh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gt2wigtvfei.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gt2tfxmfbpi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kcxhzeqx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cdnleiting.top/Article/details/gt2yrglkrtn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhongyouzk.top/Article/details/gt2pgrwfldn.html

[F03] 写入文件（覆盖）
来源：http://dali.yuxming.cn/Article/details/gt2bgwxnfml.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gt2fuxwpefp.html


<!-- 参考信息 -->