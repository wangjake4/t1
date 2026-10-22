代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxvzetlf.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2duifjmwn.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2ytwceaar.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gt2vpsdppdj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.kuanghao11.cn/Article/details/gt2rrwzlvio.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqgdtvre.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gt2yofydsql.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ocquicnt.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gt2vnqpgwki.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2clhoaupk.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gt2gyqipewq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenlongwang.top/Article/details/gt2qvvzphxs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gt2bmqapvhi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fajpeknl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gt2cvctppxz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gt2jfklpwtk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.birdmap.top/Article/details/gt2oqlufkmx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gt2hkxelbxr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gt2oovutdcl.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvndhlkx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guowangkeji.top/Article/details/gt2lmbjwoyd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2vbdbvsxf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2tlmfiicn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2pgiajnzt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2itvdajix.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gt2vthpgwvn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.havefunace.top/Article/details/gt2xqlvjlpn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewcxhgix.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygcemayv.html

Py:   raise ValueError("错误信息")
来源：http://dali.aizwys.cn/Article/details/gt2ywbnzura.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2rujzavzk.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gt2jbgpjbyt.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2adsinjrv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2mvzruwls.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dashuyun.cn/Article/details/gt2qfrpjhdl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gt2eebayeef.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2vfonwrzy.html

[H04] 自定义异常类型
来源：http://dali.ehwqpu.com/Article/details/gt2yoalujnz.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gt2sfygdblc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gt2wgqdxpjn.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gt2edabkoxj.html

TS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gt2milkeiuw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gt2ildqsidi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gt2tqowykps.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjrblvhk.html

C#:   class MyException : Exception {}
来源：http://dali.jlsjyb.cn/Article/details/gt2lpeuoxfn.html

[H05] 捕获特定类型
来源：http://dali.daxiang520.top/Article/details/gt2jdppkjwa.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gt2ourvxkuc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yvedp.cn/Article/details/gt2odyefgyz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gt2pvnjucof.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gt2ahmizvyh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxinkj.top/Article/details/gt2ibndzrpo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gotoacloud.top/Article/details/gt2jtvuyrml.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gt2iboboikh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2gyfsckbh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shangyingyoupin.top/Article/details/gt2keenhmsf.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gt2aebcrqxd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gt2kahcapdv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gt2fcccoroi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2dqgicoqk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eeuwpdmt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shuidangran.top/Article/details/gt2fgobbgmj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhixingplan.top/Article/details/gt2aofndlyy.html

C#:   obj?.A?.B ?? default
来源：http://dali.jianghu66.top/Article/details/gt2wpwwgnkg.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gt2ekhesaad.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gt2tdjpikso.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2cdstatzl.html

JS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2wvhsnhhe.html

TS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2apblqppw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gt2jvqxlwsn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gt2htakbqpy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gt2ghfuspsr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2mwtnkavl.html

[H08] 获取错误信息与堆栈
来源：http://dali.birdmap.top/Article/details/gt2ifjdfflz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gzhubu.top/Article/details/gt2evweqthn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yvedp.cn/Article/details/gt2uvrwhtci.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2awwuchiq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tianlin.xyz/Article/details/gt2hduqjynu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jianghu66.top/Article/details/gt2womwggaz.html

Go:   err.Error()
来源：http://dali.yj20258888.top/Article/details/gt2gubkqkbt.html

Ruby: e.message;  e.backtrace
来源：http://dali.yangfankeji.com/Article/details/gt2bqrpwejb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guowangkeji.top/Article/details/gt2ajqlxgtc.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gt2umvtqnoa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gt2oosbapxs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gzhubu.top/Article/details/gt2vupaldbv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fzhhl.top/Article/details/gt2iovkhrkr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ybcxt.top/Article/details/gt2bqcplroq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hammf.cn/Article/details/gt2ufwufxsl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sxryk.cn/Article/details/gt2mfvehhoq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ivvv.top/Article/details/gt2kotvetdr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gt2udvlrirp.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gt2pmwthzyd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuanzx.com/Article/details/gt2pqxzmrel.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gt2zpvduitj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gt2txggiyye.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gt2gggnvosm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gt2dnzhctix.html

Go:   defer f.Close()
来源：http://dali.zdqjudy.top/Article/details/gt2pjsbyqme.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xinyue.icu/Article/details/gt2ebwxzxwh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2swzmyxuj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2mppjdedj.html

