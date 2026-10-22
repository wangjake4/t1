代发 wailian999

R. Bash 专题
来源：http://dali.9152youxi.cn/Article/details/gt2otvcxygj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2whbmflds.html

[R01] shebang 与严格模式
来源：http://dali.vqdsnc.cn/Article/details/gt2bwsocatq.html

#!/usr/bin/env bash
来源：http://dali.yj202588.top/Article/details/gt2qvppunkl.html

set -euo pipefail
来源：http://dali.jianghu66.top/Article/details/gt2gwzpegwd.html

[R02] 变量赋值与使用
来源：http://dali.hongshengwenyu.top/Article/details/gt2uveterjp.html

name="Tom"; echo "$name"
来源：http://dali.iojbl.cn/Article/details/gt2poyeotxy.html

[R03] 只读变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zxdmnlpa.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gt2uwwzuivt.html

[R04] 位置参数
来源：http://dali.sxryk.cn/Article/details/gt2yrogxeib.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nwbrower.top/Article/details/gt2pcvpsmdh.html

[R05] 参数默认值
来源：http://dali.hywenlv.cn/Article/details/gt2mubpsifi.html

name="${1:-default}"
来源：http://dali.316326.xyz/Article/details/gt2tsvswldk.html

[R06] 判断命令是否存在
来源：http://dali.zhoulong.xyz/Article/details/gt2jpvhwbbq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aqegcckj.html

[R07] if 判断文件
来源：http://dali.yongpay.top/Article/details/gt2nxmfegqk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yanxiufei.cn/Article/details/gt2yisaazbu.html

[R08] 数值比较
来源：http://dali.zycfv.cn/Article/details/gt2tbagidxj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2amsoxjpn.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2aqsklmrw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gt2rzgwrsvo.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2njvrhsyz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.mhx1999.top/Article/details/gt2skcyhasc.html

[R11] case 多分支
来源：http://dali.dianchejie.cn/Article/details/gt2ygaoncnr.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gt2dpfrlsub.html

start) echo "启动" ;;
来源：http://dali.yuxming.cn/Article/details/gt2ipsbfdns.html

stop)  echo "停止" ;;
来源：http://dali.daxiang520.top/Article/details/gt2dohnbfge.html

*)     echo "未知命令" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2cjyochko.html

esac
来源：http://dali.ivvv.top/Article/details/gt2bqnydgfa.html

[R12] for 遍历文件
来源：http://dali.jinqigufen.top/Article/details/gt2mwhiqoxz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gt2fvekgwww.html

[R13] for 计数循环
来源：http://dali.hysaishi.cn/Article/details/gt2wrlhrfrz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gt2jmcjrcqo.html

[R14] C 风格 for
来源：http://dali.cucudq.cn/Article/details/gt2gfzfwuwe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gt2tpcjhork.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2cszbpqku.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2jdlfyqys.html

[R16] until 等待条件
来源：http://dali.hnqzz.top/Article/details/gt2truiisha.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gt2bzrdftni.html

[R17] 数组定义与取值
来源：http://dali.meibo888.top/Article/details/gt2iwecaexn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hammf.cn/Article/details/gt2fagdwmaz.html

[R18] 遍历数组
来源：http://dali.svipenyu.cn/Article/details/gt2somsfvjp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yonumen.top/Article/details/gt2ofseudpd.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gt2czskoyps.html

echo "${#arr[@]}"
来源：http://dali.yueranfly.top/Article/details/gt2ehmcjpsw.html

[R20] 关联数组（字典）
来源：http://dali.jqgfzy.top/Article/details/gt2owfghqpp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ajaodunn.html

[R21] 字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2nahkmnln.html

echo "${#s}"
来源：http://dali.xuanzx.com/Article/details/gt2ykridfeu.html

[R22] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gt2vqdackzn.html

echo "${s:0:5}"
来源：http://dali.wangdashe.top/Article/details/gt2cdtdwpgh.html

[R23] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jdssoalm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jlsjyb.cn/Article/details/gt2uhhtkzdr.html

[R24] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gt2xspbenrw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gt2jvfmnuac.html

[R25] 去后缀 / 去前缀
来源：http://dali.tian-w.cn/Article/details/gt2bnizjiuh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258888.top/Article/details/gt2sjldbpkj.html

