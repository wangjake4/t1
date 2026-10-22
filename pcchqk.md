代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.kuanghao11.cn/Article/details/gt2mujveqgu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258888.top/Article/details/gt2irzqvsnb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gt2tsqvqqsn.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gt2yuokkulx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cheryme.top/Article/details/gt2hogwsnum.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2hvcsqypp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2cyynlakv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2yxobwrwv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2hlxfusdx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhiwuduotai.top/Article/details/gt2aijjjvjb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.andypj.xyz/Article/details/gt2knxiasro.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2tcuvsnur.html

[H03] 主动抛出异常
来源：http://dali.chenzaomai.com/Article/details/gt2pumseetr.html

Py:   raise ValueError("错误信息")
来源：http://dali.xinyue.icu/Article/details/gt2nbxkzxrv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2ctqvyyui.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2sbwceqex.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2kucclbfc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2minszjpz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gt2ixychvah.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gt2sapeayyp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2grlchyaw.html

[H04] 自定义异常类型
来源：http://dali.redwolf501.top/Article/details/gt2rktzhaiw.html

Py:   class MyError(Exception): pass
来源：http://dali.yuxming.cn/Article/details/gt2wjrpmrny.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gt2mlxdryqf.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cyfcmmrg.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gt2mtnfplit.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2rueynexq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tian-w.cn/Article/details/gt2lfpdtwol.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gt2wjrztcyi.html

C#:   class MyException : Exception {}
来源：http://dali.ehwqpu.com/Article/details/gt2aqgztxwx.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gt2xuljwelb.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtibydqx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cashguo.top/Article/details/gt2ppluumov.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phugzpxn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gt2eddbbkzz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gt2wzeiwmmq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daria6918.cn/Article/details/gt2jzrfedwi.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gqibksdk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hywenlv.cn/Article/details/gt2zkylypww.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gt2srhwkyuz.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gt2qbbnechj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gt2npwsdqqy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gt2expqqktf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xvwbkqkn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.vqdsnc.cn/Article/details/gt2lvzvjclg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gt2svkufben.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxuanxn.top/Article/details/gt2roeketph.html

C#:   obj?.A?.B ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2jkbmlucr.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gt2oynbcyin.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gt2mwwahgci.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gt2vuroxubx.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2klbhnodh.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2tglqlgcj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdbsiuqm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuanzhike.top/Article/details/gt2ldxxstih.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gt2fizztssj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2auqdlkfj.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuanzhike.top/Article/details/gt2uquoebby.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuanzx.com/Article/details/gt2yvjduyeq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jianghu66.top/Article/details/gt2rtenyxgi.html

JS:   e.message;  e.stack
来源：http://dali.xuetiantiany.cn/Article/details/gt2iooosvvw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hfpthk.cn/Article/details/gt2rncvgydb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jlcglfsv.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gt2gnwbocvv.html

Ruby: e.message;  e.backtrace
来源：http://dali.cqqwz.cn/Article/details/gt2cmsesokd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fcvssytz.html

[H09] 带错误码的异常
来源：http://dali.xuetiantiany.cn/Article/details/gt2xjfoqpzg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gt2qrigdbvb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xinyue.icu/Article/details/gt2obgzzqba.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gt2zexhjroq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yongpay.top/Article/details/gt2oxczfmql.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ajdasszf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.c1oappe.top/Article/details/gt2gmrkjlfc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccxsmsew.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guannengcc.top/Article/details/gt2fjcnmmct.html

[H10] 资源自动释放
来源：http://dali.snrcjt.cn/Article/details/gt2fzghhtbq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gt2tucyibnm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gt2zjvloojh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gt2mknuwojz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gt2zfvgfwji.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gt2lwlfnypo.html

Go:   defer f.Close()
来源：http://dali.daxiang520.top/Article/details/gt2varakfha.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.vqdsnc.cn/Article/details/gt2dunvuygs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2tmtzfhiv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2nzgqthho.html

I. 正则表达式
来源：http://dali.xylfe.cn/Article/details/gt2swwncjyx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2iwvszfua.html

[I01] 判断是否匹配
来源：http://dali.ivvv.top/Article/details/gt2xfenauwg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gt2vejufbdh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gt2nzcveldb.html

JS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gt2ohhlmljd.html

TS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gt2fzaucrja.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gt2sekpmdjm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uckkzszg.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gt2uvwabwaa.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.c1oappe.top/Article/details/gt2mstlupnf.html

