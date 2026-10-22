代发 wailian999

R. Bash 专题
来源：http://dali.xylfe.cn/Article/details/gt2pkxildfj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2pyjvlcln.html

[R01] shebang 与严格模式
来源：http://dali.jinqigfzy.top/Article/details/gt2pjycnvas.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gt2rdyljdrn.html

set -euo pipefail
来源：http://dali.ybcxt.top/Article/details/gt2rpnpahrq.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gt2vumwqlfl.html

name="Tom"; echo "$name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2coibxnpm.html

[R03] 只读变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqrayglk.html

readonly PI=3.14
来源：http://dali.redwolf501.top/Article/details/gt2rlrabiqj.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gt2qojzzjcj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.bjfxy.top/Article/details/gt2ozysngoa.html

[R05] 参数默认值
来源：http://dali.vqdsnc.cn/Article/details/gt2aqqiwvru.html

name="${1:-default}"
来源：http://dali.cucudq.cn/Article/details/gt2hktiaspr.html

[R06] 判断命令是否存在
来源：http://dali.yuanzhike.top/Article/details/gt2ahdodybl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gt2dlacmtih.html

[R07] if 判断文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mlnesaom.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hysaishi.cn/Article/details/gt2ncdttibk.html

[R08] 数值比较
来源：http://dali.nwbrower.top/Article/details/gt2mrfaewdv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhstquxp.html

[R09] 字符串比较
来源：http://dali.ehwqpu.com/Article/details/gt2wycmjbkf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2vfxdizyz.html

[R10] 正则匹配
来源：http://dali.mhx1999.top/Article/details/gt2lfteapul.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.haohaochexian.top/Article/details/gt2bhqgdtjl.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gt2xqfkmllb.html

case "$1" in
来源：http://dali.hnqzz.top/Article/details/gt2anvnbmwt.html

start) echo "启动" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lgovwjjp.html

stop)  echo "停止" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2uqdfjfsj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzefwug.html

esac
来源：http://dali.zdqjudy.top/Article/details/gt2dpqifwwi.html

[R12] for 遍历文件
来源：http://dali.hysaishi.cn/Article/details/gt2nbghhvic.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2wiuepvun.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2krcpcwvc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gt2bnfzvknu.html

[R14] C 风格 for
来源：http://dali.wangshuangyany.cn/Article/details/gt2bnjiqwox.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2rrrwplhb.html

[R15] while 逐行读文件
来源：http://dali.pycfn.com/Article/details/gt2vstmchir.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gt2nlirvcfr.html

[R16] until 等待条件
来源：http://dali.gzhubu.top/Article/details/gt2kjqogkkf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gt2jssxscjm.html

[R17] 数组定义与取值
来源：http://dali.daxiang520.top/Article/details/gt2wfujimew.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sufxvd.cn/Article/details/gt2hqhkraqs.html

[R18] 遍历数组
来源：http://dali.sysykeji.top/Article/details/gt2jrylmnnz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zycfv.cn/Article/details/gt2zggnwlat.html

[R19] 数组长度
来源：http://dali.ybcxt.top/Article/details/gt2cugadioi.html

echo "${#arr[@]}"
来源：http://dali.haohaochexian.top/Article/details/gt2dogswhvt.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gt2rniiulwx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.kuanghao11.cn/Article/details/gt2eenbhihg.html

[R21] 字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2ucuapvwh.html

echo "${#s}"
来源：http://dali.zhoulong.xyz/Article/details/gt2nibejluw.html

[R22] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gt2cxvemnzd.html

echo "${s:0:5}"
来源：http://dali.jiagoushi.top/Article/details/gt2psieqvwy.html

[R23] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gt2vepytsom.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jiagoushi.top/Article/details/gt2rjsfcyal.html

[R24] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gt2nkmkbykp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjsrxhs.html

[R25] 去后缀 / 去前缀
来源：http://dali.cashguo.top/Article/details/gt2zndgzake.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.quarkkingdee.top/Article/details/gt2szshfspu.html

[R26] 命令替换
来源：http://dali.tanke756.top/Article/details/gt2ewspmmlv.html

now=$(date +%F); echo "$now"
来源：http://dali.yvedp.cn/Article/details/gt2lfowuowt.html

[R27] 算术展开
来源：http://dali.316326.xyz/Article/details/gt2zmfanhuc.html

echo $((1 + 2 * 3))
来源：http://dali.gzhubu.top/Article/details/gt2syevjawr.html

[R28] 浮点运算
来源：http://dali.daria6918.cn/Article/details/gt2xjkgjkgd.html

