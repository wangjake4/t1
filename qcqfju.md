代发 wailian999

name="${1:-default}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxfoderc.html

[R06] 判断命令是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtmbjhsxuz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gtgmckoipx.html

[R07] if 判断文件
来源：http://dali.pycfn.com/Article/details/gtupwysfbr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtafwpyvpl.html

[R08] 数值比较
来源：http://dali.vqdsnc.cn/Article/details/gtpswsakor.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fzhhl.top/Article/details/gtokpfdwvn.html

[R09] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gtnwrksnxz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.mhx1999.top/Article/details/gtiocattoj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gtrlvqsoet.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtxiwkovaw.html

[R11] case 多分支
来源：http://dali.cdnleiting.top/Article/details/gtogstsnor.html

case "$1" in
来源：http://dali.yvedp.cn/Article/details/gtmgbfvyrq.html

start) echo "启动" ;;
来源：http://dali.cqqwz.cn/Article/details/gtjrfopocz.html

stop)  echo "停止" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtrephttfi.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gtkiqqpzab.html

esac
来源：http://dali.xinyue.icu/Article/details/gtguinftsm.html

[R12] for 遍历文件
来源：http://dali.xuetiantiany.cn/Article/details/gtiznzcxjf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jianghu66.top/Article/details/gtglhgjhxc.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gtumjmlekx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gtfnjwedex.html

[R14] C 风格 for
来源：http://dali.zhengqikj.top/Article/details/gttxpthqyr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gtoqiwiwau.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtvrjedawr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cucudq.cn/Article/details/gtspkwoomx.html

[R16] until 等待条件
来源：http://dali.nanxuanxn.top/Article/details/gtgbizuefl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtarnrlwbk.html

[R17] 数组定义与取值
来源：http://dali.ybcxt.top/Article/details/gtktdzccpq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.vqdsnc.cn/Article/details/gtsskqbzbu.html

[R18] 遍历数组
来源：http://dali.ybcxt.top/Article/details/gteoopecqh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daxiang520.top/Article/details/gtbfoxuywi.html

[R19] 数组长度
来源：http://dali.sweek.top/Article/details/gttcmnwmke.html

echo "${#arr[@]}"
来源：http://dali.pengpengdd.cyou/Article/details/gttzhrteld.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatixstqe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuanzhike.top/Article/details/gtaacskjzb.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtkzejvmpc.html

echo "${#s}"
来源：http://dali.ybcxt.top/Article/details/gtukxrwgme.html

[R22] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtjicgimwp.html

echo "${s:0:5}"
来源：http://dali.sysykeji.top/Article/details/gtmppblaif.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtkxqltjiv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnqzz.top/Article/details/gtwicvayyh.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtecccfhxp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwgfeeir.html

[R25] 去后缀 / 去前缀
来源：http://dali.hammf.cn/Article/details/gtgbtjkleg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.iojbl.cn/Article/details/gtaoflxolh.html

[R26] 命令替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoaaflyhj.html

now=$(date +%F); echo "$now"
来源：http://dali.xylfe.cn/Article/details/gtphtaosof.html

[R27] 算术展开
来源：http://dali.smart0.xyz/Article/details/gtteygavra.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258888.top/Article/details/gtznuogbzb.html

[R28] 浮点运算
来源：http://dali.hysaishi.cn/Article/details/gtvnepijtr.html

echo "scale=2; 10/3" | bc
来源：http://dali.sxryk.cn/Article/details/gtmuidoazv.html

[R29] 定义函数
来源：http://dali.yvedp.cn/Article/details/gtuxwcervw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.bjfxy.top/Article/details/gtxbepefnt.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhherwhw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhengqikj.top/Article/details/gtazuvycep.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gtakfzxemz.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgfzy.top/Article/details/gtfjnwdlgk.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gtojjqkefo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtxqsnejpn.html

[R33] 捕获错误并提示行号
来源：http://dali.haohaochexian.top/Article/details/gtpdppxbau.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guannengcc.top/Article/details/gtblycuqvm.html

[R34] 退出时清理
来源：http://dali.redwolf501.top/Article/details/gtozvurbzx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtwexipuer.html

[R35] 后台执行并等待
来源：http://dali.redwolf501.top/Article/details/gtsqhunyvh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdbnfhzy.html

[R36] 并发执行多个任务
来源：http://dali.hammf.cn/Article/details/gtpyznvjbn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yueranfly.top/Article/details/gtnhalnpsz.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gtygshgrjq.html

