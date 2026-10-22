代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gt2okmdwwcm.html

[G15] 枚举
来源：http://dali.hammf.cn/Article/details/gt2atkbgqlk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daxiang520.top/Article/details/gt2zzvsgglb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zycfv.cn/Article/details/gt2zszystjd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gt2otdhenyp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2hzeaokei.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigufen.top/Article/details/gt2rqqbumvm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.0kj1m.cn/Article/details/gt2yytwkunu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hongshengwenyu.top/Article/details/gt2eksozstu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gt2zgbxsnrk.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gt2clwedwrt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gt2wqtxyucb.html

PHP:  get_object_vars($obj);
来源：http://dali.birdmap.top/Article/details/gt2lrtljalx.html

JS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gt2vttqhnav.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gt2ffnnwmww.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gt2dbqxplvh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gt2bkrjkipa.html

Ruby: obj.instance_variables
来源：http://dali.aizwys.cn/Article/details/gt2bfkqorpr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gt2uerxrwdu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tzgarolm.html

H. 异常与错误处理
来源：http://dali.haohaochexian.top/Article/details/gt2odswirvy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2noqhkgqd.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gt2fkahmcez.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gt2lixupjew.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gt2qknbuhbj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gt2jikpsjpd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gt2uomcgdde.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gt2vivzrfgd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gt2bmwxhltw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xylfe.cn/Article/details/gt2lpyjnhjd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shuidangran.top/Article/details/gt2ebrzlimj.html

[H02] finally / ensure 收尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdzmfeqf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zycfv.cn/Article/details/gt2trskirxb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbbmzckb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2qikpxuem.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2ujdnpauc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2fifiisvc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gt2feeqpuxl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gt2wblphrfd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2kgxczokj.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2aeqyexsi.html

Py:   raise ValueError("错误信息")
来源：http://dali.sysykeji.top/Article/details/gt2hcygnsbn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2qsnhzmdk.html

JS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2gdbrqzyf.html

TS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2ykkjsqtx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2klqxkkoy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.haohaochexian.top/Article/details/gt2xmaogbdr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gt2kcfxlrhi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjmisuao.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gt2mqdaqfbc.html

Py:   class MyError(Exception): pass
来源：http://dali.tian-w.cn/Article/details/gt2frlxtdcy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gt2kuzhigif.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gt2kwsyhovc.html

TS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gteqtjdk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gt2rfembtda.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenzaomai.com/Article/details/gt2basnkavp.html

Ruby: class MyError < StandardError; end
来源：http://dali.aibaodan.cn/Article/details/gt2lxwhczqs.html

C#:   class MyException : Exception {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2utvcnkns.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gt2upgcnmjc.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsqqcci.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gt2tqwmtuwl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2srijyjhu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gt2yrsqejtd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2nkesrulz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gt2oyogzddc.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangshuangyany.cn/Article/details/gt2neldfnuo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gotoacloud.top/Article/details/gt2yrgausga.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gt2zblyrihd.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gt2mmvvirlz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gt2uovcnfbc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gt2gfkjbwfr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gt2rzjediei.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gt2rbyhjguz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gt2ayymddgf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gt2bgunggwj.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2ciceluts.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gt2huhpdjma.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gt2pameheim.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2caavjwuh.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2paacdyjh.html

TS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2svzmmonn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hysaishi.cn/Article/details/gt2vtlaozdm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hywenlv.cn/Article/details/gt2eumyddgz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gogol.net.cn/Article/details/gt2qfzaytns.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2vzmmgtss.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2qkzndejg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnxiangtu.top/Article/details/gt2idcaulog.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aibaodan.cn/Article/details/gt2ydapxjbo.html

JS:   e.message;  e.stack
来源：http://dali.xinyue.icu/Article/details/gt2uxrciydz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sgxjmazq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.andypj.xyz/Article/details/gt2fpwhazov.html

Go:   err.Error()
来源：http://dali.jyoumei.cn/Article/details/gt2jajsjokt.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gt2msqfbizw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.svipenyu.cn/Article/details/gt2otidrsjd.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gt2zapsewod.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.quarkkingdee.top/Article/details/gt2uwkqoaoi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tanke756.top/Article/details/gt2zjxrtnii.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tian-w.cn/Article/details/gt2mtcryojk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.smart0.xyz/Article/details/gt2naplrlgk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zebudgba.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yvedp.cn/Article/details/gt2uyuxauao.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gmbjrycl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aizwys.cn/Article/details/gt2ynqfbxvr.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gt2ypjsjvyl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigfzy.top/Article/details/gt2jpibbaas.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hongshengwenyu.top/Article/details/gt2neoeyakb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gt2rvfloraw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gt2gpgninkd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gt2qxsbgvyv.html

