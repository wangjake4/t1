代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2svdjlchi.html

[R08] 数值比较
来源：http://dali.meibo888.top/Article/details/gt2pufhzcrb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gt2krprfmwd.html

[R09] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gt2jrnwvqrr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2tvvnlzdg.html

[R10] 正则匹配
来源：http://dali.yonumen.top/Article/details/gt2nazskfor.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynikgzrt.html

[R11] case 多分支
来源：http://dali.shuidangran.top/Article/details/gt2zgeecaxw.html

case "$1" in
来源：http://dali.cucudq.cn/Article/details/gt2ndqaiafu.html

start) echo "启动" ;;
来源：http://dali.ydzc1.top/Article/details/gt2yqktcsin.html

stop)  echo "停止" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2wxhjfwwk.html

*)     echo "未知命令" ;;
来源：http://dali.cdnleiting.top/Article/details/gt2zgifhaue.html

esac
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ibvelumq.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gt2kwsmpzdi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2pibnoask.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gt2uzsadgtc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gt2gbektinb.html

[R14] C 风格 for
来源：http://dali.0kj1m.cn/Article/details/gt2gqnwfxan.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gt2oogschrt.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gt2tnrxiotm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2agbyyyme.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gt2vmjzreee.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uoudvajl.html

[R17] 数组定义与取值
来源：http://dali.yj202588.top/Article/details/gt2ftpakonf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cheryme.top/Article/details/gt2ojjuwlxe.html

[R18] 遍历数组
来源：http://dali.smart0.xyz/Article/details/gt2fvkhlukz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kbaujlrx.html

[R19] 数组长度
来源：http://dali.cucudq.cn/Article/details/gt2ufxboysm.html

echo "${#arr[@]}"
来源：http://dali.tanke756.top/Article/details/gt2zijvddsj.html

[R20] 关联数组（字典）
来源：http://dali.hammf.cn/Article/details/gt2sljclvfe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.haohaochexian.top/Article/details/gt2duqqlgix.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwebkhat.html

echo "${#s}"
来源：http://dali.jqgfzy.top/Article/details/gt2hrubyglh.html

[R22] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gt2ugebjalp.html

echo "${s:0:5}"
来源：http://dali.nanxinkj.top/Article/details/gt2evjwrbti.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2htwbjcss.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gt2qpvpsxol.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gt2xbbotdxn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.bjfxy.top/Article/details/gt2qbpmqfco.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gt2snyuvemo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shzxlz.cn/Article/details/gt2tcjwxafi.html

[R26] 命令替换
来源：http://dali.tanke756.top/Article/details/gt2aykddusg.html

now=$(date +%F); echo "$now"
来源：http://dali.yueranfly.top/Article/details/gt2kvgnppcr.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gt2ubbyjstj.html

echo $((1 + 2 * 3))
来源：http://dali.yonumen.top/Article/details/gt2rwpyribe.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gt2dsiptvca.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfkiscdd.html

[R29] 定义函数
来源：http://dali.bjfxy.top/Article/details/gt2kpovycwr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gt2boftjiru.html

[R30] 函数返回状态码
来源：http://dali.yj20258888.top/Article/details/gt2rhcbssen.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gt2bzprdtkd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqfjjxl.html

f() { local x=1; echo "$x"; }
来源：http://dali.jianghu66.top/Article/details/gt2wwhlqajl.html

[R32] 参数个数校验
来源：http://dali.c1oappe.top/Article/details/gt2dxvqpich.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gt2tddqchvy.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2usrcvbfu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gogol.net.cn/Article/details/gt2grtfpdmn.html

[R34] 退出时清理
来源：http://dali.ppjwa.cn/Article/details/gt2vskukzyt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gt2vlwzeokf.html

[R35] 后台执行并等待
来源：http://dali.jyoumei.cn/Article/details/gt2nlbhbpln.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cqqwz.cn/Article/details/gt2njexljfq.html

[R36] 并发执行多个任务
来源：http://dali.cqqwz.cn/Article/details/gt2ygyslyqt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gt2tsovfpps.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gt2vczcmaso.html

files=$(ls -1)
来源：http://dali.nanxuanxn.top/Article/details/gt2cacrglum.html

[R38] 管道串联
来源：http://dali.zycfv.cn/Article/details/gt2yunjdrmt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gt2bpewkfuf.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigufen.top/Article/details/gt2jkdllefb.html