files=$(ls -1)
来源：http://dali.cqqwz.cn/Article/details/gtvuisjnef.html

[R38] 管道串联
来源：http://dali.9152youxi.cn/Article/details/gtctchmcif.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jyoumei.cn/Article/details/gtbfwyztci.html

[R39] 重定向标准输出与错误
来源：http://dali.hongshengwenyu.top/Article/details/gtoastefgh.html

cmd > out.log 2>&1
来源：http://dali.sxryk.cn/Article/details/gttwpznnxb.html

[R40] 追加写日志
来源：http://dali.aibaodan.cn/Article/details/gtjdtcrbwc.html

echo "log" >> out.log
来源：http://dali.cucudq.cn/Article/details/gtqneabltb.html

[R41] 丢弃输出
来源：http://dali.gogol.net.cn/Article/details/gtsuflgbap.html

cmd >/dev/null 2>&1
来源：http://dali.yuxming.cn/Article/details/gthzfkddzj.html

[R42] 输入重定向
来源：http://dali.cucudq.cn/Article/details/gtocxmqmyy.html

wc -l < a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtfcuumbcy.html

[R43] 按名字查找文件
来源：http://dali.zhongyouzk.top/Article/details/gtzabwvttz.html

find . -name "*.log" -type f
来源：http://dali.daria6918.cn/Article/details/gttckralhi.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gtyruyrogj.html

find . -mtime -7 -type f
来源：http://dali.zhongyouzk.top/Article/details/gtcvnipsvl.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gtppirjpjb.html

find . -name "*.tmp" -delete
来源：http://dali.andypj.xyz/Article/details/gtqeosemsq.html

[R46] 递归替换文件内容
来源：http://dali.gogol.net.cn/Article/details/gtlnxsymxf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuanzhike.top/Article/details/gtgveihiub.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gtluagvcbw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daria6918.cn/Article/details/gtsvokgywz.html

[R48] awk 取指定列
来源：http://dali.hammf.cn/Article/details/gtjhkfbhme.html

awk '{print $1, $3}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtirnxxfae.html

[R49] awk 带条件
来源：http://dali.9152youxi.cn/Article/details/gtzwndmyey.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jyoumei.cn/Article/details/gtizdrjpuo.html

[R50] awk 求和
来源：http://dali.316326.xyz/Article/details/gtlylpjewj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtuaudthxm.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gtbpndmhed.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yangfankeji.com/Article/details/gtwvasjdlj.html

[R52] 统计行数
来源：http://dali.ehwqpu.com/Article/details/gtslnftlhw.html

wc -l a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtbctvwaey.html

[R53] 查看文件头与实时尾
来源：http://dali.gaohongyu789.top/Article/details/gtmwgnwxhx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hongshengwenyu.top/Article/details/gtdmsznvwe.html

[R54] 比较两个文件
来源：http://dali.yueranfly.top/Article/details/gtcedayemr.html

diff a.txt b.txt
来源：http://dali.vqdsnc.cn/Article/details/gtziswimsu.html

[R55] 压缩与解压
来源：http://dali.yonumen.top/Article/details/gtbsqamyua.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shuidangran.top/Article/details/gtjnyhihuu.html

[R56] 远程拷贝
来源：http://dali.jiagoushi.top/Article/details/gtnmcalelw.html

scp file user@host:/path/
来源：http://dali.haohaochexian.top/Article/details/gtoydcvhwl.html

[R57] 远程执行命令
来源：http://dali.fengsongda.top/Article/details/gtfctgdvni.html

ssh user@host 'uptime'
来源：http://dali.mhx1999.top/Article/details/gtvlwkmyac.html

[R58] 下载文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqidaigfn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hammf.cn/Article/details/gtmszdvsdn.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gtaibgghqw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ybcxt.top/Article/details/gttbmkppuo.html

[R60] 只看 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gtljbsaooi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.redwolf501.top/Article/details/gtjvhxpubd.html

[R61] 磁盘占用
来源：http://dali.yangfankeji.com/Article/details/gttfvatzyz.html

df -h;  du -sh *
来源：http://dali.chenzaomai.com/Article/details/gtubicifea.html

[R62] 找最占空间的文件
来源：http://dali.xylfe.cn/Article/details/gtxnxugrtj.html

du -ah . | sort -rh | head -10
来源：http://dali.hywenlv.cn/Article/details/gtyshsqxkr.html