echo "scale=2; 10/3" | bc
来源：http://dali.gogol.net.cn/Article/details/gt2woynzhfs.html

[R29] 定义函数
来源：http://dali.yueranfly.top/Article/details/gt2rweqbzvk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjgjdwx.html

[R30] 函数返回状态码
来源：http://dali.sysykeji.top/Article/details/gt2gyzlzspd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gt2juosipbu.html

[R31] 局部变量
来源：http://dali.yonumen.top/Article/details/gt2hextutgw.html

f() { local x=1; echo "$x"; }
来源：http://dali.gotoacloud.top/Article/details/gt2wjastoue.html

[R32] 参数个数校验
来源：http://dali.zhengqikj.top/Article/details/gt2locdolel.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gt2upulufjn.html

[R33] 捕获错误并提示行号
来源：http://dali.tianlin.xyz/Article/details/gt2elmitywf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2soquybbm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qladyrux.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2rdvcfcdt.html

[R35] 后台执行并等待
来源：http://dali.zdqjudy.top/Article/details/gt2tskmtbyn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shzxlz.cn/Article/details/gt2allxabxl.html

[R36] 并发执行多个任务
来源：http://dali.bjfxy.top/Article/details/gt2tdyyvhjf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ivvv.top/Article/details/gt2ovbcpypk.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gt2jwtkjlct.html

files=$(ls -1)
来源：http://dali.iojbl.cn/Article/details/gt2hksmmrqh.html

[R38] 管道串联
来源：http://dali.xinyue.icu/Article/details/gt2yadrsuuj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuanzx.com/Article/details/gt2kxjxbufm.html

[R39] 重定向标准输出与错误
来源：http://dali.gzhubu.top/Article/details/gt2cegdhjbe.html

cmd > out.log 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gt2deyjhcif.html

[R40] 追加写日志
来源：http://dali.jqgfzy.top/Article/details/gt2rkpvqkvz.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gt2kiusjwuh.html

[R41] 丢弃输出
来源：http://dali.dianchejie.cn/Article/details/gt2ffrdmzwb.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigufen.top/Article/details/gt2yccomwgp.html

[R42] 输入重定向
来源：http://dali.gzhubu.top/Article/details/gt2kvlnkpit.html

wc -l < a.txt
来源：http://dali.yonumen.top/Article/details/gt2zblxotzc.html

[R43] 按名字查找文件
来源：http://dali.yanxiufei.cn/Article/details/gt2lueomatf.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gt2gyyzncaf.html

[R44] 按修改时间查找
来源：http://dali.tianlin.xyz/Article/details/gt2rfyoekzt.html

find . -mtime -7 -type f
来源：http://dali.nanxuanxn.top/Article/details/gt2atdroalp.html

[R45] 批量删除
来源：http://dali.yueranfly.top/Article/details/gt2gesnnzeg.html

find . -name "*.tmp" -delete
来源：http://dali.pengpengdd.cyou/Article/details/gt2usjncfdn.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sycuptwe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tianlin.xyz/Article/details/gt2efkemnub.html

[R47] sed 单行替换
来源：http://dali.andypj.xyz/Article/details/gt2ojpezhuc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2vxiefjdm.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gt2zijtoyng.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntglridi.html

[R49] awk 带条件
来源：http://dali.kuanghao11.cn/Article/details/gt2bxptgcuy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cdnleiting.top/Article/details/gt2wrlmwjkv.html

[R50] awk 求和
来源：http://dali.shuidangran.top/Article/details/gt2ikfesgvc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2zyfqnlye.html

[R51] 排序去重取前几
来源：http://dali.pycfn.com/Article/details/gt2xieocfmd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gt2vetpmydv.html

[R52] 统计行数
来源：http://dali.9152youxi.cn/Article/details/gt2liuajllw.html

wc -l a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2vdfufdaz.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gt2bfkobltm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ydzc1.top/Article/details/gt2dtggqtty.html

[R54] 比较两个文件
来源：http://dali.shuidangran.top/Article/details/gt2fwbxooby.html

diff a.txt b.txt
来源：http://dali.yueranfly.top/Article/details/gt2ohqhrqcm.html

[R55] 压缩与解压
来源：http://dali.zhongyouzk.top/Article/details/gt2svjkhrkz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yonumen.top/Article/details/gt2nnswirhl.html

[R56] 远程拷贝
来源：http://dali.cqqwz.cn/Article/details/gt2esdujazb.html

scp file user@host:/path/
来源：http://dali.vqdsnc.cn/Article/details/gt2yywfkyqs.html

[R57] 远程执行命令
来源：http://dali.yonumen.top/Article/details/gt2cxdfttky.html

