代发 wailian999

set -euo pipefail
来源：http://dali.zycfv.cn/Article/details/gt2zryppsuw.html

[R02] 变量赋值与使用
来源：http://dali.gotoacloud.top/Article/details/gt2fsfjozbe.html

name="Tom"; echo "$name"
来源：http://dali.dianchejie.cn/Article/details/gt2sdgmplld.html

[R03] 只读变量
来源：http://dali.jinqigfzy.top/Article/details/gt2esdtfupw.html

readonly PI=3.14
来源：http://dali.birdmap.top/Article/details/gt2ajbqxiwo.html

[R04] 位置参数
来源：http://dali.hfpthk.cn/Article/details/gt2jhzfrbll.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenlongwang.top/Article/details/gt2caotqggh.html

[R05] 参数默认值
来源：http://dali.tianlin.xyz/Article/details/gt2xipwqqpw.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gt2ltkloyef.html

[R06] 判断命令是否存在
来源：http://dali.bjfxy.top/Article/details/gt2dwdnyvsp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gt2wccehtuw.html

[R07] if 判断文件
来源：http://dali.jianghu66.top/Article/details/gt2zcyrsekk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hywenlv.cn/Article/details/gt2vxnwtutm.html

[R08] 数值比较
来源：http://dali.yuxming.cn/Article/details/gt2ncayvplr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2vvnmtrml.html

[R09] 字符串比较
来源：http://dali.fengsongda.top/Article/details/gt2vnxyqskn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.birdmap.top/Article/details/gt2pkponojo.html

[R10] 正则匹配
来源：http://dali.guowangkeji.top/Article/details/gt2zbjjuipo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2xgsvpwjx.html

[R11] case 多分支
来源：http://dali.hysaishi.cn/Article/details/gt2jnxrajfa.html

case "$1" in
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxqyhvzp.html

start) echo "启动" ;;
来源：http://dali.c1oappe.top/Article/details/gt2ntoovjhg.html

stop)  echo "停止" ;;
来源：http://dali.cdnleiting.top/Article/details/gt2jkkojwtu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzzeymt.html

esac
来源：http://dali.zdqjudy.top/Article/details/gt2xyfqaeia.html

[R12] for 遍历文件
来源：http://dali.gogol.net.cn/Article/details/gt2caxwptfy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqtjmkky.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gt2shadvopm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gt2owqqnitd.html

[R14] C 风格 for
来源：http://dali.gogol.net.cn/Article/details/gt2wxpnrdbl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gt2vaferbwo.html

[R15] while 逐行读文件
来源：http://dali.sysykeji.top/Article/details/gt2cpvozdsn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xinyue.icu/Article/details/gt2sozltazm.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hczxarrh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gt2lzrqbzzr.html

[R17] 数组定义与取值
来源：http://dali.cheryme.top/Article/details/gt2rsdirwwt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2hxiqvvsi.html

[R18] 遍历数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2klkfnohk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.c1oappe.top/Article/details/gt2oulgyvdb.html

[R19] 数组长度
来源：http://dali.aizwys.cn/Article/details/gt2cermqipl.html

echo "${#arr[@]}"
来源：http://dali.gzhubu.top/Article/details/gt2kxqclzsm.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqdkdvtw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gotoacloud.top/Article/details/gt2llymwrqd.html

[R21] 字符串长度
来源：http://dali.daria6918.cn/Article/details/gt2ptdodoih.html

echo "${#s}"
来源：http://dali.yonumen.top/Article/details/gt2egfpsies.html

[R22] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gt2icstmrkl.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gt2tdputdzt.html

[R23] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gt2qdwotwff.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258.top/Article/details/gt2dxqryual.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gt2nnpkpvlr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgufenzy.top/Article/details/gt2wbnfhcym.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwhhqhec.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ppjwa.cn/Article/details/gt2kaludzmh.html

[R26] 命令替换
来源：http://dali.hammf.cn/Article/details/gt2mgzteodj.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gt2sufkaivn.html

[R27] 算术展开
来源：http://dali.nwbrower.top/Article/details/gt2rnkipckb.html

echo $((1 + 2 * 3))
来源：http://dali.sweek.top/Article/details/gt2wxtqmwii.html

[R28] 浮点运算
来源：http://dali.gaohongyu789.top/Article/details/gt2oaoewkxq.html