[R63] 内存与进程
来源：http://dali.redwolf501.top/Article/details/gtzvlvzvow.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gtagtfpsxf.html

[R64] 结束进程
来源：http://dali.yangfankeji.com/Article/details/gtuucugmtz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.vqdsnc.cn/Article/details/gtlmwnbjvt.html

[R65] 查看端口占用
来源：http://dali.kuanghao11.cn/Article/details/gtucghtabm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gtdxvtoagj.html

[R66] 定时任务
来源：http://dali.jiagoushi.top/Article/details/gtnazlwhgs.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gtlpzyoaug.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gtzzsdnddt.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gtzvzepndq.html

[R68] 计算文件校验值
来源：http://dali.tianlin.xyz/Article/details/gtzqegdtsz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fzhhl.top/Article/details/gtzwmgijso.html

[R69] 生成随机密码
来源：http://dali.tian-w.cn/Article/details/gturxeajen.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gtgrwevhla.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gticutbpjb.html

date +%s;  date -d @1700000000
来源：http://dali.hfpthk.cn/Article/details/gtmwyjstjt.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gtdipnrvzl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gtugnvxkqf.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgbcncvo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gtyleuvtod.html

[R73] 分割大日志
来源：http://dali.feifeiyinyue.top/Article/details/gtagumflak.html

split -l 1000 big.log part_
来源：http://dali.kuanghao11.cn/Article/details/gtupmsraan.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gtdgicxttm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gttbezgmsk.html

[R75] 导出环境变量
来源：http://dali.cdnleiting.top/Article/details/gtsmvesfbb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gtdjgkjxtm.html

[R76] 使用临时文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivahfgcc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gtlohhzpgr.html

[R77] 读取用户输入
来源：http://dali.zycfv.cn/Article/details/gtotagtqsf.html

read -rp "请输入: " ans
来源：http://dali.cashguo.top/Article/details/gtzdkggncn.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gtqavacguu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gtskrabgom.html

[R79] 解析命令行选项
来源：http://dali.jyoumei.cn/Article/details/gtlcdtjxdy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhixingplan.top/Article/details/gtvjuaofoq.html

[R80] 查看脚本执行耗时
来源：http://dali.guowangkeji.top/Article/details/gtmixrkrnf.html

time ./run.sh
来源：http://dali.zhoulong.xyz/Article/details/gtelrfhznh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtphzcjjbn.html

S. C / C++ 专题
来源：http://dali.daxiang520.top/Article/details/gtangialcj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysqrauyu.html

[S01] C：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtviqmsxma.html

#include <stdio.h>
来源：http://dali.jqgfzy.top/Article/details/gtbbgnnski.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zycfv.cn/Article/details/gtooqoswzp.html

[S02] C：变量与格式化输出
来源：http://dali.hnqzz.top/Article/details/gtfxbyzgak.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gtsvpqkybl.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gterfdjqrd.html

int x; scanf("%d", &x);
来源：http://dali.birdmap.top/Article/details/gtaxaxjgcq.html

[S04] C：字符串复制
来源：http://dali.jyoumei.cn/Article/details/gtasipuutf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xinyue.icu/Article/details/gtzygvviix.html

[S05] C：字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtsrtsvaor.html

strlen(s)
来源：http://dali.xziqi.cn/Article/details/gtcqpagulr.html

[S06] C：字符串比较
来源：http://dali.gzhubu.top/Article/details/gtnptxkqko.html

strcmp(a, b) == 0
来源：http://dali.jlsjyb.cn/Article/details/gtjaeckqpz.html

[S07] C：数组遍历求和
来源：http://dali.aizwys.cn/Article/details/gtukmxsjdk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zycfv.cn/Article/details/gtglspzsvk.html

[S08] C：动态内存分配与释放
来源：http://dali.chenzaomai.com/Article/details/gtlaoxuhts.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.quarkkingdee.top/Article/details/gtvtpwrrqx.html

[S09] C：结构体定义与初始化
来源：http://dali.feifeiyinyue.top/Article/details/gtliqtqyud.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorvwmczb.html

[S10] C：指针与解引用
来源：http://dali.fzhhl.top/Article/details/gtgengjrqy.html

int *p = &a;  *p = 5;
来源：http://dali.jqgfzy.top/Article/details/gtxmxacnci.html

