代发 wailian999

Ruby: arr.tally
来源：http://dali.aibaodan.cn/Article/details/gt2cjmxocfm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gt2unvwnowv.html

[D21] 判断是否包含某元素
来源：http://dali.cucudq.cn/Article/details/gt2cmtxgjki.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gt2aunlmgeu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sxryk.cn/Article/details/gt2tljzfdwq.html

JS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gt2qetmoajj.html

TS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gt2vlmwxzgw.html

Java: list.contains(x)
来源：http://dali.yj20258888.top/Article/details/gt2wlteibiu.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2qloqnfnx.html

Ruby: arr.include?(x)
来源：http://dali.cdnleiting.top/Article/details/gt2fnwmthrp.html

C#:   list.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lhorlkgx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqpolpia.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daria6918.cn/Article/details/gt2dtngqavv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnxiangtu.top/Article/details/gt2vmnxgssm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2unfxrbak.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gt2lxuxrnyz.html

Java: new ArrayList<>(list);
来源：http://dali.yanxiufei.cn/Article/details/gt2nkwntkzy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yangfankeji.com/Article/details/gt2qgcyfvzo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tianlin.xyz/Article/details/gt2lsigwjwo.html

C#:   new List<int>(list);
来源：http://dali.c1oappe.top/Article/details/gt2joyzokfq.html

[D23] reduce 累积计算
来源：http://dali.yj20258888.top/Article/details/gt2zzdxovjv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gt2mjoxuilm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2lckgzxtp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gt2uzjdtzgs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2smhtupmx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xinyue.icu/Article/details/gt2rhoyofcv.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gt2eotlmbaa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.mhx1999.top/Article/details/gt2bstybyyk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gaohongyu789.top/Article/details/gt2xrwcnohv.html

[D24] 字典 / Map 基本操作
来源：http://dali.yueranfly.top/Article/details/gt2rlwlolga.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gt2qxiwcmgk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhengqikj.top/Article/details/gt2tyqbgfnp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.c1oappe.top/Article/details/gt2viphvdaf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2chyrxijf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gt2joeesysu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cucudq.cn/Article/details/gt2pttqnliu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxiqbshi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptqkkhqy.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gt2zcjksjij.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jyoumei.cn/Article/details/gt2brkkbnzn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jlsjyb.cn/Article/details/gt2hbzzjptb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gotoacloud.top/Article/details/gt2owowccqc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dashuyun.cn/Article/details/gt2osxhldvl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gt2zhwpphwy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258.top/Article/details/gt2pjkqgxiy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shzxlz.cn/Article/details/gt2dukwrvzv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2whlmeiic.html

[D26] 数组转字符串
来源：http://dali.yvedp.cn/Article/details/gt2bmvbbizm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2hhznblgn.html

PHP:  implode(", ", $arr);
来源：http://dali.hnqzz.top/Article/details/gt2ppqthdzh.html

JS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gt2okryjrud.html

TS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gt2grudvpak.html

Java: String.join(", ", list)
来源：http://dali.yonumen.top/Article/details/gt2rpjcshlg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tianlin.xyz/Article/details/gt2wzdihhmx.html

Ruby: arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gt2zhljgfbj.html

C#:   string.Join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzkznezf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ehuhqloh.html

E. 字符串处理
来源：http://dali.yj20258.top/Article/details/gt2exykrblu.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ixpxduib.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gt2wuvsnrey.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pengpengdd.cyou/Article/details/gt2rupxxjcv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iekdlrlp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gt2fmmpwbwc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gt2mmcjkazg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2msvldkim.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ybcxt.top/Article/details/gt2frgrktjf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.havefunace.top/Article/details/gt2dtmspegq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2tfrubsrq.html

[E02] 重复字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2avmzwmra.html

Py:   "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gt2tngvjely.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gt2iqtoqsvc.html

JS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2renrsoew.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gt2djqpomsn.html

Java: "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gt2kcxcwwmx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gt2lisdyqhz.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gt2qxmkdaka.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuanzx.com/Article/details/gt2jodutgfb.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gt2bzmqvfcy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gt2lzkklaaf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2nqqfdjvh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bxxqcfxy.html