[R26] 命令替换
来源：http://dali.zhixingplan.top/Article/details/gt2wjhccvjt.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kugyntvv.html

[R27] 算术展开
来源：http://dali.yj20258888.top/Article/details/gt2rpexzxjy.html

echo $((1 + 2 * 3))
来源：http://dali.hongshengwenyu.top/Article/details/gt2mtcwtyle.html

[R28] 浮点运算
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wrdxzwza.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenlongwang.top/Article/details/gt2ktlpqhcx.html

[R29] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xjezpofv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zycfv.cn/Article/details/gt2bkmxcflj.html

[R30] 函数返回状态码
来源：http://dali.hnqzz.top/Article/details/gt2pavcmbjz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yongpay.top/Article/details/gt2bbhgxlix.html

[R31] 局部变量
来源：http://dali.yuxming.cn/Article/details/gt2txfrguxg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2xrsxqcre.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gt2lugjqsuq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2glquguse.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258.top/Article/details/gt2hghalerb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gt2dtetxhgu.html

[R34] 退出时清理
来源：http://dali.zhengqikj.top/Article/details/gt2liirdgnt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gt2jgswxuwt.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gt2wtorhgat.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jiagoushi.top/Article/details/gt2ckruspfq.html

[R36] 并发执行多个任务
来源：http://dali.hnqzz.top/Article/details/gt2clxhpkyv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gt2egzlkafw.html

[R37] 把输出赋给变量
来源：http://dali.snrcjt.cn/Article/details/gt2knmkrlqw.html

files=$(ls -1)
来源：http://dali.fzhhl.top/Article/details/gt2erqrgsuq.html

[R38] 管道串联
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojpqdhqn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gt2dbsdzagj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhoulong.xyz/Article/details/gt2oiknzita.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gt2pqvapdww.html

[R40] 追加写日志
来源：http://dali.yj20258.top/Article/details/gt2dvmyqhvv.html

echo "log" >> out.log
来源：http://dali.hnxiangtu.top/Article/details/gt2bwlopwcs.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eloypmfi.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gt2hhylfrce.html

[R42] 输入重定向
来源：http://dali.shzxlz.cn/Article/details/gt2onaqtoqs.html

wc -l < a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2bclkmegb.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gt2yvfhetpd.html

find . -name "*.log" -type f
来源：http://dali.jianghu66.top/Article/details/gt2jvyurkdb.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangtech.top/Article/details/gt2obgsbqmz.html

find . -mtime -7 -type f
来源：http://dali.andypj.xyz/Article/details/gt2ckxzyslt.html

[R45] 批量删除
来源：http://dali.iojbl.cn/Article/details/gt2ovjucqqa.html

find . -name "*.tmp" -delete
来源：http://dali.9152youxi.cn/Article/details/gt2tklvkzlx.html

[R46] 递归替换文件内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nccronlr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sufxvd.cn/Article/details/gt2xbyicopf.html

[R47] sed 单行替换
来源：http://dali.gzhubu.top/Article/details/gt2kcxnnahi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2uyocrgdr.html

[R48] awk 取指定列
来源：http://dali.gzhubu.top/Article/details/gt2qpgtbsov.html

awk '{print $1, $3}' a.txt
来源：http://dali.fzhhl.top/Article/details/gt2xpyliqeo.html

[R49] awk 带条件
来源：http://dali.dashuyun.cn/Article/details/gt2kdibdnms.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hammf.cn/Article/details/gt2welkwato.html

[R50] awk 求和
来源：http://dali.jqgufenzy.top/Article/details/gt2mshgiytp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cashguo.top/Article/details/gt2gwmhgvjf.html

[R51] 排序去重取前几
来源：http://dali.gzhubu.top/Article/details/gt2ewgureoa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gt2eawyhizx.html

[R52] 统计行数
来源：http://dali.hywenlv.cn/Article/details/gt2zckvwyiw.html

wc -l a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2ojrcddoy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrfldwao.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gt2mczczift.html

[R54] 比较两个文件
来源：http://dali.yanxiufei.cn/Article/details/gt2citejusz.html

diff a.txt b.txt
来源：http://dali.yuanzhike.top/Article/details/gt2uozlciln.html

[R55] 压缩与解压
来源：http://dali.nwbrower.top/Article/details/gt2bkvjwmbz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhixingplan.top/Article/details/gt2bsehrnpl.html