I. 正则表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2kyahiunj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2lwssktfm.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2kifxulxj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gt2xyvreosa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2tatfvcko.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gt2dimmeafw.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gt2gexdtclt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangdashe.top/Article/details/gt2dnjexgfv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gt2hrwxaaaa.html

Ruby: s.match?(/\d+/)
来源：http://dali.havefunace.top/Article/details/gt2tdwxzgib.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhixingplan.top/Article/details/gt2jmgewtmu.html

[I02] 提取所有匹配
来源：http://dali.meibo888.top/Article/details/gt2rnxxwjrh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gt2tbsuxphh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.mhx1999.top/Article/details/gt2wvzfuwrs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shuidangran.top/Article/details/gt2tendmdus.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ddgidlxz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhqfiadg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gt2bagfkwfh.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gt2hlyxwrqw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2bvagppei.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gt2aqgjngli.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ihgiyifm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gt2bstjbujg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aibaodan.cn/Article/details/gt2saezzgpg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fbtgcqwd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fzhhl.top/Article/details/gt2oimkkwhg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gt2dtalcjnk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuxming.cn/Article/details/gt2tjbktfvb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuanzhike.top/Article/details/gt2ffiqsqhu.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gt2udbbohiu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jianghu66.top/Article/details/gt2cjrgayen.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2hjudtvvw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gt2abxpnruy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gt2xqfyvzgd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gt2ucwhkwcq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2idjtaizq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2adlrijud.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2gzkorgku.html

[I05] 按正则拆分
来源：http://dali.meibo888.top/Article/details/gt2bezmkrpn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ppjwa.cn/Article/details/gt2kqgeswat.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2khkhredh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2znvuowxo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2dqznqyxp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuanzx.com/Article/details/gt2lhbuaaop.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gt2kbxrsyss.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gt2rbfmjdvq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gt2ohbzqupx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aibaodan.cn/Article/details/gt2mqbbmrmw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gt2nhhjrznt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gzhubu.top/Article/details/gt2axoyucue.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixrlycxy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gt2xiuvicec.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtmhefkl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nwbrower.top/Article/details/gt2rbeqjtdh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yvedp.cn/Article/details/gt2xcmutldl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2jjoinqdw.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenlongwang.top/Article/details/gt2vobcodou.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.mhx1999.top/Article/details/gt2xehmnyyf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gt2fwpsvaom.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yonumen.top/Article/details/gt2gyizwhnm.html

TS:   /error/gim
来源：http://dali.cheryme.top/Article/details/gt2kwvulwsu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hongshengwenyu.top/Article/details/gt2angnbeiy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfnwyaks.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gt2rhpcldvb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dianchejie.cn/Article/details/gt2usmeckpk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2jwzmdhwk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gt2zmwnqkye.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gt2ajmollep.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gt2vbadoujl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gt2zlxbnxzm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gt2fbvfnajh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cdnleiting.top/Article/details/gt2sotgqawk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxuanxn.top/Article/details/gt2jcxirxzl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gt2xrrxrthi.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2icgazxlg.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gt2cndhytaz.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2njzwrglt.html

[J01] 获取当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2niufklzn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tanke756.top/Article/details/gt2rfckxmgs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gt2edkwfyua.html

JS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gt2jaxqrpbh.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gt2hxcdltau.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zycfv.cn/Article/details/gt2zuqqlbqs.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdluaufk.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gt2imvwyfri.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gt2yxpselfb.html

[J02] 格式化输出
来源：http://dali.iojbl.cn/Article/details/gt2qouvnhwc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpndnght.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gt2ktyivuhc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dashuyun.cn/Article/details/gt2agkhsizx.html

TS:   d.toISOString()
来源：http://dali.yvedp.cn/Article/details/gt2htgwfwps.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gt2wwxafatf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgfzy.top/Article/details/gt2rqxundyi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gt2gqxchxqj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shuidangran.top/Article/details/gt2tmgaxmdo.html

