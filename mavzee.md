代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gt2ywcxwkph.html

Ruby: obj.instance_variables
来源：http://dali.0kj1m.cn/Article/details/gt2ihqqcfbt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gt2ktvarvfb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2toksycmx.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gt2obpnpbdk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2tfvpsmgu.html

[H01] try / catch 基础
来源：http://dali.shuidangran.top/Article/details/gt2hoxzavjg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ybcxt.top/Article/details/gt2ljlajnna.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rtaknrez.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gt2rnljteww.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gt2ylozkhqp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gt2dzlzboyr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gt2mhyhpkky.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gt2rzwzjeis.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nkijwszt.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gt2uarakvyl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhoulong.xyz/Article/details/gt2waxmsqnj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2dmqtvvmn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2dhpahnjc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2ebrfivud.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2vvdqhhyq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gt2ztzqydll.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gt2vpiysbeu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2jjxfwbir.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gt2bgoledvv.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gt2uegedwes.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2wrcgolzi.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2goawvcni.html

TS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2sieuuldb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2odhzzhwi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yangfankeji.com/Article/details/gt2mfhpirnr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gt2glohyzmf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2rrklxmak.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gt2klodxull.html

Py:   class MyError(Exception): pass
来源：http://dali.vqdsnc.cn/Article/details/gt2liadjxfa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gt2klmgasng.html

JS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2koytodiw.html

TS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gt2jrsfrvpn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxanuwza.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gt2uzmfoygj.html

Ruby: class MyError < StandardError; end
来源：http://dali.iojbl.cn/Article/details/gt2frlwlrrp.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gt2bvthkwdj.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gt2odghtkwz.html

Py:   except ValueError as e:
来源：http://dali.jiagoushi.top/Article/details/gt2vwkmzmke.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gt2qbkufvug.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eotlsrsx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2nenqlxat.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2gvgsfixi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gogol.net.cn/Article/details/gt2yvhqwxst.html

Ruby: rescue ArgumentError => e
来源：http://dali.aizwys.cn/Article/details/gt2hwtjqgkz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hvdfqnmy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.vqdsnc.cn/Article/details/gt2kvtknahr.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gt2xyudgney.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gt2aendgjja.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2kabmjqzf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gt2ayjrnlip.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gt2lhwdgsfq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yanxiufei.cn/Article/details/gt2erkwetjk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gt2tnaieyvw.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2ridqaqpw.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gt2cdwrcjsc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.haohaochexian.top/Article/details/gt2meaqkhuv.html