cmd > out.log 2>&1
来源：http://dali.xuanzx.com/Article/details/gt2gpmbxeff.html

[R40] 追加写日志
来源：http://dali.yueranfly.top/Article/details/gt2atrtwnro.html

echo "log" >> out.log
来源：http://dali.yj202588.top/Article/details/gt2kehcaktp.html

[R41] 丢弃输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2dhgfrtoh.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gt2xvkpxydd.html

[R42] 输入重定向
来源：http://dali.haohaochexian.top/Article/details/gt2ytyhfzlp.html

wc -l < a.txt
来源：http://dali.daria6918.cn/Article/details/gt2veistnto.html

[R43] 按名字查找文件
来源：http://dali.fzhhl.top/Article/details/gt2xcjpefiw.html

find . -name "*.log" -type f
来源：http://dali.c1oappe.top/Article/details/gt2biszocge.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gt2syrflmcc.html

find . -mtime -7 -type f
来源：http://dali.xylfe.cn/Article/details/gt2cnmibewt.html

[R45] 批量删除
来源：http://dali.tianlin.xyz/Article/details/gt2xztjsplj.html

find . -name "*.tmp" -delete
来源：http://dali.jqgufenzy.top/Article/details/gt2wakfotlk.html

[R46] 递归替换文件内容
来源：http://dali.zhoulong.xyz/Article/details/gt2wzlbyogx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhoulong.xyz/Article/details/gt2prydzihq.html

[R47] sed 单行替换
来源：http://dali.cucudq.cn/Article/details/gt2yfjnacux.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.smart0.xyz/Article/details/gt2gaxnycoz.html

[R48] awk 取指定列
来源：http://dali.meibo888.top/Article/details/gt2qxtcynlx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2kaawepma.html

[R49] awk 带条件
来源：http://dali.yj202588.top/Article/details/gt2uddfiphj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhoulong.xyz/Article/details/gt2jftcqyha.html

[R50] awk 求和
来源：http://dali.cdnleiting.top/Article/details/gt2qyywhykh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2ymyrsyaa.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gt2xilwunqt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gzhubu.top/Article/details/gt2kjehrkcb.html

[R52] 统计行数
来源：http://dali.zhoulong.xyz/Article/details/gt2dgumvqja.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gt2iwkhyoci.html

[R53] 查看文件头与实时尾
来源：http://dali.ppjwa.cn/Article/details/gt2rebpdvho.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gt2hwfqtrvt.html

[R54] 比较两个文件
来源：http://dali.yongpay.top/Article/details/gt2eabqeksx.html

diff a.txt b.txt
来源：http://dali.hfpthk.cn/Article/details/gt2mzyfmnok.html

[R55] 压缩与解压
来源：http://dali.nwbrower.top/Article/details/gt2mjcpunvk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yueranfly.top/Article/details/gt2mvyfaxaz.html

[R56] 远程拷贝
来源：http://dali.nanxuanxn.top/Article/details/gt2sfjfdljf.html

scp file user@host:/path/
来源：http://dali.guannengcc.top/Article/details/gt2akwnqimh.html

[R57] 远程执行命令
来源：http://dali.c1oappe.top/Article/details/gt2fsgxgpgk.html

ssh user@host 'uptime'
来源：http://dali.chenzaomai.com/Article/details/gt2mfqzisym.html

[R58] 下载文件
来源：http://dali.hammf.cn/Article/details/gt2zjqkikjn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.andypj.xyz/Article/details/gt2jroqovok.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gt2njwryhaf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gt2ptotiygy.html

[R60] 只看 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gt2dgpbbywg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gt2xkuapdyz.html

[R61] 磁盘占用
来源：http://dali.dashuyun.cn/Article/details/gt2schlhnkm.html

df -h;  du -sh *
来源：http://dali.ybcxt.top/Article/details/gt2eebwcikn.html

[R62] 找最占空间的文件
来源：http://dali.wangdashe.top/Article/details/gt2ixmcsmcy.html

du -ah . | sort -rh | head -10
来源：http://dali.yj202588.top/Article/details/gt2gbuvnpet.html

[R63] 内存与进程
来源：http://dali.jianghu66.top/Article/details/gt2ybzrnhrv.html

free -h;  ps aux | grep nginx
来源：http://dali.hfpthk.cn/Article/details/gt2wkxgkqsy.html

