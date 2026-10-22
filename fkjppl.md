代发 wailian999

name="${1:-default}"
来源：http://dali.chenzaomai.com/Article/details/gt2yssojycp.html

[R06] 判断命令是否存在
来源：http://dali.jlsjyb.cn/Article/details/gt2txangqfa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gt2qidbvusn.html

[R07] if 判断文件
来源：http://dali.yvedp.cn/Article/details/gt2mlpvkpeb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daxiang520.top/Article/details/gt2ngzavvlh.html

[R08] 数值比较
来源：http://dali.havefunace.top/Article/details/gt2czvhwhfy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2jlrecssp.html

[R09] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gt2gnjlonbg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxafzzdk.html

[R10] 正则匹配
来源：http://dali.hnqzz.top/Article/details/gt2keyccaxv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ivvv.top/Article/details/gt2kkrdwkja.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gt2zrfuzdiz.html

case "$1" in
来源：http://dali.0kj1m.cn/Article/details/gt2jfmoqmdi.html

start) echo "启动" ;;
来源：http://dali.316326.xyz/Article/details/gt2xzdnogfv.html

stop)  echo "停止" ;;
来源：http://dali.guowangkeji.top/Article/details/gt2xjzdwtxk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dssqluze.html

esac
来源：http://dali.wangdashe.top/Article/details/gt2owxvjmnj.html

[R12] for 遍历文件
来源：http://dali.chenlongwang.top/Article/details/gt2ngzybisp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gt2pepqwuki.html

[R13] for 计数循环
来源：http://dali.ehwqpu.com/Article/details/gt2bojmywas.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2xnyfhnmk.html

[R14] C 风格 for
来源：http://dali.yongpay.top/Article/details/gt2supstwkd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gt2yrikxocx.html

[R15] while 逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2rigoduon.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2hzjinhbt.html

[R16] until 等待条件
来源：http://dali.xylfe.cn/Article/details/gt2qficmdgl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gt2qucyrlzm.html

[R17] 数组定义与取值
来源：http://dali.cucudq.cn/Article/details/gt2jculbygm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ppjwa.cn/Article/details/gt2ioetmenr.html

[R18] 遍历数组
来源：http://dali.ydzc1.top/Article/details/gt2ldijbdvt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2ltwwyxkp.html

[R19] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pkiakjhb.html

echo "${#arr[@]}"
来源：http://dali.hfpthk.cn/Article/details/gt2acosxczv.html

[R20] 关联数组（字典）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ktxoxorc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cheryme.top/Article/details/gt2uznbdsfu.html

[R21] 字符串长度
来源：http://dali.svipenyu.cn/Article/details/gt2egonvwas.html

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gt2nnkcgwzn.html

[R22] 截取子串
来源：http://dali.havefunace.top/Article/details/gt2hietupqb.html

echo "${s:0:5}"
来源：http://dali.ybcxt.top/Article/details/gt2ockcdflp.html

[R23] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gt2meumqmwb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gt2zvexbbcf.html

[R24] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gt2temccujk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.iojbl.cn/Article/details/gt2fdyconnp.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gt2szfmwpyk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.kuanghao11.cn/Article/details/gt2cjwgbowa.html

[R26] 命令替换
来源：http://dali.c1oappe.top/Article/details/gt2bjczkagk.html

now=$(date +%F); echo "$now"
来源：http://dali.tian-w.cn/Article/details/gt2myjtqxkc.html

[R27] 算术展开
来源：http://dali.sweek.top/Article/details/gt2jactlfwz.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2nqdwtand.html

[R28] 浮点运算
来源：http://dali.daxiang520.top/Article/details/gt2szjtwxgv.html

echo "scale=2; 10/3" | bc
来源：http://dali.jlsjyb.cn/Article/details/gt2sbneljve.html

[R29] 定义函数
来源：http://dali.redwolf501.top/Article/details/gt2mgufnvgy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ppjwa.cn/Article/details/gt2gadpcgsd.html

[R30] 函数返回状态码
来源：http://dali.xziqi.cn/Article/details/gt2rgplhssv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aizwys.cn/Article/details/gt2iccoasze.html

[R31] 局部变量
来源：http://dali.sufxvd.cn/Article/details/gt2zflfgnom.html

f() { local x=1; echo "$x"; }
来源：http://dali.ehwqpu.com/Article/details/gt2ctyvlrzo.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gt2zsqajwse.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gt2dlczklfc.html