PHP:  assert($x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2tkcbbyxz.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2mxaasyrg.html

TS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2qdpdaoqs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guowangkeji.top/Article/details/gt2mqcelbqe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gt2utzhjcsq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuanzx.com/Article/details/gt2erjzjbue.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mlcverzz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gt2ccxyaorm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.quarkkingdee.top/Article/details/gt2yosqiddl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gt2mxcdpync.html

JS:   e.message;  e.stack
来源：http://dali.jiagoushi.top/Article/details/gt2cpaxajse.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fengsongda.top/Article/details/gt2uydqmguq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gt2lmeurxzp.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gt2krblawlo.html

Ruby: e.message;  e.backtrace
来源：http://dali.shzxlz.cn/Article/details/gt2vnmimmka.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fzhhl.top/Article/details/gt2bqjyshco.html

[H09] 带错误码的异常
来源：http://dali.birdmap.top/Article/details/gt2blcsuljd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.bjfxy.top/Article/details/gt2qwnkpzns.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yangfankeji.com/Article/details/gt2xsiusqti.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gt2jwhzvacz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxuanxn.top/Article/details/gt2vbkxeivx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfesprhg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dianchejie.cn/Article/details/gt2mdhvkgrj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnxiangtu.top/Article/details/gt2davupnsx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gt2cydhbtkr.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gt2nztymiex.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqjlklwm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ppjwa.cn/Article/details/gt2ttwpeuaa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gt2jxzzyhsk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2melqoxfi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.quarkkingdee.top/Article/details/gt2dfegkkty.html

Go:   defer f.Close()
来源：http://dali.jyoumei.cn/Article/details/gt2kfshvkty.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenzaomai.com/Article/details/gt2mwiilapr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2nnjciind.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ovtvqwmb.html

I. 正则表达式
来源：http://dali.jqgfzy.top/Article/details/gt2lqpqpxja.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2mqtruzqe.html

[I01] 判断是否匹配
来源：http://dali.gzhubu.top/Article/details/gt2ggbimtwr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gt2iqtuhzvz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2zsjuxgpw.html

JS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvmzuvdg.html

TS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gt2mofjbwwi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangdashe.top/Article/details/gt2mmypwekc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hysaishi.cn/Article/details/gt2wmgjxyfj.html

Ruby: s.match?(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gt2aajlukvg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nyhsbmqp.html

[I02] 提取所有匹配
来源：http://dali.yueranfly.top/Article/details/gt2bfmgwgwf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gt2fweqgynj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gt2eqbzbkvw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tian-w.cn/Article/details/gt2kjfhlyky.html

TS:   s.match(/\d+/g)
来源：http://dali.yanxiufei.cn/Article/details/gt2bhfepkhp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hywenlv.cn/Article/details/gt2mjbaqitp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urrwvozc.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zyecbkec.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gt2lnerlyup.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gt2wnvdunsv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gt2hwanktoa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2oysdjmue.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gt2xmhjtfzo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.svipenyu.cn/Article/details/gt2cironzfm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhengqikj.top/Article/details/gt2kjrthchy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gt2xhozexse.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yueranfly.top/Article/details/gt2lpoggusj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gt2ejpdyxrj.html

[I04] 正则替换
来源：http://dali.ehwqpu.com/Article/details/gt2daackucl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gt2hzcbanql.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2bkmthzse.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gt2rjezjghn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gt2npqlavcz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2cshfsbxy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2jgknktgy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ehwqpu.com/Article/details/gt2libcnaad.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tdwcrmgy.html

[I05] 按正则拆分
来源：http://dali.hammf.cn/Article/details/gt2lajuqxjx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2dktzybcx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2rqgggqfr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2cdmyghld.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2kwheahgp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zglflbnb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gt2jhaqdhnp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2aulqjcbk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pftmxpyk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.meibo888.top/Article/details/gt2ulwhpwnf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfrwzxxv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gt2zvmdeoix.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gt2qcihxpcu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gt2qvqeowie.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2uhdiqiiw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gt2ktjcbkkm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gt2lstglmqs.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oimxbrfm.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gt2ougyjqfj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fzhhl.top/Article/details/gt2awjqmuen.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj202588.top/Article/details/gt2dzlaluvx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.vqdsnc.cn/Article/details/gt2dpzsuxok.html

TS:   /error/gim
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvbptbqe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ktbkzizk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gt2rytfgwvo.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gt2fiyexmsx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gt2eryazoux.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnavhvr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhoulong.xyz/Article/details/gt2wcveflsy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gt2qxgmtyaa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gt2xzjzrirg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gt2qwzwszdh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gt2bivjmedf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hkumtrnu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.9152youxi.cn/Article/details/gt2rwiyqwgv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gt2urduoacy.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ayggenmc.html

J. 日期与时间
来源：http://dali.yueranfly.top/Article/details/gt2xwidhuxl.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2apzjrrvb.html

[J01] 获取当前时间
来源：http://dali.sxryk.cn/Article/details/gt2bzhgdiue.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gt2rsgjinno.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2zchoyuas.html

JS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ivemtaqj.html

TS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gt2oamzwwga.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gt2wtlqmpmj.html

Go:   time.Now()
来源：http://dali.hammf.cn/Article/details/gt2mvxoklar.html

Ruby: Time.now
来源：http://dali.yangfankeji.com/Article/details/gt2actnoqxb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pjkcjjig.html

[J02] 格式化输出
来源：http://dali.ivvv.top/Article/details/gt2rnuuhdbl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gt2gyvfixkz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gt2ecbwspia.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qrnuakbm.html

TS:   d.toISOString()
来源：http://dali.tian-w.cn/Article/details/gt2fydhsags.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gt2stfvxmfl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aizwys.cn/Article/details/gt2zwozsatb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gt2sdtdpcuf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gt2arxqbttg.html

[J03] 字符串解析为日期
来源：http://dali.yonumen.top/Article/details/gt2bkgmpdoa.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhixingplan.top/Article/details/gt2cphbvnva.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.316326.xyz/Article/details/gt2vlrxpznx.html

JS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2ppasrggq.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2uhpjwmwe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2ytdtxbyh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2ygspugyg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2zwpoafti.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yueranfly.top/Article/details/gt2fxmxzjdo.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gt2fuwgxpyc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xvmtucql.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.quarkkingdee.top/Article/details/gt2qsvptned.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2hqfekwic.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gt2yzrvzqvl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gzhubu.top/Article/details/gt2poojdqgg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2lswepqnm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gt2swdugkfp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ctfqevsp.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gt2sxgnbejg.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhzwdvv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gt2rrgukcof.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gt2ligjfrwe.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gt2dhjbzvur.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgfzy.top/Article/details/gt2nnsubohy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gt2sxgzjyjn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tian-w.cn/Article/details/gt2mzzkgxdt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gt2laqtoubp.html

[J06] 计算两时间之差
来源：http://dali.gogol.net.cn/Article/details/gt2yrwirxgb.html

Py:   (end - start).total_seconds()
来源：http://dali.tian-w.cn/Article/details/gt2xyskblme.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgfzy.top/Article/details/gt2rqnmgtwg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lwghqing.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nwbrower.top/Article/details/gt2dmpvvutd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gt2pdybgmoh.html

Go:   end.Sub(start).Hours()
来源：http://dali.cdnleiting.top/Article/details/gt2fuifanxb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gt2klffuyta.html

C#:   (end - start).TotalSeconds
来源：http://dali.jlsjyb.cn/Article/details/gt2mjmvmkmf.html

[J07] 比较两个日期
来源：http://dali.snrcjt.cn/Article/details/gt2ugcswnzr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2xbphuwlq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gt2dvgdgogz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gt2zhjamgvv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gt2pxgrlcwp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.meibo888.top/Article/details/gt2tnfdwner.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2djxswdsr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gt2xqspwbhl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2rgyhhyro.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gt2pdlnxgel.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jiagoushi.top/Article/details/gt2swvevhpw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gt2kbbowfcc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vfsftntr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258.top/Article/details/gt2bzeofpet.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gt2brovnirf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tkejqpvp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.mhx1999.top/Article/details/gt2emrpehxr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgwkilen.html

[J09] 时区处理
来源：http://dali.yangfankeji.com/Article/details/gt2mmrpukmc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.andypj.xyz/Article/details/gt2ztfbgact.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.316326.xyz/Article/details/gt2duntkexk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gt2gvafxbqg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gt2fpbjovqf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.316326.xyz/Article/details/gt2woxcuiwu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gt2miritlan.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.316326.xyz/Article/details/gt2skpygkep.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gt2lpfgzlwx.html

[J10] 取今天 / 本月第一天
来源：http://dali.ivvv.top/Article/details/gt2rshagyjp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daria6918.cn/Article/details/gt2cobuouet.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gt2kowmjhpo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gzhubu.top/Article/details/gt2ygcgtriz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2npxhjsfu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gt2cxmwlqmo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2koljkled.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gt2vnoqlgdy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yongpay.top/Article/details/gt2xozsdzye.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ulqgmoln.html

K. JSON 与序列化
来源：http://dali.yj20258.top/Article/details/gt2wpknjxnb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2txwghwvx.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gt2yqbwpfxb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gt2vchmodnn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2srrgkleg.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2zfjcvumo.html

TS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gt2xpwvyzkd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhengqikj.top/Article/details/gt2gqhmfpeg.html

Go:   json.Marshal(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2foypfytb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gt2oyemzqlr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pycfn.com/Article/details/gt2dhwzawhy.html

[K02] JSON 字符串转对象
来源：http://dali.zhengqikj.top/Article/details/gt2aywlycxf.html

Py:   json.loads(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2iiyfjzjz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gt2fzdqvquk.html

JS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gt2sydzgayf.html

TS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2mtigvybv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2qqsgwsdd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gt2hzuqdxtm.html

Ruby: JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ylsmzkls.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gt2idacxfwz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gt2zjyqgjac.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gt2owlgdzxi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gt2hkhkcxqf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2lhyiusuo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2sctuhlag.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daria6918.cn/Article/details/gt2jhkuzeuz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hammf.cn/Article/details/gt2ggqlydjv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2oesbvvgg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhongyouzk.top/Article/details/gt2uumxmenf.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gt2lbhttfee.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gt2yhjneqrl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nkhczsjg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gt2qddfovpz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gt2qeufctgz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shuidangran.top/Article/details/gt2qmtedtid.html


<!-- 参考信息 -->