ssh user@host 'uptime'
来源：http://dali.yvedp.cn/Article/details/gt2ygdyhgfk.html

[R58] 下载文件
来源：http://dali.xylfe.cn/Article/details/gt2jeyvyanr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.mhx1999.top/Article/details/gt2tnbkiihc.html

[R59] 发 POST JSON
来源：http://dali.yj202588.top/Article/details/gt2otlcsmkf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sysykeji.top/Article/details/gt2trjmahuc.html

[R60] 只看 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gt2evrgyyto.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gzhubu.top/Article/details/gt2yldiiqjz.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gt2bthsrdap.html

df -h;  du -sh *
来源：http://dali.yonumen.top/Article/details/gt2iwzacxtg.html

[R62] 找最占空间的文件
来源：http://dali.zdqjudy.top/Article/details/gt2wjhmkvtn.html

du -ah . | sort -rh | head -10
来源：http://dali.sweek.top/Article/details/gt2ydpzqwpl.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gt2gpdfjtqx.html

free -h;  ps aux | grep nginx
来源：http://dali.xylfe.cn/Article/details/gt2wsftkigv.html

[R64] 结束进程
来源：http://dali.yj20258888.top/Article/details/gt2clwdczcf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sxryk.cn/Article/details/gt2pwtlmgqt.html

[R65] 查看端口占用
来源：http://dali.iojbl.cn/Article/details/gt2yxtanbbr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangtech.top/Article/details/gt2logagvgu.html

[R66] 定时任务
来源：http://dali.yangfankeji.com/Article/details/gt2qkaahpjx.html

crontab -e;  crontab -l
来源：http://dali.zhongyouzk.top/Article/details/gt2pyavwdyh.html

[R67] 生成随机十六进制串
来源：http://dali.jqgufenzy.top/Article/details/gt2nocwbvyf.html

openssl rand -hex 16
来源：http://dali.iojbl.cn/Article/details/gt2ryuhsoao.html

[R68] 计算文件校验值
来源：http://dali.ppjwa.cn/Article/details/gt2clzltews.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pycfn.com/Article/details/gt2ejfwirao.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gt2sxhgnsrs.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bjvoczhp.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2oiipjrsv.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gt2zthakumo.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gt2gsbhjzzc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gotoacloud.top/Article/details/gt2fxpqbssz.html

[R72] 等待端口就绪
来源：http://dali.yj202588.top/Article/details/gt2vefajwer.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gt2yyrjyfjo.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gt2yeuwaxzf.html

split -l 1000 big.log part_
来源：http://dali.smart0.xyz/Article/details/gt2bkjltkmk.html

[R74] 批量重命名
来源：http://dali.zycfv.cn/Article/details/gt2amuubvpa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258888.top/Article/details/gt2vzcbqzfq.html

[R75] 导出环境变量
来源：http://dali.sxryk.cn/Article/details/gt2qjftmcrq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hfpthk.cn/Article/details/gt2eydghhxk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgpoyvo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gt2aerfwkbu.html

[R77] 读取用户输入
来源：http://dali.aizwys.cn/Article/details/gt2wvswpdjf.html

read -rp "请输入: " ans
来源：http://dali.cucudq.cn/Article/details/gt2bnsetggs.html

[R78] 交互式菜单
来源：http://dali.yongpay.top/Article/details/gt2aslaqtrq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.316326.xyz/Article/details/gt2jtqqcubi.html

[R79] 解析命令行选项
来源：http://dali.yj20258.top/Article/details/gt2frizfoly.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.birdmap.top/Article/details/gt2kvkihfpx.html

[R80] 查看脚本执行耗时
来源：http://dali.gogol.net.cn/Article/details/gt2harjlxwa.html

time ./run.sh
来源：http://dali.sysykeji.top/Article/details/gt2fjkpopik.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2vuuqvzzb.html

S. C / C++ 专题
来源：http://dali.cucudq.cn/Article/details/gt2tzecjekx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2sllfufur.html

[S01] C：Hello World
来源：http://dali.birdmap.top/Article/details/gt2wnmpimwn.html

#include <stdio.h>
来源：http://dali.hywenlv.cn/Article/details/gt2darshcup.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2amilauxq.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2kgtbdzkr.html

int a = 10; printf("%d\n", a);
来源：http://dali.cqqwz.cn/Article/details/gt2xiwzgjxb.html

[S03] C：读入整数
来源：http://dali.yj202588.top/Article/details/gt2apuogxro.html

int x; scanf("%d", &x);
来源：http://dali.vqdsnc.cn/Article/details/gt2tqjqmajk.html