[R33] 捕获错误并提示行号
来源：http://dali.sweek.top/Article/details/gt2srqxrwze.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenjidiqi.icu/Article/details/gt2qcfufdeu.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gt2mgqucxyu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gt2ogobwnsh.html

[R35] 后台执行并等待
来源：http://dali.birdmap.top/Article/details/gt2ngophgfp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ivvv.top/Article/details/gt2ctssliac.html

[R36] 并发执行多个任务
来源：http://dali.yueranfly.top/Article/details/gt2vrjjheii.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guowangkeji.top/Article/details/gt2yoyqccfo.html

[R37] 把输出赋给变量
来源：http://dali.yueranfly.top/Article/details/gt2vnjnprgr.html

files=$(ls -1)
来源：http://dali.fengsongda.top/Article/details/gt2pwrhsplo.html

[R38] 管道串联
来源：http://dali.jiagoushi.top/Article/details/gt2wnklbpor.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xylfe.cn/Article/details/gt2tcsxlpym.html

[R39] 重定向标准输出与错误
来源：http://dali.hysaishi.cn/Article/details/gt2lpjyxruw.html

cmd > out.log 2>&1
来源：http://dali.nwbrower.top/Article/details/gt2lkbmaklg.html

[R40] 追加写日志
来源：http://dali.kuanghao11.cn/Article/details/gt2kylszqcj.html

echo "log" >> out.log
来源：http://dali.jyoumei.cn/Article/details/gt2dhrdqaym.html

[R41] 丢弃输出
来源：http://dali.sweek.top/Article/details/gt2dvwabngd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmmskxn.html

[R42] 输入重定向
来源：http://dali.cucudq.cn/Article/details/gt2zgxhmami.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gt2tuuuxgmt.html

[R43] 按名字查找文件
来源：http://dali.c1oappe.top/Article/details/gt2srohkyiv.html

find . -name "*.log" -type f
来源：http://dali.zhiwuduotai.top/Article/details/gt2drxcdvth.html

[R44] 按修改时间查找
来源：http://dali.tanke756.top/Article/details/gt2guziclmt.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gt2rigtssmv.html

[R45] 批量删除
来源：http://dali.sufxvd.cn/Article/details/gt2xnsfvdmw.html

find . -name "*.tmp" -delete
来源：http://dali.guowangkeji.top/Article/details/gt2yethpobp.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2diwzzzgl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dashuyun.cn/Article/details/gt2kqqgsujk.html

[R47] sed 单行替换
来源：http://dali.havefunace.top/Article/details/gt2zvvtjmhu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2phhybfnr.html

[R48] awk 取指定列
来源：http://dali.yanxiufei.cn/Article/details/gt2glyzcfxl.html

awk '{print $1, $3}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2fynhnaxg.html

[R49] awk 带条件
来源：http://dali.yj202588.top/Article/details/gt2bauwckcs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pengpengdd.cyou/Article/details/gt2oresbxzy.html

[R50] awk 求和
来源：http://dali.meibo888.top/Article/details/gt2eoevtwyu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ejstwxuz.html

[R51] 排序去重取前几
来源：http://dali.haohaochexian.top/Article/details/gt2abiptswh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shzxlz.cn/Article/details/gt2nszoliuh.html

[R52] 统计行数
来源：http://dali.hywenlv.cn/Article/details/gt2fcwnadvh.html

wc -l a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2ttvgqnbc.html

[R53] 查看文件头与实时尾
来源：http://dali.gotoacloud.top/Article/details/gt2fmkzelyx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnxiangtu.top/Article/details/gt2bpwiaofj.html

[R54] 比较两个文件
来源：http://dali.yongpay.top/Article/details/gt2hvluhdgh.html

diff a.txt b.txt
来源：http://dali.redwolf501.top/Article/details/gt2jpaeyeld.html

[R55] 压缩与解压
来源：http://dali.aibaodan.cn/Article/details/gt2uumqfpxy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhongyouzk.top/Article/details/gt2qvwvumtc.html

[R56] 远程拷贝
来源：http://dali.ydzc1.top/Article/details/gt2txagwtbp.html

scp file user@host:/path/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aszhmrre.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppwkkegw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qmchtmjl.html

[R58] 下载文件
来源：http://dali.jyoumei.cn/Article/details/gt2tyblvnsu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gt2xubfuzea.html

[R59] 发 POST JSON
来源：http://dali.sxryk.cn/Article/details/gt2zqlpgcat.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.9152youxi.cn/Article/details/gt2exfcapqs.html

