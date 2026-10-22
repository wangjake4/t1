代发 wailian999

Go:   // 无重载：用不同函数名
来源：http://dali.tian-w.cn/Article/details/gtoxsgwsnb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuanzx.com/Article/details/gtucygvbhs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgufenzy.top/Article/details/gtnauoyyis.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnutqxaec.html

D. 数组 / 列表 / 集合
来源：http://dali.snrcjt.cn/Article/details/gtovjezfkh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtjunesfsn.html

[D01] 创建数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtwsleoysc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jyoumei.cn/Article/details/gtfuukyglo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gtbknizkki.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuanzx.com/Article/details/gtdnxnxorn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.redwolf501.top/Article/details/gtmxuqzojc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258888.top/Article/details/gtpoyecshn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhongyouzk.top/Article/details/gtsnnehjao.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gotoacloud.top/Article/details/gtutxaxpuo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxhjkces.html

[D02] 追加元素到末尾
来源：http://dali.hnqzz.top/Article/details/gtgrtmbkgq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hysaishi.cn/Article/details/gtogqdktfy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cucudq.cn/Article/details/gtbifeoybm.html

JS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtldtqaeqf.html

TS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gtlsnlixun.html

Java: list.add(4);
来源：http://dali.zhongyouzk.top/Article/details/gtrhtborrw.html

Go:   arr = append(arr, 4)
来源：http://dali.redwolf501.top/Article/details/gtekclbftz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fengsongda.top/Article/details/gtxbsqqkxi.html

C#:   list.Add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugxbpzsp.html

[D03] 在指定位置插入元素
来源：http://dali.ivvv.top/Article/details/gtycyvqkvb.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258.top/Article/details/gtniyplaot.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tianlin.xyz/Article/details/gtcankhepf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhoulong.xyz/Article/details/gtogbxniqz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.bjfxy.top/Article/details/gtannpoblt.html

Java: list.add(0, 0);
来源：http://dali.daxiang520.top/Article/details/gtowydzsne.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhengqikj.top/Article/details/gtrxpqzkut.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tian-w.cn/Article/details/gtyzwybymq.html

C#:   list.Insert(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfhcvqxt.html

[D04] 删除元素
来源：http://dali.daxiang520.top/Article/details/gtcibhnfhi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hywenlv.cn/Article/details/gtbjgdhgvg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cheryme.top/Article/details/gtgryxcalx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhongyouzk.top/Article/details/gtcqvpdkfm.html

TS:   arr.splice(0, 1);
来源：http://dali.xziqi.cn/Article/details/gtmmzllzud.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yonumen.top/Article/details/gtyqwmucxs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigufen.top/Article/details/gtiqhvyluu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gtdcoishrz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ivvv.top/Article/details/gtyanswicr.html

[D05] 访问与修改元素
来源：http://dali.redwolf501.top/Article/details/gtxfdiqhwt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtbssopzij.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtzvhcrfvc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtchxlqnjp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258.top/Article/details/gtrmbcvyyj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zycfv.cn/Article/details/gtqgqccwqg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtdxeyqmfz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtufjszmxo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtohoozsse.html

[D06] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtcotevaxc.html

Py:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtzoyytmap.html

PHP:  count($arr);
来源：http://dali.tanke756.top/Article/details/gtaaetnzpy.html

JS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gtmmpchvgp.html

TS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtxzywefed.html

Java: list.size();
来源：http://dali.mhx1999.top/Article/details/gtfjdudimp.html

Go:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtlsobfcsb.html

Ruby: arr.length; arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gtqhgewgav.html

C#:   list.Count;
来源：http://dali.yj20258.top/Article/details/gtkkihpcum.html

[D07] 切片 / 取子数组
来源：http://dali.jinghuilouyu.cn/Article/details/gthhfoavme.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sysykeji.top/Article/details/gtdvkyqsva.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtlxcqlaiu.html

JS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtwgwwldva.html

TS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtfwxseptq.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmxiodmp.html

Go:   arr[1:4]
来源：http://dali.zhengqikj.top/Article/details/gtfwthvhkg.html

Ruby: arr[1, 3]
来源：http://dali.xylfe.cn/Article/details/gtmadjexfv.html

