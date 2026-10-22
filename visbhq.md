代发 wailian999

name="${1:-default}"
来源：http://dali.yuxming.cn/Article/details/gt2skhezydh.html

[R06] 判断命令是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2hgzwngrd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gt2yfuotuau.html

[R07] if 判断文件
来源：http://dali.cheryme.top/Article/details/gt2cdyqqadm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ybcxt.top/Article/details/gt2igvrulco.html

[R08] 数值比较
来源：http://dali.andypj.xyz/Article/details/gt2aoeqliwu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2wbjtiqcp.html

[R09] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gt2avencrpw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ehwqpu.com/Article/details/gt2lmdqrxnx.html

[R10] 正则匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wyyyjunc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2wwbzyhrw.html

[R11] case 多分支
来源：http://dali.tanke756.top/Article/details/gt2ewhkxdkp.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqmsewhz.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gt2osrrbqza.html

stop)  echo "停止" ;;
来源：http://dali.ydzc1.top/Article/details/gt2rpnxylmx.html

*)     echo "未知命令" ;;
来源：http://dali.guannengcc.top/Article/details/gt2ibymfhjx.html

esac
来源：http://dali.svipenyu.cn/Article/details/gt2hnazibqs.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2omnhzsja.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jyoumei.cn/Article/details/gt2uhkstlec.html

[R13] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gt2rorsvfxe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gt2jlxepckm.html

[R14] C 风格 for
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iuhmuprm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gt2qkqaayue.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrpdpis.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigufen.top/Article/details/gt2aniorsvt.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gt2ehrvneif.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gt2mkpljpub.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gt2hupyjbec.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gt2cbccxyyy.html

[R18] 遍历数组
来源：http://dali.smart0.xyz/Article/details/gt2fqufhzbj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hysaishi.cn/Article/details/gt2umyevwqb.html

[R19] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gt2qddboutm.html

echo "${#arr[@]}"
来源：http://dali.ivvv.top/Article/details/gt2lscioear.html

[R20] 关联数组（字典）
来源：http://dali.hammf.cn/Article/details/gt2uikcdhje.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cheryme.top/Article/details/gt2sqkerbaz.html

[R21] 字符串长度
来源：http://dali.dianchejie.cn/Article/details/gt2rvswkztl.html

echo "${#s}"
来源：http://dali.snrcjt.cn/Article/details/gt2lrruvqax.html

[R22] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gt2cvqgzfzo.html

echo "${s:0:5}"
来源：http://dali.aibaodan.cn/Article/details/gt2lncagoxm.html

[R23] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gt2ogypynfv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gt2tkkgracr.html

[R24] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gt2nxjammek.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhongyouzk.top/Article/details/gt2xuyvafgx.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258.top/Article/details/gt2tvqfzqfg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2azgllaiv.html

[R26] 命令替换
来源：http://dali.zdqjudy.top/Article/details/gt2phcrmbai.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gt2yxargbeg.html

[R27] 算术展开
来源：http://dali.yonumen.top/Article/details/gt2ryvxeyrf.html

echo $((1 + 2 * 3))
来源：http://dali.c1oappe.top/Article/details/gt2lkzraimb.html

[R28] 浮点运算
来源：http://dali.yuxming.cn/Article/details/gt2mkylxknj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhengqikj.top/Article/details/gt2hqrwhzgm.html

[R29] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gt2ghhhpfaq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shuidangran.top/Article/details/gt2girhlhgs.html

[R30] 函数返回状态码
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahkfwnqc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gt2hfoypfeb.html

[R31] 局部变量
来源：http://dali.meibo888.top/Article/details/gt2lwzkrxzr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhengqikj.top/Article/details/gt2gbrijsir.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gt2gaxwnqye.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gt2oznnrmxp.html

[R33] 捕获错误并提示行号
来源：http://dali.sufxvd.cn/Article/details/gt2lcweaych.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj202588.top/Article/details/gt2sfxkujya.html

[R34] 退出时清理
来源：http://dali.zhixingplan.top/Article/details/gt2pygurvoi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkuexnwn.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gt2wwfakkzd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jlsjyb.cn/Article/details/gt2shlbtiaw.html

[R36] 并发执行多个任务
来源：http://dali.yvedp.cn/Article/details/gt2molnqyfj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhongyouzk.top/Article/details/gt2onkqxxqe.html