[S04] C：字符串复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgmcbucb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenzaomai.com/Article/details/gt2tlheiopr.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gt2cktllqzj.html

strlen(s)
来源：http://dali.meibo888.top/Article/details/gt2nvffjgdi.html

[S06] C：字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2syildcnz.html

strcmp(a, b) == 0
来源：http://dali.yueranfly.top/Article/details/gt2cwanrzej.html

[S07] C：数组遍历求和
来源：http://dali.aibaodan.cn/Article/details/gt2mhrelgmx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.quarkkingdee.top/Article/details/gt2xqqkybwf.html

[S08] C：动态内存分配与释放
来源：http://dali.kuanghao11.cn/Article/details/gt2kciiiuhw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zdqjudy.top/Article/details/gt2pgaokbyx.html

[S09] C：结构体定义与初始化
来源：http://dali.andypj.xyz/Article/details/gt2igiqznin.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ppjwa.cn/Article/details/gt2shmvzdwx.html

[S10] C：指针与解引用
来源：http://dali.cdnleiting.top/Article/details/gt2nkkbtauw.html

int *p = &a;  *p = 5;
来源：http://dali.xylfe.cn/Article/details/gt2hsscnxvr.html

[S11] C：逐行读文件
来源：http://dali.tanke756.top/Article/details/gt2dyccwcfr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkxisxef.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ehwqpu.com/Article/details/gt2pztaghvs.html

fclose(f);
来源：http://dali.guannengcc.top/Article/details/gt2wcdyfvpg.html

[S12] C：写文件
来源：http://dali.xylfe.cn/Article/details/gt2sqywirsy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vicdwrgt.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gt2qdnxmcha.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shuidangran.top/Article/details/gt2gzmvelzc.html

[S14] C：枚举
来源：http://dali.jyoumei.cn/Article/details/gt2lqwmxkxf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigufen.top/Article/details/gt2xefoprqn.html

[S15] C：类型转换
来源：http://dali.jqgfzy.top/Article/details/gt2xwjhloln.html

(double) a / b
来源：http://dali.sysykeji.top/Article/details/gt2zatlszeq.html

[S16] C：位操作置位
来源：http://dali.mhx1999.top/Article/details/gt2idbmktrs.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gt2wqcvmxhz.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gt2zrzdtoky.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangshuangyany.cn/Article/details/gt2eghubfwc.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gt2xinsypuy.html

int main(int argc, char **argv)
来源：http://dali.nanxinkj.top/Article/details/gt2ktglcjuq.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gt2cncaorvj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2cmkvbaav.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gt2ovueszsu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gt2dehsxwzt.html

[S21] C：字符类别判断
来源：http://dali.zycfv.cn/Article/details/gt2cpgildzq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuanzx.com/Article/details/gt2irztjyoa.html

[S22] C：字符串转数字
来源：http://dali.havefunace.top/Article/details/gt2qmkoapnh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangshuangyany.cn/Article/details/gt2smlyhupj.html

[S23] C：随机数
来源：http://dali.0kj1m.cn/Article/details/gt2ebzjqpjj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guowangkeji.top/Article/details/gt2pexwysin.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2uihbzodn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.redwolf501.top/Article/details/gt2xhjyoaod.html

[S25] C：内存拷贝
来源：http://dali.tanke756.top/Article/details/gt2nfahbgbd.html

memcpy(dst, src, n);
来源：http://dali.316326.xyz/Article/details/gt2pwyuifnj.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gt2iihjbhjr.html

memset(a, 0, sizeof a);
来源：http://dali.nwbrower.top/Article/details/gt2nkhcgpjw.html

[S27] C：定义常量
来源：http://dali.316326.xyz/Article/details/gt2fjowpnfs.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2odrnmoym.html

[S28] C：静态变量
来源：http://dali.ybcxt.top/Article/details/gt2urditgsb.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gt2luogsruo.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gt2gvoezzab.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daria6918.cn/Article/details/gt2avihurum.html

[S30] C：头文件保护
来源：http://dali.yanxiufei.cn/Article/details/gt2zmnldncz.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gt2qdkuibzp.html

#define X_H
来源：http://dali.yanxiufei.cn/Article/details/gt2xxyicgmk.html

#endif
来源：http://dali.ydzc1.top/Article/details/gt2lcdidryk.html

[S31] C++：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2yoytfols.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gt2nkkztkjh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cucudq.cn/Article/details/gt2adpbgjmx.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xnsrlkin.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gt2dmkgdxsk.html