[R60] 只看 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbeyuaqv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hfpthk.cn/Article/details/gt2iqbtoyhq.html

[R61] 磁盘占用
来源：http://dali.jlsjyb.cn/Article/details/gt2kthzeqvm.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gt2dvsxzqlh.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gt2sxwhwzum.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgfzy.top/Article/details/gt2vvkuaemh.html

[R63] 内存与进程
来源：http://dali.hnqzz.top/Article/details/gt2govxyclp.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gt2hjkzwdvx.html

[R64] 结束进程
来源：http://dali.yj20258888.top/Article/details/gt2imrmqftv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.iojbl.cn/Article/details/gt2pqcwicxb.html

[R65] 查看端口占用
来源：http://dali.hammf.cn/Article/details/gt2kmvkqjxj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2idrzzfem.html

[R66] 定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gt2lllbvwtt.html

crontab -e;  crontab -l
来源：http://dali.9152youxi.cn/Article/details/gt2rekoouqx.html

[R67] 生成随机十六进制串
来源：http://dali.yuanzhike.top/Article/details/gt2tpmfwsnn.html

openssl rand -hex 16
来源：http://dali.zycfv.cn/Article/details/gt2difjuqtv.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gt2tacuqjrh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2osotfddr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rokrwklc.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenjidiqi.icu/Article/details/gt2jawaewqo.html

[R70] 时间戳与互转
来源：http://dali.snrcjt.cn/Article/details/gt2pvtfbvuc.html

date +%s;  date -d @1700000000
来源：http://dali.svipenyu.cn/Article/details/gt2ljyyvsmq.html

[R71] 日期格式化
来源：http://dali.cashguo.top/Article/details/gt2zsqmnqfx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cashguo.top/Article/details/gt2kuutglrd.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gt2aakjbguw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gt2fwityhmc.html

[R73] 分割大日志
来源：http://dali.yanxiufei.cn/Article/details/gt2kjxhhiys.html

split -l 1000 big.log part_
来源：http://dali.yuxming.cn/Article/details/gt2gzlyzheg.html

[R74] 批量重命名
来源：http://dali.tanke756.top/Article/details/gt2rarzhaez.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2itmfhxpv.html

[R75] 导出环境变量
来源：http://dali.jiagoushi.top/Article/details/gt2nlbjkhsz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gt2eyfhzouv.html

[R76] 使用临时文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2cxbykgfx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gt2scxqnmwz.html

[R77] 读取用户输入
来源：http://dali.gzhubu.top/Article/details/gt2irqktscp.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mdiusyoe.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gt2koibdemd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xziqi.cn/Article/details/gt2plzgxloc.html

[R79] 解析命令行选项
来源：http://dali.dashuyun.cn/Article/details/gt2qnzazfgb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yvedp.cn/Article/details/gt2bqaxwzfs.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgufenzy.top/Article/details/gt2soawedwb.html

time ./run.sh
来源：http://dali.dashuyun.cn/Article/details/gt2moinonmz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhyzvrg.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gt2kfiufxdb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2gxuronid.html

[S01] C：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2ricycapa.html

#include <stdio.h>
来源：http://dali.fengsongda.top/Article/details/gt2saruwxxa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuanzx.com/Article/details/gt2bowapeza.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gt2gvforeeg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kklryuzt.html

[S03] C：读入整数
来源：http://dali.yongpay.top/Article/details/gt2upumgdvg.html

int x; scanf("%d", &x);
来源：http://dali.ehwqpu.com/Article/details/gt2lgtnrblt.html

[S04] C：字符串复制
来源：http://dali.meibo888.top/Article/details/gt2tevfofyz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2squzqkrp.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gt2vhewatnm.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gt2ammkkogb.html

[S06] C：字符串比较
来源：http://dali.nanxinkj.top/Article/details/gt2xmcoqcef.html

strcmp(a, b) == 0
来源：http://dali.zdqjudy.top/Article/details/gt2qyhtlizb.html

[S07] C：数组遍历求和
来源：http://dali.sweek.top/Article/details/gt2yhtwblwb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zdqjudy.top/Article/details/gt2lzficryq.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gt2yxnlwsrj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hammf.cn/Article/details/gt2dvacmaxb.html

[S09] C：结构体定义与初始化
来源：http://dali.andypj.xyz/Article/details/gt2uqllxxll.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenzaomai.com/Article/details/gt2ixiapqhl.html