[R56] 远程拷贝
来源：http://dali.0kj1m.cn/Article/details/gt2izwfkytl.html

scp file user@host:/path/
来源：http://dali.yvedp.cn/Article/details/gt2ukqangca.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gt2umkcwrih.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jobavjvm.html

[R58] 下载文件
来源：http://dali.birdmap.top/Article/details/gt2gaxogmew.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gt2jchpdwxa.html

[R59] 发 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gt2unzbfwru.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenzaomai.com/Article/details/gt2zqfjvwgp.html

[R60] 只看 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gt2orbofcht.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuanzhike.top/Article/details/gt2vyqekgct.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gt2zxdbmxda.html

df -h;  du -sh *
来源：http://dali.shuidangran.top/Article/details/gt2gujwjfne.html

[R62] 找最占空间的文件
来源：http://dali.yuanzhike.top/Article/details/gt2cnumniqs.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxuanxn.top/Article/details/gt2yihtooys.html

[R63] 内存与进程
来源：http://dali.cucudq.cn/Article/details/gt2jfldxdpn.html

free -h;  ps aux | grep nginx
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2metzuxtu.html

[R64] 结束进程
来源：http://dali.316326.xyz/Article/details/gt2gjovlgwa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnxiangtu.top/Article/details/gt2dqwlbgtj.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gt2zqvfonpt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.snrcjt.cn/Article/details/gt2rpkkzaoy.html

[R66] 定时任务
来源：http://dali.yuanzhike.top/Article/details/gt2ixuersej.html

crontab -e;  crontab -l
来源：http://dali.wangdashe.top/Article/details/gt2lhdsmzce.html

[R67] 生成随机十六进制串
来源：http://dali.svipenyu.cn/Article/details/gt2lxqvwsop.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gt2evxxzuxf.html

[R68] 计算文件校验值
来源：http://dali.jqgufenzy.top/Article/details/gt2khyjxqvb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2yoozhvel.html

[R69] 生成随机密码
来源：http://dali.xuanzx.com/Article/details/gt2fktlikrw.html

head -c 16 /dev/urandom | base64
来源：http://dali.redwolf501.top/Article/details/gt2xtzyfkzm.html

[R70] 时间戳与互转
来源：http://dali.yanxiufei.cn/Article/details/gt2yqjqbvzs.html

date +%s;  date -d @1700000000
来源：http://dali.shuidangran.top/Article/details/gt2spjayemr.html

[R71] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wyyursht.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hywenlv.cn/Article/details/gt2bwweflcm.html

[R72] 等待端口就绪
来源：http://dali.sweek.top/Article/details/gt2jgcllpig.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gt2qptvmeyo.html

[R73] 分割大日志
来源：http://dali.ydzc1.top/Article/details/gt2xnmmkpuw.html

split -l 1000 big.log part_
来源：http://dali.fengsongda.top/Article/details/gt2qmnmyskg.html

[R74] 批量重命名
来源：http://dali.xuanzx.com/Article/details/gt2wmrzvzhz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2znjjenja.html

[R75] 导出环境变量
来源：http://dali.zhengqikj.top/Article/details/gt2tqhpnoak.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hfpthk.cn/Article/details/gt2sijbwwcn.html

[R76] 使用临时文件
来源：http://dali.cucudq.cn/Article/details/gt2uspakfrv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zwwnqepy.html

[R77] 读取用户输入
来源：http://dali.tanke756.top/Article/details/gt2gqnpmgxa.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gt2vcxukqiy.html

[R78] 交互式菜单
来源：http://dali.yongpay.top/Article/details/gt2yfnrxlar.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.mhx1999.top/Article/details/gt2wwqqkqsq.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gt2epvbdpbf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2grcukefa.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ocohtrsf.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gt2zsmbetap.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2jberpied.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqilgwm.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2qtoltgzu.html

[S01] C：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2jbbnyhub.html

#include <stdio.h>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yhbcesao.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.redwolf501.top/Article/details/gt2zvhsxyur.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2brbbfthx.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gt2tgvgkkwt.html

[S03] C：读入整数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mivwljmu.html

int x; scanf("%d", &x);
来源：http://dali.0kj1m.cn/Article/details/gt2wfwvvoun.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gt2ginhiyit.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbmhpexh.html