TS:   s.slice(1, 4)
来源：http://dali.ydzc1.top/Article/details/gt2itdjymlz.html

Java: s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2qoovwhcz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gt2irzdrakp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xylfe.cn/Article/details/gt2fedjqmit.html

C#:   s.Substring(1, 3)
来源：http://dali.zhixingplan.top/Article/details/gt2gjhegstb.html

[E04] 查找子串位置
来源：http://dali.hammf.cn/Article/details/gt2rreippae.html

Py:   s.find("x");  s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gt2nwtmpfut.html

PHP:  strpos($s, "x");
来源：http://dali.fzhhl.top/Article/details/gt2cmqnmpmr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.mhx1999.top/Article/details/gt2kvnouzoz.html

TS:   s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gt2kgtfpouw.html

Java: s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gt2hcagfxkj.html

Go:   strings.Index(s, "x")
来源：http://dali.yanxiufei.cn/Article/details/gt2tczsvvfc.html

Ruby: s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2lyrlptqa.html

C#:   s.IndexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dlzdgavv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kdmjkypf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aibaodan.cn/Article/details/gt2lhietbjf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenlongwang.top/Article/details/gt2xnelwupj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gt2iqnmduls.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.havefunace.top/Article/details/gt2hwolcmsr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gt2rgqdqand.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yueranfly.top/Article/details/gt2qjiqyfnd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangdashe.top/Article/details/gt2lyenovxg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gt2pqqfnmbn.html

[E06] 替换子串
来源：http://dali.yanxiufei.cn/Article/details/gt2axvhdwxd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gt2wazpadpk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigufen.top/Article/details/gt2hoejkmnm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2mmesfkoi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2ujgfpkpz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2gsokqqij.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gt2vgolcnyu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2spfggyef.html

C#:   s.Replace("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2tsuhgfue.html

[E07] 按分隔符拆分
来源：http://dali.xuanzx.com/Article/details/gt2aconeaqj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daxiang520.top/Article/details/gt2mcnuahhk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2thtvicqp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hfpthk.cn/Article/details/gt2ldcxrykw.html

TS:   s.split(",")
来源：http://dali.ppjwa.cn/Article/details/gt2mrpnvmpm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gt2kctgdwab.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cashguo.top/Article/details/gt2mquurtmm.html

Ruby: s.split(",");  s.split
来源：http://dali.9152youxi.cn/Article/details/gt2bnwyybsa.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxuxvgx.html

[E08] 数组按分隔符合并
来源：http://dali.yongpay.top/Article/details/gt2estmndhs.html

Py:   ",".join(items)
来源：http://dali.gotoacloud.top/Article/details/gt2pjajzvbb.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpizncn.html

JS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gt2iianwtpu.html

TS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gt2lyegopbz.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gt2jppqdjrx.html

Go:   strings.Join(items, ",")
来源：http://dali.smart0.xyz/Article/details/gt2nrydzzsg.html

Ruby: items.join(",")
来源：http://dali.gzhubu.top/Article/details/gt2jurxbwmu.html

C#:   string.Join(",", items)
来源：http://dali.hnqzz.top/Article/details/gt2pbabkgdr.html

[E09] 去除所有空白字符
来源：http://dali.yueranfly.top/Article/details/gt2ypepohsg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gt2vupizmai.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fzhhl.top/Article/details/gt2pdgorwqm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gt2uogdiwzd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2fpvfbqib.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sweek.top/Article/details/gt2dniebyff.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gotoacloud.top/Article/details/gt2opjoisfz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cheryme.top/Article/details/gt2qizzabkw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2equnuxlr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gt2kramtkbt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daxiang520.top/Article/details/gt2drqwezmc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ehwqpu.com/Article/details/gt2pmdbduav.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxkimhyl.html

TS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2ytfhromj.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2esumjflj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gt2hlvcbksq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2uynhrvyn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.smart0.xyz/Article/details/gt2zhoftyvl.html