Go:   defer f.Close()
来源：http://dali.dashuyun.cn/Article/details/gt2kcxbnguj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gt2cnybjeda.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2lfhaspxb.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2rsjgwduw.html

I. 正则表达式
来源：http://dali.jiagoushi.top/Article/details/gt2ekafkkxs.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2wrqkuftl.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gt2nvftbhow.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gt2uxrkrbnx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.birdmap.top/Article/details/gt2hxiwioqk.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gt2keyayqsl.html

TS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gt2gwljnayf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daria6918.cn/Article/details/gt2pmfvnrwp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xinyue.icu/Article/details/gt2whwwknvx.html

Ruby: s.match?(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gt2pjdcevky.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gt2ldctbbsp.html

[I02] 提取所有匹配
来源：http://dali.nwbrower.top/Article/details/gt2shsryvyp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gt2iskyxcse.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgufenzy.top/Article/details/gt2tzvgbbez.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yccefthm.html

TS:   s.match(/\d+/g)
来源：http://dali.aibaodan.cn/Article/details/gt2myhvrcgs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2pkdswqfm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gt2ctsrbere.html

Ruby: s.scan(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdeflxze.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ivvv.top/Article/details/gt2qyzemxqv.html

[I03] 提取捕获分组
来源：http://dali.yonumen.top/Article/details/gt2svsflyto.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bqrhyinr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fengsongda.top/Article/details/gt2ezopjgzn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.mhx1999.top/Article/details/gt2tftvlsfe.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2zzgntruu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.c1oappe.top/Article/details/gt2kosdlvyw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.svipenyu.cn/Article/details/gt2wdwgwett.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhongyouzk.top/Article/details/gt2lctntkne.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aibaodan.cn/Article/details/gt2lpmcdvmh.html

[I04] 正则替换
来源：http://dali.quarkkingdee.top/Article/details/gt2hkhzmxaw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gt2ydcqasfq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gt2futoxcad.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gt2nxsqbmbe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2lpjmfkgn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gt2wzydwect.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2vgucwkba.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2ivldgqmr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jfyqneyd.html

[I05] 按正则拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aswrwgob.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gt2rndgflvs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2rkqtnakx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gt2yfsqnwxr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2gvmxnyqm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.316326.xyz/Article/details/gt2yuqnhkdx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gt2huvslsyf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gt2hmekbjqp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guannengcc.top/Article/details/gt2cwxnoexq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.316326.xyz/Article/details/gt2rvlkbsng.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2tpeecmtp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tian-w.cn/Article/details/gt2vwpuptel.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gt2ziqcszns.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gt2bybwhuul.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2uqzzlbns.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhixingplan.top/Article/details/gt2wmpgapgn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aizwys.cn/Article/details/gt2wheadpbr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gt2jfrdxcxh.html

[I07] 忽略大小写与多行模式
来源：http://dali.aibaodan.cn/Article/details/gt2vtlecgso.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangdashe.top/Article/details/gt2wrimxujx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gt2oscujylt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhengqikj.top/Article/details/gt2krkscgnc.html

TS:   /error/gim
来源：http://dali.zdqjudy.top/Article/details/gt2jghyeupd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fyyjujca.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkpjfttc.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gt2tdoftnzr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gt2ihdokdug.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuanzhike.top/Article/details/gt2zavodfto.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sufxvd.cn/Article/details/gt2reebnilf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gt2jluslrbv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gt2umuyfgzi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gt2xujrmjzu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2rifgobip.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fengsongda.top/Article/details/gt2tipxypms.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ipazdabk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gt2zbcilaqp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2qwnzrrlx.html

J. 日期与时间
来源：http://dali.haohaochexian.top/Article/details/gt2zgnqxoql.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2twjmjhcc.html

[J01] 获取当前时间
来源：http://dali.tanke756.top/Article/details/gt2dchabkwf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gt2lpldzhom.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gt2evuwolcx.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2blxwdmfr.html

TS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gt2ftvyzndp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2fhqzabmv.html

Go:   time.Now()
来源：http://dali.zycfv.cn/Article/details/gt2egidnyfl.html

Ruby: Time.now
来源：http://dali.cheryme.top/Article/details/gt2pucojkmy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gt2xkawkper.html

[J02] 格式化输出
来源：http://dali.pycfn.com/Article/details/gt2bcruloml.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gssaystf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gt2kzydpolm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2inobpugw.html

TS:   d.toISOString()
来源：http://dali.zdqjudy.top/Article/details/gt2mmhtfnbw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pybyozlf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzujegh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gt2mskogfyf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aldbpwwo.html

[J03] 字符串解析为日期
来源：http://dali.vqdsnc.cn/Article/details/gt2ogurxfvt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gt2uasnyvel.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tanke756.top/Article/details/gt2xqglnszb.html

JS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2pkvqgwpo.html

TS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2aivygvcl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2ivlnyofj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2glzuhmgk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2wlgdkmbo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.smart0.xyz/Article/details/gt2pmikyapq.html

[J04] 时间戳与日期互转
来源：http://dali.bjfxy.top/Article/details/gt2bxqerpgu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2fsdbxoyi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gt2bpxpmtof.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.birdmap.top/Article/details/gt2vihrpdwp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.birdmap.top/Article/details/gt2itqnegxh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gt2oybzavtj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gt2brplaagz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gsbdktnt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2czhwqprs.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gt2ztubyqhx.html

Py:   now + timedelta(days=7)
来源：http://dali.shuidangran.top/Article/details/gt2qjaciqqp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gt2gtkpfrhp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gt2fvymciqn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gt2pxgrjtow.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hywenlv.cn/Article/details/gt2rocyojkc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gt2kfibrlgo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gt2ijwssgvb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.svipenyu.cn/Article/details/gt2gfzxnxqk.html

[J06] 计算两时间之差
来源：http://dali.zhixingplan.top/Article/details/gt2zbfrtmck.html

Py:   (end - start).total_seconds()
来源：http://dali.jlsjyb.cn/Article/details/gt2xwydmccj.html

PHP:  $end->diff($start)->days;
来源：http://dali.yonumen.top/Article/details/gt2dgglzphz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezwbebcf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jrhdywjn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gt2ablmspji.html

Go:   end.Sub(start).Hours()
来源：http://dali.sxryk.cn/Article/details/gt2rpocptop.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yangfankeji.com/Article/details/gt2rnmmswmk.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gt2hanjytyn.html

[J07] 比较两个日期
来源：http://dali.hfpthk.cn/Article/details/gt2lnumrqyw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpojclep.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cucudq.cn/Article/details/gt2zolsgnhp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gt2mytaldxe.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gt2ltmjfnuo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gt2yifcfxyl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgufenzy.top/Article/details/gt2tmmlaala.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2afxiarcc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gt2ofurzhuk.html

[J08] 提取年月日与星期
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqbbwatw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuxming.cn/Article/details/gt2qxjrdpfj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258.top/Article/details/gt2ddpiuwcu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnqzz.top/Article/details/gt2dnzmxpdb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gt2qzbdytgl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gt2axdrtsqn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fzhhl.top/Article/details/gt2crqjjopg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gt2bsiszswa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daxiang520.top/Article/details/gt2ldsbqrly.html

[J09] 时区处理
来源：http://dali.jqgufenzy.top/Article/details/gt2bcdqvyye.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gogol.net.cn/Article/details/gt2fcpubzeg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rkmtqaon.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gt2tgfvlbdp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gt2wrearptb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cdnleiting.top/Article/details/gt2eckfvxmr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqatyoqb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnxiangtu.top/Article/details/gt2mszwknas.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenzaomai.com/Article/details/gt2lsjwtdbu.html

[J10] 取今天 / 本月第一天
来源：http://dali.hammf.cn/Article/details/gt2cxcxqjll.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2usjkrmtr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pycfn.com/Article/details/gt2obbvhvqs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sweek.top/Article/details/gt2iqqkpkug.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2lzbaxqea.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2cxlqfuhz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gt2medsjdwn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gt2aqzhdkwy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ajdyqmid.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2qvyfvfwe.html

K. JSON 与序列化
来源：http://dali.hywenlv.cn/Article/details/gt2vnooxpcn.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2nonthnqq.html

[K01] 对象转 JSON 字符串
来源：http://dali.snrcjt.cn/Article/details/gt2akuqyazu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gt2zldmxznd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zyqaugoa.html

JS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2nnhcwdtk.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2vryslune.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.snrcjt.cn/Article/details/gt2lxphumri.html

Go:   json.Marshal(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2ponpksxs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tian-w.cn/Article/details/gt2uhtsytgt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcymzqu.html

[K02] JSON 字符串转对象
来源：http://dali.0kj1m.cn/Article/details/gt2htumkqev.html

Py:   json.loads(s)
来源：http://dali.tianlin.xyz/Article/details/gt2lhpdtmni.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjmyanrx.html

JS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gt2fsyfiyqm.html

TS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gt2tltibbxu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ppjwa.cn/Article/details/gt2jrvkmsvq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gt2jairbggu.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wvdyatdi.html


<!-- 参考信息 -->