C#:   list.GetRange(1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtshyohmnk.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gtbrkpbbos.html

Py:   a + b;  a.extend(b)
来源：http://dali.guowangkeji.top/Article/details/gthnlakbzx.html

PHP:  array_merge($a, $b);
来源：http://dali.tianlin.xyz/Article/details/gtayqsprlj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenzaomai.com/Article/details/gtqredbpna.html

TS:   [...a, ...b];
来源：http://dali.zdqjudy.top/Article/details/gtbpunuhul.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.redwolf501.top/Article/details/gtlstaornw.html

Go:   append(a, b...)
来源：http://dali.pycfn.com/Article/details/gtfgpemkws.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hysaishi.cn/Article/details/gtujhxyxfe.html

C#:   a.Concat(b).ToList()
来源：http://dali.redwolf501.top/Article/details/gtqhbwkykg.html

[D09] 排序（升序）
来源：http://dali.cqqwz.cn/Article/details/gtpzcgnfkf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gttavszuof.html

PHP:  sort($arr);
来源：http://dali.sufxvd.cn/Article/details/gtarazlxjm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.quarkkingdee.top/Article/details/gtpbabzmob.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jyoumei.cn/Article/details/gtbwrgvisg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxuanxn.top/Article/details/gtnmymgpjb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gtgxhvhjst.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtgocequwq.html

C#:   list.Sort();
来源：http://dali.nanxinkj.top/Article/details/gtgnqnnwfl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.c1oappe.top/Article/details/gtgjegpdzc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.haohaochexian.top/Article/details/gttllmimri.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gtknpakpbs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtvqzfherx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtqfbrumit.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258.top/Article/details/gtzptlebii.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.meibo888.top/Article/details/gtqnbuwgfl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jiagoushi.top/Article/details/gtfkmhkusx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cashguo.top/Article/details/gtkqawkbyz.html

[D11] 反转数组
来源：http://dali.yuxming.cn/Article/details/gtpiuyujor.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.0kj1m.cn/Article/details/gtsrleciyn.html

PHP:  array_reverse($arr);
来源：http://dali.316326.xyz/Article/details/gtipgttzvj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pycfn.com/Article/details/gtufavnrfo.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvnldgpd.html

Java: Collections.reverse(list);
来源：http://dali.jiagoushi.top/Article/details/gtxrqdnapa.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gtdtgjepyh.html

Ruby: arr.reverse
来源：http://dali.chenzaomai.com/Article/details/gtjktwscsl.html

C#:   list.Reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gtshsapqev.html

[D12] 查找元素下标
来源：http://dali.316326.xyz/Article/details/gthejdbnol.html

Py:   arr.index(x);  x in arr
来源：http://dali.meibo888.top/Article/details/gtimhcmeeo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigufen.top/Article/details/gthuywzvmc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gtidnfgipb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtofisosbr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daria6918.cn/Article/details/gtmiwivsyk.html