[E11] 反转字符串
来源：http://dali.jqgfzy.top/Article/details/gt2braiafzm.html

Py:   s[::-1]
来源：http://dali.sweek.top/Article/details/gt2kmwhlfkv.html

PHP:  strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhxtkdie.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwuabtq.html

TS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gt2lqtqgkij.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tianlin.xyz/Article/details/gt2bdaondbl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangdashe.top/Article/details/gt2bzanciqq.html

Ruby: s.reverse
来源：http://dali.havefunace.top/Article/details/gt2ukiecnhi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwtnija.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gt2ydsvfyku.html

Py:   s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2evudolwb.html

PHP:  substr_count($s, "a");
来源：http://dali.cdnleiting.top/Article/details/gt2sredhlgh.html

JS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gt2cveycunw.html

TS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gt2xvofwibv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.meibo888.top/Article/details/gt2rqotvxki.html

Go:   strings.Count(s, "a")
来源：http://dali.yonumen.top/Article/details/gt2wrhelklr.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vteihoyn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aizwys.cn/Article/details/gt2ldqcnrse.html

[E13] 逐字符遍历
来源：http://dali.tian-w.cn/Article/details/gt2kxjecspy.html

Py:   for ch in s: print(ch)
来源：http://dali.cucudq.cn/Article/details/gt2ykcdzjgd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gt2xyqmmpzd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gt2vvlnuqgq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2ivmuggpa.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2laodyaze.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tian-w.cn/Article/details/gt2tvohnghu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.svipenyu.cn/Article/details/gt2burhxtwd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2jtmscbac.html

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gt2gobalwnt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangdashe.top/Article/details/gt2mbhzsccy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fengsongda.top/Article/details/gt2fbuhvdml.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzijpwhh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fengsongda.top/Article/details/gt2uctawrxk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ivvv.top/Article/details/gt2uqsncphs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gt2uchmetqz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.svipenyu.cn/Article/details/gt2hbkscqgr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xziqi.cn/Article/details/gt2xwaqtdvj.html

[E15] HTML 转义 / 反转义
来源：http://dali.daria6918.cn/Article/details/gt2ykwfjbfv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gt2ahvjdvve.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gt2harlnfdt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gt2vbdwjmhl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gt2apscwnex.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gotoacloud.top/Article/details/gt2sgfpiqfi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pycfn.com/Article/details/gt2jbsawson.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daxiang520.top/Article/details/gt2tpiedrpv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brefutlr.html

[E16] 数字千分位
来源：http://dali.yj20258.top/Article/details/gt2cjlqlzzh.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ooliqrsm.html

PHP:  number_format(1234567);
来源：http://dali.guannengcc.top/Article/details/gt2vnlkzbdj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gt2tefedqkt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbjhoouc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shuidangran.top/Article/details/gt2mosdklxe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gt2ckjxehya.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2jhstqwcd.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2utgmosgx.html

[E17] 首字母大写
来源：http://dali.cdnleiting.top/Article/details/gt2ajegutbs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hfpthk.cn/Article/details/gt2ckgzeqjv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gogol.net.cn/Article/details/gt2bzseoktn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gt2netkqzaa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2vxpblgzo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jnniwaun.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.iojbl.cn/Article/details/gt2mbdnrcdb.html

Ruby: s.capitalize
来源：http://dali.havefunace.top/Article/details/gt2cmdspwfm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tianlin.xyz/Article/details/gt2igybryqw.html

[E18] 模板占位符替换
来源：http://dali.kuanghao11.cn/Article/details/gt2jqtdhuvr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.redwolf501.top/Article/details/gt2mszjkggf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gogol.net.cn/Article/details/gt2jxpibwir.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2jxhdcywv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2zqtvluvl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258.top/Article/details/gt2cjvqujfq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2xklgyfwv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sufxvd.cn/Article/details/gt2hudufbyv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuanzhike.top/Article/details/gt2zfvystpa.html

[E19] 多行文本按行拆分
来源：http://dali.cashguo.top/Article/details/gt2tcyzhakr.html

