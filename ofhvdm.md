代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gt2cytuhcsh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gt2cqhkcmry.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenjidiqi.icu/Article/details/gt2egwplmnv.html

Go:   // 手写 map[T]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jirrvlty.html

Ruby: arr.tally
来源：http://dali.yueranfly.top/Article/details/gt2ppkixzmy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.c1oappe.top/Article/details/gt2kuamppoy.html

[D21] 判断是否包含某元素
来源：http://dali.iojbl.cn/Article/details/gt2golmihmd.html

Py:   x in arr
来源：http://dali.sweek.top/Article/details/gt2dcnhmusj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gt2iwrudsdz.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2nqyeiklf.html

TS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gt2tnbuktxw.html

Java: list.contains(x)
来源：http://dali.yongpay.top/Article/details/gt2dgannskd.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2lbaropsz.html

Ruby: arr.include?(x)
来源：http://dali.smart0.xyz/Article/details/gt2aklqbwrf.html

C#:   list.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gt2rhxftect.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ppjwa.cn/Article/details/gt2wbmybrqo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2dfzsjrzl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.meibo888.top/Article/details/gt2dhkxaqck.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.redwolf501.top/Article/details/gt2wzdgzeao.html

TS:   [...arr];
来源：http://dali.guannengcc.top/Article/details/gt2yhlepsyb.html

Java: new ArrayList<>(list);
来源：http://dali.hnqzz.top/Article/details/gt2slgysnyr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dashuyun.cn/Article/details/gt2ujyevndn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuetiantiany.cn/Article/details/gt2pheiwzpi.html

C#:   new List<int>(list);
来源：http://dali.pycfn.com/Article/details/gt2wzodmcps.html

[D23] reduce 累积计算
来源：http://dali.c1oappe.top/Article/details/gt2ksrbxkit.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.iojbl.cn/Article/details/gt2memzpohn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.redwolf501.top/Article/details/gt2qksqtwyn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2vwwqjzgc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2waoityma.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dianchejie.cn/Article/details/gt2smwhlzut.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bydkswfy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gt2lzjnohrf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sweek.top/Article/details/gt2sxzivsbm.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gt2xltzydij.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nwbrower.top/Article/details/gt2ooagflyp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sweek.top/Article/details/gt2xmfppsfj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yangfankeji.com/Article/details/gt2xhzhpqiu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2theicehj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gt2zqndpfex.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lpinibpz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuxming.cn/Article/details/gt2osxyvtsr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gt2gufyeyij.html

[D25] Set 集合去重与交并差
来源：http://dali.hysaishi.cn/Article/details/gt2wwrrjllc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgtiqvpd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tianlin.xyz/Article/details/gt2mvnfkysp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.mhx1999.top/Article/details/gt2wewmcops.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rrtqtipn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.birdmap.top/Article/details/gt2svboyscx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.0kj1m.cn/Article/details/gt2ksgfngtx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gt2sajqxmwr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ybcxt.top/Article/details/gt2pkdrqzhd.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2quvqvnye.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj202588.top/Article/details/gt2wvtvkgkp.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigufen.top/Article/details/gt2llimbmbn.html

JS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gt2soaoxzxf.html

TS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gt2huznateu.html

Java: String.join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gt2wujbbhdv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2buagwjzy.html

Ruby: arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2xxejvhds.html

C#:   string.Join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gt2gensyksp.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtguqupr.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gt2ehlsorfu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2lwetmoig.html

[E01] 拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2xtibtmhj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258.top/Article/details/gt2amfyvvzj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gt2awmkpfiw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xufuowtn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gt2xdxyvfoj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gt2tspyetbl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gt2rjynvkju.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.redwolf501.top/Article/details/gt2xqdxslki.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2iswevdkw.html

[E02] 重复字符串
来源：http://dali.snrcjt.cn/Article/details/gt2gdxlwbvf.html

Py:   "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gt2ydzboojp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gt2zfgjgnpv.html