[R64] 结束进程
来源：http://dali.jyoumei.cn/Article/details/gt2bytddwjj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xylfe.cn/Article/details/gt2yaxchqmt.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gt2johbmpwk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tian-w.cn/Article/details/gt2twobbjsr.html

[R66] 定时任务
来源：http://dali.yuxming.cn/Article/details/gt2luqampcc.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gt2mtnmsbco.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kpurulby.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gt2qmzwawyt.html

[R68] 计算文件校验值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ajbdxhxx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kfvjkbgk.html

[R69] 生成随机密码
来源：http://dali.kuanghao11.cn/Article/details/gt2hfbkrwnh.html

head -c 16 /dev/urandom | base64
来源：http://dali.smart0.xyz/Article/details/gt2dzustxvs.html

[R70] 时间戳与互转
来源：http://dali.shzxlz.cn/Article/details/gt2mkffjcdm.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gt2jrmkrefv.html

[R71] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gt2pksimnft.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ydzc1.top/Article/details/gt2eeuyyqqy.html

[R72] 等待端口就绪
来源：http://dali.ppjwa.cn/Article/details/gt2pnuzzamr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gt2cdqijqol.html

[R73] 分割大日志
来源：http://dali.ppjwa.cn/Article/details/gt2ubnrstvd.html

split -l 1000 big.log part_
来源：http://dali.ehwqpu.com/Article/details/gt2ghksfocn.html

[R74] 批量重命名
来源：http://dali.hfpthk.cn/Article/details/gt2hbaefoub.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gixpfofg.html

[R75] 导出环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtrimqdr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gt2ljcoogmd.html

[R76] 使用临时文件
来源：http://dali.daria6918.cn/Article/details/gt2atjsixjx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gt2yxumtdbc.html

[R77] 读取用户输入
来源：http://dali.hongshengwenyu.top/Article/details/gt2wlxkipdp.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjtdriqj.html

[R78] 交互式菜单
来源：http://dali.ivvv.top/Article/details/gt2llfhywkz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xylfe.cn/Article/details/gt2pxjoclsc.html

[R79] 解析命令行选项
来源：http://dali.kuanghao11.cn/Article/details/gt2qjlquwih.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xinyue.icu/Article/details/gt2avhbwmfg.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ulorivjx.html

time ./run.sh
来源：http://dali.birdmap.top/Article/details/gt2sffofweo.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2iwuhstqn.html

S. C / C++ 专题
来源：http://dali.mhx1999.top/Article/details/gt2ayvknaqh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2kodeopve.html

[S01] C：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2rdnvxkog.html

#include <stdio.h>
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqphfumj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.snrcjt.cn/Article/details/gt2nlfsiacc.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gt2svjaimvs.html

int a = 10; printf("%d\n", a);
来源：http://dali.birdmap.top/Article/details/gt2pqioawph.html

[S03] C：读入整数
来源：http://dali.zycfv.cn/Article/details/gt2liqobnru.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gt2crrzbcgt.html

[S04] C：字符串复制
来源：http://dali.yangfankeji.com/Article/details/gt2ueszftbo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tanke756.top/Article/details/gt2xmrswmlt.html

[S05] C：字符串长度
来源：http://dali.haohaochexian.top/Article/details/gt2bcdydghb.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gt2wkzqdtmt.html

[S06] C：字符串比较
来源：http://dali.hywenlv.cn/Article/details/gt2rfxkxajk.html

strcmp(a, b) == 0
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hbrcqhud.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cgafbsmn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.svipenyu.cn/Article/details/gt2nofldgyo.html

[S08] C：动态内存分配与释放
来源：http://dali.pycfn.com/Article/details/gt2hvfzrxdl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvwywcpk.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gt2qsagizzj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dashuyun.cn/Article/details/gt2gsvpkhiw.html

[S10] C：指针与解引用
来源：http://dali.nanxuanxn.top/Article/details/gt2gdywpuol.html

int *p = &a;  *p = 5;
来源：http://dali.iojbl.cn/Article/details/gt2bqhdixgq.html

[S11] C：逐行读文件
来源：http://dali.316326.xyz/Article/details/gt2txqrlwen.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenlongwang.top/Article/details/gt2hgsmlieu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2zvqxrpio.html

fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rponaohh.html