Py:   s.splitlines()
来源：http://dali.cheryme.top/Article/details/gt2rxtxrnrg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2idongclf.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ukeecshx.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgtqdht.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gt2xmkvwivv.html

Go:   strings.Split(s, "\n")
来源：http://dali.birdmap.top/Article/details/gt2dzlbyajf.html

Ruby: s.lines
来源：http://dali.gzhubu.top/Article/details/gt2hdtpelpd.html

C#:   s.Split('\n')
来源：http://dali.ehwqpu.com/Article/details/gt2sswtrqyf.html

[E20] 判断字符串是否为空
来源：http://dali.jianghu66.top/Article/details/gt2lcxeuogj.html

Py:   if not s:
来源：http://dali.hywenlv.cn/Article/details/gt2dcqceolo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnqzz.top/Article/details/gt2vaepxbyn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.meibo888.top/Article/details/gt2lcdzxybj.html

TS:   if (s === "") {}
来源：http://dali.zhoulong.xyz/Article/details/gt2rkuoxixc.html

Java: if (s.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gt2oqrjoivv.html

Go:   if s == "" {}
来源：http://dali.chenzaomai.com/Article/details/gt2ffrkwnlp.html

Ruby: if s.empty?
来源：http://dali.gotoacloud.top/Article/details/gt2oelfjebe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dashuyun.cn/Article/details/gt2aoinybhr.html

[E21] 超长截断加省略号
来源：http://dali.chenlongwang.top/Article/details/gt2kyyzganu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yueranfly.top/Article/details/gt2odzmngyz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sweek.top/Article/details/gt2ynnufmwn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2ehgjijnd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2xdcezemd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2yhxsedxx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gt2vmyqzxij.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2bsxztdtg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2qqysznto.html

[E22] 字节长度与字符长度
来源：http://dali.shzxlz.cn/Article/details/gt2ghpycnow.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gt2xzuhwizf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfyavrbc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzvciuvw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gt2qxqnbvfr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gt2yunscrpf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guowangkeji.top/Article/details/gt2kmofvxjc.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2ymfnozfe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxinkj.top/Article/details/gt2qcmtjlrh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2ogpzvxtn.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gt2bimlqpfn.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2tlrofugk.html

[F01] 读取整个文件
来源：http://dali.jiagoushi.top/Article/details/gt2uctktiwd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.mhx1999.top/Article/details/gt2xlftmjdk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2vxdadsgg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.mhx1999.top/Article/details/gt2mpfeepeu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuanzx.com/Article/details/gt2mbrgcpfm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2qoqtcweb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gt2qfyvdqzl.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2yjckcftt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2jnlqfjmj.html

[F02] 逐行读取文件
来源：http://dali.kuanghao11.cn/Article/details/gt2kxvggalv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guannengcc.top/Article/details/gt2gmrswvlx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gt2ncdxkcco.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gt2krxmdwxb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gt2hxloskye.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gt2xgmxeeko.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gt2xwaroxng.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nedcyows.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kfagxjyz.html

[F03] 写入文件（覆盖）
来源：http://dali.sufxvd.cn/Article/details/gt2orodgnis.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yongpay.top/Article/details/gt2ewzzwkoh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gt2zasaaorb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gt2oupelmgm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2exxuxugb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dashuyun.cn/Article/details/gt2rqpnepbd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigfzy.top/Article/details/gt2uoeezdea.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.meibo888.top/Article/details/gt2whsthgug.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gt2xelwlbcc.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gt2nuovmlku.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258888.top/Article/details/gt2huiostmh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gt2xmrkqkhs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2rxxkothu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gt2jscigcaj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cashguo.top/Article/details/gt2kxynvqzq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xinyue.icu/Article/details/gt2nxzwqmjc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gzhubu.top/Article/details/gt2xofypplj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daria6918.cn/Article/details/gt2ttunktvo.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gt2uzzwnxwt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gt2wujhenbb.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2ybxnnsnj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2ibqsekym.html


<!-- 参考信息 -->