[S05] C：字符串长度
来源：http://dali.daria6918.cn/Article/details/gt2lyxscqia.html

strlen(s)
来源：http://dali.c1oappe.top/Article/details/gt2iszgsxna.html

[S06] C：字符串比较
来源：http://dali.xinyue.icu/Article/details/gt2foucbwhg.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gt2ypdktois.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gt2ksqoqjci.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.birdmap.top/Article/details/gt2vwqwdynz.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gt2zitpegzf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangdashe.top/Article/details/gt2orybdmlj.html

[S09] C：结构体定义与初始化
来源：http://dali.fengsongda.top/Article/details/gt2dxfzcvbh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hywenlv.cn/Article/details/gt2vxabcqoa.html

[S10] C：指针与解引用
来源：http://dali.jlsjyb.cn/Article/details/gt2ccvftnnd.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gt2vrjzoqyh.html

[S11] C：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gt2ytaemace.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangshuangyany.cn/Article/details/gt2odzgzkdi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.316326.xyz/Article/details/gt2oonixeaj.html

fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gt2wakafoil.html

[S12] C：写文件
来源：http://dali.zhixingplan.top/Article/details/gt2qpgpbxwz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gt2rgyohcuz.html

[S13] C：宏定义
来源：http://dali.sysykeji.top/Article/details/gt2crguavvz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ivvv.top/Article/details/gt2hwcavytb.html

[S14] C：枚举
来源：http://dali.jqgfzy.top/Article/details/gt2bctndedr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gt2djtlxzqm.html

[S15] C：类型转换
来源：http://dali.hnqzz.top/Article/details/gt2cfsemohr.html

(double) a / b
来源：http://dali.hywenlv.cn/Article/details/gt2ubsrpugr.html

[S16] C：位操作置位
来源：http://dali.chenzaomai.com/Article/details/gt2wzrluliv.html

x |= (1 << 3);
来源：http://dali.guowangkeji.top/Article/details/gt2nucsxsmh.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2svjwezrc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gt2lbyftcen.html

[S18] C：命令行参数
来源：http://dali.sweek.top/Article/details/gt2xxxqptsz.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gt2zmsvfqqn.html

[S19] C：快速排序
来源：http://dali.hfpthk.cn/Article/details/gt2qfmoxvxj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gt2mgvadcxg.html

[S20] C：二分查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xthwqeyn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jdgpmioy.html

[S21] C：字符类别判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jyijxokx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.havefunace.top/Article/details/gt2ratjeedn.html

[S22] C：字符串转数字
来源：http://dali.yuanzhike.top/Article/details/gt2lwyprejd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gt2dbjwemxm.html

[S23] C：随机数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2avdljtxg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gt2cfmsvqbf.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gt2kbcqultr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gt2wdtqcibl.html

[S25] C：内存拷贝
来源：http://dali.xziqi.cn/Article/details/gt2ekhbbznh.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gt2xhywtzpq.html

[S26] C：内存清零
来源：http://dali.yangfankeji.com/Article/details/gt2ntrowrau.html

memset(a, 0, sizeof a);
来源：http://dali.iojbl.cn/Article/details/gt2nrociudn.html

[S27] C：定义常量
来源：http://dali.haohaochexian.top/Article/details/gt2oygqpphr.html

const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ernumiwb.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gt2ooaxnewj.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gt2vsnusdxp.html

[S29] C：变参函数
来源：http://dali.birdmap.top/Article/details/gt2qnrvdadd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zdqjudy.top/Article/details/gt2sorbtnws.html

[S30] C：头文件保护
来源：http://dali.jinqigfzy.top/Article/details/gt2njcorioc.html

#ifndef X_H
来源：http://dali.fzhhl.top/Article/details/gt2ardycvvp.html

#define X_H
来源：http://dali.yj202588.top/Article/details/gt2kfgnsobh.html

#endif
来源：http://dali.hnxiangtu.top/Article/details/gt2abmdojqn.html

[S31] C++：Hello World
来源：http://dali.yonumen.top/Article/details/gt2ozsmswbi.html

#include <iostream>
来源：http://dali.gaohongyu789.top/Article/details/gt2ontnxabe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.meibo888.top/Article/details/gt2cxyavpsi.html

[S32] C++：字符串
来源：http://dali.jyoumei.cn/Article/details/gt2vccexaew.html