[S12] C：写文件
来源：http://dali.zdqjudy.top/Article/details/gt2lcsovonv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fufihcei.html

[S13] C：宏定义
来源：http://dali.ybcxt.top/Article/details/gt2zmoxsnah.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhongyouzk.top/Article/details/gt2fosjkrsl.html

[S14] C：枚举
来源：http://dali.hfpthk.cn/Article/details/gt2wktcrxoc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenzaomai.com/Article/details/gt2uquyrpkh.html

[S15] C：类型转换
来源：http://dali.guannengcc.top/Article/details/gt2dtgajobw.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gt2undxpwwq.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fadxyugm.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gt2huhuxarc.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gt2forwrrbc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wybtxvzg.html

[S18] C：命令行参数
来源：http://dali.snrcjt.cn/Article/details/gt2wqcayabu.html

int main(int argc, char **argv)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hspirltn.html

[S19] C：快速排序
来源：http://dali.ivvv.top/Article/details/gt2kzpwusye.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gt2duoqfjpw.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gt2rwtslmqb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rsolemfq.html

[S21] C：字符类别判断
来源：http://dali.yj202588.top/Article/details/gt2zfktlskp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daria6918.cn/Article/details/gt2dhkoyqpm.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gt2gtufuvke.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gt2ravlklfb.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gt2aifkzdgn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nwbrower.top/Article/details/gt2cvoklbuk.html

[S24] C：获取本地时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2wcurokex.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gt2tryqitcb.html

[S25] C：内存拷贝
来源：http://dali.zhixingplan.top/Article/details/gt2irxensju.html

memcpy(dst, src, n);
来源：http://dali.hysaishi.cn/Article/details/gt2bghnkkod.html

[S26] C：内存清零
来源：http://dali.daria6918.cn/Article/details/gt2vzaihibv.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gt2beforkav.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gt2zrzjvtoy.html

const double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gt2lmxswymd.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gt2qvsaqkcj.html

static int counter = 0;
来源：http://dali.yuanzhike.top/Article/details/gt2uihnawzy.html

[S29] C：变参函数
来源：http://dali.jinqigfzy.top/Article/details/gt2ywnsvxsp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhengqikj.top/Article/details/gt2hcyplpei.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gt2pasqbohc.html

#ifndef X_H
来源：http://dali.iojbl.cn/Article/details/gt2cguxtpbh.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gt2nwuxjbrj.html

#endif
来源：http://dali.hysaishi.cn/Article/details/gt2ghdkpoeq.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gt2kgpkefyx.html

#include <iostream>
来源：http://dali.dianchejie.cn/Article/details/gt2qwxwyhgv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.316326.xyz/Article/details/gt2pigemvcj.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gt2yzufxpvm.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgufenzy.top/Article/details/gt2osisnqng.html

[S33] C++：vector 增删
来源：http://dali.yuanzhike.top/Article/details/gt2ogkreinn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fzhhl.top/Article/details/gt2hqfvlrsl.html

[S34] C++：遍历 vector
来源：http://dali.ppjwa.cn/Article/details/gt2dnsfgajg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.316326.xyz/Article/details/gt2gxviawvo.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gt2uoduwaxc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gt2eoqvnizc.html

[S36] C++：unordered_map
来源：http://dali.hammf.cn/Article/details/gt2yusstnhv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gt2fxafzask.html

[S37] C++：set
来源：http://dali.ivvv.top/Article/details/gt2wrtkwsea.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hywenlv.cn/Article/details/gt2qvrahbys.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gt2ycyxgatg.html

std::sort(v.begin(), v.end());
来源：http://dali.yuanzhike.top/Article/details/gt2eukekrkd.html

[S39] C++：自定义比较器排序
来源：http://dali.cheryme.top/Article/details/gt2vuyxjkge.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.c1oappe.top/Article/details/gt2ncdwfprx.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gt2kjgbjrmk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guowangkeji.top/Article/details/gt2znilgjdi.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gt2lxdxreim.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daxiang520.top/Article/details/gt2zfdpnqrh.html

[S42] C++：继承与虚函数
来源：http://dali.hysaishi.cn/Article/details/gt2vpvrnxiz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhongyouzk.top/Article/details/gt2ygavsxfq.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gt2pjntwpjc.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258.top/Article/details/gt2vuphebpm.html