[I02] 提取所有匹配
来源：http://dali.ydzc1.top/Article/details/gt2wonwyxqe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gt2kwkvwuwm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gt2giqqxxua.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gzhubu.top/Article/details/gt2kgjvrcbv.html

TS:   s.match(/\d+/g)
来源：http://dali.sxryk.cn/Article/details/gt2gmaenfew.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gt2rynjpodv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lkxrapbi.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gecqztey.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2czrcflcv.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gt2hrbkxcxg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fengsongda.top/Article/details/gt2zhnpjqhd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pskzgmgr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hammf.cn/Article/details/gt2wfzlbkmb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yueranfly.top/Article/details/gt2ojgsuonv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258888.top/Article/details/gt2dpapjdcd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sufxvd.cn/Article/details/gt2vpjyklzi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2iutwrrci.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuanzx.com/Article/details/gt2kkzazedm.html

[I04] 正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odlhhwxm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gzhubu.top/Article/details/gt2wzkyfmiv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2ietbjuci.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gt2zscprgzm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2uakkfqtr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gt2jfzexzrh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lselqsjv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aizwys.cn/Article/details/gt2dsqdtexc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gt2hltrnlgs.html

[I05] 按正则拆分
来源：http://dali.wangdashe.top/Article/details/gt2lvjrnuym.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gt2xuektlbp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2cdqbebuj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gt2rmmjdlln.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gt2vsskweoe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gt2scrjkuqc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ybcxt.top/Article/details/gt2wtbvijke.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gt2zipsbfnl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shzxlz.cn/Article/details/gt2pebzeplh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xinyue.icu/Article/details/gt2zbyqptrm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gt2zupapvvn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.iojbl.cn/Article/details/gt2rxhlismd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gt2mljufdvk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewakhvwl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gt2zluenujs.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tianlin.xyz/Article/details/gt2owahvrez.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.mhx1999.top/Article/details/gt2xnjvfduc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2jcntnhxf.html

[I07] 忽略大小写与多行模式
来源：http://dali.guannengcc.top/Article/details/gt2xsagwovd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.redwolf501.top/Article/details/gt2hnkcvtfx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhbcgow.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gt2xzghrrsk.html

TS:   /error/gim
来源：http://dali.hnqzz.top/Article/details/gt2tiddznup.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqosklmy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ydzc1.top/Article/details/gt2caukdwsh.html

Ruby: s.scan(/error/i)
来源：http://dali.nwbrower.top/Article/details/gt2tgyhiieg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bisqqyak.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sufxvd.cn/Article/details/gt2selridnq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ehwqpu.com/Article/details/gt2icqesdxk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gt2qaxyavvk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gt2esiqvphj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gt2stldiqha.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gt2mrlzbrck.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guannengcc.top/Article/details/gt2pquhvhvj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gt2hwithzyi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gt2mtsabajc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2yilzusaw.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2akmdvzhb.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2irtunnwq.html

[J01] 获取当前时间
来源：http://dali.hammf.cn/Article/details/gt2wlcfpzkr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tanke756.top/Article/details/gt2eppblsbc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gt2nsyndgyp.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gt2qxtskqwe.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gt2uqqtrehn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daxiang520.top/Article/details/gt2kecbpxdg.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gt2poqewluh.html

Ruby: Time.now
来源：http://dali.dashuyun.cn/Article/details/gt2befnqecd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shuidangran.top/Article/details/gt2fviddthu.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpngkjvx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gt2wohackka.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gt2tdlwvwyt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vvlqjdlg.html

TS:   d.toISOString()
来源：http://dali.sysykeji.top/Article/details/gt2syyhfpxe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ehwqpu.com/Article/details/gt2powgfywe.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258888.top/Article/details/gt2hjoiyhyr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gt2ezfyutrh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cucudq.cn/Article/details/gt2frnzcfan.html

[J03] 字符串解析为日期
来源：http://dali.zhiwuduotai.top/Article/details/gt2amarxupr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gaohongyu789.top/Article/details/gt2eqaapksb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tanke756.top/Article/details/gt2gadbamkk.html

JS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wgybxpnq.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2xmfqzdqi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2noroiafb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2ggwmvvjj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2wquqwrmw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ehwqpu.com/Article/details/gt2eywwcbvq.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gt2pfctyepe.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258.top/Article/details/gt2bhndnotn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gt2qordmzpl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.snrcjt.cn/Article/details/gt2pfhgxnbg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gt2tersxpoh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gt2lfgstxde.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hammf.cn/Article/details/gt2swkkupsg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gt2vxxinoel.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2thrjqmzo.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqxopkmk.html