[S10] C：指针与解引用
来源：http://dali.zhengqikj.top/Article/details/gt2kmcvejok.html

int *p = &a;  *p = 5;
来源：http://dali.cucudq.cn/Article/details/gt2snyrtlha.html

[S11] C：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gt2rwmppqob.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cqqwz.cn/Article/details/gt2avvketqd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cdnleiting.top/Article/details/gt2pnkkiwip.html

fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gt2ynnfnljf.html

[S12] C：写文件
来源：http://dali.cqqwz.cn/Article/details/gt2rwimgaar.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gt2dezirqrd.html

[S13] C：宏定义
来源：http://dali.aibaodan.cn/Article/details/gt2cruvhscq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cucudq.cn/Article/details/gt2wnpbcdxr.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfakggg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj202588.top/Article/details/gt2dvgebdpl.html

[S15] C：类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2skzqunkc.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gt2cemlpkcw.html

[S16] C：位操作置位
来源：http://dali.jinqigfzy.top/Article/details/gt2vhsomifj.html

x |= (1 << 3);
来源：http://dali.andypj.xyz/Article/details/gt2azwjoiym.html

[S17] C：安全拼接字符串
来源：http://dali.yuxming.cn/Article/details/gt2guiyzoat.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.svipenyu.cn/Article/details/gt2ksiixphu.html

[S18] C：命令行参数
来源：http://dali.yj20258.top/Article/details/gt2vxjueiml.html

int main(int argc, char **argv)
来源：http://dali.nanxuanxn.top/Article/details/gt2drlxdexo.html

[S19] C：快速排序
来源：http://dali.nanxinkj.top/Article/details/gt2aaxyffdd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gt2esfbrwvp.html

[S20] C：二分查找
来源：http://dali.daxiang520.top/Article/details/gt2dbrlnjyf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gt2hdnjbnce.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gt2drriqeag.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwhikkgz.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gt2cfzmmyzt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.mhx1999.top/Article/details/gt2dqpgpusq.html

[S23] C：随机数
来源：http://dali.gotoacloud.top/Article/details/gt2idymrbhk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.redwolf501.top/Article/details/gt2iijzcucu.html

[S24] C：获取本地时间
来源：http://dali.jiagoushi.top/Article/details/gt2fmaaayhi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aizwys.cn/Article/details/gt2lrkxdzgg.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gt2ydqlpjjs.html

memcpy(dst, src, n);
来源：http://dali.hywenlv.cn/Article/details/gt2rpjxnenc.html

[S26] C：内存清零
来源：http://dali.jiagoushi.top/Article/details/gt2rjrnunct.html

memset(a, 0, sizeof a);
来源：http://dali.bjfxy.top/Article/details/gt2zaoywtcy.html

[S27] C：定义常量
来源：http://dali.jinqigufen.top/Article/details/gt2slerupul.html

const double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gt2cisboify.html

[S28] C：静态变量
来源：http://dali.shuidangran.top/Article/details/gt2omrgflaf.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gt2ugiyxrwy.html

[S29] C：变参函数
来源：http://dali.jlsjyb.cn/Article/details/gt2eovpnrqr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sysykeji.top/Article/details/gt2pkurwipi.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gt2qorkxniw.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvhmxper.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gt2bqutebfu.html

#endif
来源：http://dali.fengsongda.top/Article/details/gt2amjzccoe.html

[S31] C++：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2zzlyrvow.html

#include <iostream>
来源：http://dali.aizwys.cn/Article/details/gt2blixyhdj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.svipenyu.cn/Article/details/gt2sjdzfttl.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjkhexjy.html

std::string s = "hi";  s += "!";
来源：http://dali.iojbl.cn/Article/details/gt2jxrekufg.html

[S33] C++：vector 增删
来源：http://dali.tian-w.cn/Article/details/gt2mwbgartz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvyhngzm.html

[S34] C++：遍历 vector
来源：http://dali.nwbrower.top/Article/details/gt2laxtijck.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.0kj1m.cn/Article/details/gt2xueimmmk.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gt2ctcoepeq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2hfykdyip.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gt2mlaucjio.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2rjqxbtdc.html

[S37] C++：set
来源：http://dali.hywenlv.cn/Article/details/gt2cufckhsh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aizwys.cn/Article/details/gt2wovoaoyr.html