[R37] 把输出赋给变量
来源：http://dali.guannengcc.top/Article/details/gt2sdqzdrgc.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2cvwttvfd.html

[R38] 管道串联
来源：http://dali.cqqwz.cn/Article/details/gt2blrsqand.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tqbvowuf.html

[R39] 重定向标准输出与错误
来源：http://dali.tanke756.top/Article/details/gt2cairvihb.html

cmd > out.log 2>&1
来源：http://dali.yj20258888.top/Article/details/gt2ddkvfhku.html

[R40] 追加写日志
来源：http://dali.guowangkeji.top/Article/details/gt2qzgjgpxl.html

echo "log" >> out.log
来源：http://dali.jinqigufen.top/Article/details/gt2drulzrhd.html

[R41] 丢弃输出
来源：http://dali.yj20258888.top/Article/details/gt2zjhoozvs.html

cmd >/dev/null 2>&1
来源：http://dali.cucudq.cn/Article/details/gt2jexjsqwa.html

[R42] 输入重定向
来源：http://dali.yangfankeji.com/Article/details/gt2egercfzh.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2twktchpn.html

[R43] 按名字查找文件
来源：http://dali.xziqi.cn/Article/details/gt2fgbmtjgm.html

find . -name "*.log" -type f
来源：http://dali.ivvv.top/Article/details/gt2gktvhgfd.html

[R44] 按修改时间查找
来源：http://dali.yuxming.cn/Article/details/gt2szyvjjuu.html

find . -mtime -7 -type f
来源：http://dali.sxryk.cn/Article/details/gt2ptlrqdfm.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gt2bkcmcbdq.html

find . -name "*.tmp" -delete
来源：http://dali.pycfn.com/Article/details/gt2lfulbxfk.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gt2nzoqmjso.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2elazxovu.html

[R47] sed 单行替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2meghmzel.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.birdmap.top/Article/details/gt2vyjyscbe.html

[R48] awk 取指定列
来源：http://dali.yj202588.top/Article/details/gt2aqjbqjix.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj202588.top/Article/details/gt2nfgzntcw.html

[R49] awk 带条件
来源：http://dali.jqgfzy.top/Article/details/gt2cfozwlbi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daxiang520.top/Article/details/gt2yeprrehh.html

[R50] awk 求和
来源：http://dali.yuxming.cn/Article/details/gt2dhjffylb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2vfzbhbwh.html

[R51] 排序去重取前几
来源：http://dali.zhoulong.xyz/Article/details/gt2bfcjhfdx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.redwolf501.top/Article/details/gt2hamhmohd.html

[R52] 统计行数
来源：http://dali.yj20258.top/Article/details/gt2mmvybbwr.html

wc -l a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2dqaqqgrb.html

[R53] 查看文件头与实时尾
来源：http://dali.yongpay.top/Article/details/gt2kgpcfxsh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gt2flxutkxj.html

[R54] 比较两个文件
来源：http://dali.yanxiufei.cn/Article/details/gt2ihfczyap.html

diff a.txt b.txt
来源：http://dali.xziqi.cn/Article/details/gt2zszizkyv.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gt2cfwccmce.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigfzy.top/Article/details/gt2iabynjlc.html

[R56] 远程拷贝
来源：http://dali.cqqwz.cn/Article/details/gt2tbklfxyr.html

scp file user@host:/path/
来源：http://dali.yuanzhike.top/Article/details/gt2ylwzeans.html

[R57] 远程执行命令
来源：http://dali.jqgfzy.top/Article/details/gt2wseyeewz.html

ssh user@host 'uptime'
来源：http://dali.nanxinkj.top/Article/details/gt2ekrjgepn.html

[R58] 下载文件
来源：http://dali.yonumen.top/Article/details/gt2qypiaknb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuetiantiany.cn/Article/details/gt2weqhbdcm.html

[R59] 发 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wsjaczve.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhaumpuq.html

[R60] 只看 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gt2nllvtbql.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mypzisch.html

[R61] 磁盘占用
来源：http://dali.gaohongyu789.top/Article/details/gt2jtpnxbxr.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gt2wjgnmsgh.html

[R62] 找最占空间的文件
来源：http://dali.tanke756.top/Article/details/gt2vosfefkw.html

du -ah . | sort -rh | head -10
来源：http://dali.fengsongda.top/Article/details/gt2gcnznftg.html