[S33] C++：vector 增删
来源：http://dali.cheryme.top/Article/details/gt2yzwfmjey.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nwbrower.top/Article/details/gt2phaolupl.html

[S34] C++：遍历 vector
来源：http://dali.pengpengdd.cyou/Article/details/gt2pgicrtmv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yofbbddw.html

[S35] C++：map
来源：http://dali.cheryme.top/Article/details/gt2hhdodlww.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2pjzaxvcw.html

[S36] C++：unordered_map
来源：http://dali.cqqwz.cn/Article/details/gt2hzhkaibe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2iylrkpqt.html

[S37] C++：set
来源：http://dali.yuanzhike.top/Article/details/gt2zwweaoor.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gt2nrywmvyr.html

[S38] C++：排序
来源：http://dali.xylfe.cn/Article/details/gt2hvppcesx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gt2qpjtdhyp.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gt2kvmvexsq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gt2yqfpudxy.html

[S40] C++：查找元素
来源：http://dali.meibo888.top/Article/details/gt2sqjhbmvv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.svipenyu.cn/Article/details/gt2mxewyjzp.html

[S41] C++：类与构造函数
来源：http://dali.quarkkingdee.top/Article/details/gt2sfyeglsu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gt2ulvoqbvh.html

[S42] C++：继承与虚函数
来源：http://dali.ybcxt.top/Article/details/gt2xascbybh.html

class B : public Base { public: void f() override {} };
来源：http://dali.ybcxt.top/Article/details/gt2wavrkpbb.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gt2btplcyyj.html

auto p = std::make_unique<int>(5);
来源：http://dali.nwbrower.top/Article/details/gt2ykutkfjl.html

[S44] C++：引用传参
来源：http://dali.yj20258.top/Article/details/gt2etfkvctl.html

void inc(int &x) { ++x; }
来源：http://dali.yangfankeji.com/Article/details/gt2dyqyqbxu.html

[S45] C++：lambda
来源：http://dali.zhiwuduotai.top/Article/details/gt2byhuyntt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jlsjyb.cn/Article/details/gt2mlzuuxpc.html

[S46] C++：函数模板
来源：http://dali.chenzaomai.com/Article/details/gt2lvxhwfkc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gotoacloud.top/Article/details/gt2nioanwty.html

[S47] C++：结构化绑定遍历
来源：http://dali.daxiang520.top/Article/details/gt2tshfugwe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhengqikj.top/Article/details/gt2crgydckq.html

[S48] C++：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2ynlxztcn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.c1oappe.top/Article/details/gt2gqjxiyki.html

while (std::getline(in, line)) { }
来源：http://dali.cucudq.cn/Article/details/gt2xstjjspj.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gt2qtazymdi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dashuyun.cn/Article/details/gt2xybbklwd.html

[S50] C++：格式化数字
来源：http://dali.xziqi.cn/Article/details/gt2rcnynsym.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2jxgfklbw.html

[S51] C++：显式类型转换
来源：http://dali.gotoacloud.top/Article/details/gt2cqasbvub.html

static_cast<double>(a) / b
来源：http://dali.sufxvd.cn/Article/details/gt2vorfugzx.html

[S52] C++：const 与 noexcept
来源：http://dali.hammf.cn/Article/details/gt2rxpbbuss.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gt2klkynjel.html

[S53] C++：移动语义
来源：http://dali.xinyue.icu/Article/details/gt2tfmxnszj.html

std::vector<int> w = std::move(v);
来源：http://dali.316326.xyz/Article/details/gt2wgvobjru.html

[S54] C++：异常处理
来源：http://dali.nanxuanxn.top/Article/details/gt2psmcqhtv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtsladvb.html

[S55] C++：结构化绑定
来源：http://dali.jiagoushi.top/Article/details/gt2woolujjh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.316326.xyz/Article/details/gt2fcroebvn.html

[S56] C++：optional
来源：http://dali.yueranfly.top/Article/details/gt2yskjyzxh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jyoumei.cn/Article/details/gt2ojhmvseq.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jonfjjiw.html

constexpr int N = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2zutzsdtv.html

[S58] C++：命名空间
来源：http://dali.daria6918.cn/Article/details/gt2jqokbchv.html

namespace ns { int f() { return 1; } }
来源：http://dali.yonumen.top/Article/details/gt2hvxvopgv.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wzxsnkou.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhengqikj.top/Article/details/gt2marmbvzi.html

[S60] C++：遍历并删除元素
来源：http://dali.fzhhl.top/Article/details/gt2vnthoafs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqxddzx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tdqwdlgn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gt2negypcmy.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2rzycffwo.html


<!-- 参考信息 -->