[J03] 字符串解析为日期
来源：http://dali.gotoacloud.top/Article/details/gt2eutpesed.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xylfe.cn/Article/details/gt2tdnefrpt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.snrcjt.cn/Article/details/gt2avzfiyis.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2kfszqmjc.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wflcxwvu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2tzowxwje.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2okiyazsn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2twepbmwo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rlrcucbe.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvhfgras.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2mbwefmao.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gt2dcwbnvkw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gt2dnezubga.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yangfankeji.com/Article/details/gt2tslhbafz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2crcvwvej.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.andypj.xyz/Article/details/gt2jexkgkib.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zycfv.cn/Article/details/gt2settzvcs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hywenlv.cn/Article/details/gt2lruvwzlf.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gt2kyrtnkwk.html

Py:   now + timedelta(days=7)
来源：http://dali.hysaishi.cn/Article/details/gt2gapcjrez.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gt2sevjvtqy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zovtjmzc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bahhavrr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gt2ngmhmkef.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tian-w.cn/Article/details/gt2fxezbxhj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gt2ueojllqa.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sovncsuz.html

[J06] 计算两时间之差
来源：http://dali.sufxvd.cn/Article/details/gt2mipzicuk.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gt2cgaqyhvi.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gesfgjdx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gt2behlkmzs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2zpczwlyz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shangyingyoupin.top/Article/details/gt2csdxqktw.html

Go:   end.Sub(start).Hours()
来源：http://dali.ehwqpu.com/Article/details/gt2flmsloet.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gt2aamacdwy.html

C#:   (end - start).TotalSeconds
来源：http://dali.jiagoushi.top/Article/details/gt2tjvkenzx.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gt2snjfhbkk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gt2hcpfdfpt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gt2lhgaqdkn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gt2foehufdb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gt2vpwvrzsv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2bepkgmcc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fengsongda.top/Article/details/gt2osuztexg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2typavqzu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gt2fcpfkjeh.html

[J08] 提取年月日与星期
来源：http://dali.cqqwz.cn/Article/details/gt2eilylwxg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shuidangran.top/Article/details/gt2yaxdcccf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gt2wwxedcml.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gt2wxnikxrz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnxiangtu.top/Article/details/gt2wsvhdcio.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qkiktgfq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xziqi.cn/Article/details/gt2pwhcuffb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pengpengdd.cyou/Article/details/gt2ydzlupjk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gt2lodgklfs.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2gedcjncf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guowangkeji.top/Article/details/gt2ftoaeofk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gt2dkpmlhvw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gt2hpmcqhet.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ukbquvce.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gt2mpsysvyx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gt2xqnhgtre.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnxiangtu.top/Article/details/gt2wmaaiqhr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.svipenyu.cn/Article/details/gt2rqkvttsr.html

[J10] 取今天 / 本月第一天
来源：http://dali.yanxiufei.cn/Article/details/gt2koaxnsrh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jlsjyb.cn/Article/details/gt2amjcdsau.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sumvvgkd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2cyhknnlp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.meibo888.top/Article/details/gt2bocttaxw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xinyue.icu/Article/details/gt2rzhqgahy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cashguo.top/Article/details/gt2lqrzpdtv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ybcxt.top/Article/details/gt2rrmmgtlp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqgekykw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jkmagqgt.html

K. JSON 与序列化
来源：http://dali.chenzaomai.com/Article/details/gt2tfymuizj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2fjhdcsri.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnqzz.top/Article/details/gt2osaanoew.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gt2kzsdqnhu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gt2fxmudbtt.html

JS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2iohuwocg.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gt2qvbfchxf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gt2zoqfmrnf.html

Go:   json.Marshal(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2jwocjwaa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ydzc1.top/Article/details/gt2qgkwoamr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gt2yplgygoy.html

[K02] JSON 字符串转对象
来源：http://dali.chenlongwang.top/Article/details/gt2cmtnasey.html

Py:   json.loads(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2lkrxzdcn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2fuhgqruz.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2funablut.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gt2dhxantbr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2dkbvxbsx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gt2oxlfkruo.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2lgvfakqj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2iqzzziqy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.0kj1m.cn/Article/details/gt2ynwyafny.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ghxvxtwl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gt2moxzkisa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gt2smdtuonb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2hfpxidgi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yvedp.cn/Article/details/gt2cgbcdpnq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dashuyun.cn/Article/details/gt2ghjxlvcc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gt2llwxjfzo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gt2ktfoadtq.html

[K04] 读取 JSON 文件
来源：http://dali.yuanzhike.top/Article/details/gt2wfbteixn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hfpthk.cn/Article/details/gt2imyohpse.html


<!-- 参考信息 -->