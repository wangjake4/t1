代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2vvfmmtcr.html

Ruby: arr.include?(x)
来源：http://dali.fengsongda.top/Article/details/gt2kphtzwer.html

C#:   list.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2gwazxwyb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gt2ogzsmzet.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258.top/Article/details/gt2kbrfbwoc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.haohaochexian.top/Article/details/gt2rvvumisq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htfshvvd.html

TS:   [...arr];
来源：http://dali.haohaochexian.top/Article/details/gt2kddvddie.html

Java: new ArrayList<>(list);
来源：http://dali.ppjwa.cn/Article/details/gt2znmfrtki.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hfpthk.cn/Article/details/gt2vbxxangh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aibaodan.cn/Article/details/gt2yrrxsdqo.html

C#:   new List<int>(list);
来源：http://dali.zycfv.cn/Article/details/gt2yegenpzm.html

[D23] reduce 累积计算
来源：http://dali.svipenyu.cn/Article/details/gt2qsleuvum.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gt2vkrrlxoe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2sumqsbtz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gt2yrecyqry.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jneyvtgw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pycfn.com/Article/details/gt2fsgkirbw.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gt2wndfkpuz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gt2ghuyxxjr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.bjfxy.top/Article/details/gt2dmnrsajd.html

[D24] 字典 / Map 基本操作
来源：http://dali.ybcxt.top/Article/details/gt2xpovycwf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ybcxt.top/Article/details/gt2jdhiwukp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2chhprspl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dtehozfl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2njogzpre.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yueranfly.top/Article/details/gt2iosipsax.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sufxvd.cn/Article/details/gt2vtemsvhd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwuendka.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ivvv.top/Article/details/gt2wrggyzsf.html

[D25] Set 集合去重与交并差
来源：http://dali.meibo888.top/Article/details/gt2vbydsjrb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zdqjudy.top/Article/details/gt2nanumkow.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gt2leoxfoeb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gogol.net.cn/Article/details/gt2etynrsew.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guowangkeji.top/Article/details/gt2pvbalehy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.birdmap.top/Article/details/gt2wxwyyswx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgfzy.top/Article/details/gt2ramcqxjc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sysykeji.top/Article/details/gt2oscbavwq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ehwqpu.com/Article/details/gt2faqusonl.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gt2mvvrpanv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigufen.top/Article/details/gt2deojzoey.html

PHP:  implode(", ", $arr);
来源：http://dali.nwbrower.top/Article/details/gt2axryekcz.html

JS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2xwhvngjh.html

TS:   arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2reilsbew.html

Java: String.join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gt2ocnhqgok.html

