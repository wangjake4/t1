代发 wailian999

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxbulzvg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.smart0.xyz/Article/details/gt2rihiceau.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.birdmap.top/Article/details/gt2jvbkdure.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.snrcjt.cn/Article/details/gt2gmbybrju.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.birdmap.top/Article/details/gt2ycxevgiy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hammf.cn/Article/details/gt2weldsqus.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zdqjudy.top/Article/details/gt2ubrbmfpj.html

[D02] 追加元素到末尾
来源：http://dali.hongshengwenyu.top/Article/details/gt2nhutablb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gzhubu.top/Article/details/gt2wmrfwwrc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ybcxt.top/Article/details/gt2mnacuvhm.html

JS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gt2yzunucfi.html

TS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gt2vwrgoenn.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gt2ftxqnlhy.html

Go:   arr = append(arr, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdrbcqqw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigufen.top/Article/details/gt2enhakbar.html

C#:   list.Add(4);
来源：http://dali.fengsongda.top/Article/details/gt2mfchszey.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2wzddikwr.html

Py:   arr.insert(0, 0)
来源：http://dali.yuxming.cn/Article/details/gt2dphtmoay.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hysaishi.cn/Article/details/gt2tibijxrp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.kuanghao11.cn/Article/details/gt2bywbsanj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2mmewwgli.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2fsyzzutn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pcrymskf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jyoumei.cn/Article/details/gt2asljefqf.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2uoifwaxh.html

[D04] 删除元素
来源：http://dali.9152youxi.cn/Article/details/gt2wjdmzpak.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yonpgxed.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnqzz.top/Article/details/gt2kgsyobty.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuanzhike.top/Article/details/gt2oipcxbin.html

TS:   arr.splice(0, 1);
来源：http://dali.jlsjyb.cn/Article/details/gt2hcyaqmpo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aizwys.cn/Article/details/gt2urxgoofk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.wangdashe.top/Article/details/gt2ygqwlflf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ppjwa.cn/Article/details/gt2wtoblfwt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gzhubu.top/Article/details/gt2upqaukhc.html

[D05] 访问与修改元素
来源：http://dali.smart0.xyz/Article/details/gt2lflnsjex.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gt2qxucbytf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gt2tlooyjse.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gt2tzckqgyi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gt2ronxnhks.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gt2ogpifnbs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gt2qnledljj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gt2wobqlstx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gt2inpolwzy.html

[D06] 数组长度
来源：http://dali.aizwys.cn/Article/details/gt2nczjvzqy.html

Py:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rebcrpae.html

PHP:  count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hgnwzdjg.html

JS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gt2xsxxltoe.html

TS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydptymvb.html

Java: list.size();
来源：http://dali.vqdsnc.cn/Article/details/gt2nmiwpsih.html

Go:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2mmhxsawb.html

Ruby: arr.length; arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzfdcfly.html

C#:   list.Count;
来源：http://dali.yj20258888.top/Article/details/gt2ehqmfmxa.html

[D07] 切片 / 取子数组
来源：http://dali.sxryk.cn/Article/details/gt2urfahlzg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.svipenyu.cn/Article/details/gt2qmakabam.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cucudq.cn/Article/details/gt2xeccrywe.html

JS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gt2eivfdnun.html

TS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gt2lolowwby.html

Java: list.subList(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gt2itxjsnfd.html

Go:   arr[1:4]
来源：http://dali.dashuyun.cn/Article/details/gt2qkgfpzrb.html

Ruby: arr[1, 3]
来源：http://dali.svipenyu.cn/Article/details/gt2ubdbzfzz.html

C#:   list.GetRange(1, 3);
来源：http://dali.jianghu66.top/Article/details/gt2wmgspzsf.html

[D08] 合并两个数组
来源：http://dali.nwbrower.top/Article/details/gt2yezknfiu.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pfwnksxy.html

PHP:  array_merge($a, $b);
来源：http://dali.cheryme.top/Article/details/gt2ooswujmu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pycfn.com/Article/details/gt2lewxnpfl.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gt2jrjbxmfl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2auqlityk.html

Go:   append(a, b...)
来源：http://dali.zhengqikj.top/Article/details/gt2mbpuohgs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jianghu66.top/Article/details/gt2dcwwzdzh.html

C#:   a.Concat(b).ToList()
来源：http://dali.tanke756.top/Article/details/gt2nxmqgwxi.html

[D09] 排序（升序）
来源：http://dali.sxryk.cn/Article/details/gt2kwsocswq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gt2hhpksnqx.html

PHP:  sort($arr);
来源：http://dali.bjfxy.top/Article/details/gt2azkwiuey.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.andypj.xyz/Article/details/gt2ubiixkpc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cxiixnuu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gt2pihjvqxc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2ywnemkjb.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gt2chppehrr.html

C#:   list.Sort();
来源：http://dali.tianlin.xyz/Article/details/gt2rporgzvo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj202588.top/Article/details/gt2kczggdhz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ivvv.top/Article/details/gt2vbcmmniw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gt2lyabxfma.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gt2ggnriywa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gt2eukvorpu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigfzy.top/Article/details/gt2srfgtnlf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.0kj1m.cn/Article/details/gt2hrnacdgr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yangfankeji.com/Article/details/gt2fjnuwzhd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.9152youxi.cn/Article/details/gt2zhxnkgym.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gt2qbaxpode.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rnxforlt.html

PHP:  array_reverse($arr);
来源：http://dali.fzhhl.top/Article/details/gt2zfgdgdld.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gt2gkmwjjvs.html

TS:   [...arr].reverse();
来源：http://dali.cheryme.top/Article/details/gt2shonhmvw.html

Java: Collections.reverse(list);
来源：http://dali.jlsjyb.cn/Article/details/gt2fserofxk.html

Go:   slices.Reverse(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2vljicjuf.html

Ruby: arr.reverse
来源：http://dali.yj20258.top/Article/details/gt2vuqzihyx.html

C#:   list.Reverse();
来源：http://dali.gotoacloud.top/Article/details/gt2xzzbfegx.html

[D12] 查找元素下标
来源：http://dali.jlsjyb.cn/Article/details/gt2dgakgktj.html

Py:   arr.index(x);  x in arr
来源：http://dali.sweek.top/Article/details/gt2tgrwtsdu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cucudq.cn/Article/details/gt2mwqpyjxc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gt2eujhehkl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gt2xnhwwcsj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnxiangtu.top/Article/details/gt2zwjvhwhk.html

Go:   slices.Index(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2cdxtlyqb.html

Ruby: arr.index(x)
来源：http://dali.bjfxy.top/Article/details/gt2zruqdokj.html

C#:   list.IndexOf(x);
来源：http://dali.gaohongyu789.top/Article/details/gt2tmmmdaxm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhixingplan.top/Article/details/gt2pojoysps.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2xzuypzyw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guowangkeji.top/Article/details/gt2fccecfgz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gt2mxmbvhzh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2vhxubofl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tian-w.cn/Article/details/gt2fholmdnc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gt2pxqexxos.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gt2vekpibqn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gt2iiojpuag.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hfpthk.cn/Article/details/gt2hmquenhc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnhmimfr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2dnptpghr.html

JS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gt2wkkabhwv.html

TS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gt2syekagfx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvytbnhr.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gt2stdlrawl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2myhnhwmn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2ozjyflqo.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2juzmjznw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gt2tnjkoslb.html

PHP:  array_unique($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2thiudnan.html

JS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gt2rwwexjpd.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gt2kommehuo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daxiang520.top/Article/details/gt2mioasnoh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahrcfkxs.html

Ruby: arr.uniq
来源：http://dali.pycfn.com/Article/details/gt2pgsqbcnk.html

C#:   list.Distinct().ToList()
来源：http://dali.sysykeji.top/Article/details/gt2kjstofwj.html

[D16] 求和与平均值
来源：http://dali.dianchejie.cn/Article/details/gt2ngccarih.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eiyhrmqn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aizwys.cn/Article/details/gt2dxerbkuu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2dgaoamzn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2auhhekup.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gt2mfniavhg.html

Go:   // 手写循环累加
来源：http://dali.dashuyun.cn/Article/details/gt2nhhhvjko.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dianchejie.cn/Article/details/gt2bpmgtsdl.html

C#:   list.Sum();  list.Average()
来源：http://dali.zdqjudy.top/Article/details/gt2iaarexjp.html

[D17] 最大值与最小值
来源：http://dali.sufxvd.cn/Article/details/gt2ysroczhg.html

Py:   max(arr);  min(arr)
来源：http://dali.havefunace.top/Article/details/gt2ebivvahz.html

PHP:  max($arr);  min($arr);
来源：http://dali.tian-w.cn/Article/details/gt2cseboqgu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cheryme.top/Article/details/gt2eysythvl.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gt2jppnclnv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2ebnwpdjg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xylfe.cn/Article/details/gt2mtoqruhk.html

Ruby: arr.max;  arr.min
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hjuhhzua.html

C#:   list.Max();  list.Min()
来源：http://dali.tanke756.top/Article/details/gt2ugceyhde.html

[D18] 扁平化嵌套数组
来源：http://dali.dianchejie.cn/Article/details/gt2yhwyuayj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daria6918.cn/Article/details/gt2llufjhwr.html

PHP:  array_merge(...$nested);
来源：http://dali.yuanzhike.top/Article/details/gt2qazrqrrs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hsivvsml.html

TS:   nested.flat();
来源：http://dali.jiagoushi.top/Article/details/gt2ohmatjnx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aizwys.cn/Article/details/gt2yguknbkc.html

Go:   // 手写双层循环
来源：http://dali.zhoulong.xyz/Article/details/gt2wetgejzb.html

Ruby: nested.flatten
来源：http://dali.yvedp.cn/Article/details/gt2jrcpzupd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2cgfykseg.html

[D19] 按字段分组
来源：http://dali.pycfn.com/Article/details/gt2hkvbijpd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sysykeji.top/Article/details/gt2bpjdokwe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ybcxt.top/Article/details/gt2vgsdypqa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigufen.top/Article/details/gt2vlbaznsg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gt2qdnpdljc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yanxiufei.cn/Article/details/gt2mgppjacy.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gt2rjuqbkym.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gt2tfavyhqc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jlsjyb.cn/Article/details/gt2qyawaanz.html

[D20] 统计每个元素出现次数
来源：http://dali.zdqjudy.top/Article/details/gt2ddzaufyn.html

Py:   Counter(arr)
来源：http://dali.sysykeji.top/Article/details/gt2fejpfgef.html

PHP:  array_count_values($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhhqqcis.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gt2nzzryzia.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gt2syzqunkg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jianghu66.top/Article/details/gt2claancqu.html

Go:   // 手写 map[T]int
来源：http://dali.gzhubu.top/Article/details/gt2dhinghfl.html

Ruby: arr.tally
来源：http://dali.snrcjt.cn/Article/details/gt2xqujznof.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sysykeji.top/Article/details/gt2fmbvibtf.html

[D21] 判断是否包含某元素
来源：http://dali.tian-w.cn/Article/details/gt2kwqgmexq.html

Py:   x in arr
来源：http://dali.yonumen.top/Article/details/gt2fsjnatnw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ivvv.top/Article/details/gt2hiudosmw.html

JS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gt2mejagegp.html

TS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2mckshpna.html

Java: list.contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pgvldtnl.html

Go:   slices.Contains(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2tmlunvpv.html

Ruby: arr.include?(x)
来源：http://dali.mhx1999.top/Article/details/gt2hoxlamig.html

C#:   list.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gt2wbabhomi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gt2ywypnawk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2acnhuwly.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hammf.cn/Article/details/gt2omxcehuh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2mcumwmlh.html

TS:   [...arr];
来源：http://dali.ybcxt.top/Article/details/gt2yaqmaibg.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gt2vztvklcu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ivvv.top/Article/details/gt2qzjsudqk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jianghu66.top/Article/details/gt2gximouwd.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awvlltpg.html

[D23] reduce 累积计算
来源：http://dali.hammf.cn/Article/details/gt2bmegfvsp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ydzc1.top/Article/details/gt2zhkvhndi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2yqqnbath.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2kcqjdinp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gt2llkkgziv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gt2djidzgmu.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gt2fbqtletl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fzhhl.top/Article/details/gt2vhhupudc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenlongwang.top/Article/details/gt2wozsydls.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhoulong.xyz/Article/details/gt2tltfmbbf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.iojbl.cn/Article/details/gt2msppzmnk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdofdopr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ivvv.top/Article/details/gt2algplvvu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daxiang520.top/Article/details/gt2gghfmoko.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pevmoylu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jswpcmxs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gzhubu.top/Article/details/gt2obncufxe.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.kuanghao11.cn/Article/details/gt2kylgkmbm.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gt2chefafgq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gt2giaglzfg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.snrcjt.cn/Article/details/gt2pcpgapeu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrmnsjir.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gt2vyunlyfx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gt2vgvtcfap.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dianchejie.cn/Article/details/gt2iqschiba.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pycfn.com/Article/details/gt2zzbfkfkx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.iojbl.cn/Article/details/gt2ekqnjvbj.html

[D26] 数组转字符串
来源：http://dali.nwbrower.top/Article/details/gt2xfrmecky.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxinkj.top/Article/details/gt2zahrzqfr.html

PHP:  implode(", ", $arr);
来源：http://dali.guannengcc.top/Article/details/gt2brtpevfj.html

JS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gt2blxlxftu.html

TS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gt2zarhfdmz.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gt2lscyagkw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hammf.cn/Article/details/gt2nftdpmoh.html

Ruby: arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gt2mgqzgzwp.html

C#:   string.Join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gt2yklasnqf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2zqptzohf.html

E. 字符串处理
来源：http://dali.guowangkeji.top/Article/details/gt2ouerprqi.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2pybczpbf.html

[E01] 拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2bfrhyqmz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangdashe.top/Article/details/gt2fhigbcxj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.redwolf501.top/Article/details/gt2hnlvqgit.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gt2tfldcgbf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gt2ozybopzu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tanke756.top/Article/details/gt2stetsavl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2smghowyv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gt2epjatrpw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2gbswybps.html

[E02] 重复字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2jwoxqaso.html

Py:   "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gt2xwnlkflp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gt2vwcsulcc.html

JS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gt2qnrflats.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2voebhjxb.html

Java: "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gt2xeedbfwd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gt2hbckcoxf.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gt2sewgtoew.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ijpzhhyq.html

[E03] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gt2awaiyces.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jianghu66.top/Article/details/gt2kjftzrqr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2kzsuhdvn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ugmiacwe.html

TS:   s.slice(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdupfsta.html

Java: s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2ukwtiejr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cwfifrxu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhixingplan.top/Article/details/gt2pdzyvbws.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gt2jozdnupg.html

[E04] 查找子串位置
来源：http://dali.zhoulong.xyz/Article/details/gt2lxzzsdca.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangdashe.top/Article/details/gt2yybxkocz.html

PHP:  strpos($s, "x");
来源：http://dali.havefunace.top/Article/details/gt2gdbdvpar.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zycfv.cn/Article/details/gt2vhyvsbzg.html

TS:   s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhpfyebk.html

Java: s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gt2puoxejpc.html

Go:   strings.Index(s, "x")
来源：http://dali.cashguo.top/Article/details/gt2aroaadnf.html

Ruby: s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gt2letaxlpi.html

C#:   s.IndexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2qotgwbxb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hammf.cn/Article/details/gt2dyiwoqwy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gt2lowadwpc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.quarkkingdee.top/Article/details/gt2lwazpdmu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gt2hfmprmnm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangdashe.top/Article/details/gt2qmocwmpc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gt2uvnnhlpi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gt2cvqfhdmy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tianlin.xyz/Article/details/gt2hmbbbxek.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2swoyrxhg.html

[E06] 替换子串
来源：http://dali.birdmap.top/Article/details/gt2wcsofemu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzmtaznb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yueranfly.top/Article/details/gt2bpsvmszs.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2mrxegktv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2tlacvjst.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2bsqqvuyy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gt2yrdxanmj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sweek.top/Article/details/gt2suskrldg.html

C#:   s.Replace("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2rvipuand.html

[E07] 按分隔符拆分
来源：http://dali.gotoacloud.top/Article/details/gt2bthhthzu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.iojbl.cn/Article/details/gt2ffajlwhx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2znjhjgsr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sweek.top/Article/details/gt2nwludhny.html

TS:   s.split(",")
来源：http://dali.ehwqpu.com/Article/details/gt2efdlutqv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuanzx.com/Article/details/gt2fsxeouwx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangdashe.top/Article/details/gt2lvlmrolh.html

Ruby: s.split(",");  s.split
来源：http://dali.hywenlv.cn/Article/details/gt2yqztfczz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnqzz.top/Article/details/gt2lfnfazym.html

[E08] 数组按分隔符合并
来源：http://dali.zdqjudy.top/Article/details/gt2zkjkocef.html

Py:   ",".join(items)
来源：http://dali.chenzaomai.com/Article/details/gt2yblaszlm.html


<!-- 参考信息 -->