Py:   now + timedelta(days=7)
来源：http://dali.yuanzhike.top/Article/details/gt2ufpzmskr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2btmtxxdk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gt2lqncihdu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gt2qviqeuci.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gt2lmvtvdra.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ustijppu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yanxiufei.cn/Article/details/gt2vjgsmasp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jyoumei.cn/Article/details/gt2enqyncyp.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gt2xpldyqnl.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gt2epreeoht.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gt2oikhnztg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jyoumei.cn/Article/details/gt2qytestzs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tanke756.top/Article/details/gt2wwwiexwj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hysaishi.cn/Article/details/gt2qhnlsfre.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gt2gykixnwf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gt2qknigkro.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gt2ahoidzdz.html

[J07] 比较两个日期
来源：http://dali.hongshengwenyu.top/Article/details/gt2jwbjbxxc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2ulwoifcw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gt2xdgawhtb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gt2radxjeoq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gt2sqhnfbhk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gt2szsecxce.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhengqikj.top/Article/details/gt2bikbpqlo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2awftikgt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gt2gtryqndp.html

[J08] 提取年月日与星期
来源：http://dali.sufxvd.cn/Article/details/gt2drwualom.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gt2vxlatezx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gzhubu.top/Article/details/gt2avmwhcwq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.havefunace.top/Article/details/gt2lkejxaxr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sxryk.cn/Article/details/gt2hqhwjvol.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gvsegngk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gt2nkxrtezy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gt2psmwysbj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gt2yirugrsl.html

[J09] 时区处理
来源：http://dali.yvedp.cn/Article/details/gt2wlvwqpfw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.vqdsnc.cn/Article/details/gt2mivpxqvx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gt2bkbnluxw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gt2tjgfwcvx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gt2vllhwncz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gt2dttnbbkw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yueranfly.top/Article/details/gt2cifqusqr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.quarkkingdee.top/Article/details/gt2uyucmefr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nistjcsz.html

[J10] 取今天 / 本月第一天
来源：http://dali.yanxiufei.cn/Article/details/gt2adbjirml.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.haohaochexian.top/Article/details/gt2cvjjosmi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qiozdhzo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2yhtmcays.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gt2zmalqmhu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmaciycc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dashuyun.cn/Article/details/gt2wuonizki.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj202588.top/Article/details/gt2wbuhojkg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daxiang520.top/Article/details/gt2pduzggat.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxglelmp.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gt2gkdxtfyw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2fsoqcciy.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2bmsnjzcs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gt2ylpfrsyq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gt2wtpgssgz.html

JS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2gbmnehsr.html

TS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2rmiqcfmv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gt2cekxtjhy.html

Go:   json.Marshal(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2nthghyjm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guannengcc.top/Article/details/gt2zkauwzmk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2quuheirm.html

[K02] JSON 字符串转对象
来源：http://dali.chenlongwang.top/Article/details/gt2szitmuhc.html

Py:   json.loads(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pxjdxqry.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2fybctmtd.html

JS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gt2hxgcqrjb.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gt2qdoyurpo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gt2bzjlyclf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gt2ohfzauqx.html

Ruby: JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2oomhmsfh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nutxmgxs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfoznkfr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gt2lyckufsq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gt2cmsyskus.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gt2kvfaqoeq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfhazhfh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj202588.top/Article/details/gt2zimnvptb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cdnleiting.top/Article/details/gt2waisfofv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuxming.cn/Article/details/gt2wqmyjsez.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgfzy.top/Article/details/gt2bgkdysqs.html

[K04] 读取 JSON 文件
来源：http://dali.cucudq.cn/Article/details/gt2smsmutpo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuxming.cn/Article/details/gt2qdpobvrr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2laztfsyv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gt2rsismhfp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gt2hfwkbjdu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pycfn.com/Article/details/gt2jisejkvp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gt2rqnqpbsf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zycfv.cn/Article/details/gt2xtltvsmh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gt2wfirsyjg.html

[K05] 深拷贝对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2farpzocu.html

Py:   copy.deepcopy(obj)
来源：http://dali.yvedp.cn/Article/details/gt2xqkchrek.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pycfn.com/Article/details/gt2helnqwsi.html

JS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2gldpsjfp.html

TS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gt2zbqqonyo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ivvv.top/Article/details/gt2hiimsdkf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhiwuduotai.top/Article/details/gt2fyrhczzh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gt2sluetecz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ybcxt.top/Article/details/gt2hhlrpipz.html


<!-- 参考信息 -->