Go:   strings.Join(strs, ", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2bbdqorqu.html

Ruby: arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gt2vowjeugw.html

C#:   string.Join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gt2lqsvgtxj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2kjgulvtg.html

E. 字符串处理
来源：http://dali.tian-w.cn/Article/details/gt2jbdurfkg.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2dkvgbboj.html

[E01] 拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gt2hrjthesa.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhixingplan.top/Article/details/gt2fepoknmc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenlongwang.top/Article/details/gt2kbbzktod.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gt2pynwrynz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gt2sxnialhd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.vqdsnc.cn/Article/details/gt2xcmlzbch.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sysykeji.top/Article/details/gt2bmfmatkk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.redwolf501.top/Article/details/gt2oqwgvchp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2hswmjkgs.html

[E02] 重复字符串
来源：http://dali.yj20258.top/Article/details/gt2kqsknxlm.html

Py:   "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gt2ikwzfjym.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gt2cdifjhob.html

JS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gt2dlsauofl.html

TS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gt2gpaxdixp.html

Java: "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gt2zxlwekke.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cqqwz.cn/Article/details/gt2pendzzbh.html

Ruby: "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gt2szvokufq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yueranfly.top/Article/details/gt2kpvwurfx.html

[E03] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gt2xihitdlf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hammf.cn/Article/details/gt2ovnrwrun.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2pfukmess.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2uybbfnhz.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gt2xiofcnuo.html

Java: s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gt2xxhknuxi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ivvv.top/Article/details/gt2aegsnvzv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daria6918.cn/Article/details/gt2mevpfvei.html

C#:   s.Substring(1, 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adakzkpu.html

[E04] 查找子串位置
来源：http://dali.sweek.top/Article/details/gt2ojwcnkic.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gt2xlvyfgpi.html

PHP:  strpos($s, "x");
来源：http://dali.meibo888.top/Article/details/gt2ulklmzeh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uxpgrtrs.html

TS:   s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2fmquizjm.html

Java: s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2riuupnbi.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgfzy.top/Article/details/gt2olfrfiik.html

Ruby: s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2eacfsoig.html

C#:   s.IndexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ysaaxwol.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj202588.top/Article/details/gt2adenjahx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2owhaeudx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ehwqpu.com/Article/details/gt2cflatmjh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gt2irpheljw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xijkihqy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xzedkajb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hysaishi.cn/Article/details/gt2uvrcszqf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.birdmap.top/Article/details/gt2chuyzgqd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.c1oappe.top/Article/details/gt2tvovwrba.html

[E06] 替换子串
来源：http://dali.ivvv.top/Article/details/gt2flrhexwb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rkobryfw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.redwolf501.top/Article/details/gt2wrdgzhak.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2ysargywk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2rnzbtpyu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2dcpgppzt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2nuntleup.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2ajuykdkg.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2btzagutj.html

[E07] 按分隔符拆分
来源：http://dali.pycfn.com/Article/details/gt2ksmeidqw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ljiynuyd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2jinuqyyh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258.top/Article/details/gt2wtkppuyb.html

TS:   s.split(",")
来源：http://dali.tanke756.top/Article/details/gt2ysbepgkk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jyoumei.cn/Article/details/gt2rgvyxdoi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jianghu66.top/Article/details/gt2drjdtznz.html

Ruby: s.split(",");  s.split
来源：http://dali.zycfv.cn/Article/details/gt2ezbefjrb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fengsongda.top/Article/details/gt2wnpevjzq.html

[E08] 数组按分隔符合并
来源：http://dali.zycfv.cn/Article/details/gt2bcazpbmg.html

Py:   ",".join(items)
来源：http://dali.jianghu66.top/Article/details/gt2deadtwnh.html

PHP:  implode(",", $items);
来源：http://dali.fzhhl.top/Article/details/gt2bmhjaxbk.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2gtraciua.html

TS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjcyyzmp.html

Java: String.join(",", items)
来源：http://dali.iojbl.cn/Article/details/gt2yztzahjd.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2unizqybm.html

Ruby: items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gt2uvbczzgw.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gt2zobwzrni.html

[E09] 去除所有空白字符
来源：http://dali.fzhhl.top/Article/details/gt2bhdqmolp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sjdhgoui.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfvxeqxy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gt2kwisicgy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gt2xdnsgbtv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gt2pbntdnha.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigfzy.top/Article/details/gt2itbmxeuw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ydzc1.top/Article/details/gt2plaeskff.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gt2nkoszzxi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guowangkeji.top/Article/details/gt2zhmzupfy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2kdxiqxmr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jyoumei.cn/Article/details/gt2khwuvpdm.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gt2ktnewfrq.html

TS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2elwteznu.html

Java: String.format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gt2gjoljxix.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gt2glwstsvw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gt2vkdgsvvw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aibaodan.cn/Article/details/gt2tgizybnc.html

[E11] 反转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2jnaxhred.html

Py:   s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2ylurrrzo.html

PHP:  strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gt2jrjqunmt.html

JS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2gouvpigr.html

TS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2qqceativ.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shuidangran.top/Article/details/gt2ofhciksn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.smart0.xyz/Article/details/gt2sedpgfgg.html

Ruby: s.reverse
来源：http://dali.316326.xyz/Article/details/gt2ktucyylv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gt2zjwoqbgf.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvoaknjx.html

Py:   s.count("a")
来源：http://dali.hnqzz.top/Article/details/gt2mggnhoqi.html

PHP:  substr_count($s, "a");
来源：http://dali.cheryme.top/Article/details/gt2bmdkrnhs.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gt2rcjlwneb.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ocauqsgw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgufenzy.top/Article/details/gt2ynyziacs.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gt2qbelwgbv.html

Ruby: s.count("a")
来源：http://dali.yuxming.cn/Article/details/gt2kxkfoelo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daria6918.cn/Article/details/gt2ktbqsvbi.html

[E13] 逐字符遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ipvyeogo.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gt2yukpdfru.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ogayifjp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2zjjsmxml.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2yazjlgrf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2qaopfyzq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gt2masamvya.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gt2pyhtgrdb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2pikdxedz.html

[E14] URL 编码与 Base64
来源：http://dali.sysykeji.top/Article/details/gt2vcptvskg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.vqdsnc.cn/Article/details/gt2crgvilgm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cdnleiting.top/Article/details/gt2nnmrgyrm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fzhhl.top/Article/details/gt2hmlbfluc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdrxypes.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guannengcc.top/Article/details/gt2owvvhojl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.snrcjt.cn/Article/details/gt2pkjdlskr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xziqi.cn/Article/details/gt2zebywzfx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gt2cmzttnyz.html

[E15] HTML 转义 / 反转义
来源：http://dali.tianlin.xyz/Article/details/gt2zghfkbbr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pycfn.com/Article/details/gt2suzikqdi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hysaishi.cn/Article/details/gt2zdjfbcrh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jyoumei.cn/Article/details/gt2qklcayqn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2noxddtux.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ybcxt.top/Article/details/gt2svyqqrgc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yangfankeji.com/Article/details/gt2srqcarco.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2rfolimyf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sxryk.cn/Article/details/gt2dzbzmfvs.html

[E16] 数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gt2jqqbmkpz.html

Py:   f"{1234567:,}"
来源：http://dali.chenzaomai.com/Article/details/gt2mqtyrejg.html

PHP:  number_format(1234567);
来源：http://dali.c1oappe.top/Article/details/gt2hqpohiyx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gt2dftgyahv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gt2oerjlzin.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gt2giaowuxj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gt2jjvkhspk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cheryme.top/Article/details/gt2naypclsx.html

C#:   1234567.ToString("N0")
来源：http://dali.yvedp.cn/Article/details/gt2ivrxjkgv.html

[E17] 首字母大写
来源：http://dali.shzxlz.cn/Article/details/gt2iceysflf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxuanxn.top/Article/details/gt2qwjoclvo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yangfankeji.com/Article/details/gt2votmddvs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wtosdkxi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gt2tmntwtxb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gt2wlfifrtl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gt2ddhzesfs.html

Ruby: s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gt2poayhujt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cashguo.top/Article/details/gt2nwyxelyn.html

[E18] 模板占位符替换
来源：http://dali.nanxinkj.top/Article/details/gt2qmmhikgq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aizwys.cn/Article/details/gt2deljsufv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xinyue.icu/Article/details/gt2ftvhdosj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2ofgvdvfq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gt2hxgvczur.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2sayelwbf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2iubtoeex.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gt2eksrspxq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.9152youxi.cn/Article/details/gt2biiiatqt.html

[E19] 多行文本按行拆分
来源：http://dali.redwolf501.top/Article/details/gt2olbqfdyg.html

Py:   s.splitlines()
来源：http://dali.yonumen.top/Article/details/gt2mivkzhqu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jianghu66.top/Article/details/gt2vrhglwmk.html

JS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gt2cfqjaqve.html

TS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gt2srrzfdjp.html

Java: s.lines().toList()
来源：http://dali.havefunace.top/Article/details/gt2bwedliiq.html

Go:   strings.Split(s, "\n")
来源：http://dali.xinyue.icu/Article/details/gt2nmuoyfyu.html

Ruby: s.lines
来源：http://dali.fengsongda.top/Article/details/gt2vuagtyir.html

C#:   s.Split('\n')
来源：http://dali.gaohongyu789.top/Article/details/gt2xuisuprx.html

[E20] 判断字符串是否为空
来源：http://dali.sweek.top/Article/details/gt2ptrcvkfl.html

Py:   if not s:
来源：http://dali.ppjwa.cn/Article/details/gt2ogdqjdko.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.meibo888.top/Article/details/gt2kyozvtnx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gt2bmoeoxfc.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gt2vqawtips.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gt2ocbbcilf.html

Go:   if s == "" {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2hixrtmrt.html

Ruby: if s.empty?
来源：http://dali.cqqwz.cn/Article/details/gt2ieewjdfm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.c1oappe.top/Article/details/gt2yjdljrqx.html

[E21] 超长截断加省略号
来源：http://dali.316326.xyz/Article/details/gt2diiwclfo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gaohongyu789.top/Article/details/gt2kruzgzvf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2auxafusl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2ibxomfiz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dnxlmtbm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2treuapwk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.9152youxi.cn/Article/details/gt2cfzvrbvm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2dfmcdtvi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2zuihbgyu.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gt2aqkakjug.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.andypj.xyz/Article/details/gt2gaekbety.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gt2fghjqsfe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2ghllcwse.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gt2hazwnmjm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gt2oexhpvnu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aibaodan.cn/Article/details/gt2iurpwtou.html

Ruby: s.bytesize;  s.length
来源：http://dali.aibaodan.cn/Article/details/gt2dxjuvkay.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yvedp.cn/Article/details/gt2eawuzqsp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2bfintcyx.html

F. 文件与目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2ollozqmq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2khmhhwwo.html

[F01] 读取整个文件
来源：http://dali.c1oappe.top/Article/details/gt2cvsuiiej.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gt2eeybpgby.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2xtawjwre.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hongshengwenyu.top/Article/details/gt2ebzavkci.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jianghu66.top/Article/details/gt2zattmwim.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2gajxduzu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elnwssqh.html

Ruby: File.read("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2fkjkzyyl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2wegknotr.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gt2godhgxzq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.iojbl.cn/Article/details/gt2vidvoays.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnqzz.top/Article/details/gt2nudsyohe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2qzhuntgk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2okcleeei.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gt2rugtrzsh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cashguo.top/Article/details/gt2gsghdsso.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj202588.top/Article/details/gt2ovcunusy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gt2pyszxeuk.html

[F03] 写入文件（覆盖）
来源：http://dali.vqdsnc.cn/Article/details/gt2tbeoptkl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gt2exeqjtiy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gt2dwlukspj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gt2atffgrsq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2yrvnqrpw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fifxigdf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hongshengwenyu.top/Article/details/gt2laemnzjf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pycfn.com/Article/details/gt2cofzzbgp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hdwpejuo.html

[F04] 追加写入文件
来源：http://dali.cucudq.cn/Article/details/gt2wzgjubxv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rywplopl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cucudq.cn/Article/details/gt2fynopghd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2mrrpbpaq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gt2ziifwcxl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gt2hekypzqn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gt2mxmqxsbw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vixtsyod.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cdnleiting.top/Article/details/gt2cvlyympf.html

[F05] 判断文件或目录是否存在
来源：http://dali.xylfe.cn/Article/details/gt2gzhwfymg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zycfv.cn/Article/details/gt2rhgcjjxe.html

PHP:  file_exists("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2agsdbdxc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2zxblyeov.html

TS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2cnqbhoei.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2pmhtnpcx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gt2hbkloqkl.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2zvpvdmfd.html

C#:   File.Exists("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2nvhbddti.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gt2tupiuvda.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2tmbgkxee.html

PHP:  unlink("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2eeipdbpx.html


<!-- 参考信息 -->