[S38] C++：排序
来源：http://dali.gogol.net.cn/Article/details/gt2mhlkgxzr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gt2bcwtnbto.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lalvzbru.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hongshengwenyu.top/Article/details/gt2mwgoeghc.html

[S40] C++：查找元素
来源：http://dali.gotoacloud.top/Article/details/gt2mukjwzsc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuanzhike.top/Article/details/gt2ouarlwxq.html

[S41] C++：类与构造函数
来源：http://dali.yanxiufei.cn/Article/details/gt2chypusop.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gt2fcmxcnce.html

[S42] C++：继承与虚函数
来源：http://dali.yj202588.top/Article/details/gt2adbxameu.html

class B : public Base { public: void f() override {} };
来源：http://dali.iojbl.cn/Article/details/gt2fmwkbgls.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rawppufm.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gt2bgwtbgoq.html

[S44] C++：引用传参
来源：http://dali.vqdsnc.cn/Article/details/gt2cthofrvf.html

void inc(int &x) { ++x; }
来源：http://dali.hnqzz.top/Article/details/gt2wyvnkkgb.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gt2muicnmqb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigfzy.top/Article/details/gt2ynizcfrr.html

[S46] C++：函数模板
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmxgxryl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ivvv.top/Article/details/gt2jphphsdz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gt2hilacvwu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tsdmplaj.html

[S48] C++：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2wrslhvcs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.svipenyu.cn/Article/details/gt2rvsqgadh.html

while (std::getline(in, line)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqwvkjly.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gt2ozkkefwf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jlsjyb.cn/Article/details/gt2msfypsyf.html

[S50] C++：格式化数字
来源：http://dali.fzhhl.top/Article/details/gt2prhbixhg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2ejazvlkf.html

[S51] C++：显式类型转换
来源：http://dali.tianlin.xyz/Article/details/gt2lwgxsrsy.html

static_cast<double>(a) / b
来源：http://dali.sufxvd.cn/Article/details/gt2svmpjudv.html

[S52] C++：const 与 noexcept
来源：http://dali.nwbrower.top/Article/details/gt2qczpddtv.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gt2hmnnzgrs.html

[S53] C++：移动语义
来源：http://dali.jyoumei.cn/Article/details/gt2dmrjdedj.html

std::vector<int> w = std::move(v);
来源：http://dali.hammf.cn/Article/details/gt2cbedixlz.html

[S54] C++：异常处理
来源：http://dali.nanxinkj.top/Article/details/gt2byunkrsk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hywenlv.cn/Article/details/gt2bkwncbxa.html

[S55] C++：结构化绑定
来源：http://dali.yuanzhike.top/Article/details/gt2witudftd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hammf.cn/Article/details/gt2cpcaulhm.html

[S56] C++：optional
来源：http://dali.cashguo.top/Article/details/gt2ujmgcqca.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gt2zorplpjx.html

[S57] C++：编译期常量
来源：http://dali.chenlongwang.top/Article/details/gt2alvintmm.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2ihkdreqi.html

[S58] C++：命名空间
来源：http://dali.hysaishi.cn/Article/details/gt2syezsdvi.html

namespace ns { int f() { return 1; } }
来源：http://dali.yueranfly.top/Article/details/gt2dmtjlsbe.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gt2pahelwxz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sdscgzja.html

[S60] C++：遍历并删除元素
来源：http://dali.fzhhl.top/Article/details/gt2xyhoqbad.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sysykeji.top/Article/details/gt2lqlopuzn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ibnyyjts.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gt2lqhublsa.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2dyclckvq.html

[T01] Kotlin：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2vcnktuuh.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gt2wtaapoyk.html

[T02] Kotlin：变量
来源：http://dali.kuanghao11.cn/Article/details/gt2mqqjxowa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.9152youxi.cn/Article/details/gt2iulkffkc.html

[T03] Kotlin：字符串模板
来源：http://dali.pycfn.com/Article/details/gt2bmvoetfw.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gt2qigrufxb.html

[T04] Kotlin：空安全
来源：http://dali.jinqigfzy.top/Article/details/gt2snretzmb.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gt2odypossp.html

[T05] Kotlin：when 表达式
来源：http://dali.ehwqpu.com/Article/details/gt2osqefdtr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zdqjudy.top/Article/details/gt2vkqogvvh.html

[T06] Kotlin：集合映射
来源：http://dali.9152youxi.cn/Article/details/gt2faeumgyl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.meibo888.top/Article/details/gt2xotpzmuy.html


<!-- 参考信息 -->