[R63] 内存与进程
来源：http://dali.smart0.xyz/Article/details/gt2qodauuzs.html

free -h;  ps aux | grep nginx
来源：http://dali.gaohongyu789.top/Article/details/gt2ayspleoj.html

[R64] 结束进程
来源：http://dali.pycfn.com/Article/details/gt2ombnhgsj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gt2ggbjenbj.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gt2hhwfdarf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gt2imfowzwd.html

[R66] 定时任务
来源：http://dali.yj202588.top/Article/details/gt2otxjzyid.html

crontab -e;  crontab -l
来源：http://dali.svipenyu.cn/Article/details/gt2swasuqxp.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gt2qykvsmee.html

openssl rand -hex 16
来源：http://dali.hongshengwenyu.top/Article/details/gt2jynvnnvm.html

[R68] 计算文件校验值
来源：http://dali.sufxvd.cn/Article/details/gt2aonggnda.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2xsmdgwwl.html

[R69] 生成随机密码
来源：http://dali.zhongyouzk.top/Article/details/gt2ousrplld.html

head -c 16 /dev/urandom | base64
来源：http://dali.sxryk.cn/Article/details/gt2jtpfuiuf.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gt2aokblnhl.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gt2nyyvgspy.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gt2xjkcqesn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xinyue.icu/Article/details/gt2dvzyukjq.html

[R72] 等待端口就绪
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2atjupkfj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gt2tjqbezpv.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gt2dldjlzku.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gt2fdcyjqhq.html

[R74] 批量重命名
来源：http://dali.zhiwuduotai.top/Article/details/gt2uqdydmlj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hfpthk.cn/Article/details/gt2ncjtqbds.html

[R75] 导出环境变量
来源：http://dali.gotoacloud.top/Article/details/gt2uaoqpbsi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258888.top/Article/details/gt2ytkedgsi.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gt2ubeamusm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gt2uopmqcpu.html

[R77] 读取用户输入
来源：http://dali.gaohongyu789.top/Article/details/gt2yglnfpqk.html

read -rp "请输入: " ans
来源：http://dali.zycfv.cn/Article/details/gt2grhihjfe.html

[R78] 交互式菜单
来源：http://dali.chenlongwang.top/Article/details/gt2ufnevfum.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.bjfxy.top/Article/details/gt2tzozerjt.html

[R79] 解析命令行选项
来源：http://dali.smart0.xyz/Article/details/gt2rjogosim.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenlongwang.top/Article/details/gt2kwjoujnd.html

[R80] 查看脚本执行耗时
来源：http://dali.gzhubu.top/Article/details/gt2ecqgzgzj.html

time ./run.sh
来源：http://dali.0kj1m.cn/Article/details/gt2dgumxkyw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2qciystwr.html

S. C / C++ 专题
来源：http://dali.yj202588.top/Article/details/gt2eaatvrrr.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2mpghyrso.html

[S01] C：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2dgssepyg.html

#include <stdio.h>
来源：http://dali.yvedp.cn/Article/details/gt2vcnryjty.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zdhuykmj.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gt2gcbflsjp.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgufenzy.top/Article/details/gt2ndogvjpc.html

[S03] C：读入整数
来源：http://dali.zhoulong.xyz/Article/details/gt2ebknchge.html

int x; scanf("%d", &x);
来源：http://dali.hnxiangtu.top/Article/details/gt2ccqvxxoi.html

[S04] C：字符串复制
来源：http://dali.gaohongyu789.top/Article/details/gt2kxarmzka.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.quarkkingdee.top/Article/details/gt2jeosvsgg.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnpxuqrs.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gt2mmyqpkqa.html

[S06] C：字符串比较
来源：http://dali.andypj.xyz/Article/details/gt2mmmiykkx.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gt2mieuajzq.html

[S07] C：数组遍历求和
来源：http://dali.daxiang520.top/Article/details/gt2vyizvdsr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ppjwa.cn/Article/details/gt2ftoizotw.html

[S08] C：动态内存分配与释放
来源：http://dali.jlsjyb.cn/Article/details/gt2hdrouupy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jrjjrgpo.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258.top/Article/details/gt2uktctyxa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozvuzvkj.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wprbiojr.html

int *p = &a;  *p = 5;
来源：http://dali.zhoulong.xyz/Article/details/gt2pdmlzqcj.html

