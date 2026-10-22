代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.xuanzx.com/Article/details/gt2fcfjspak.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gt2yedntpww.html

[G16] 对象转数组 / 字典
来源：http://dali.pycfn.com/Article/details/gt2uhotdpya.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jiagoushi.top/Article/details/gt2odzdomae.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigfzy.top/Article/details/gt2wjfwebje.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gt2jawvbaou.html

TS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2itwfygyy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gt2hxpvhvma.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gt2qloqqoah.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gt2tdeaedsh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gt2utmwwmgc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmgtyzct.html

H. 异常与错误处理
来源：http://dali.gzhubu.top/Article/details/gt2ivfvuidy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2jzazwlye.html

[H01] try / catch 基础
来源：http://dali.shangyingyoupin.top/Article/details/gt2oyxgvuex.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gt2wxpaewdh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.bjfxy.top/Article/details/gt2hxyquqiq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kimkdoac.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gt2oskrajsd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gt2dgaashwp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tbctnsqz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tianlin.xyz/Article/details/gt2nanzsuwv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgsbblzb.html

[H02] finally / ensure 收尾
来源：http://dali.c1oappe.top/Article/details/gt2crnwvnmk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gt2sezjxqrb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2uikixgqj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2gqgdeatw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2woowxkjw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2sfbthrbr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yueranfly.top/Article/details/gt2ppyhgyzg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gt2mipcxirg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2dvzqlodc.html

[H03] 主动抛出异常
来源：http://dali.chenzaomai.com/Article/details/gt2ajbnyjum.html

Py:   raise ValueError("错误信息")
来源：http://dali.cqqwz.cn/Article/details/gt2czmzreck.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2sexytgsz.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2wceqnrrs.html

TS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2nwnxedjh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2zqawmbaz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gt2oimoeapz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gt2pwgfhwwg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2ugrzjfai.html

[H04] 自定义异常类型
来源：http://dali.cheryme.top/Article/details/gt2qjvfewcc.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gt2btmkosby.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gt2ttsfbvnf.html

JS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gt2prdjulgj.html

TS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gt2svvlurqz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vilyluiw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gogol.net.cn/Article/details/gt2vqgbfmdf.html

Ruby: class MyError < StandardError; end
来源：http://dali.yvedp.cn/Article/details/gt2mjvdfpbn.html

C#:   class MyException : Exception {}
来源：http://dali.ivvv.top/Article/details/gt2tlpgxemn.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpnzxpx.html

Py:   except ValueError as e:
来源：http://dali.jinghuilouyu.cn/Article/details/gt2krjhssij.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.havefunace.top/Article/details/gt2jsbjspal.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gt2gkkqyahj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gt2fchbwyqc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hfpthk.cn/Article/details/gt2npmhsqij.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gt2ckytsvro.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gt2zxlmhzzr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gt2epysnofo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aibaodan.cn/Article/details/gt2uatkwpqh.html

Py:   value = d.get("k") or default
来源：http://dali.quarkkingdee.top/Article/details/gt2uhlrpxps.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gt2euahpdvh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gt2legjwclh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gt2yujjfjox.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gt2sowdttas.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pvouituq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gszqkzpd.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gt2ypxoadej.html

[H07] 断言
来源：http://dali.aibaodan.cn/Article/details/gt2iduoonag.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dashuyun.cn/Article/details/gt2mwqiwhrk.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2tpgkiofj.html

JS:   console.assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2pijvkjwq.html

TS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2ycaynjrn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.quarkkingdee.top/Article/details/gt2obfhwgim.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gt2objupvvi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gt2yckesuye.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gt2voddqtex.html

[H08] 获取错误信息与堆栈
来源：http://dali.hywenlv.cn/Article/details/gt2emkkqlyp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gt2elpefqxq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zdqjudy.top/Article/details/gt2etukyjsu.html

JS:   e.message;  e.stack
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nvoueepk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gt2fosnfzgr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daria6918.cn/Article/details/gt2znedzgcy.html

Go:   err.Error()
来源：http://dali.yuxming.cn/Article/details/gt2rhebesay.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gt2ozrdpjuc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gt2frbbmhxr.html

[H09] 带错误码的异常
来源：http://dali.cheryme.top/Article/details/gt2mobbebkt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ybcxt.top/Article/details/gt2dlxhyqcw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gt2mbkdlfxz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dianchejie.cn/Article/details/gt2opfstfjv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2muavqcur.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gt2lctktljc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jyoumei.cn/Article/details/gt2eluzgswd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aizwys.cn/Article/details/gt2jvvqabem.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gt2nilwwbso.html

