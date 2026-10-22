代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gt2mlzjjkjo.html

[R08] 数值比较
来源：http://dali.0kj1m.cn/Article/details/gt2uguduunp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gt2kznrqekd.html

[R09] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gt2twtpzimb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuxming.cn/Article/details/gt2djbfvzms.html

[R10] 正则匹配
来源：http://dali.xylfe.cn/Article/details/gt2dgddrxoq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guowangkeji.top/Article/details/gt2rpyplumm.html

[R11] case 多分支
来源：http://dali.xylfe.cn/Article/details/gt2bgiohpwu.html

case "$1" in
来源：http://dali.havefunace.top/Article/details/gt2ayoyzmik.html

start) echo "启动" ;;
来源：http://dali.jiagoushi.top/Article/details/gt2uzixfcjv.html

stop)  echo "停止" ;;
来源：http://dali.redwolf501.top/Article/details/gt2gcahsdhc.html

*)     echo "未知命令" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bdwbmvdb.html

esac
来源：http://dali.meibo888.top/Article/details/gt2owjddxfu.html

[R12] for 遍历文件
来源：http://dali.yanxiufei.cn/Article/details/gt2uhxwszvl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigfzy.top/Article/details/gt2esyhutoq.html

[R13] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gt2bantekbf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gt2hrbxvkqw.html

[R14] C 风格 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bszemhgj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gt2vnecloxs.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wtowocyw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gt2jgsnvevg.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gt2lutlxtnd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohxamoxg.html

[R17] 数组定义与取值
来源：http://dali.fengsongda.top/Article/details/gt2bvjqzscf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gotoacloud.top/Article/details/gt2essdhqhc.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gt2truiocna.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gt2vccbogmt.html

[R19] 数组长度
来源：http://dali.xylfe.cn/Article/details/gt2qbiroqxz.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jvbkcprl.html

[R20] 关联数组（字典）
来源：http://dali.shzxlz.cn/Article/details/gt2impaqmwl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yonumen.top/Article/details/gt2abfeouhy.html

[R21] 字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gt2amcsdonf.html

echo "${#s}"
来源：http://dali.jyoumei.cn/Article/details/gt2ozpngsxl.html

[R22] 截取子串
来源：http://dali.pycfn.com/Article/details/gt2skgtbxpd.html

echo "${s:0:5}"
来源：http://dali.cdnleiting.top/Article/details/gt2utmkydbo.html

[R23] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gt2ocbosbtu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hysaishi.cn/Article/details/gt2cosuoyos.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gt2ujypzeic.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yangfankeji.com/Article/details/gt2gdsaspma.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gt2esqsrauq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cashguo.top/Article/details/gt2zckzqinh.html

[R26] 命令替换
来源：http://dali.snrcjt.cn/Article/details/gt2gchyqnel.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dlqyvyba.html

[R27] 算术展开
来源：http://dali.ehwqpu.com/Article/details/gt2cbvrniiz.html

echo $((1 + 2 * 3))
来源：http://dali.316326.xyz/Article/details/gt2bhbbcnqa.html

[R28] 浮点运算
来源：http://dali.mhx1999.top/Article/details/gt2bbnainme.html

echo "scale=2; 10/3" | bc
来源：http://dali.cheryme.top/Article/details/gt2ietvxvxh.html

[R29] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gt2smvpyuhk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yangfankeji.com/Article/details/gt2toztxibo.html

[R30] 函数返回状态码
来源：http://dali.wangshuangyany.cn/Article/details/gt2vhtyvbuq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gt2znvgkhcn.html

[R31] 局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2chzswwbw.html

f() { local x=1; echo "$x"; }
来源：http://dali.xinyue.icu/Article/details/gt2swcxaejf.html

[R32] 参数个数校验
来源：http://dali.hnxiangtu.top/Article/details/gt2tkcsnezb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gt2cxustjof.html

[R33] 捕获错误并提示行号
来源：http://dali.aibaodan.cn/Article/details/gt2tesyklok.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guannengcc.top/Article/details/gt2qpqtdblf.html

[R34] 退出时清理
来源：http://dali.xuetiantiany.cn/Article/details/gt2iwvaxjds.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gt2hgkcwloq.html

[R35] 后台执行并等待
来源：http://dali.aibaodan.cn/Article/details/gt2xmepowdb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.316326.xyz/Article/details/gt2bdrixfbo.html