[S11] C：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2rpapagaq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daxiang520.top/Article/details/gt2nnmsxtyp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tian-w.cn/Article/details/gt2zkhxavku.html

fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wtdvyypb.html

[S12] C：写文件
来源：http://dali.fzhhl.top/Article/details/gt2cdrliexh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gt2aaebzqff.html

[S13] C：宏定义
来源：http://dali.shzxlz.cn/Article/details/gt2pvjmjwxl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jiagoushi.top/Article/details/gt2dxsljaqb.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gt2doeoslgp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.snrcjt.cn/Article/details/gt2jaoahwwj.html

[S15] C：类型转换
来源：http://dali.gzhubu.top/Article/details/gt2aiuwwoii.html

(double) a / b
来源：http://dali.sweek.top/Article/details/gt2koblqfhz.html

[S16] C：位操作置位
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwursmcp.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2bdiermev.html

[S17] C：安全拼接字符串
来源：http://dali.aizwys.cn/Article/details/gt2syxdypcz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nwbrower.top/Article/details/gt2aijmbccj.html

[S18] C：命令行参数
来源：http://dali.daria6918.cn/Article/details/gt2slqhtail.html

int main(int argc, char **argv)
来源：http://dali.nanxinkj.top/Article/details/gt2bppiljvz.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gt2ummrjaoz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgygbtwr.html

[S20] C：二分查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bgkvduuv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gt2avcdswpj.html

[S21] C：字符类别判断
来源：http://dali.zhongyouzk.top/Article/details/gt2kxxrzkng.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dashuyun.cn/Article/details/gt2hfjednpn.html

[S22] C：字符串转数字
来源：http://dali.tanke756.top/Article/details/gt2fnsghqlg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnxiangtu.top/Article/details/gt2asppfpqg.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gt2zieocqro.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.kuanghao11.cn/Article/details/gt2vtwcmhnb.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gt2shqgwnkl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigfzy.top/Article/details/gt2omwebdtl.html

[S25] C：内存拷贝
来源：http://dali.9152youxi.cn/Article/details/gt2skebsgrh.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gt2wxayluww.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gt2irkdtofl.html

memset(a, 0, sizeof a);
来源：http://dali.0kj1m.cn/Article/details/gt2axosdjxg.html

[S27] C：定义常量
来源：http://dali.yj20258.top/Article/details/gt2heuwpghk.html

const double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gt2kdyvxumg.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gt2jhyehloc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjysoec.html

[S29] C：变参函数
来源：http://dali.redwolf501.top/Article/details/gt2hryhzvsq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nwbrower.top/Article/details/gt2znzlcrwc.html

[S30] C：头文件保护
来源：http://dali.bjfxy.top/Article/details/gt2hjzxziyn.html

#ifndef X_H
来源：http://dali.zhiwuduotai.top/Article/details/gt2wezcpmyd.html

#define X_H
来源：http://dali.meibo888.top/Article/details/gt2fqxsdkwl.html

#endif
来源：http://dali.fengsongda.top/Article/details/gt2bdithwsk.html

[S31] C++：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2plbajkpn.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gt2wmqgoncr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.9152youxi.cn/Article/details/gt2adiocbxk.html

[S32] C++：字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdrlkwat.html

std::string s = "hi";  s += "!";
来源：http://dali.birdmap.top/Article/details/gt2iaicagsx.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gt2cbhqmewp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fzhhl.top/Article/details/gt2xecsszue.html

[S34] C++：遍历 vector
来源：http://dali.cheryme.top/Article/details/gt2eilqvnqf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.316326.xyz/Article/details/gt2bgrpeapy.html

[S35] C++：map
来源：http://dali.ivvv.top/Article/details/gt2atuzgjfd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvcwbhn.html

[S36] C++：unordered_map
来源：http://dali.yvedp.cn/Article/details/gt2anyzlcqb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2jzjbepcm.html

[S37] C++：set
来源：http://dali.jqgfzy.top/Article/details/gt2ueqiaxyf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tian-w.cn/Article/details/gt2gfgagbye.html

[S38] C++：排序
来源：http://dali.kuanghao11.cn/Article/details/gt2jwgzunif.html