[H10] 资源自动释放
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mersohia.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pycfn.com/Article/details/gt2gyfqhzel.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gt2apnadotg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gt2idqnhwny.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gt2owxjbblf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmngcgpu.html

Go:   defer f.Close()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hehazuwv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenlongwang.top/Article/details/gt2jhqgreug.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2vkfkvywh.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2tmmdwjty.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2otgkrmhs.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2orzzrbsc.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gt2locmcjdy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2gtvgcwqo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2thmuqvhp.html

JS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gt2bevwgxpe.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2dvbamkhz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qlqjjpeo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cdnleiting.top/Article/details/gt2eseqekot.html

Ruby: s.match?(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gt2jhetyvml.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hfpthk.cn/Article/details/gt2obhznhfo.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gt2jjysafgr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2zgrgxcwk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cucudq.cn/Article/details/gt2aucmfzht.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gt2qijgsayy.html

TS:   s.match(/\d+/g)
来源：http://dali.redwolf501.top/Article/details/gt2gmwpxatt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tian-w.cn/Article/details/gt2lpneihxj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2xgfilkya.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2mgrswzzw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2julgoxio.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jmegtlhl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhixingplan.top/Article/details/gt2jismqzxm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gt2gnvffowf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.smart0.xyz/Article/details/gt2kgwymmjl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gt2tssnfvry.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xdlwbntz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cqqwz.cn/Article/details/gt2iebivbps.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tanke756.top/Article/details/gt2ivmfbbme.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zdqjudy.top/Article/details/gt2bbcixbta.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gt2zsjtnqpv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gt2nynvdxmo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gt2kybwkqca.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gt2bixvkuvb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2bwyfaivs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gt2lxilzoww.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2itiplnum.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hfpthk.cn/Article/details/gt2lzehfsnj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gt2nkkajnow.html

[I05] 按正则拆分
来源：http://dali.smart0.xyz/Article/details/gt2yduyjezp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnqzz.top/Article/details/gt2gauukbxj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2mkmspjzc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gt2pzkdfbgv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zpzijvxw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhengqikj.top/Article/details/gt2sudvggad.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.havefunace.top/Article/details/gt2tpthzccn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tzyebdut.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xylfe.cn/Article/details/gt2grqnnuli.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mcbwmivn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2ejcaidzx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258888.top/Article/details/gt2tqutgdla.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gt2khmsfifh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gt2ozgvqqcs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gt2kjbqvtfm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gt2zdmasjlc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gt2mlrdclgt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2zahmcgch.html

[I07] 忽略大小写与多行模式
来源：http://dali.yonumen.top/Article/details/gt2hibseyta.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gt2usmzmkly.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gt2qixbwkmq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gt2nctcprja.html

TS:   /error/gim
来源：http://dali.gotoacloud.top/Article/details/gt2tasqemax.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fsenzzlv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gt2sgigkslb.html

Ruby: s.scan(/error/i)
来源：http://dali.xziqi.cn/Article/details/gt2dencwlhh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gt2tkcyyjub.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ydzc1.top/Article/details/gt2mpqswqlc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tian-w.cn/Article/details/gt2jirojxij.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2hamgrufw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gt2iedrjfbj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gt2xjqnyyur.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gt2aksdcfrg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhixingplan.top/Article/details/gt2dnupacif.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gt2stqsqcpc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gedjagbm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2chmoynaw.html

J. 日期与时间
来源：http://dali.daria6918.cn/Article/details/gt2osuuesky.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2qoqmywan.html

[J01] 获取当前时间
来源：http://dali.jianghu66.top/Article/details/gt2xdxbjrdv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gt2qrxsagal.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gt2fuslgvhr.html

JS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gt2jnehrule.html

TS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gt2ajrwfdnq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cdnleiting.top/Article/details/gt2vywlyqqb.html

Go:   time.Now()
来源：http://dali.dashuyun.cn/Article/details/gt2tqtnfbar.html

Ruby: Time.now
来源：http://dali.xuetiantiany.cn/Article/details/gt2mbfuyijb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gt2jffewehv.html

[J02] 格式化输出
来源：http://dali.cheryme.top/Article/details/gt2xcohavss.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gt2dqedklcx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gt2fugnwnyz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gogol.net.cn/Article/details/gt2pbpnwiej.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gt2iwpfbryp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnxiangtu.top/Article/details/gt2llrebfzh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj202588.top/Article/details/gt2ffvuospm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wrluomzx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gt2zzkzavrx.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gt2rrbxfchd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.redwolf501.top/Article/details/gt2zpjmiddf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gt2tnkbitvl.html

JS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2aalnzrjf.html

TS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2spmkoznr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2pzbwocim.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2soouuyeb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2rxnltcla.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvgceipt.html

[J04] 时间戳与日期互转
来源：http://dali.tanke756.top/Article/details/gt2iroqawuj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gt2laihgnve.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuanzx.com/Article/details/gt2hbcwjvth.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yonumen.top/Article/details/gt2lwrlnepa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yvedp.cn/Article/details/gt2bvjwymea.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tian-w.cn/Article/details/gt2qkftgvmz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuanzx.com/Article/details/gt2csqkxwxr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guannengcc.top/Article/details/gt2yojpobzt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cucudq.cn/Article/details/gt2ugkgccar.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gt2pccfxblb.html

Py:   now + timedelta(days=7)
来源：http://dali.ydzc1.top/Article/details/gt2qxydhssi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gt2njrmcdde.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2stbbeqox.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gt2wudleeih.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gt2wecgjrpz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gt2michqgxi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gt2hthjjwfr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigufen.top/Article/details/gt2kheuqevf.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gt2aqhczadx.html

Py:   (end - start).total_seconds()
来源：http://dali.svipenyu.cn/Article/details/gt2qnyntfov.html

PHP:  $end->diff($start)->days;
来源：http://dali.jlsjyb.cn/Article/details/gt2kdpxpttn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gt2naxouvvb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daria6918.cn/Article/details/gt2qsvpaigu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnxiangtu.top/Article/details/gt2iynscxkt.html

Go:   end.Sub(start).Hours()
来源：http://dali.zdqjudy.top/Article/details/gt2qsuxbbam.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxinkj.top/Article/details/gt2vbryaqlp.html

C#:   (end - start).TotalSeconds
来源：http://dali.ybcxt.top/Article/details/gt2gifezlds.html

[J07] 比较两个日期
来源：http://dali.chenjidiqi.icu/Article/details/gt2uekrfxmw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gt2rnmeoxty.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxrpepfa.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gt2sldqfhsz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gt2jqwhpack.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.svipenyu.cn/Article/details/gt2lbynuqpt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jlsjyb.cn/Article/details/gt2lsgxeboh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2kuwzubjj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gt2ozwrvjvi.html

[J08] 提取年月日与星期
来源：http://dali.shuidangran.top/Article/details/gt2zizpaygw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljgenosk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gt2tuiuwzjq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ivkwpfml.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hysaishi.cn/Article/details/gt2nktcools.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhongyouzk.top/Article/details/gt2nlubmqtt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gt2bulcekga.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xziqi.cn/Article/details/gt2eunzmdin.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gt2ufifojgv.html

[J09] 时区处理
来源：http://dali.cashguo.top/Article/details/gt2cbgxcvho.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gt2dodsjpau.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kteuajzr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gt2otliqtxs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jutxhvmn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.9152youxi.cn/Article/details/gt2bxvrocmp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sweek.top/Article/details/gt2biwuebpo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gt2khnthqqh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gt2durisdhp.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gt2yoeewmni.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhengqikj.top/Article/details/gt2pgmoprue.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gt2ktudbfez.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2ucwvarcq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2nefvysgb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuanzhike.top/Article/details/gt2vdhhpbln.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gt2qwdnkyvs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gt2nwfwxcjh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cqqwz.cn/Article/details/gt2oislcvti.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2gnpckovh.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gt2snkcnqvs.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2tfmjkidk.html

[K01] 对象转 JSON 字符串
来源：http://dali.sweek.top/Article/details/gt2qihsxocp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gt2sovqcamv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ikkrzghd.html

JS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gt2uhgbcogx.html

TS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gt2kutezqdn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.bjfxy.top/Article/details/gt2tlmwjnah.html

Go:   json.Marshal(obj)
来源：http://dali.cashguo.top/Article/details/gt2dzgvthju.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gt2inymszlq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gt2arvlisil.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gt2dltxyywb.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gt2rpkzxyoi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2akpfmvex.html

JS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gt2emwozufk.html

TS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gt2fypswmpa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cheryme.top/Article/details/gt2lqzvnwin.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gt2ycgbdcwe.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2yhwczgzd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nwbrower.top/Article/details/gt2eajpewco.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dashuyun.cn/Article/details/gt2mzxbejhd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gt2cjkgfsov.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gt2alnempkj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2hzdbadna.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2caqnktua.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gkwzxjst.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gt2zdysxpic.html


<!-- 参考信息 -->