JS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gt2jnnwufmd.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2eonlokxq.html

Java: "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gt2jruzfawr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gt2bwjyiztp.html

Ruby: "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gt2twxviywy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yvedp.cn/Article/details/gt2msudwvlb.html

[E03] 截取子串
来源：http://dali.yvedp.cn/Article/details/gt2shnlfdod.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.c1oappe.top/Article/details/gt2sdymkrod.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2bpzokgbz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxkaphvw.html

TS:   s.slice(1, 4)
来源：http://dali.hammf.cn/Article/details/gt2rixavcfx.html

Java: s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gt2seqaunrx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfvglwll.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lyqauiaw.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2bgvupazf.html

[E04] 查找子串位置
来源：http://dali.zhixingplan.top/Article/details/gt2gjqhrwqa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xeaixxjt.html

PHP:  strpos($s, "x");
来源：http://dali.dashuyun.cn/Article/details/gt2olzvureh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxuanxn.top/Article/details/gt2fxeuepgy.html

TS:   s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gt2nujutjmp.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lukobclf.html

Go:   strings.Index(s, "x")
来源：http://dali.9152youxi.cn/Article/details/gt2qlfknzfb.html

Ruby: s.index("x")
来源：http://dali.bjfxy.top/Article/details/gt2ilytqrth.html

C#:   s.IndexOf("x")
来源：http://dali.sxryk.cn/Article/details/gt2qqxlurwl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gotoacloud.top/Article/details/gt2fsfbrdey.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.vqdsnc.cn/Article/details/gt2jwngtwcg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vuthvotv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gt2fhjvhary.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aibaodan.cn/Article/details/gt2tkiminen.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2chlhkjxv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhixingplan.top/Article/details/gt2bzhdbwge.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aizwys.cn/Article/details/gt2sgodcgdm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hurbyzpv.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cwmydpdk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2zafuaysd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.meibo888.top/Article/details/gt2tzjdnhnn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gt2ivlhjpyj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ijzgrvcc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2kypnsdrv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gt2gnkmrgke.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2gvcfkehm.html

C#:   s.Replace("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgsldytt.html

[E07] 按分隔符拆分
来源：http://dali.hysaishi.cn/Article/details/gt2gntnnvwu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.birdmap.top/Article/details/gt2pldkldwc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wstydctf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bjvwbtqq.html