std::sort(v.begin(), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vunefxly.html

[S39] C++：自定义比较器排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrhdmwed.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shuidangran.top/Article/details/gt2oyqllrnj.html

[S40] C++：查找元素
来源：http://dali.aibaodan.cn/Article/details/gt2vfjiqgky.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2icyqfqts.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2znvgzure.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fengsongda.top/Article/details/gt2fwnhidet.html

[S42] C++：继承与虚函数
来源：http://dali.xuanzx.com/Article/details/gt2vfrpucod.html

class B : public Base { public: void f() override {} };
来源：http://dali.daxiang520.top/Article/details/gt2tkpyqpzr.html

[S43] C++：智能指针
来源：http://dali.gotoacloud.top/Article/details/gt2zwnocuak.html

auto p = std::make_unique<int>(5);
来源：http://dali.zycfv.cn/Article/details/gt2svrtgmsi.html

[S44] C++：引用传参
来源：http://dali.chenzaomai.com/Article/details/gt2upqyuict.html

void inc(int &x) { ++x; }
来源：http://dali.hammf.cn/Article/details/gt2afevpecb.html

[S45] C++：lambda
来源：http://dali.316326.xyz/Article/details/gt2axmdqmzh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hammf.cn/Article/details/gt2ttptqcba.html

[S46] C++：函数模板
来源：http://dali.yj20258.top/Article/details/gt2xwnpsprx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gogol.net.cn/Article/details/gt2eekrhjhf.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gt2oyjdcoki.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gt2teebiexf.html

[S48] C++：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2kovnfkre.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ztwrajfz.html

while (std::getline(in, line)) { }
来源：http://dali.sufxvd.cn/Article/details/gt2flajhram.html

[S49] C++：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oqjnupnz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.iojbl.cn/Article/details/gt2zwxmjxfw.html

[S50] C++：格式化数字
来源：http://dali.sweek.top/Article/details/gt2yciquram.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2lfhmafzo.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gt2nbeoafuv.html

static_cast<double>(a) / b
来源：http://dali.jqgfzy.top/Article/details/gt2tojmbibe.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gt2llmlwjia.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gt2khfhalgx.html

[S53] C++：移动语义
来源：http://dali.cdnleiting.top/Article/details/gt2ediddwrd.html

std::vector<int> w = std::move(v);
来源：http://dali.cheryme.top/Article/details/gt2bemsvaun.html

[S54] C++：异常处理
来源：http://dali.snrcjt.cn/Article/details/gt2jszcgrhh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangdashe.top/Article/details/gt2mdsffbok.html

[S55] C++：结构化绑定
来源：http://dali.jqgufenzy.top/Article/details/gt2xvvibras.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2oulkuxtl.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gt2keoolyrg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqipjnfa.html

[S57] C++：编译期常量
来源：http://dali.andypj.xyz/Article/details/gt2saittjch.html

constexpr int N = 10;
来源：http://dali.wangdashe.top/Article/details/gt2gndgvkzg.html

[S58] C++：命名空间
来源：http://dali.jinqigfzy.top/Article/details/gt2xybnoeiu.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2aaomjyqe.html

[S59] C++：静态断言
来源：http://dali.zdqjudy.top/Article/details/gt2ggmnncpr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuanzhike.top/Article/details/gt2rtkchlrw.html

[S60] C++：遍历并删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2alqmwtqk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gt2itqkfbwf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2xfaeqtym.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gt2huupqpsw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2mmumakcu.html

[T01] Kotlin：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2oxjcehwo.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2xkjerhfh.html

[T02] Kotlin：变量
来源：http://dali.dianchejie.cn/Article/details/gt2ouwvykki.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigufen.top/Article/details/gt2dzesjezh.html

[T03] Kotlin：字符串模板
来源：http://dali.shangyingyoupin.top/Article/details/gt2gokszxae.html

"值: $b"
来源：http://dali.yvedp.cn/Article/details/gt2jvvfijak.html

[T04] Kotlin：空安全
来源：http://dali.hammf.cn/Article/details/gt2gyqwpmdh.html

val n: String? = null;  n?.length
来源：http://dali.zhixingplan.top/Article/details/gt2tlkdrkct.html

[T05] Kotlin：when 表达式
来源：http://dali.316326.xyz/Article/details/gt2kafeqssr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxuanxn.top/Article/details/gt2iwnognky.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gt2lrcrnqtn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2oovcvpar.html


<!-- 参考信息 -->