[R36] 并发执行多个任务
来源：http://dali.guannengcc.top/Article/details/gt2hhraxckn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hfpthk.cn/Article/details/gt2kbposeyv.html

[R37] 把输出赋给变量
来源：http://dali.andypj.xyz/Article/details/gt2jzsnrckf.html

files=$(ls -1)
来源：http://dali.fengsongda.top/Article/details/gt2wtlbaymc.html

[R38] 管道串联
来源：http://dali.fzhhl.top/Article/details/gt2tfiaxbhv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gt2sfobetlf.html

[R39] 重定向标准输出与错误
来源：http://dali.yj202588.top/Article/details/gt2cbqzctsz.html

cmd > out.log 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2devfyjpg.html

[R40] 追加写日志
来源：http://dali.aibaodan.cn/Article/details/gt2zwofesoq.html

echo "log" >> out.log
来源：http://dali.bjfxy.top/Article/details/gt2gdcqatky.html

[R41] 丢弃输出
来源：http://dali.yj20258888.top/Article/details/gt2rfcqilfb.html

cmd >/dev/null 2>&1
来源：http://dali.hywenlv.cn/Article/details/gt2vxhzkhxb.html

[R42] 输入重定向
来源：http://dali.zycfv.cn/Article/details/gt2wntohlno.html

wc -l < a.txt
来源：http://dali.fengsongda.top/Article/details/gt2yspwnust.html

[R43] 按名字查找文件
来源：http://dali.bjfxy.top/Article/details/gt2xwuivhej.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gt2rrqbcsyk.html

[R44] 按修改时间查找
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmhakbpb.html

find . -mtime -7 -type f
来源：http://dali.guannengcc.top/Article/details/gt2uosyjivs.html

[R45] 批量删除
来源：http://dali.chenzaomai.com/Article/details/gt2ewzbewjz.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gt2adamqapg.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gt2osvdofcl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangdashe.top/Article/details/gt2dlrcsmcj.html

[R47] sed 单行替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozotciqc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oegchxoo.html

[R48] awk 取指定列
来源：http://dali.gotoacloud.top/Article/details/gt2fdmctmdj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2ipxzdcvy.html

[R49] awk 带条件
来源：http://dali.haohaochexian.top/Article/details/gt2vgrlhoxx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.feifeiyinyue.top/Article/details/gt2mxkowwke.html

[R50] awk 求和
来源：http://dali.sufxvd.cn/Article/details/gt2dxxruwir.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gt2mgypflil.html

[R51] 排序去重取前几
来源：http://dali.hysaishi.cn/Article/details/gt2knrdzdcy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gotoacloud.top/Article/details/gt2mwclhica.html

[R52] 统计行数
来源：http://dali.yonumen.top/Article/details/gt2dfxdgmdi.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2tajbzghu.html

[R53] 查看文件头与实时尾
来源：http://dali.guannengcc.top/Article/details/gt2clzldjkn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gt2fcghatja.html

[R54] 比较两个文件
来源：http://dali.jqgufenzy.top/Article/details/gt2wqpdlohf.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gt2wltaglic.html

[R55] 压缩与解压
来源：http://dali.guowangkeji.top/Article/details/gt2seatmmfh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rfqlzprk.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ueqpabse.html

scp file user@host:/path/
来源：http://dali.vqdsnc.cn/Article/details/gt2vbzloxlt.html

[R57] 远程执行命令
来源：http://dali.fengsongda.top/Article/details/gt2zmfhjkes.html

ssh user@host 'uptime'
来源：http://dali.9152youxi.cn/Article/details/gt2voauuoxj.html

[R58] 下载文件
来源：http://dali.xinyue.icu/Article/details/gt2ratpxzki.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gt2urxknjkq.html

[R59] 发 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ttpwwuuj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gt2uqkkfxvf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gt2pbzgmrgf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hywenlv.cn/Article/details/gt2bektqkpt.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gt2pcaobslm.html

df -h;  du -sh *
来源：http://dali.jlsjyb.cn/Article/details/gt2dyapcnti.html

[R62] 找最占空间的文件
来源：http://dali.yj202588.top/Article/details/gt2afkqchtd.html

du -ah . | sort -rh | head -10
来源：http://dali.yueranfly.top/Article/details/gt2lnwebhwz.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gt2fkunkhkk.html

