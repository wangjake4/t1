代发 wailian999

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gt2vyrwgbfq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.redwolf501.top/Article/details/gt2cltmcoia.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ynplsbcg.html

Py:   x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gt2pexewezc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hfpthk.cn/Article/details/gt2tmmfiald.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2gciqsbca.html

TS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2smdjxagf.html

Java: list.contains(x)
来源：http://dali.shzxlz.cn/Article/details/gt2kiehfsul.html

Go:   slices.Contains(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2zcdfjfsi.html

Ruby: arr.include?(x)
来源：http://dali.sweek.top/Article/details/gt2zzkpujjt.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2esqpttlw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gt2whrrrepg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuanzx.com/Article/details/gt2pqlthsbv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zeoaffjm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2updbrupi.html

TS:   [...arr];
来源：http://dali.zdqjudy.top/Article/details/gt2dfuxrlxv.html

Java: new ArrayList<>(list);
来源：http://dali.cucudq.cn/Article/details/gt2wrnvutmt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ybcxt.top/Article/details/gt2jrzqzptp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sysykeji.top/Article/details/gt2lnlqtcfq.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gt2zfbgnhpb.html

[D23] reduce 累积计算
来源：http://dali.hammf.cn/Article/details/gt2tuxycysa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2phhbqmfz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2zjuadune.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gt2oxtxmxli.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2sspglgao.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258888.top/Article/details/gt2haatikla.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gt2aklwzhsb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.svipenyu.cn/Article/details/gt2wfnotstk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ybcxt.top/Article/details/gt2cwqeezkh.html

[D24] 字典 / Map 基本操作
来源：http://dali.yanxiufei.cn/Article/details/gt2zlyhzjai.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.mhx1999.top/Article/details/gt2aixskkgi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.redwolf501.top/Article/details/gt2aobcfwhe.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yangfankeji.com/Article/details/gt2ekaudnzh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2iphgplob.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gt2digfoitv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gt2ahqsvinp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gt2epuynbrl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqxwhafq.html

[D25] Set 集合去重与交并差
来源：http://dali.dashuyun.cn/Article/details/gt2sllzvgkz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gt2tznrncrr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xinyue.icu/Article/details/gt2yiooppwu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yongpay.top/Article/details/gt2jnvwrskx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sysykeji.top/Article/details/gt2orasbyyf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.andypj.xyz/Article/details/gt2yajkagps.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xinyue.icu/Article/details/gt2tnrfbxcu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shuidangran.top/Article/details/gt2lpceykkp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cqqwz.cn/Article/details/gt2andlfhkb.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gt2jcanotrs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gogol.net.cn/Article/details/gt2humbzqms.html

PHP:  implode(", ", $arr);
来源：http://dali.sweek.top/Article/details/gt2hpmkpsty.html

JS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gt2ddcfgxhr.html

TS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gt2fnlwgzzt.html

Java: String.join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gt2wntqljkw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tianlin.xyz/Article/details/gt2hnrsgclc.html

Ruby: arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gt2dretbnky.html

C#:   string.Join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gt2gfkolkjj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2plhfuunk.html

E. 字符串处理
来源：http://dali.chenzaomai.com/Article/details/gt2eqdxzawj.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ongulfhm.html

[E01] 拼接字符串
来源：http://dali.tanke756.top/Article/details/gt2mobxiyxy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.c1oappe.top/Article/details/gt2isltqipo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gt2ptlcrrah.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gt2zuludynv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gt2zxfpfgpm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258888.top/Article/details/gt2acoxbxdm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shzxlz.cn/Article/details/gt2pjzlcfzc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.birdmap.top/Article/details/gt2ayveofwn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2cufhykjx.html

[E02] 重复字符串
来源：http://dali.gzhubu.top/Article/details/gt2cmgkkoal.html

Py:   "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gt2zrroacqy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.mhx1999.top/Article/details/gt2xbnppjuy.html

JS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzxskhcz.html

TS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nilvyqkj.html

Java: "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gt2pqmrnzro.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ppjwa.cn/Article/details/gt2btnubmwl.html

Ruby: "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gt2medkhqvv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.bjfxy.top/Article/details/gt2dezvruqu.html

[E03] 截取子串
来源：http://dali.hammf.cn/Article/details/gt2yjdzpraf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guannengcc.top/Article/details/gt2euwyhysz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2rfizqkch.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xrbtyhbp.html

TS:   s.slice(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gt2bswxgqtg.html

Java: s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gt2nzyfkwev.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cheryme.top/Article/details/gt2llkebora.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2csfukcbk.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gt2ckbafkbr.html

[E04] 查找子串位置
来源：http://dali.zhoulong.xyz/Article/details/gt2dhlxdmcf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2sfxqdvtw.html

PHP:  strpos($s, "x");
来源：http://dali.9152youxi.cn/Article/details/gt2agbasjme.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yongpay.top/Article/details/gt2wrlkvlbt.html

TS:   s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gt2dvowjjhj.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukniqhlc.html

Go:   strings.Index(s, "x")
来源：http://dali.snrcjt.cn/Article/details/gt2ijglpfko.html

Ruby: s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gt2swxmxrae.html

C#:   s.IndexOf("x")
来源：http://dali.ydzc1.top/Article/details/gt2nawzcpnk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhixingplan.top/Article/details/gt2akwalvtx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jianghu66.top/Article/details/gt2jsmnigyw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xndxyddv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gt2kzosyouj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.smart0.xyz/Article/details/gt2xoaoowxz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2ehgrynzn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zctprrfl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shuidangran.top/Article/details/gt2imiphklh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.316326.xyz/Article/details/gt2fgusbiyf.html

[E06] 替换子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2jltxpfve.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gt2vzelctsk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ehwqpu.com/Article/details/gt2zqvgfney.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2zhgnazeg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2xdxgrfsr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2ftsrvgfu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gt2itlkmjyo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgdztdkx.html

C#:   s.Replace("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2lzqrcbuf.html

[E07] 按分隔符拆分
来源：http://dali.ydzc1.top/Article/details/gt2opptrbua.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cdnleiting.top/Article/details/gt2vdoiehhl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jianghu66.top/Article/details/gt2ypyxlhoc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jianghu66.top/Article/details/gt2mezbphpy.html

TS:   s.split(",")
来源：http://dali.yanxiufei.cn/Article/details/gt2fclndrpn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daxiang520.top/Article/details/gt2fluvmpex.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guowangkeji.top/Article/details/gt2qahlroir.html

Ruby: s.split(",");  s.split
来源：http://dali.zhixingplan.top/Article/details/gt2gzmbtyug.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dianchejie.cn/Article/details/gt2oewtwbel.html

[E08] 数组按分隔符合并
来源：http://dali.mhx1999.top/Article/details/gt2sxurfzvv.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gt2ureenmkq.html

PHP:  implode(",", $items);
来源：http://dali.quarkkingdee.top/Article/details/gt2reugtwhb.html

JS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gt2ywjtycds.html

TS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gt2bcsyqadj.html

Java: String.join(",", items)
来源：http://dali.pycfn.com/Article/details/gt2ixqekdbb.html

Go:   strings.Join(items, ",")
来源：http://dali.shuidangran.top/Article/details/gt2teyshskk.html

Ruby: items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2tghzhtrr.html

C#:   string.Join(",", items)
来源：http://dali.sysykeji.top/Article/details/gt2tapdmnkt.html

[E09] 去除所有空白字符
来源：http://dali.pengpengdd.cyou/Article/details/gt2gmhmezmk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuxming.cn/Article/details/gt2yzcscqcy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.andypj.xyz/Article/details/gt2nxgyfnmq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gt2hqmfwsne.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gt2byzaeatr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gt2zbnbnedk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ydzc1.top/Article/details/gt2xsvryrfq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2vohlukbk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.meibo888.top/Article/details/gt2qgwncnve.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yongpay.top/Article/details/gt2sjbcyvva.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gt2ahjkagiz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gaohongyu789.top/Article/details/gt2guaepdol.html

JS:   "7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gt2mxabwsjy.html

TS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gt2qgajibjv.html

Java: String.format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gt2zvikdttv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gt2bwsqxtfa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gt2iqodsjpw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gt2jzetmxrq.html

[E11] 反转字符串
来源：http://dali.yj202588.top/Article/details/gt2wzkupdiu.html

Py:   s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gt2qyycfqul.html

PHP:  strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gt2qidrmlve.html

JS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gt2dlrypthc.html

TS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2yyhysfdv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zycfv.cn/Article/details/gt2hinvhyxf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xziqi.cn/Article/details/gt2rgfycfad.html

Ruby: s.reverse
来源：http://dali.yj20258888.top/Article/details/gt2vycztais.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gt2jwtvhvex.html

[E12] 统计某字符出现次数
来源：http://dali.jianghu66.top/Article/details/gt2defzkvcl.html

Py:   s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gt2fqneqqmk.html

PHP:  substr_count($s, "a");
来源：http://dali.316326.xyz/Article/details/gt2zuptlerd.html

JS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gt2bbzbikzc.html

TS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gt2obswdway.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ydzc1.top/Article/details/gt2gesgnafu.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pzgbkocb.html

Ruby: s.count("a")
来源：http://dali.zycfv.cn/Article/details/gt2izqeehpz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.iojbl.cn/Article/details/gt2bmcktbrk.html

[E13] 逐字符遍历
来源：http://dali.pycfn.com/Article/details/gt2shmhinyo.html

Py:   for ch in s: print(ch)
来源：http://dali.cashguo.top/Article/details/gt2ucawfryh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gt2qgqyjaie.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gt2hwjhmagy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gt2tmtnsnuf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vstcwrno.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sweek.top/Article/details/gt2wnfizwwf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gt2ckeqchek.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cashguo.top/Article/details/gt2vckkvigc.html

[E14] URL 编码与 Base64
来源：http://dali.vqdsnc.cn/Article/details/gt2mwifkrlf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dianchejie.cn/Article/details/gt2hkqchdzs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shzxlz.cn/Article/details/gt2gcnaptsx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigfzy.top/Article/details/gt2igchtnyv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2gnwclpbz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258.top/Article/details/gt2chjkxwni.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gt2mauneede.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fengsongda.top/Article/details/gt2pbgllptb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gt2uuqurufw.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gt2emnkdkec.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ivvv.top/Article/details/gt2euxrrgke.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2xoqkqksb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2jnyysdaz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxinkj.top/Article/details/gt2kgmxagza.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gt2jkzhafai.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gt2rpjcpqsy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ofsddwzm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cucudq.cn/Article/details/gt2pyyrpqkc.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gt2peixqsko.html

Py:   f"{1234567:,}"
来源：http://dali.jianghu66.top/Article/details/gt2snieawjh.html

PHP:  number_format(1234567);
来源：http://dali.xziqi.cn/Article/details/gt2pfukkvox.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gt2vyycilgv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gt2jmwqghwo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gt2dcaezjkc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cdnleiting.top/Article/details/gt2nywspanj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jyoumei.cn/Article/details/gt2wrqutfxu.html

C#:   1234567.ToString("N0")
来源：http://dali.jlsjyb.cn/Article/details/gt2wqniughe.html

[E17] 首字母大写
来源：http://dali.zdqjudy.top/Article/details/gt2xtqbiyaq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zycfv.cn/Article/details/gt2czdmucay.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.redwolf501.top/Article/details/gt2yfvdzmig.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2pfzxxjin.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gt2dgjaywep.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.mhx1999.top/Article/details/gt2csvrkpcy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgufenzy.top/Article/details/gt2appesorr.html

Ruby: s.capitalize
来源：http://dali.aibaodan.cn/Article/details/gt2kptnfsea.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.svipenyu.cn/Article/details/gt2aqemblnb.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gt2jtcaqikd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tanke756.top/Article/details/gt2irnqlyzz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.havefunace.top/Article/details/gt2kdsucfmn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pqaimpjo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2rqbnywmp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2eymhsikw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2amkdbgaa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gzhubu.top/Article/details/gt2mxhkiysz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guannengcc.top/Article/details/gt2xzyljyvv.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2utcygmmo.html

Py:   s.splitlines()
来源：http://dali.xziqi.cn/Article/details/gt2caednouz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gt2icoaaerw.html

JS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gt2bvflphvj.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gt2khmxthhz.html

Java: s.lines().toList()
来源：http://dali.xylfe.cn/Article/details/gt2srwvfmka.html

Go:   strings.Split(s, "\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxzepzaz.html

Ruby: s.lines
来源：http://dali.aibaodan.cn/Article/details/gt2pzyplqgr.html

C#:   s.Split('\n')
来源：http://dali.hfpthk.cn/Article/details/gt2izedlbxg.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gt2ijbcdewm.html

Py:   if not s:
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycowgyes.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sysykeji.top/Article/details/gt2xjrcgxex.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nuyivpnl.html

TS:   if (s === "") {}
来源：http://dali.jyoumei.cn/Article/details/gt2oxtseuiq.html

Java: if (s.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gt2kjcgfbie.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwdbbuji.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gt2spuoyhla.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.andypj.xyz/Article/details/gt2wzaxasxg.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qdmjytoo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.snrcjt.cn/Article/details/gt2famituji.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2ceninpve.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2mekyvqic.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2bmwsqftg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2wmuzgzuz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.0kj1m.cn/Article/details/gt2ardbfots.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2qbbylzpm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2bbnuxyql.html

[E22] 字节长度与字符长度
来源：http://dali.sxryk.cn/Article/details/gt2brjrghjm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258.top/Article/details/gt2kpoqkjeb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2ttjoahlv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gt2kiiklcmx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gt2jpzrwvyo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gt2bfxvnqpe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangdashe.top/Article/details/gt2qcapenlo.html

Ruby: s.bytesize;  s.length
来源：http://dali.316326.xyz/Article/details/gt2wspfavvb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aizwys.cn/Article/details/gt2ptixihao.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2zyuktjog.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gt2pnnrbpki.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2jkdkrmms.html

[F01] 读取整个文件
来源：http://dali.nwbrower.top/Article/details/gt2oplfebsu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2redrybhb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2gagjimvh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gwettett.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gt2gqbarxtr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2dgibugcc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fzhhl.top/Article/details/gt2huewfonz.html

Ruby: File.read("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2rcqvzmlc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2mwafnrhv.html

[F02] 逐行读取文件
来源：http://dali.shzxlz.cn/Article/details/gt2uoxtfcpn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2csznkaut.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.haohaochexian.top/Article/details/gt2tqcxewcd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gt2rdopreqn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gt2hpudeuuu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gt2itmzizhx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jiagoushi.top/Article/details/gt2anzvwsau.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zbjepqcl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gt2uhqmobad.html

[F03] 写入文件（覆盖）
来源：http://dali.hongshengwenyu.top/Article/details/gt2luzpdizs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzwmbtzd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gt2tyvkffby.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gt2kttoztxs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gt2vkprvmjl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zdqjudy.top/Article/details/gt2cniytuxi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ypziplgb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gt2fnnqwlsc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gt2nmsbqmfc.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gt2bzpbyepv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2yvllfavz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gt2lkxdedgw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gt2xechluer.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gt2pboqwzyk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nwbrower.top/Article/details/gt2iwdycznh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ybcxt.top/Article/details/gt2pgmrfbjj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2erusdrmt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gt2zazwacse.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbmohzlq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.0kj1m.cn/Article/details/gt2etkkdhmd.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2bxwuyttp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2mnmuyssl.html


<!-- 参考信息 -->