[S44] C++：引用传参
来源：http://dali.zycfv.cn/Article/details/gt2phteglty.html

void inc(int &x) { ++x; }
来源：http://dali.xuanzx.com/Article/details/gt2ngwgyfcv.html

[S45] C++：lambda
来源：http://dali.jyoumei.cn/Article/details/gt2eallcamq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gogol.net.cn/Article/details/gt2pfotuszf.html

[S46] C++：函数模板
来源：http://dali.sufxvd.cn/Article/details/gt2hrmnpqnr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ppjwa.cn/Article/details/gt2zntcgrvk.html

[S47] C++：结构化绑定遍历
来源：http://dali.hammf.cn/Article/details/gt2xxtiowpd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yonumen.top/Article/details/gt2raeykulj.html

[S48] C++：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gt2sxmtbgxt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cheryme.top/Article/details/gt2biqyhlwf.html

while (std::getline(in, line)) { }
来源：http://dali.yuxming.cn/Article/details/gt2vwraaxes.html

[S49] C++：写文件
来源：http://dali.ybcxt.top/Article/details/gt2djlpdcxa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangshuangyany.cn/Article/details/gt2zcypfvcl.html

[S50] C++：格式化数字
来源：http://dali.iojbl.cn/Article/details/gt2yobkacdg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hammf.cn/Article/details/gt2cvwjidza.html

[S51] C++：显式类型转换
来源：http://dali.jinqigufen.top/Article/details/gt2hfgizimj.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gt2jqpuxgdq.html

[S52] C++：const 与 noexcept
来源：http://dali.haohaochexian.top/Article/details/gt2xkywvczb.html

int size() const noexcept { return n_; }
来源：http://dali.sysykeji.top/Article/details/gt2ikpwlsdg.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gt2ifqbtevl.html

std::vector<int> w = std::move(v);
来源：http://dali.yuanzhike.top/Article/details/gt2bcrkglhx.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gt2jsefmzez.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hfpthk.cn/Article/details/gt2uulilefo.html

[S55] C++：结构化绑定
来源：http://dali.gaohongyu789.top/Article/details/gt2wswpmxob.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuanzhike.top/Article/details/gt2cbhdpbvc.html

[S56] C++：optional
来源：http://dali.bjfxy.top/Article/details/gt2bkuebdps.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jiagoushi.top/Article/details/gt2bmxpeyqq.html

[S57] C++：编译期常量
来源：http://dali.nwbrower.top/Article/details/gt2fdmishtk.html

constexpr int N = 10;
来源：http://dali.cdnleiting.top/Article/details/gt2tjjtwesl.html

[S58] C++：命名空间
来源：http://dali.sufxvd.cn/Article/details/gt2dqnmrmzk.html

namespace ns { int f() { return 1; } }
来源：http://dali.ydzc1.top/Article/details/gt2wbaugbhd.html

[S59] C++：静态断言
来源：http://dali.cashguo.top/Article/details/gt2ehjvhqcg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guowangkeji.top/Article/details/gt2tzolfuyq.html

[S60] C++：遍历并删除元素
来源：http://dali.havefunace.top/Article/details/gt2eemtprui.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuanzx.com/Article/details/gt2ceozvgbr.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2efykylcl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2srbhekxx.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2smbbdcpx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rzldalee.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bmohqyba.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gt2cfgdvgfb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yanxiufei.cn/Article/details/gt2sxikfyzl.html

[T03] Kotlin：字符串模板
来源：http://dali.kuanghao11.cn/Article/details/gt2ppknuuhw.html

"值: $b"
来源：http://dali.hnqzz.top/Article/details/gt2ghltkieq.html

[T04] Kotlin：空安全
来源：http://dali.mhx1999.top/Article/details/gt2mldmykyo.html

val n: String? = null;  n?.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnqiiutg.html

[T05] Kotlin：when 表达式
来源：http://dali.sysykeji.top/Article/details/gt2biwlvecf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zycfv.cn/Article/details/gt2fsebamne.html

[T06] Kotlin：集合映射
来源：http://dali.hfpthk.cn/Article/details/gt2dburmnlo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gt2pqypzwnf.html

[T07] Kotlin：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gt2rmjxricq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yangfankeji.com/Article/details/gt2dnqlxcih.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gt2pzzustii.html

data class User(val name: String, val age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gt2gtwjhlem.html


<!-- 参考信息 -->