std::string s = "hi";  s += "!";
来源：http://dali.yangfankeji.com/Article/details/gt2xbapgpmf.html

[S33] C++：vector 增删
来源：http://dali.shuidangran.top/Article/details/gt2htuvyqnm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ehwqpu.com/Article/details/gt2bfjjjxjc.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gt2ygkkywid.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dianchejie.cn/Article/details/gt2mehmpvww.html

[S35] C++：map
来源：http://dali.shuidangran.top/Article/details/gt2ucchjmsg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gt2mxpqmikh.html

[S36] C++：unordered_map
来源：http://dali.yueranfly.top/Article/details/gt2lcomfryg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2pintfwmg.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbpmxjad.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gt2uplmvsrp.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gt2gjnzgmck.html

std::sort(v.begin(), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulblcirr.html

[S39] C++：自定义比较器排序
来源：http://dali.xylfe.cn/Article/details/gt2lswlpwoc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.quarkkingdee.top/Article/details/gt2lnvwpwas.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gt2myvwafut.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2pxnhkoqv.html

[S41] C++：类与构造函数
来源：http://dali.316326.xyz/Article/details/gt2rkpfbeve.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dianchejie.cn/Article/details/gt2wubfwscp.html

[S42] C++：继承与虚函数
来源：http://dali.havefunace.top/Article/details/gt2zvtsrurv.html

class B : public Base { public: void f() override {} };
来源：http://dali.tian-w.cn/Article/details/gt2pjilkaed.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gt2ofcbfgnr.html

auto p = std::make_unique<int>(5);
来源：http://dali.0kj1m.cn/Article/details/gt2xpbhrwfu.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gt2ohuhuccn.html

void inc(int &x) { ++x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zyxprlpj.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gt2loprrthl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2jzbqlkzj.html

[S46] C++：函数模板
来源：http://dali.xuetiantiany.cn/Article/details/gt2dskxgguj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sxryk.cn/Article/details/gt2yhbhdprr.html

[S47] C++：结构化绑定遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2nzydgpve.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sxryk.cn/Article/details/gt2edmzhwxy.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2eawderyr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.haohaochexian.top/Article/details/gt2micoqpop.html

while (std::getline(in, line)) { }
来源：http://dali.snrcjt.cn/Article/details/gt2mginzcgx.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2qcywcjbe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guowangkeji.top/Article/details/gt2srdiicrg.html

[S50] C++：格式化数字
来源：http://dali.birdmap.top/Article/details/gt2qxylyobt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gt2xqpksbln.html

[S51] C++：显式类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2ihhctckz.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmqofyon.html

[S52] C++：const 与 noexcept
来源：http://dali.daxiang520.top/Article/details/gt2ruonxgcd.html

int size() const noexcept { return n_; }
来源：http://dali.svipenyu.cn/Article/details/gt2cwthjodr.html

[S53] C++：移动语义
来源：http://dali.xinyue.icu/Article/details/gt2yvneljck.html

std::vector<int> w = std::move(v);
来源：http://dali.yongpay.top/Article/details/gt2eavcbojg.html

[S54] C++：异常处理
来源：http://dali.snrcjt.cn/Article/details/gt2sjbftvox.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yangfankeji.com/Article/details/gt2hzycdcjd.html

[S55] C++：结构化绑定
来源：http://dali.c1oappe.top/Article/details/gt2kslcsxft.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tianlin.xyz/Article/details/gt2umeqyksm.html

[S56] C++：optional
来源：http://dali.guowangkeji.top/Article/details/gt2aqmmdfue.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gt2picusiib.html

[S57] C++：编译期常量
来源：http://dali.yueranfly.top/Article/details/gt2icvewurz.html

constexpr int N = 10;
来源：http://dali.redwolf501.top/Article/details/gt2hzpsjxpp.html

[S58] C++：命名空间
来源：http://dali.snrcjt.cn/Article/details/gt2dlorxtbv.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgufenzy.top/Article/details/gt2wfrkqqir.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gt2bxvlfbyu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuanzhike.top/Article/details/gt2stbzmpow.html

[S60] C++：遍历并删除元素
来源：http://dali.fengsongda.top/Article/details/gt2jxsfybqk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gt2wcbcjngl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2xtimzbfc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxuanxn.top/Article/details/gt2abmsajnv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjmfhwsh.html


<!-- 参考信息 -->