Go:   slices.Index(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtonqkvnkp.html

Ruby: arr.index(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtpcjlxvlz.html

C#:   list.IndexOf(x);
来源：http://dali.vqdsnc.cn/Article/details/gtuuqycqko.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hfpthk.cn/Article/details/gtmjfalyus.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenzaomai.com/Article/details/gtlhfmvizv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigfzy.top/Article/details/gtodwuqzjm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gtslcrgmca.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gttjuldbqf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigufen.top/Article/details/gtnrvvpjhk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhiwuduotai.top/Article/details/gtmimorieb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guannengcc.top/Article/details/gtqknothbk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nwbrower.top/Article/details/gttykkdodq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.feifeiyinyue.top/Article/details/gtxleiinam.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yangfankeji.com/Article/details/gttboxexei.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtrlbhlavb.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtezqcxvfa.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtuchdlxiw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.havefunace.top/Article/details/gtswcgenbn.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gtsvstmpyz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtjhimsduf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthosumhtg.html

[D15] 去重
来源：http://dali.chenzaomai.com/Article/details/gtidokbfrw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gtenqprfmq.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtlvrgtesh.html

JS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtykrgkrzq.html

TS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtdqgkrshw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gthklvwckc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxuanxn.top/Article/details/gthbbrdapt.html

Ruby: arr.uniq
来源：http://dali.wangdashe.top/Article/details/gtzmkpeydn.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigufen.top/Article/details/gttlwgpzds.html

[D16] 求和与平均值
来源：http://dali.yj20258888.top/Article/details/gtzazqooll.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.smart0.xyz/Article/details/gtkcfkmhlj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtwmlxfghu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtoyglcqum.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtlqgpixfy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.mhx1999.top/Article/details/gtauqtizsi.html

Go:   // 手写循环累加
来源：http://dali.haohaochexian.top/Article/details/gtlgdpezav.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gtidrjnpsn.html

C#:   list.Sum();  list.Average()
来源：http://dali.haohaochexian.top/Article/details/gtymbufnmy.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gtpwkoshom.html

Py:   max(arr);  min(arr)
来源：http://dali.yangfankeji.com/Article/details/gtzflverqj.html

PHP:  max($arr);  min($arr);
来源：http://dali.havefunace.top/Article/details/gtjgimkdqu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.0kj1m.cn/Article/details/gthspvinfa.html

TS:   Math.max(...arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtpqtpofzs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.birdmap.top/Article/details/gtiuhdcqsl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtrvffwmuo.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gtukuwaadk.html

C#:   list.Max();  list.Min()
来源：http://dali.aibaodan.cn/Article/details/gtohflgjxh.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gtgzufnzkf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.havefunace.top/Article/details/gtzuqsvaex.html

PHP:  array_merge(...$nested);
来源：http://dali.cdnleiting.top/Article/details/gtumrsyaiy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj202588.top/Article/details/gtxmvdepdy.html

TS:   nested.flat();
来源：http://dali.hongshengwenyu.top/Article/details/gtmhfelixr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtkvldmqkc.html

Go:   // 手写双层循环
来源：http://dali.zhiwuduotai.top/Article/details/gtyztmkwtv.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gtrfyhrpcu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangdashe.top/Article/details/gttvjxmghc.html

[D19] 按字段分组
来源：http://dali.sweek.top/Article/details/gtidkwqkme.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebdkhnrm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sweek.top/Article/details/gtapmqvvsx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gtyrwoamch.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gtojeybkat.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzotlasue.html

Go:   // 手写 map[string][]T
来源：http://dali.xuetiantiany.cn/Article/details/gtuvbpmqiq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfvljbhp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hongshengwenyu.top/Article/details/gtsgjbdcxt.html

[D20] 统计每个元素出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gtpcvpomxz.html

Py:   Counter(arr)
来源：http://dali.birdmap.top/Article/details/gthnrocrkh.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258888.top/Article/details/gtbrdcqzre.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtjhcffgvc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gtlfohoykf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gtncqptakx.html

Go:   // 手写 map[T]int
来源：http://dali.gzhubu.top/Article/details/gtuznswpqx.html

Ruby: arr.tally
来源：http://dali.jianghu66.top/Article/details/gtvpnhsilh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxinkj.top/Article/details/gttzapqxzv.html

[D21] 判断是否包含某元素
来源：http://dali.guowangkeji.top/Article/details/gtospxeink.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gtfsorpxmk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xziqi.cn/Article/details/gthfjpxdaw.html

JS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtssslrrfv.html

TS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjylckfjd.html

Java: list.contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmazkibyr.html

Go:   slices.Contains(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtvwcfkwpw.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gtxvcqznvf.html

C#:   list.Contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gthwxoqorb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.iojbl.cn/Article/details/gtphqeczih.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtpojtzeqm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zdqjudy.top/Article/details/gtbcozetot.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shzxlz.cn/Article/details/gtnpxasbkh.html

TS:   [...arr];
来源：http://dali.ehwqpu.com/Article/details/gtkmsjwapc.html

Java: new ArrayList<>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gteaqmoqcm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.snrcjt.cn/Article/details/gtpafgepnr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gtryirmqeb.html

C#:   new List<int>(list);
来源：http://dali.zdqjudy.top/Article/details/gtdgwxttgq.html

[D23] reduce 累积计算
来源：http://dali.hnqzz.top/Article/details/gtzjovhtvf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gtgnlkxudn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gogol.net.cn/Article/details/gtawsxhqmc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtgjmheksp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gthcpimggy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.haohaochexian.top/Article/details/gtdoqyefpm.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gthzzsscbm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gtybhqsepo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gtdhtdjpnw.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gttulldnia.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nwbrower.top/Article/details/gtlijieokz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvpxamnw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.mhx1999.top/Article/details/gtfjgruerq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtargypyli.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nwbrower.top/Article/details/gtyxlsjobv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuanzx.com/Article/details/gtcrdhxefb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guowangkeji.top/Article/details/gtmatzqmvm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gotoacloud.top/Article/details/gtlhavbnfw.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gthxzgfpbh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.snrcjt.cn/Article/details/gtqsddsfuz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hywenlv.cn/Article/details/gttuowkwhn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.kuanghao11.cn/Article/details/gtboammtdy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gtvasolnbt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gzhubu.top/Article/details/gtgdpimsbd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gtomvfkrxv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigufen.top/Article/details/gtcuwbuzdc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zycfv.cn/Article/details/gtccasbyes.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gtygoehqdz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gzhubu.top/Article/details/gtkoznbudy.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtdocixqax.html

JS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtchbbinpk.html

TS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtbbuidcff.html

Java: String.join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtwaigyvqv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtnreoqgim.html

Ruby: arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtslnkqqpn.html

C#:   string.Join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gtzwhpwuwv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtriubwqbe.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gtrsqgedoc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gttzmvpnlk.html

[E01] 拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtruanflrv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gotoacloud.top/Article/details/gtkrxqpsud.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.smart0.xyz/Article/details/gtrwxnlxgq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gtvrliequz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtcmwcegeo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxuanxn.top/Article/details/gtotvtrqhk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gtmvyrpsdp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hywenlv.cn/Article/details/gtrflgekqx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtapdcoqsr.html

[E02] 重复字符串
来源：http://dali.aibaodan.cn/Article/details/gtqcsrflxz.html

Py:   "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gtozwfrkuw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guannengcc.top/Article/details/gtdwcvqbau.html

JS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtmsdayril.html

TS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtcaibchpt.html

Java: "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtdbxwtwmk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cashguo.top/Article/details/gtxtejeion.html

Ruby: "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtmadjuxgf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gtrfwcwank.html

[E03] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtrpdelgvd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqozpdocj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtoxefiwcm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtikfeosjg.html

TS:   s.slice(1, 4)
来源：http://dali.xylfe.cn/Article/details/gtbtdlbcry.html

Java: s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gtnhqfkfqj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.smart0.xyz/Article/details/gtpoqbeygb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvamayoh.html

C#:   s.Substring(1, 3)
来源：http://dali.wangdashe.top/Article/details/gtikvchyyq.html

[E04] 查找子串位置
来源：http://dali.yuxming.cn/Article/details/gtmvreremg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtywharegf.html

PHP:  strpos($s, "x");
来源：http://dali.tian-w.cn/Article/details/gtbonqpnku.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangshuangyany.cn/Article/details/gtnsszaeid.html

TS:   s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtefoqtzuj.html

Java: s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gtblrceknj.html

Go:   strings.Index(s, "x")
来源：http://dali.ppjwa.cn/Article/details/gtzjzoavrh.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtbtbvfyrx.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtofqkjkry.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwrxbhyb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gogol.net.cn/Article/details/gtrwukejnf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.316326.xyz/Article/details/gtxtixsncp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gthgjgaqwe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhoulong.xyz/Article/details/gthgrzogzz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtesolwcmj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gtcuztvemi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gaohongyu789.top/Article/details/gtkutrrhhu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtgnrqrtva.html

[E06] 替换子串
来源：http://dali.iojbl.cn/Article/details/gttgqmorxa.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gtbpggitku.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtgdgolain.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtogfkouwu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtyswamrbk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtlbfltutm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gteqiloicv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtewvpdlzd.html

C#:   s.Replace("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtnwgdibir.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gtqpfgbiho.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gtugabfuul.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwonptjer.html


<!-- 参考信息 -->