[S11] C：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtnmvsbgkk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwuqcmuq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pycfn.com/Article/details/gtmldqbqst.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtvbdgjhqz.html

[S12] C：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtultwsbtz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtolbdrxrg.html

[S13] C：宏定义
来源：http://dali.quarkkingdee.top/Article/details/gtnvindabi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hammf.cn/Article/details/gtjdsptzek.html

[S14] C：枚举
来源：http://dali.nwbrower.top/Article/details/gtgzcgmpbz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsiqrstxw.html

[S15] C：类型转换
来源：http://dali.hammf.cn/Article/details/gtxsmntlrn.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gtqgpswgbt.html

[S16] C：位操作置位
来源：http://dali.mhx1999.top/Article/details/gtqhyvybqi.html

x |= (1 << 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtbsenppls.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtthejjaie.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ybcxt.top/Article/details/gtgciqqbzm.html

[S18] C：命令行参数
来源：http://dali.c1oappe.top/Article/details/gtuhznlkkk.html

int main(int argc, char **argv)
来源：http://dali.tanke756.top/Article/details/gtsfsvdmxr.html

[S19] C：快速排序
来源：http://dali.quarkkingdee.top/Article/details/gtnqenomuz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtpftowova.html

[S20] C：二分查找
来源：http://dali.quarkkingdee.top/Article/details/gthlqkatee.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gtddzxhwtm.html

[S21] C：字符类别判断
来源：http://dali.xylfe.cn/Article/details/gtwvqxbmdi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.vqdsnc.cn/Article/details/gtcanjycuq.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gttulroleg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuetiantiany.cn/Article/details/gtvseukork.html

[S23] C：随机数
来源：http://dali.guowangkeji.top/Article/details/gtetodgkqc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnqzz.top/Article/details/gtcpaicaro.html

[S24] C：获取本地时间
来源：http://dali.wangdashe.top/Article/details/gthkhhcfsf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxinkj.top/Article/details/gttchlizfn.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtzojzcpfu.html

memcpy(dst, src, n);
来源：http://dali.nwbrower.top/Article/details/gtwkjtgnfc.html

[S26] C：内存清零
来源：http://dali.wangdashe.top/Article/details/gtgwtxvbpm.html

memset(a, 0, sizeof a);
来源：http://dali.jiagoushi.top/Article/details/gtsmbefwrs.html

[S27] C：定义常量
来源：http://dali.xylfe.cn/Article/details/gtizdybbru.html

const double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtxatnvdyo.html

[S28] C：静态变量
来源：http://dali.gzhubu.top/Article/details/gtqnuhwjdx.html

static int counter = 0;
来源：http://dali.birdmap.top/Article/details/gtzksopten.html

[S29] C：变参函数
来源：http://dali.ppjwa.cn/Article/details/gtkpxqwwbf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.bjfxy.top/Article/details/gtvadwoesg.html

[S30] C：头文件保护
来源：http://dali.316326.xyz/Article/details/gthjlukusa.html

#ifndef X_H
来源：http://dali.fengsongda.top/Article/details/gtogsxzivj.html

#define X_H
来源：http://dali.quarkkingdee.top/Article/details/gtdgrhxapr.html

#endif
来源：http://dali.xziqi.cn/Article/details/gtjzbsvrta.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtqszlftme.html

#include <iostream>
来源：http://dali.sxryk.cn/Article/details/gtqqmywfph.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aibaodan.cn/Article/details/gtnslpwckn.html

[S32] C++：字符串
来源：http://dali.yangfankeji.com/Article/details/gtiwxlsdhr.html

std::string s = "hi";  s += "!";
来源：http://dali.nwbrower.top/Article/details/gtiphxhvgx.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gtwvnjuwfs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gtdpxfqokh.html

[S34] C++：遍历 vector
来源：http://dali.hongshengwenyu.top/Article/details/gtvpmkwpby.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuanzhike.top/Article/details/gtqttsohfk.html

[S35] C++：map
来源：http://dali.wangshuangyany.cn/Article/details/gtdgzslqut.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtendblxql.html

[S36] C++：unordered_map
来源：http://dali.ppjwa.cn/Article/details/gtktkakhpy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtwqfsvxps.html

[S37] C++：set
来源：http://dali.ppjwa.cn/Article/details/gtthjfjyey.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gogol.net.cn/Article/details/gtidcooetq.html

[S38] C++：排序
来源：http://dali.daxiang520.top/Article/details/gtqmbhicuh.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gtdqntowyb.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtorsfhzwn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.feifeiyinyue.top/Article/details/gtmocyfmzj.html

[S40] C++：查找元素
来源：http://dali.hnqzz.top/Article/details/gtstjdebqs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gtbfdndukt.html

[S41] C++：类与构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtsuamecmg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ydzc1.top/Article/details/gtyjjrsuuf.html

[S42] C++：继承与虚函数
来源：http://dali.zhengqikj.top/Article/details/gthkzutfrt.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxinkj.top/Article/details/gtgrwmjipm.html

[S43] C++：智能指针
来源：http://dali.sufxvd.cn/Article/details/gtvgbihjdt.html

auto p = std::make_unique<int>(5);
来源：http://dali.cqqwz.cn/Article/details/gtxzsoefqs.html

[S44] C++：引用传参
来源：http://dali.jyoumei.cn/Article/details/gtiklaewwh.html

void inc(int &x) { ++x; }
来源：http://dali.hammf.cn/Article/details/gtmypyvode.html

[S45] C++：lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtfwdhnsnb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cqqwz.cn/Article/details/gtxqpkhoam.html

[S46] C++：函数模板
来源：http://dali.shangyingyoupin.top/Article/details/gtuqxxxxjo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jianghu66.top/Article/details/gtrhvjwmhn.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gtrsvnhady.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.meibo888.top/Article/details/gtfnelnnmj.html

[S48] C++：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtdzdmgcri.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenlongwang.top/Article/details/gtwtwxliip.html

while (std::getline(in, line)) { }
来源：http://dali.shzxlz.cn/Article/details/gtixhvjkoi.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklbcgqrs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gtbuqlppxs.html

[S50] C++：格式化数字
来源：http://dali.fzhhl.top/Article/details/gtxndcwucy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtjgdzskte.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gtwvboqawo.html

static_cast<double>(a) / b
来源：http://dali.yueranfly.top/Article/details/gtnsktbpvu.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigufen.top/Article/details/gtpoqazjwm.html

int size() const noexcept { return n_; }
来源：http://dali.tianlin.xyz/Article/details/gtxucmkgwz.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gticnqrrga.html

std::vector<int> w = std::move(v);
来源：http://dali.feifeiyinyue.top/Article/details/gtknjveuhf.html

[S54] C++：异常处理
来源：http://dali.chenzaomai.com/Article/details/gtfncavews.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hfpthk.cn/Article/details/gtvpxbrlzk.html

[S55] C++：结构化绑定
来源：http://dali.yueranfly.top/Article/details/gtvnpgpgyf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.mhx1999.top/Article/details/gtopdgovmw.html

[S56] C++：optional
来源：http://dali.svipenyu.cn/Article/details/gthwopzqmo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gtosbhbpfp.html

[S57] C++：编译期常量
来源：http://dali.daria6918.cn/Article/details/gtzyikqray.html

constexpr int N = 10;
来源：http://dali.hywenlv.cn/Article/details/gthblxnhug.html

[S58] C++：命名空间
来源：http://dali.yj20258888.top/Article/details/gtikiqzylq.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gtwrqwbxvj.html

[S59] C++：静态断言
来源：http://dali.gaohongyu789.top/Article/details/gtfzegiybb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258888.top/Article/details/gtsvbkbulu.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtyaxbpaff.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtvhdwftni.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdawnyafm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gtwwzibdvp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtsaiprlbb.html

[T01] Kotlin：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnyupqes.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtljrgpojd.html

[T02] Kotlin：变量
来源：http://dali.dianchejie.cn/Article/details/gttexlrnlr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhiwuduotai.top/Article/details/gtafmawobr.html

[T03] Kotlin：字符串模板
来源：http://dali.cashguo.top/Article/details/gtfuddyrpv.html

"值: $b"
来源：http://dali.hnxiangtu.top/Article/details/gtcoqbydyz.html

[T04] Kotlin：空安全
来源：http://dali.mhx1999.top/Article/details/gthojtzbkz.html

val n: String? = null;  n?.length
来源：http://dali.smart0.xyz/Article/details/gtbxhejbno.html

[T05] Kotlin：when 表达式
来源：http://dali.svipenyu.cn/Article/details/gtggesltrz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guannengcc.top/Article/details/gtgptseqht.html

[T06] Kotlin：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gtlmqjekrt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtspeaymnn.html


<!-- 参考信息 -->