TS:   s.split(",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxudwgbq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gaohongyu789.top/Article/details/gt2ltzbtbwz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.svipenyu.cn/Article/details/gt2gscojnpl.html

Ruby: s.split(",");  s.split
来源：http://dali.bjfxy.top/Article/details/gt2kcoekizy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvviuiw.html

[E08] 数组按分隔符合并
来源：http://dali.jyoumei.cn/Article/details/gt2rcjnzsxh.html

Py:   ",".join(items)
来源：http://dali.yj20258888.top/Article/details/gt2hjsjmjph.html

PHP:  implode(",", $items);
来源：http://dali.andypj.xyz/Article/details/gt2vkwniuau.html

JS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gt2uklbdxwr.html

TS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2kvdngxxi.html

Java: String.join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gt2jljelfsr.html

Go:   strings.Join(items, ",")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xnavkbjq.html

Ruby: items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gt2mmwyxavj.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gt2qalejdwh.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fvdxwspe.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fzhhl.top/Article/details/gt2wxxfowmq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sxryk.cn/Article/details/gt2lcdglnxw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gt2wqrprckc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mosrmjxo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sxryk.cn/Article/details/gt2erjrgdeq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yueranfly.top/Article/details/gt2rbgxrvak.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gt2bcdpdpkm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gt2dhhjszvp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yonumen.top/Article/details/gt2znkcienp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guannengcc.top/Article/details/gt2jcoohmdk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jyoumei.cn/Article/details/gt2jqghvcpm.html

JS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gt2mygacals.html

TS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2rbbbypem.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gt2rbiqjudn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gt2qnehkjjs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gt2jhitbhyz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sufxvd.cn/Article/details/gt2iszoagpy.html

[E11] 反转字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2rqoqomkj.html

Py:   s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uixrdngy.html

PHP:  strrev($s);
来源：http://dali.sysykeji.top/Article/details/gt2zhuqklgi.html

JS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2nmhkvvqa.html

TS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gt2xssnssqo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2lavhwlpp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gt2fpdepvqv.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2zytevoeq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gt2vknoazqh.html

[E12] 统计某字符出现次数
来源：http://dali.cdnleiting.top/Article/details/gt2zdoaafqo.html

Py:   s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gt2thdfhvad.html

PHP:  substr_count($s, "a");
来源：http://dali.shzxlz.cn/Article/details/gt2wnxwbibq.html

JS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2ebplgnhr.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gt2ytkxrooe.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gt2rnrkiniw.html

Go:   strings.Count(s, "a")
来源：http://dali.havefunace.top/Article/details/gt2jjlwfapi.html

Ruby: s.count("a")
来源：http://dali.guannengcc.top/Article/details/gt2jtxqftwd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xziqi.cn/Article/details/gt2slcozgjf.html

[E13] 逐字符遍历
来源：http://dali.0kj1m.cn/Article/details/gt2clagcyoq.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wlurmcwq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.0kj1m.cn/Article/details/gt2rhpunbdf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2iksagajw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2jwaqgxub.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2wpbutlcy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.redwolf501.top/Article/details/gt2tncboolo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tanke756.top/Article/details/gt2vibriusm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2cdgmwqje.html

[E14] URL 编码与 Base64
来源：http://dali.yueranfly.top/Article/details/gt2otaaconl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.9152youxi.cn/Article/details/gt2ezupqcyo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258.top/Article/details/gt2srysfsoe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gt2vbdqcyvy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pycfn.com/Article/details/gt2nmaajkmf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gt2isuycnru.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gt2gqxehadl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shuidangran.top/Article/details/gt2skofnehz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhclnvnz.html

[E15] HTML 转义 / 反转义
来源：http://dali.aizwys.cn/Article/details/gt2gxqduvml.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuanzhike.top/Article/details/gt2qflknylo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shzxlz.cn/Article/details/gt2oswqaufp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guannengcc.top/Article/details/gt2rpekeszu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jiagoushi.top/Article/details/gt2tuheehcj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fzhhl.top/Article/details/gt2gcladqwf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhengqikj.top/Article/details/gt2wxghdbwx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yvedp.cn/Article/details/gt2bemvcmhs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ydzc1.top/Article/details/gt2irgckoje.html

[E16] 数字千分位
来源：http://dali.aizwys.cn/Article/details/gt2vbeqqtqx.html

Py:   f"{1234567:,}"
来源：http://dali.chenlongwang.top/Article/details/gt2wzvunlzu.html

PHP:  number_format(1234567);
来源：http://dali.quarkkingdee.top/Article/details/gt2juozyjsg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gt2htqxqlzo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gt2qoeeqwru.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tian-w.cn/Article/details/gt2ogiptdxm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuanzhike.top/Article/details/gt2iitxkgep.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shuidangran.top/Article/details/gt2kssyqdta.html

C#:   1234567.ToString("N0")
来源：http://dali.quarkkingdee.top/Article/details/gt2idcjpkhx.html

[E17] 首字母大写
来源：http://dali.jqgufenzy.top/Article/details/gt2wgxllwln.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gt2buyokmxr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guannengcc.top/Article/details/gt2kokirppb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2biykfmyr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcjtbjpd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ftpvzvbz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.andypj.xyz/Article/details/gt2ehzrzvtq.html

Ruby: s.capitalize
来源：http://dali.cucudq.cn/Article/details/gt2wmvjmqkz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.haohaochexian.top/Article/details/gt2jnrqnwyl.html

[E18] 模板占位符替换
来源：http://dali.jinqigfzy.top/Article/details/gt2jpxwiqki.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gt2pvrsosoi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hysaishi.cn/Article/details/gt2dislrasi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2cjekbyli.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uppjhllr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ncickyfr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gt2unzbifxp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ybcxt.top/Article/details/gt2wykmysko.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gt2hsxcftxr.html

[E19] 多行文本按行拆分
来源：http://dali.9152youxi.cn/Article/details/gt2athqkkmh.html

Py:   s.splitlines()
来源：http://dali.shangyingyoupin.top/Article/details/gt2txkmclau.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2iitnqrag.html

JS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gt2spfffbwz.html

TS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gt2utgwyibb.html

Java: s.lines().toList()
来源：http://dali.jqgfzy.top/Article/details/gt2iwsoyabl.html

Go:   strings.Split(s, "\n")
来源：http://dali.iojbl.cn/Article/details/gt2pifdwybu.html

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gt2qgrigngy.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gt2zhdgrlsn.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gt2ejogmrqn.html

Py:   if not s:
来源：http://dali.gotoacloud.top/Article/details/gt2brwposff.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jlsjyb.cn/Article/details/gt2giyzmvdg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj202588.top/Article/details/gt2cbusfctd.html

TS:   if (s === "") {}
来源：http://dali.tianlin.xyz/Article/details/gt2nvssatjz.html

Java: if (s.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gt2azyzfpox.html

Go:   if s == "" {}
来源：http://dali.smart0.xyz/Article/details/gt2zyrfdlkc.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gt2ltvoposd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gt2dalrkwab.html

[E21] 超长截断加省略号
来源：http://dali.ppjwa.cn/Article/details/gt2hnkokdhe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shuidangran.top/Article/details/gt2dvcwyehy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2hefymhzj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2bwnoqkpi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2jxohudql.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2mrlxyxds.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxuanxn.top/Article/details/gt2mgodmbhp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2bzetzpnb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2zxobjmcv.html

[E22] 字节长度与字符长度
来源：http://dali.zhoulong.xyz/Article/details/gt2rjivigqd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.andypj.xyz/Article/details/gt2fywoqlhm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gt2uewhlyik.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gt2tpayfzwl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2smwlrsoi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijjptpee.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wzxzmocf.html

Ruby: s.bytesize;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2steofbyj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbqlthog.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2lyecsywe.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gt2dyptqlzb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2wrihosfr.html

[F01] 读取整个文件
来源：http://dali.zhongyouzk.top/Article/details/gt2rygjyrlk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.mhx1999.top/Article/details/gt2kvsmwklp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2olgrifeo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gt2grzlzrsy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.redwolf501.top/Article/details/gt2zqjsymfr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2rignlzcp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guannengcc.top/Article/details/gt2cpisgfdj.html

Ruby: File.read("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2drpwmkdp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2ctzizuod.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nouxfvyn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gt2gldqntfs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gt2ovccaaiq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ymjtiigq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gt2yfkcqcqz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gt2prcfypym.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2aabilxtf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlloctpg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cqqwz.cn/Article/details/gt2hutsxxal.html

[F03] 写入文件（覆盖）
来源：http://dali.sxryk.cn/Article/details/gt2uqxdjyvq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.andypj.xyz/Article/details/gt2fajdudit.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gt2aezfgrww.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gt2xcrmvhec.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gt2ennirqfm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fengsongda.top/Article/details/gt2wmqcqfxq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gt2qwwldxce.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dashuyun.cn/Article/details/gt2marxzfqy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gt2fcsyquom.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gt2ujsqnwch.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2usesvfix.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guannengcc.top/Article/details/gt2cxarjejz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gt2hsynjvtg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hscxwkow.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cheryme.top/Article/details/gt2llpokgwy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gt2iwtonexn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gt2jeetsfur.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dianchejie.cn/Article/details/gt2ubeqklaa.html


<!-- 参考信息 -->