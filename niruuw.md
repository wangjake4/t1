代发 wailian999

Ruby: arr.tally
来源：http://dali.vqdsnc.cn/Article/details/gt2bnnzxnjs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.0kj1m.cn/Article/details/gt2tkpvlqhx.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2phmbuoxw.html

Py:   x in arr
来源：http://dali.cdnleiting.top/Article/details/gt2tyoxftzf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.birdmap.top/Article/details/gt2lsezmtuk.html

JS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gt2adkcuplw.html

TS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gt2kfhgorxe.html

Java: list.contains(x)
来源：http://dali.xziqi.cn/Article/details/gt2zvhuzeop.html

Go:   slices.Contains(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2styehdvk.html

Ruby: arr.include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wzkijdxr.html

C#:   list.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2aeuykwgt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.quarkkingdee.top/Article/details/gt2rdjcofkn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2zvxnuzil.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ppjwa.cn/Article/details/gt2kiyilagg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2jdbaiscw.html

TS:   [...arr];
来源：http://dali.ivvv.top/Article/details/gt2sjfqphcr.html

Java: new ArrayList<>(list);
来源：http://dali.yangfankeji.com/Article/details/gt2xmmwqsrc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pycfn.com/Article/details/gt2qmtktdug.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ydzc1.top/Article/details/gt2deluwbvk.html

C#:   new List<int>(list);
来源：http://dali.daxiang520.top/Article/details/gt2mrkzpzps.html

[D23] reduce 累积计算
来源：http://dali.dashuyun.cn/Article/details/gt2rpvnplvx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2tejctmai.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.c1oappe.top/Article/details/gt2hqbpiols.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qikuaeif.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2kalrkxrs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hfpthk.cn/Article/details/gt2qmuiimlc.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gt2ptfrubkp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nwbrower.top/Article/details/gt2efyedyis.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fzhhl.top/Article/details/gt2mrtongmp.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigufen.top/Article/details/gt2suxuclmz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daxiang520.top/Article/details/gt2krgayspt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daria6918.cn/Article/details/gt2mcnklvpj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohsttlur.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2hckpkjms.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aizwys.cn/Article/details/gt2yeeolmxx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gt2ctylzker.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gaohongyu789.top/Article/details/gt2uceygdgo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.meibo888.top/Article/details/gt2nechfujj.html

[D25] Set 集合去重与交并差
来源：http://dali.aizwys.cn/Article/details/gt2vfrskozk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gt2kkhvrnfp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.bjfxy.top/Article/details/gt2udbhajif.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tcyxhpqd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hysaishi.cn/Article/details/gt2ehnegulo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dashuyun.cn/Article/details/gt2nupkixkg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.0kj1m.cn/Article/details/gt2pxnzgkqz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gt2svgrgyoj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gt2nkelrlpg.html

[D26] 数组转字符串
来源：http://dali.yvedp.cn/Article/details/gt2itkrfojx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.bjfxy.top/Article/details/gt2jkigderp.html

PHP:  implode(", ", $arr);
来源：http://dali.zycfv.cn/Article/details/gt2mhtdhcmr.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gt2vsajmpmy.html

TS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gt2dpestvdi.html

Java: String.join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gt2krrimdzn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sweek.top/Article/details/gt2zcoqtara.html

Ruby: arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gt2xqplkdyf.html

C#:   string.Join(", ", list)
来源：http://dali.cheryme.top/Article/details/gt2viovrhvj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2tuwmpvbm.html

E. 字符串处理
来源：http://dali.shuidangran.top/Article/details/gt2vjuahryd.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2wgarufie.html

[E01] 拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gt2utiywyjl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.mhx1999.top/Article/details/gt2jlwkqabz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zycfv.cn/Article/details/gt2zjapwxzg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gt2qvgeunpr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gt2whhspirt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hfpthk.cn/Article/details/gt2figxxpvg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daxiang520.top/Article/details/gt2uowkawyn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gt2svoenuav.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2eagqrhad.html

[E02] 重复字符串
来源：http://dali.yuanzhike.top/Article/details/gt2slwdpjje.html

Py:   "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gt2ottoabhs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2eyklwfkt.html

JS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gt2lvtzhowf.html

TS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gt2ruozeqvb.html

Java: "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gt2sbyhvtlk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.havefunace.top/Article/details/gt2uhfipalr.html

Ruby: "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gt2gelfyjxx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2povlnokv.html

[E03] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gt2swuyeycr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hywenlv.cn/Article/details/gt2shforcyp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gt2uvzsdkvf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2hrsuqxsk.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gt2talnztzs.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gt2ydefmpdi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zdqjudy.top/Article/details/gt2lbaatpio.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.bjfxy.top/Article/details/gt2hwflwdtb.html

C#:   s.Substring(1, 3)
来源：http://dali.hnqzz.top/Article/details/gt2tlqutoed.html

[E04] 查找子串位置
来源：http://dali.ivvv.top/Article/details/gt2eclrtsnu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ivvv.top/Article/details/gt2hlsiknxx.html

PHP:  strpos($s, "x");
来源：http://dali.zhongyouzk.top/Article/details/gt2uyejyqok.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cashguo.top/Article/details/gt2vtejuvpj.html

TS:   s.indexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gt2wqkbryyk.html

Java: s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gt2mlkguzst.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gt2bqpoynnx.html

Ruby: s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gt2oiepbjyh.html

C#:   s.IndexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gt2rixarvjv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daxiang520.top/Article/details/gt2cyxhcwqz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sxryk.cn/Article/details/gt2ggeknvja.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tianlin.xyz/Article/details/gt2wsdhtwty.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gt2zjdbdfaw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jiagoushi.top/Article/details/gt2ipzprrcm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2dweeeywt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnxiangtu.top/Article/details/gt2luulsuuq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.316326.xyz/Article/details/gt2hqkjcsfa.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzjvbcn.html

[E06] 替换子串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxjblhcx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gt2cvxjrfoz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnqzz.top/Article/details/gt2iklfkoiv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2fxzioiip.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2aqwvmjdc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2uenwezng.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gt2hwandetl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2vydsrfbo.html

C#:   s.Replace("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2vpjfffnl.html

[E07] 按分隔符拆分
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvsuffho.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ivvv.top/Article/details/gt2hdovyqwa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cheryme.top/Article/details/gt2nzveahiq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xziqi.cn/Article/details/gt2hugvqqto.html

TS:   s.split(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2fbhwpumw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dashuyun.cn/Article/details/gt2ecwcdufs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hammf.cn/Article/details/gt2jtwhvwgv.html

Ruby: s.split(",");  s.split
来源：http://dali.tanke756.top/Article/details/gt2xrynqfjj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jianghu66.top/Article/details/gt2enlkzepm.html

[E08] 数组按分隔符合并
来源：http://dali.wangdashe.top/Article/details/gt2dxxugjvx.html

Py:   ",".join(items)
来源：http://dali.meibo888.top/Article/details/gt2hwpgwdnb.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gt2etfgebdz.html

JS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gt2tkdvoryx.html

TS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gt2beveoeil.html

Java: String.join(",", items)
来源：http://dali.sweek.top/Article/details/gt2hevbywus.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gt2lryiqzis.html

Ruby: items.join(",")
来源：http://dali.hnqzz.top/Article/details/gt2yvjjtuko.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gt2nhvgvlyb.html

[E09] 去除所有空白字符
来源：http://dali.birdmap.top/Article/details/gt2ulflkfcf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cheryme.top/Article/details/gt2mxwiriep.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2aqagzuox.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gt2mmntitls.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gt2uezciphz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gt2lbtclxzk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpkfwkup.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pecrnxkt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gt2mvcbgaig.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yangfankeji.com/Article/details/gt2avlecfks.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2mqhbhyzu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gaohongyu789.top/Article/details/gt2nswhdnlr.html

JS:   "7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2jwkztmvn.html

TS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gt2xpmirizc.html

Java: String.format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2usfalolo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gt2vfhxgkvx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2alkyqucv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hongshengwenyu.top/Article/details/gt2pnksvdfb.html

[E11] 反转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2zsfvjevs.html

Py:   s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gt2gxchxeij.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gt2fsvlemik.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2zcibxyym.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cdkmgvsb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxqmhwau.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuanzx.com/Article/details/gt2pnbpebui.html

Ruby: s.reverse
来源：http://dali.svipenyu.cn/Article/details/gt2xuyoifza.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gt2bwjdpqwc.html

[E12] 统计某字符出现次数
来源：http://dali.yj202588.top/Article/details/gt2izdzzvps.html

Py:   s.count("a")
来源：http://dali.nwbrower.top/Article/details/gt2ezjmglus.html

PHP:  substr_count($s, "a");
来源：http://dali.redwolf501.top/Article/details/gt2mxxfaeky.html

JS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gt2dnjrysva.html

TS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gt2tcwshxyx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cheryme.top/Article/details/gt2orxnnmvu.html

Go:   strings.Count(s, "a")
来源：http://dali.ybcxt.top/Article/details/gt2ztfpbdwz.html

Ruby: s.count("a")
来源：http://dali.daria6918.cn/Article/details/gt2dnykrtpd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gt2acfixcyx.html

[E13] 逐字符遍历
来源：http://dali.guowangkeji.top/Article/details/gt2ueqavkiw.html

Py:   for ch in s: print(ch)
来源：http://dali.andypj.xyz/Article/details/gt2jgqudzee.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gt2mdiaeybr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gt2nkfpkoqc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2jtsvzqyc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2mbtuxvag.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lmaeteiz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jyoumei.cn/Article/details/gt2gyytaejq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhmzcrg.html

[E14] URL 编码与 Base64
来源：http://dali.chenlongwang.top/Article/details/gt2vjjvunfq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gt2bgounmvm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gssytmeb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gt2tqpyqpsf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.birdmap.top/Article/details/gt2zygmpwce.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gt2bdkgebcj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gaohongyu789.top/Article/details/gt2znpdueii.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zycfv.cn/Article/details/gt2ttizvtfl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yangfankeji.com/Article/details/gt2psqlvwly.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gt2qclenphl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cucudq.cn/Article/details/gt2mytfxrpk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gt2texkjjvb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yongpay.top/Article/details/gt2tdsiksxz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpxnyqn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fengsongda.top/Article/details/gt2gkvexowp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jianghu66.top/Article/details/gt2hdpdtqch.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gt2afprmrdv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gt2znzajnyd.html

[E16] 数字千分位
来源：http://dali.0kj1m.cn/Article/details/gt2krfzlcny.html

Py:   f"{1234567:,}"
来源：http://dali.hysaishi.cn/Article/details/gt2pqecrvoc.html

PHP:  number_format(1234567);
来源：http://dali.dianchejie.cn/Article/details/gt2vtehccxb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gt2pddslazy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gt2epihsrxm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gt2pwemfoas.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aizwys.cn/Article/details/gt2kbjcinkx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.iojbl.cn/Article/details/gt2oymabwhs.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yujksfyv.html

[E17] 首字母大写
来源：http://dali.pengpengdd.cyou/Article/details/gt2xyztdsox.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaaickn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gt2ejwhnuke.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gt2cqzeiyhe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gt2gtlgwxxc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sxryk.cn/Article/details/gt2batmgfgp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2krbiwchr.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2asjccxfq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.snrcjt.cn/Article/details/gt2oyxtracj.html

[E18] 模板占位符替换
来源：http://dali.snrcjt.cn/Article/details/gt2qzdlfmpx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dianchejie.cn/Article/details/gt2wwpqwzgt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gt2xdngfsjq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gt2qytmfimc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2mtwxszdv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2medvgzeq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2xgckpaiz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gt2erttmbxa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guowangkeji.top/Article/details/gt2udydojlt.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gt2wmevbpzt.html

Py:   s.splitlines()
来源：http://dali.guannengcc.top/Article/details/gt2usbxebqs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shuidangran.top/Article/details/gt2peqeynks.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gjgqbeaa.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gt2kltjpxvv.html

Java: s.lines().toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2rlljzmnm.html

Go:   strings.Split(s, "\n")
来源：http://dali.yongpay.top/Article/details/gt2nepaeemd.html

Ruby: s.lines
来源：http://dali.cqqwz.cn/Article/details/gt2uumtloth.html

C#:   s.Split('\n')
来源：http://dali.gogol.net.cn/Article/details/gt2jqoabsaa.html

[E20] 判断字符串是否为空
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2esbxngzt.html

Py:   if not s:
来源：http://dali.tianlin.xyz/Article/details/gt2lzelhxvv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gt2snuhjzzp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gt2kyihyell.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gt2tkxndbbi.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2yntxgrtq.html

Go:   if s == "" {}
来源：http://dali.smart0.xyz/Article/details/gt2casqowpz.html

Ruby: if s.empty?
来源：http://dali.yueranfly.top/Article/details/gt2djhhcqhx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenlongwang.top/Article/details/gt2thwyqklj.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gt2cumtzwbm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhoulong.xyz/Article/details/gt2xysdxeqt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2umorfsch.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2grwcidjt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2odkakwid.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2reanxbgp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.9152youxi.cn/Article/details/gt2atyboqro.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2khnzwklw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2wohfhhkg.html

[E22] 字节长度与字符长度
来源：http://dali.cdnleiting.top/Article/details/gt2mwfqsfkn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gt2wiohvsun.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2fgvmfawn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gt2ixufrlnu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2ohvekzgy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.haohaochexian.top/Article/details/gt2rizbhwtp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sxryk.cn/Article/details/gt2lleynveg.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2mxblzabi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gt2vnfvckeq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2cslmhgxy.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gt2mjhqocls.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2elkyugku.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmzdovgm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2znmjasia.html

PHP:  file_get_contents("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2zgvnxnra.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.mhx1999.top/Article/details/gt2leuhyqch.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cheryme.top/Article/details/gt2dhmzogtz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ypbfsyhi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hywenlv.cn/Article/details/gt2bhanathj.html

Ruby: File.read("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2djnmubtw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxnpxebk.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wkvezoyu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.birdmap.top/Article/details/gt2ryllltbe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jiagoushi.top/Article/details/gt2sfqzmzqf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gt2cialcaag.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzmrgmt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gt2xzqcfcgq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gt2hdwrwjgv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gt2yoejhlvd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gzhubu.top/Article/details/gt2earfmgyk.html

[F03] 写入文件（覆盖）
来源：http://dali.c1oappe.top/Article/details/gt2bbuyidfr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gotoacloud.top/Article/details/gt2ninyyhhb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gt2cmnvhclj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gt2zxuojegr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gt2nrjinhwg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jlsjyb.cn/Article/details/gt2mkkrdvzn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xinyue.icu/Article/details/gt2xjhqldws.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qunrvkas.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gt2mjydbxfb.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gt2rpqldcpp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2eumyzwsp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xinyue.icu/Article/details/gt2fsljfbre.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gt2axmlawdm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2zwohhdjz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yangfankeji.com/Article/details/gt2ukyqutxn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2veqbfsjx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gt2wgdgzjaf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj202588.top/Article/details/gt2uvoqufzb.html

[F05] 判断文件或目录是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2oaxujupj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpsnthd.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2ynjgaogu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2wyfxljis.html


<!-- 参考信息 -->