free -h;  ps aux | grep nginx
来源：http://dali.daria6918.cn/Article/details/gt2gewblhhy.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gt2fsrztagu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xinyue.icu/Article/details/gt2dnmqcfmr.html

[R65] 查看端口占用
来源：http://dali.aizwys.cn/Article/details/gt2vaknbovx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.snrcjt.cn/Article/details/gt2nmolrenf.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gt2vwlqolmd.html

crontab -e;  crontab -l
来源：http://dali.zhongyouzk.top/Article/details/gt2eyjaskpz.html

[R67] 生成随机十六进制串
来源：http://dali.nwbrower.top/Article/details/gt2mxpzrhoj.html

openssl rand -hex 16
来源：http://dali.yvedp.cn/Article/details/gt2gqvdbnvt.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gt2wdqypequ.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2howizwkb.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gt2ckxdcqjh.html

head -c 16 /dev/urandom | base64
来源：http://dali.ppjwa.cn/Article/details/gt2fzqtcqnn.html

[R70] 时间戳与互转
来源：http://dali.jyoumei.cn/Article/details/gt2dbnlgxab.html

date +%s;  date -d @1700000000
来源：http://dali.jlsjyb.cn/Article/details/gt2yreipent.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifmhwenh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daxiang520.top/Article/details/gt2ucmgvltq.html

[R72] 等待端口就绪
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zpgaafya.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gt2jjatpofn.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gt2robhymyd.html

split -l 1000 big.log part_
来源：http://dali.cdnleiting.top/Article/details/gt2fuuiwkkp.html

[R74] 批量重命名
来源：http://dali.wangshuangyany.cn/Article/details/gt2baaxlhot.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xinyue.icu/Article/details/gt2tphjdmbc.html

[R75] 导出环境变量
来源：http://dali.xinyue.icu/Article/details/gt2watofufa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqrkqrki.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gt2pqzikbov.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gt2eqcrsjfm.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gt2urrywirs.html

read -rp "请输入: " ans
来源：http://dali.dashuyun.cn/Article/details/gt2ixdugebd.html

[R78] 交互式菜单
来源：http://dali.chenzaomai.com/Article/details/gt2ywsaavlk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gt2pktzqrhg.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gt2xuugmkwg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxuanxn.top/Article/details/gt2wbcyjhlb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jltmfjqv.html

time ./run.sh
来源：http://dali.yueranfly.top/Article/details/gt2tgvhnvfo.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2lmzgeund.html

S. C / C++ 专题
来源：http://dali.meibo888.top/Article/details/gt2ynvbpeaj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djaasvkv.html

[S01] C：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2xpcuccaz.html

#include <stdio.h>
来源：http://dali.andypj.xyz/Article/details/gt2wtmvraqj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pycfn.com/Article/details/gt2wxjaulco.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gt2gmdbouji.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gt2wbldmezf.html

[S03] C：读入整数
来源：http://dali.cucudq.cn/Article/details/gt2tzkitzfd.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gt2bbbbszvr.html

[S04] C：字符串复制
来源：http://dali.snrcjt.cn/Article/details/gt2bmnlcbec.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shuidangran.top/Article/details/gt2bolsgfzv.html

[S05] C：字符串长度
来源：http://dali.xylfe.cn/Article/details/gt2tfzgyrjc.html