echo "scale=2; 10/3" | bc
来源：http://dali.birdmap.top/Article/details/gt2vdlecilt.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gt2mppieomt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hysaishi.cn/Article/details/gt2zidagglk.html

[R30] 函数返回状态码
来源：http://dali.cheryme.top/Article/details/gt2busnzzdy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cheryme.top/Article/details/gt2fadvkudm.html

[R31] 局部变量
来源：http://dali.haohaochexian.top/Article/details/gt2cjdeykhg.html

f() { local x=1; echo "$x"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2nzpedttj.html

[R32] 参数个数校验
来源：http://dali.zhixingplan.top/Article/details/gt2qdogszqw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gt2zefavkwf.html

[R33] 捕获错误并提示行号
来源：http://dali.shangyingyoupin.top/Article/details/gt2tvkdanzb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuanzhike.top/Article/details/gt2tjqilxlo.html

[R34] 退出时清理
来源：http://dali.vqdsnc.cn/Article/details/gt2rtfgoula.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gt2rrhrmive.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bwlkbsiv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.316326.xyz/Article/details/gt2yxwtgdsb.html

[R36] 并发执行多个任务
来源：http://dali.fengsongda.top/Article/details/gt2mezvgfsq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gt2atkylage.html

[R37] 把输出赋给变量
来源：http://dali.dianchejie.cn/Article/details/gt2rdyavzcs.html

files=$(ls -1)
来源：http://dali.guannengcc.top/Article/details/gt2vllntktl.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gt2qfnnnweb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shangyingyoupin.top/Article/details/gt2vdlsoufn.html

[R39] 重定向标准输出与错误
来源：http://dali.birdmap.top/Article/details/gt2tccraqqs.html

cmd > out.log 2>&1
来源：http://dali.wangdashe.top/Article/details/gt2rtqngzef.html

[R40] 追加写日志
来源：http://dali.jianghu66.top/Article/details/gt2osunobep.html

echo "log" >> out.log
来源：http://dali.mhx1999.top/Article/details/gt2azerxsaa.html

[R41] 丢弃输出
来源：http://dali.cashguo.top/Article/details/gt2mgoukduv.html

cmd >/dev/null 2>&1
来源：http://dali.pycfn.com/Article/details/gt2elcwmbah.html

[R42] 输入重定向
来源：http://dali.jlsjyb.cn/Article/details/gt2hveasgwa.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2inwabsug.html

[R43] 按名字查找文件
来源：http://dali.bjfxy.top/Article/details/gt2wpktgpal.html

find . -name "*.log" -type f
来源：http://dali.cqqwz.cn/Article/details/gt2shqsirxu.html

[R44] 按修改时间查找
来源：http://dali.zhengqikj.top/Article/details/gt2xyvrebzv.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gt2hqvyhayi.html

[R45] 批量删除
来源：http://dali.gogol.net.cn/Article/details/gt2aqfjcxxe.html

find . -name "*.tmp" -delete
来源：http://dali.cashguo.top/Article/details/gt2lzskojli.html

[R46] 递归替换文件内容
来源：http://dali.daria6918.cn/Article/details/gt2fqwxsdco.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gt2bahmtjhb.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gt2hfzjeven.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuxming.cn/Article/details/gt2onzcwrry.html

[R48] awk 取指定列
来源：http://dali.iojbl.cn/Article/details/gt2phnqigtg.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2sfdyrqox.html

[R49] awk 带条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ydkwtqsq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.smart0.xyz/Article/details/gt2jnrsrysv.html

[R50] awk 求和
来源：http://dali.iojbl.cn/Article/details/gt2esacjcdy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2amrqicpo.html

[R51] 排序去重取前几
来源：http://dali.yueranfly.top/Article/details/gt2vtdamjcg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gt2lujimjyz.html

[R52] 统计行数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ngwejffv.html

wc -l a.txt
来源：http://dali.tian-w.cn/Article/details/gt2azghjyhe.html

[R53] 查看文件头与实时尾
来源：http://dali.daria6918.cn/Article/details/gt2jjxvpuyu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gt2fhdzcxnp.html

[R54] 比较两个文件
来源：http://dali.hysaishi.cn/Article/details/gt2bjpousca.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gt2yixenerk.html

[R55] 压缩与解压
来源：http://dali.andypj.xyz/Article/details/gt2tcxrvwjn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hgzhegaw.html

[R56] 远程拷贝
来源：http://dali.gaohongyu789.top/Article/details/gt2iblbdlqj.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gt2oanomyer.html

[R57] 远程执行命令
来源：http://dali.gotoacloud.top/Article/details/gt2zrtrmdzr.html

ssh user@host 'uptime'
来源：http://dali.yvedp.cn/Article/details/gt2eqqdycif.html

[R58] 下载文件
来源：http://dali.dashuyun.cn/Article/details/gt2xqzwtode.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pengpengdd.cyou/Article/details/gt2lfmbckeh.html

[R59] 发 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgkuudhp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sgnezncj.html

[R60] 只看 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gt2zwbnufjp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hammf.cn/Article/details/gt2ajtlagos.html

[R61] 磁盘占用
来源：http://dali.haohaochexian.top/Article/details/gt2dafkfemt.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gt2wqyyctrm.html

[R62] 找最占空间的文件
来源：http://dali.shzxlz.cn/Article/details/gt2qkrxoydq.html

du -ah . | sort -rh | head -10
来源：http://dali.tanke756.top/Article/details/gt2odciussm.html

[R63] 内存与进程
来源：http://dali.fengsongda.top/Article/details/gt2gqfumnzf.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gt2stvbrifo.html

[R64] 结束进程
来源：http://dali.daria6918.cn/Article/details/gt2igcrnpzc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.haohaochexian.top/Article/details/gt2kdpjvmqp.html

[R65] 查看端口占用
来源：http://dali.sweek.top/Article/details/gt2ihlicyev.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gt2xxlnbquk.html

[R66] 定时任务
来源：http://dali.cucudq.cn/Article/details/gt2dascroug.html

crontab -e;  crontab -l
来源：http://dali.tianlin.xyz/Article/details/gt2atakjxke.html

[R67] 生成随机十六进制串
来源：http://dali.meibo888.top/Article/details/gt2jqflusaa.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gt2cbexihay.html

[R68] 计算文件校验值
来源：http://dali.nanxuanxn.top/Article/details/gt2fksfcxlj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2ybztvayz.html

[R69] 生成随机密码
来源：http://dali.yuanzhike.top/Article/details/gt2oqclbiyv.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gt2admkkzgz.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2kjymrwcd.html

date +%s;  date -d @1700000000
来源：http://dali.svipenyu.cn/Article/details/gt2jkccmjor.html

[R71] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gt2xfujdqop.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tian-w.cn/Article/details/gt2btqpuoqs.html

[R72] 等待端口就绪
来源：http://dali.ehwqpu.com/Article/details/gt2wrrpsnsa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gt2dtsinlku.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gt2iouidiac.html

split -l 1000 big.log part_
来源：http://dali.hywenlv.cn/Article/details/gt2tpjcpxkk.html

[R74] 批量重命名
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zcczfful.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tanke756.top/Article/details/gt2lccjibfd.html

[R75] 导出环境变量
来源：http://dali.yangfankeji.com/Article/details/gt2yujteqyf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.c1oappe.top/Article/details/gt2drrsjgja.html

[R76] 使用临时文件
来源：http://dali.zhongyouzk.top/Article/details/gt2lcsvcpoc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gt2lfuqtkbr.html

[R77] 读取用户输入
来源：http://dali.daria6918.cn/Article/details/gt2bsymggzh.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gt2lvhische.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gt2ywulwlza.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hfpthk.cn/Article/details/gt2ptgaxecf.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckzabjah.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aibaodan.cn/Article/details/gt2zdeyxwng.html

[R80] 查看脚本执行耗时
来源：http://dali.zhiwuduotai.top/Article/details/gt2qibxcitr.html

time ./run.sh
来源：http://dali.birdmap.top/Article/details/gt2azuzgmmq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2bjrczvar.html

S. C / C++ 专题
来源：http://dali.xylfe.cn/Article/details/gt2knmkzahf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2icphlihk.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2lvsocmlo.html

#include <stdio.h>
来源：http://dali.sysykeji.top/Article/details/gt2cmyzikui.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuxming.cn/Article/details/gt2ytewkduk.html

[S02] C：变量与格式化输出
来源：http://dali.yangfankeji.com/Article/details/gt2vhqaidfs.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gt2ivglrphc.html

[S03] C：读入整数
来源：http://dali.jinqigfzy.top/Article/details/gt2ropfrtro.html

int x; scanf("%d", &x);
来源：http://dali.jinqigfzy.top/Article/details/gt2iietnlty.html

[S04] C：字符串复制
来源：http://dali.cheryme.top/Article/details/gt2ychltafh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.vqdsnc.cn/Article/details/gt2afaepiwz.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kxtzpbkl.html

strlen(s)
来源：http://dali.ehwqpu.com/Article/details/gt2itqwsrzm.html

[S06] C：字符串比较
来源：http://dali.xylfe.cn/Article/details/gt2jmdmvviq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbqwjnj.html

[S07] C：数组遍历求和
来源：http://dali.xylfe.cn/Article/details/gt2nqgawpvo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gotoacloud.top/Article/details/gt2jzzfxsvl.html

[S08] C：动态内存分配与释放
来源：http://dali.iojbl.cn/Article/details/gt2uzpfqxum.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gt2dtrcswok.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gt2lbnmibyn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhongyouzk.top/Article/details/gt2gzrieowu.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gt2wkhomscg.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ixdpxlca.html

[S11] C：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gt2ssbhxmav.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gaohongyu789.top/Article/details/gt2gujrnlgp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sysykeji.top/Article/details/gt2geezdlrk.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gt2yjdatxib.html

[S12] C：写文件
来源：http://dali.tianlin.xyz/Article/details/gt2auwytwyf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gt2lieeesnn.html

[S13] C：宏定义
来源：http://dali.dianchejie.cn/Article/details/gt2lhwkrdyp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhixingplan.top/Article/details/gt2zxgqtgpa.html

[S14] C：枚举
来源：http://dali.ybcxt.top/Article/details/gt2pawjexbj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guowangkeji.top/Article/details/gt2qwdubjud.html

[S15] C：类型转换
来源：http://dali.hnqzz.top/Article/details/gt2axzekwpm.html

(double) a / b
来源：http://dali.yonumen.top/Article/details/gt2fmavpbvu.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gt2dzxjpxea.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2zvljlxrp.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yncenvcz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gt2uijjawjy.html

[S18] C：命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gt2byvzzemm.html

int main(int argc, char **argv)
来源：http://dali.cashguo.top/Article/details/gt2exvykkmg.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gt2yspdtlfp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ghwsyvbu.html

[S20] C：二分查找
来源：http://dali.mhx1999.top/Article/details/gt2uqqxkkmu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gt2pzhazaev.html

[S21] C：字符类别判断
来源：http://dali.meibo888.top/Article/details/gt2metpqdqc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbmwwgsr.html

[S22] C：字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gt2mfybgvgl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangdashe.top/Article/details/gt2gfitjuzm.html

[S23] C：随机数
来源：http://dali.jyoumei.cn/Article/details/gt2aohgarzo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yvedp.cn/Article/details/gt2yurlnmjt.html

[S24] C：获取本地时间
来源：http://dali.c1oappe.top/Article/details/gt2mifoawqp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ppjwa.cn/Article/details/gt2yhswvtiq.html

[S25] C：内存拷贝
来源：http://dali.chenzaomai.com/Article/details/gt2gcocaebb.html

memcpy(dst, src, n);
来源：http://dali.svipenyu.cn/Article/details/gt2lfswyjzo.html

[S26] C：内存清零
来源：http://dali.pengpengdd.cyou/Article/details/gt2evcilbld.html

memset(a, 0, sizeof a);
来源：http://dali.cqqwz.cn/Article/details/gt2nqlapzny.html

[S27] C：定义常量
来源：http://dali.jinqigfzy.top/Article/details/gt2gyiionro.html

const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2ejggwuxj.html

[S28] C：静态变量
来源：http://dali.jqgufenzy.top/Article/details/gt2nnvsowbv.html

static int counter = 0;
来源：http://dali.shangyingyoupin.top/Article/details/gt2sywnsikb.html

[S29] C：变参函数
来源：http://dali.hywenlv.cn/Article/details/gt2uxgncnsq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gt2jdwyzapw.html

[S30] C：头文件保护
来源：http://dali.fengsongda.top/Article/details/gt2gqtlulpx.html

#ifndef X_H
来源：http://dali.yuanzhike.top/Article/details/gt2lecemtiq.html

#define X_H
来源：http://dali.hnxiangtu.top/Article/details/gt2hefbbcpr.html

#endif
来源：http://dali.zhoulong.xyz/Article/details/gt2yltbvzhx.html

[S31] C++：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2eyleyhgy.html

#include <iostream>
来源：http://dali.xylfe.cn/Article/details/gt2vatnyjom.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenzaomai.com/Article/details/gt2hwzjguxv.html

[S32] C++：字符串
来源：http://dali.cucudq.cn/Article/details/gt2xmlzispa.html

std::string s = "hi";  s += "!";
来源：http://dali.aibaodan.cn/Article/details/gt2onvotfpt.html

[S33] C++：vector 增删
来源：http://dali.hnqzz.top/Article/details/gt2qupnnald.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2gnmgdjaz.html

[S34] C++：遍历 vector
来源：http://dali.snrcjt.cn/Article/details/gt2kdotntxr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daria6918.cn/Article/details/gt2glenblhn.html

[S35] C++：map
来源：http://dali.yangfankeji.com/Article/details/gt2fpmvkckk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2efrcfqrw.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycrsbhql.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2eeciigzy.html

[S37] C++：set
来源：http://dali.jinqigufen.top/Article/details/gt2eazjfieg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hkcmqvqg.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gt2wamtxpvc.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gt2faqnymiy.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gt2tqmsivdw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tanke756.top/Article/details/gt2gpmalktm.html

[S40] C++：查找元素
来源：http://dali.guannengcc.top/Article/details/gt2limjgomm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gt2istwzvkj.html

[S41] C++：类与构造函数
来源：http://dali.yj20258.top/Article/details/gt2sxxoceyv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jlsjyb.cn/Article/details/gt2wzelrare.html

[S42] C++：继承与虚函数
来源：http://dali.chenlongwang.top/Article/details/gt2nztcdfrw.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gt2wxthbmmb.html

[S43] C++：智能指针
来源：http://dali.quarkkingdee.top/Article/details/gt2zyawkyyn.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gt2lduqzygk.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gt2clmcwmdy.html

void inc(int &x) { ++x; }
来源：http://dali.yonumen.top/Article/details/gt2jersubot.html

[S45] C++：lambda
来源：http://dali.sufxvd.cn/Article/details/gt2uqopyfbv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gt2qriqqiwi.html

[S46] C++：函数模板
来源：http://dali.gotoacloud.top/Article/details/gt2alndnxpa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cqqwz.cn/Article/details/gt2kiormlua.html

[S47] C++：结构化绑定遍历
来源：http://dali.c1oappe.top/Article/details/gt2ftjddato.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghairire.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2qiwikvvp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hfpthk.cn/Article/details/gt2dlbteaig.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gt2umyuggcm.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gt2zpxgnfye.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gt2eiapscpt.html

[S50] C++：格式化数字
来源：http://dali.daria6918.cn/Article/details/gt2yagcycmc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gt2duuaeymy.html

[S51] C++：显式类型转换
来源：http://dali.jinqigufen.top/Article/details/gt2ghkuzcoh.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gt2ndxhayqu.html

[S52] C++：const 与 noexcept
来源：http://dali.shangyingyoupin.top/Article/details/gt2vsuxnwhj.html

int size() const noexcept { return n_; }
来源：http://dali.cqqwz.cn/Article/details/gt2vswyegvt.html

[S53] C++：移动语义
来源：http://dali.jqgufenzy.top/Article/details/gt2ebrhaumf.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigfzy.top/Article/details/gt2mbpwkxow.html

[S54] C++：异常处理
来源：http://dali.ivvv.top/Article/details/gt2mienefbg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guannengcc.top/Article/details/gt2nvddksrd.html

[S55] C++：结构化绑定
来源：http://dali.yueranfly.top/Article/details/gt2axuiyqse.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yueranfly.top/Article/details/gt2aacisodt.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gt2xmxpxxop.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2itqbgtjx.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gt2uegtiiaz.html

constexpr int N = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wriysvod.html

[S58] C++：命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qfkpftlh.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gt2kgkifrsi.html

[S59] C++：静态断言
来源：http://dali.yuanzhike.top/Article/details/gt2uehvqfeh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pquslmad.html

[S60] C++：遍历并删除元素
来源：http://dali.ppjwa.cn/Article/details/gt2jaysxnlx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gotoacloud.top/Article/details/gt2ahxfxhzb.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2tmtiusbm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gzhubu.top/Article/details/gt2xslntapg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2wphfnrja.html

[T01] Kotlin：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2vgmeojng.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2azicnpog.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gt2tusyngbm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gzhubu.top/Article/details/gt2ogikunxu.html


<!-- 参考信息 -->