strlen(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2jcoejeox.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gt2mzervgsj.html

strcmp(a, b) == 0
来源：http://dali.cashguo.top/Article/details/gt2ztxyremo.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gt2ioeihvdc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cdnleiting.top/Article/details/gt2qdkstder.html

[S08] C：动态内存分配与释放
来源：http://dali.sxryk.cn/Article/details/gt2ekarilhp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnxiangtu.top/Article/details/gt2hrwsqdte.html

[S09] C：结构体定义与初始化
来源：http://dali.ydzc1.top/Article/details/gt2ednasmqp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nwbrower.top/Article/details/gt2lmswshis.html

[S10] C：指针与解引用
来源：http://dali.wangshuangyany.cn/Article/details/gt2artolbzw.html

int *p = &a;  *p = 5;
来源：http://dali.9152youxi.cn/Article/details/gt2ibfdzcwa.html

[S11] C：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2ayfjekpr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gt2ydfjbceq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigufen.top/Article/details/gt2yuxqnsab.html

fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gt2akijsnkz.html

[S12] C：写文件
来源：http://dali.sweek.top/Article/details/gt2oeblyxky.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gt2wzvsaekx.html

[S13] C：宏定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2esbrbrcu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gt2sawmfnkk.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gt2pcntrohw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daria6918.cn/Article/details/gt2ckonzzsj.html

[S15] C：类型转换
来源：http://dali.ivvv.top/Article/details/gt2cxekmqtc.html

(double) a / b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mplhzxen.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gt2coefgqwm.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2lqxhrtfr.html

[S17] C：安全拼接字符串
来源：http://dali.yonumen.top/Article/details/gt2hkjifggo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gt2uebjndda.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gt2qtpacucm.html

int main(int argc, char **argv)
来源：http://dali.yuanzhike.top/Article/details/gt2szquexgw.html

[S19] C：快速排序
来源：http://dali.hfpthk.cn/Article/details/gt2czcnfovk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2rhrnjqrv.html

[S20] C：二分查找
来源：http://dali.dianchejie.cn/Article/details/gt2vprdtdco.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gt2acbzjumh.html

[S21] C：字符类别判断
来源：http://dali.xylfe.cn/Article/details/gt2evufunqi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wetodtbp.html

[S22] C：字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gt2egaigwlg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daxiang520.top/Article/details/gt2echpsgys.html

[S23] C：随机数
来源：http://dali.tianlin.xyz/Article/details/gt2yuniqycm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.haohaochexian.top/Article/details/gt2fawqjnyh.html

[S24] C：获取本地时间
来源：http://dali.9152youxi.cn/Article/details/gt2tyupvsbb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gt2lxyjlyma.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gt2elztqjqv.html

memcpy(dst, src, n);
来源：http://dali.zhengqikj.top/Article/details/gt2lzechpng.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gt2qkvtvybq.html

memset(a, 0, sizeof a);
来源：http://dali.zdqjudy.top/Article/details/gt2oiigxjys.html

[S27] C：定义常量
来源：http://dali.ivvv.top/Article/details/gt2nyaxulsg.html

const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2itzqknqk.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebbppsnm.html

static int counter = 0;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvwzsloa.html

[S29] C：变参函数
来源：http://dali.shuidangran.top/Article/details/gt2hpspexmn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gt2xnvjxunm.html

[S30] C：头文件保护
来源：http://dali.zhengqikj.top/Article/details/gt2unefzbtv.html

#ifndef X_H
来源：http://dali.jinqigufen.top/Article/details/gt2yxlaxgui.html

#define X_H
来源：http://dali.xziqi.cn/Article/details/gt2owakygbh.html

#endif
来源：http://dali.wangdashe.top/Article/details/gt2hhghdbie.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2qyexkcqg.html

#include <iostream>
来源：http://dali.fzhhl.top/Article/details/gt2inqcgvlg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gt2qqnqyuvv.html

[S32] C++：字符串
来源：http://dali.316326.xyz/Article/details/gt2fpqplmhg.html

std::string s = "hi";  s += "!";
来源：http://dali.sweek.top/Article/details/gt2kiuwwfnu.html

[S33] C++：vector 增删
来源：http://dali.fzhhl.top/Article/details/gt2dsmvwdbl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.316326.xyz/Article/details/gt2tjaxdknm.html

[S34] C++：遍历 vector
来源：http://dali.hfpthk.cn/Article/details/gt2ajggnlbc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2sncoikpf.html

[S35] C++：map
来源：http://dali.yj202588.top/Article/details/gt2ofhlqyga.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2othqmdxt.html

[S36] C++：unordered_map
来源：http://dali.guowangkeji.top/Article/details/gt2xwycrtwt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2rtrzzirv.html

[S37] C++：set
来源：http://dali.xylfe.cn/Article/details/gt2hxhtrtqe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tianlin.xyz/Article/details/gt2qyjzrnun.html

[S38] C++：排序
来源：http://dali.pycfn.com/Article/details/gt2eektfabw.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gt2alxfopba.html

[S39] C++：自定义比较器排序
来源：http://dali.yongpay.top/Article/details/gt2kdaaudtw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gt2hlboyigy.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gt2dqyxuwww.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gt2jilqzxas.html

[S41] C++：类与构造函数
来源：http://dali.yj20258888.top/Article/details/gt2omsdhvll.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hywenlv.cn/Article/details/gt2xkfqxbht.html

[S42] C++：继承与虚函数
来源：http://dali.guowangkeji.top/Article/details/gt2zevfqnyj.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pueelhzy.html

[S43] C++：智能指针
来源：http://dali.snrcjt.cn/Article/details/gt2vaqcgpha.html

auto p = std::make_unique<int>(5);
来源：http://dali.gogol.net.cn/Article/details/gt2fahsmeos.html

[S44] C++：引用传参
来源：http://dali.zycfv.cn/Article/details/gt2xoepkhrv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubffrolr.html

[S45] C++：lambda
来源：http://dali.andypj.xyz/Article/details/gt2zbazofww.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gt2suclwbly.html

[S46] C++：函数模板
来源：http://dali.yongpay.top/Article/details/gt2grpbhogw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ypdifwcc.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gt2yvsiyonm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gt2kdbfihdz.html

[S48] C++：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2rjhawawl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cqqwz.cn/Article/details/gt2gqawgktv.html

while (std::getline(in, line)) { }
来源：http://dali.zhixingplan.top/Article/details/gt2rnrojeol.html

[S49] C++：写文件
来源：http://dali.cqqwz.cn/Article/details/gt2nkwkcexy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.havefunace.top/Article/details/gt2efqoffky.html

[S50] C++：格式化数字
来源：http://dali.chenlongwang.top/Article/details/gt2ddknqvam.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sweek.top/Article/details/gt2jttuqkgc.html

[S51] C++：显式类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfzgqqfw.html

static_cast<double>(a) / b
来源：http://dali.birdmap.top/Article/details/gt2ibfxzvfz.html

[S52] C++：const 与 noexcept
来源：http://dali.cdnleiting.top/Article/details/gt2hmgcgiii.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gt2ijovatmm.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgbyxdzk.html

std::vector<int> w = std::move(v);
来源：http://dali.aibaodan.cn/Article/details/gt2yxzzdmuj.html

[S54] C++：异常处理
来源：http://dali.gogol.net.cn/Article/details/gt2wvmxmblu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangdashe.top/Article/details/gt2hhlbyxiu.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gt2zjpkdpmj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2ndlwwxrb.html

[S56] C++：optional
来源：http://dali.ivvv.top/Article/details/gt2vneyqxag.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhengqikj.top/Article/details/gt2uoeemqhm.html

[S57] C++：编译期常量
来源：http://dali.wangdashe.top/Article/details/gt2ujpfrzac.html

constexpr int N = 10;
来源：http://dali.hnxiangtu.top/Article/details/gt2rkubayky.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mnbggkmc.html

namespace ns { int f() { return 1; } }
来源：http://dali.jiagoushi.top/Article/details/gt2bfjdvxrh.html

[S59] C++：静态断言
来源：http://dali.xuetiantiany.cn/Article/details/gt2rrlkwuux.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqnvfwuo.html

[S60] C++：遍历并删除元素
来源：http://dali.hammf.cn/Article/details/gt2unnerlhf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhengqikj.top/Article/details/gt2vpwcthqy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2mapdqdtz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gt2hrxegkar.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2tfsmmylj.html

[T01] Kotlin：Hello World
来源：http://dali.hammf.cn/Article/details/gt2ifzhhdue.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gt2ihaftdvn.html

[T02] Kotlin：变量
来源：http://dali.chenzaomai.com/Article/details/gt2khapvmpm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xinyue.icu/Article/details/gt2hnngrmwx.html

[T03] Kotlin：字符串模板
来源：http://dali.sxryk.cn/Article/details/gt2xvixjnfa.html

"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gt2ndmkbxks.html

[T04] Kotlin：空安全
来源：http://dali.chenlongwang.top/Article/details/gt2ffjwgpeb.html

val n: String? = null;  n?.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2tbajgufy.html

[T05] Kotlin：when 表达式
来源：http://dali.yuxming.cn/Article/details/gt2fclvnktt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigfzy.top/Article/details/gt2pyjumeag.html

[T06] Kotlin：集合映射
来源：http://dali.yonumen.top/Article/details/gt2gaqghkch.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2bvqjssxp.html

[T07] Kotlin：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gt2ovlfxgjf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aibaodan.cn/Article/details/gt2zsqqjauk.html

[T08] Kotlin：数据类
来源：http://dali.gotoacloud.top/Article/details/gt2kvhwizsn.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oucicudg.html


<!-- 参考信息 -->