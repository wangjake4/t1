代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.xylfe.cn/Article/details/gtkksgcnkj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuetiantiany.cn/Article/details/gtlwdooqiv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtftsnbqxm.html

[Q89] 判断表是否存在
来源：http://dali.yongpay.top/Article/details/gtixhttmuw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnqzz.top/Article/details/gtucbnznio.html

[Q90] 生成序号列
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmxkhcyt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aizwys.cn/Article/details/gttzganpbw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtuwbmjgcg.html

R. Bash 专题
来源：http://dali.cdnleiting.top/Article/details/gtiedgjasz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtlyrspbrh.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gtigstknrk.html

#!/usr/bin/env bash
来源：http://dali.zhengqikj.top/Article/details/gtgtbjdhjy.html

set -euo pipefail
来源：http://dali.nwbrower.top/Article/details/gtgorrlloa.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gtnbvuqrcc.html

name="Tom"; echo "$name"
来源：http://dali.yueranfly.top/Article/details/gthapumcja.html

[R03] 只读变量
来源：http://dali.0kj1m.cn/Article/details/gtikmdhzib.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gtzllhvxps.html

[R04] 位置参数
来源：http://dali.yangfankeji.com/Article/details/gtpyrvhyud.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cucudq.cn/Article/details/gtirnvwwxm.html

[R05] 参数默认值
来源：http://dali.meibo888.top/Article/details/gtopfxrvfs.html

name="${1:-default}"
来源：http://dali.andypj.xyz/Article/details/gtxpbizpiv.html

[R06] 判断命令是否存在
来源：http://dali.daria6918.cn/Article/details/gtsvzwuskv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gtnyfbgjqn.html

[R07] if 判断文件
来源：http://dali.vqdsnc.cn/Article/details/gtlyzjyjnw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dashuyun.cn/Article/details/gtbdazibkh.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gtqnairoux.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yongpay.top/Article/details/gtekmautbx.html

[R09] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqwgmeyy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tian-w.cn/Article/details/gtsadcrwqz.html

[R10] 正则匹配
来源：http://dali.wangdashe.top/Article/details/gtltazynxy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.mhx1999.top/Article/details/gtllutxrdq.html

[R11] case 多分支
来源：http://dali.yanxiufei.cn/Article/details/gtnpttgiuz.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gtpocwygsv.html

start) echo "启动" ;;
来源：http://dali.fzhhl.top/Article/details/gtwfsgjftk.html

stop)  echo "停止" ;;
来源：http://dali.ybcxt.top/Article/details/gtdyjfmoyi.html

*)     echo "未知命令" ;;
来源：http://dali.yonumen.top/Article/details/gtbzdgosjf.html

esac
来源：http://dali.ivvv.top/Article/details/gtrygagorp.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gtlvjrtrfi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gtxmaewuaw.html

[R13] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gtbkxwtvqh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtykaglbsh.html

[R14] C 风格 for
来源：http://dali.vqdsnc.cn/Article/details/gtoxbvcwnz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqfqefmu.html

[R15] while 逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtxfghfsnt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cqqwz.cn/Article/details/gtuxjofvib.html

[R16] until 等待条件
来源：http://dali.gotoacloud.top/Article/details/gtpsxlyolq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gtwjqzmqib.html

[R17] 数组定义与取值
来源：http://dali.pengpengdd.cyou/Article/details/gtejajzfiw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tanke756.top/Article/details/gthjxdfkse.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gtyrbuvsan.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.meibo888.top/Article/details/gtpfpexqen.html

[R19] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gtgjcwalby.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gtqktikwof.html

[R20] 关联数组（字典）
来源：http://dali.sxryk.cn/Article/details/gtbtgasydd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gtstchfmag.html

[R21] 字符串长度
来源：http://dali.zdqjudy.top/Article/details/gtnarcgdfz.html

echo "${#s}"
来源：http://dali.chenjidiqi.icu/Article/details/gtluvzgyuh.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gttyqmdcdm.html

echo "${s:0:5}"
来源：http://dali.tian-w.cn/Article/details/gtpizqgixy.html

[R23] 字符串替换
来源：http://dali.ivvv.top/Article/details/gtumgdvfeg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpzsijgb.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtosvexsmj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpukrnhb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtdvktcalv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtutxmpifd.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gtcigvptij.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfzbzcfn.html

[R27] 算术展开
来源：http://dali.wangdashe.top/Article/details/gtahrteyry.html

echo $((1 + 2 * 3))
来源：http://dali.ydzc1.top/Article/details/gtsxlpmtqt.html

[R28] 浮点运算
来源：http://dali.yj20258.top/Article/details/gtpgmedckr.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gtgplzdrto.html

[R29] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtvslzfqsh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shuidangran.top/Article/details/gtenwljuaz.html

[R30] 函数返回状态码
来源：http://dali.jianghu66.top/Article/details/gtvgiwjtes.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsxtuyvv.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gtonwmradb.html

f() { local x=1; echo "$x"; }
来源：http://dali.gogol.net.cn/Article/details/gtjiqchfse.html

[R32] 参数个数校验
来源：http://dali.yj20258.top/Article/details/gttsawqyoz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gtrqqvdnww.html

[R33] 捕获错误并提示行号
来源：http://dali.zhengqikj.top/Article/details/gtiqarvuqq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yangfankeji.com/Article/details/gtmdlhktoi.html

[R34] 退出时清理
来源：http://dali.hnqzz.top/Article/details/gtnyrtxtdz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqyovoha.html

[R35] 后台执行并等待
来源：http://dali.yanxiufei.cn/Article/details/gtfsknncsa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.bjfxy.top/Article/details/gtdataxidd.html

[R36] 并发执行多个任务
来源：http://dali.chenzaomai.com/Article/details/gtiuiscgrn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhmqbgjc.html

[R37] 把输出赋给变量
来源：http://dali.yj202588.top/Article/details/gtzaezgfud.html

files=$(ls -1)
来源：http://dali.vqdsnc.cn/Article/details/gtjxdkdzwg.html

[R38] 管道串联
来源：http://dali.zhongyouzk.top/Article/details/gtapdyyflt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gaohongyu789.top/Article/details/gtlmnqkqyx.html

[R39] 重定向标准输出与错误
来源：http://dali.xinyue.icu/Article/details/gtwdeccunq.html

cmd > out.log 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gtefrglspm.html

[R40] 追加写日志
来源：http://dali.tian-w.cn/Article/details/gtyervjlov.html

echo "log" >> out.log
来源：http://dali.daria6918.cn/Article/details/gtyzcttxpe.html

[R41] 丢弃输出
来源：http://dali.cqqwz.cn/Article/details/gtdgiqhpja.html

cmd >/dev/null 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtpuxkarwp.html

[R42] 输入重定向
来源：http://dali.feifeiyinyue.top/Article/details/gtqheycalp.html

wc -l < a.txt
来源：http://dali.ydzc1.top/Article/details/gtninuzzny.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gtnewpwyrd.html

find . -name "*.log" -type f
来源：http://dali.daxiang520.top/Article/details/gtwvsarbhr.html

[R44] 按修改时间查找
来源：http://dali.xuetiantiany.cn/Article/details/gtxshhmeiu.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gtlfgbehgk.html

[R45] 批量删除
来源：http://dali.yj20258.top/Article/details/gtyegjfqrx.html

find . -name "*.tmp" -delete
来源：http://dali.shuidangran.top/Article/details/gtvwbroygk.html

[R46] 递归替换文件内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlddnyjy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigfzy.top/Article/details/gtkjctqxtf.html

[R47] sed 单行替换
来源：http://dali.daria6918.cn/Article/details/gthkxzybva.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jianghu66.top/Article/details/gtktgffhfr.html

[R48] awk 取指定列
来源：http://dali.yueranfly.top/Article/details/gtnspyhxdj.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj202588.top/Article/details/gtqwqmkrhp.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gtotcwpqxs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.c1oappe.top/Article/details/gtjtpqlpha.html

[R50] awk 求和
来源：http://dali.wangdashe.top/Article/details/gtsawmwocq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfwtqqtp.html

[R51] 排序去重取前几
来源：http://dali.zhixingplan.top/Article/details/gtoukzyjlb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzzjssfv.html

[R52] 统计行数
来源：http://dali.zhengqikj.top/Article/details/gtwxcdqdvy.html

wc -l a.txt
来源：http://dali.jianghu66.top/Article/details/gteoyvvqmc.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gtgeiodvci.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.snrcjt.cn/Article/details/gtsmhetiwd.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gtmgbspuvj.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtqscyhfto.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcykzrsb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhiwuduotai.top/Article/details/gtvnmkjtmx.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gtlkozlsta.html

scp file user@host:/path/
来源：http://dali.ydzc1.top/Article/details/gtoxuzxcok.html

[R57] 远程执行命令
来源：http://dali.ivvv.top/Article/details/gtnvyuuaxa.html

ssh user@host 'uptime'
来源：http://dali.pycfn.com/Article/details/gtwdvsyviw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gtupujuihi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zdqjudy.top/Article/details/gtdciqslxm.html

[R59] 发 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtflyshlnu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gtganeltgy.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtorpaanli.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigfzy.top/Article/details/gtnsitlzmm.html

[R61] 磁盘占用
来源：http://dali.quarkkingdee.top/Article/details/gtsakvfien.html

df -h;  du -sh *
来源：http://dali.daria6918.cn/Article/details/gtivfqucdf.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gtuecjrotz.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gttsgfxzqy.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtihrkmulj.html

free -h;  ps aux | grep nginx
来源：http://dali.ehwqpu.com/Article/details/gtndxfgkrr.html

[R64] 结束进程
来源：http://dali.gaohongyu789.top/Article/details/gtezcgriwa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.havefunace.top/Article/details/gtjgbngwjp.html

[R65] 查看端口占用
来源：http://dali.jinqigfzy.top/Article/details/gtxghqzyie.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sxryk.cn/Article/details/gtspnbfxwb.html

[R66] 定时任务
来源：http://dali.cashguo.top/Article/details/gtuvwrlrjl.html

crontab -e;  crontab -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcqumeva.html

[R67] 生成随机十六进制串
来源：http://dali.xuetiantiany.cn/Article/details/gttjdaqjvm.html

openssl rand -hex 16
来源：http://dali.hysaishi.cn/Article/details/gtxgkcegtv.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpulfbqay.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gtjmleegcn.html

[R69] 生成随机密码
来源：http://dali.tanke756.top/Article/details/gtwxqhecwb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhoulong.xyz/Article/details/gtvtzuzmhc.html

[R70] 时间戳与互转
来源：http://dali.shzxlz.cn/Article/details/gtackaithx.html

date +%s;  date -d @1700000000
来源：http://dali.pengpengdd.cyou/Article/details/gtyddnspaz.html

[R71] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtmvxdgryl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tianlin.xyz/Article/details/gtkuynrwwr.html

[R72] 等待端口就绪
来源：http://dali.316326.xyz/Article/details/gtpzqgbfhu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtfubplygm.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gtydiebotm.html

split -l 1000 big.log part_
来源：http://dali.hongshengwenyu.top/Article/details/gteuuyiwdr.html

[R74] 批量重命名
来源：http://dali.jinqigufen.top/Article/details/gtmvofkwuz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shuidangran.top/Article/details/gtptkwcwjg.html

[R75] 导出环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtqujgcxpv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zycfv.cn/Article/details/gtksekhprg.html

[R76] 使用临时文件
来源：http://dali.aibaodan.cn/Article/details/gtbxfcnhie.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuirgiqqv.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgirngpso.html

read -rp "请输入: " ans
来源：http://dali.tian-w.cn/Article/details/gtbcrulvns.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gtstaceyuc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fengsongda.top/Article/details/gthvfnjwuh.html

[R79] 解析命令行选项
来源：http://dali.0kj1m.cn/Article/details/gtisyghjqu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sysykeji.top/Article/details/gtkstmzibs.html

[R80] 查看脚本执行耗时
来源：http://dali.9152youxi.cn/Article/details/gtdrebqhbf.html

time ./run.sh
来源：http://dali.gzhubu.top/Article/details/gtwvzebezs.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxcbcuanb.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gtxcewwodu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtjrizlofb.html

[S01] C：Hello World
来源：http://dali.pycfn.com/Article/details/gtszjqxvdz.html

#include <stdio.h>
来源：http://dali.tanke756.top/Article/details/gtquuxmlvo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqmprmaqg.html

[S02] C：变量与格式化输出
来源：http://dali.svipenyu.cn/Article/details/gtyrwzfelj.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gtbblemswk.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gtveoqrzop.html

int x; scanf("%d", &x);
来源：http://dali.feifeiyinyue.top/Article/details/gtutydutby.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gtscjrznlm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gtwzyxwyxc.html

[S05] C：字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtqqdvjvbb.html

strlen(s)
来源：http://dali.jqgufenzy.top/Article/details/gtzocoirhb.html

[S06] C：字符串比较
来源：http://dali.daxiang520.top/Article/details/gtjumrpbrj.html

strcmp(a, b) == 0
来源：http://dali.pengpengdd.cyou/Article/details/gtgkbxpugz.html

[S07] C：数组遍历求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtquxxhphm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jlsjyb.cn/Article/details/gteqwsmdzx.html

[S08] C：动态内存分配与释放
来源：http://dali.zycfv.cn/Article/details/gtzkewtrza.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gtedcfvglb.html

[S09] C：结构体定义与初始化
来源：http://dali.hnqzz.top/Article/details/gtfwjbkdeq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sufxvd.cn/Article/details/gtkphbrdmf.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gtslnsgxmz.html

int *p = &a;  *p = 5;
来源：http://dali.vqdsnc.cn/Article/details/gtixannvva.html

[S11] C：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtyyhfkunf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhongyouzk.top/Article/details/gttwfumglz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zdqjudy.top/Article/details/gtbkugkbsm.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gtscaanjub.html

[S12] C：写文件
来源：http://dali.yanxiufei.cn/Article/details/gthkisxavs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shuidangran.top/Article/details/gtqbwqddcw.html

[S13] C：宏定义
来源：http://dali.yanxiufei.cn/Article/details/gtbllqpuhk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ivvv.top/Article/details/gtdpvrktgx.html

[S14] C：枚举
来源：http://dali.jyoumei.cn/Article/details/gtksmuoayr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gtoiejoyxy.html

[S15] C：类型转换
来源：http://dali.jiagoushi.top/Article/details/gtmvtcntzm.html

(double) a / b
来源：http://dali.xinyue.icu/Article/details/gtkytkcalv.html

[S16] C：位操作置位
来源：http://dali.xinyue.icu/Article/details/gtcgddvrwu.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gtfdlqoqmx.html

[S17] C：安全拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtdpqdibgh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sysykeji.top/Article/details/gthknwaiqr.html

[S18] C：命令行参数
来源：http://dali.hnqzz.top/Article/details/gtyhtbrqfs.html

int main(int argc, char **argv)
来源：http://dali.hywenlv.cn/Article/details/gtqxqhhkky.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gthtqkgksh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gtgktmxhtu.html

[S20] C：二分查找
来源：http://dali.0kj1m.cn/Article/details/gtzmgxncqc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gtqswwnujs.html

[S21] C：字符类别判断
来源：http://dali.0kj1m.cn/Article/details/gtfpdqznzc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnoislnf.html

[S22] C：字符串转数字
来源：http://dali.feifeiyinyue.top/Article/details/gtqjpddtnw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yonumen.top/Article/details/gtdxrqhsys.html

[S23] C：随机数
来源：http://dali.sufxvd.cn/Article/details/gtsvfqmctc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhoulong.xyz/Article/details/gtfwgvtosd.html

[S24] C：获取本地时间
来源：http://dali.yongpay.top/Article/details/gtxjduhsvy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hywenlv.cn/Article/details/gtjzffuexn.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gtogiqiftp.html

memcpy(dst, src, n);
来源：http://dali.jiagoushi.top/Article/details/gtuqbqlkvs.html

[S26] C：内存清零
来源：http://dali.daxiang520.top/Article/details/gtlclnkzcx.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gtajqibnsg.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gtqoolhzte.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmyejchs.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gtipyaxowo.html

static int counter = 0;
来源：http://dali.ehwqpu.com/Article/details/gtlhyxvxra.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gtwkxhdeia.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ybcxt.top/Article/details/gttclojhhs.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gtbhbqtjxj.html

#ifndef X_H
来源：http://dali.ivvv.top/Article/details/gtnbaajylu.html

#define X_H
来源：http://dali.tanke756.top/Article/details/gtflmjieyc.html

#endif
来源：http://dali.xziqi.cn/Article/details/gtjfyzhsfc.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gtfuczupvg.html

#include <iostream>
来源：http://dali.yanxiufei.cn/Article/details/gtvsqjvggd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfdzhdfb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gtwnnyfyrb.html

std::string s = "hi";  s += "!";
来源：http://dali.hongshengwenyu.top/Article/details/gtbpceclzc.html

[S33] C++：vector 增删
来源：http://dali.c1oappe.top/Article/details/gtkqtkljmi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenlongwang.top/Article/details/gtmhzvqaqg.html

[S34] C++：遍历 vector
来源：http://dali.0kj1m.cn/Article/details/gtosambycm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj202588.top/Article/details/gtgmzojkov.html

[S35] C++：map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqclxajh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtzacycxds.html

[S36] C++：unordered_map
来源：http://dali.zycfv.cn/Article/details/gtskijbudv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtwjsaavxj.html

[S37] C++：set
来源：http://dali.sysykeji.top/Article/details/gtwgojoxjb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yanxiufei.cn/Article/details/gtiloukqvh.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbfelcsm.html

std::sort(v.begin(), v.end());
来源：http://dali.xylfe.cn/Article/details/gtoklelhds.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gtimtdgbcj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258.top/Article/details/gtvuqniita.html

[S40] C++：查找元素
来源：http://dali.snrcjt.cn/Article/details/gttpfoldit.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guannengcc.top/Article/details/gtlnpjvcsb.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gtaafbtkye.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gotoacloud.top/Article/details/gtlbeuqthk.html

[S42] C++：继承与虚函数
来源：http://dali.0kj1m.cn/Article/details/gttfctmdfg.html

class B : public Base { public: void f() override {} };
来源：http://dali.kuanghao11.cn/Article/details/gtskauiblu.html

[S43] C++：智能指针
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbfnsjau.html

auto p = std::make_unique<int>(5);
来源：http://dali.dianchejie.cn/Article/details/gthsbqmmhm.html

[S44] C++：引用传参
来源：http://dali.daxiang520.top/Article/details/gtwqkcvczp.html

void inc(int &x) { ++x; }
来源：http://dali.hammf.cn/Article/details/gtctpgwybx.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gtbwxkskpy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gtuffplrur.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gtoujpgzbw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenzaomai.com/Article/details/gtaectqtyx.html

[S47] C++：结构化绑定遍历
来源：http://dali.fengsongda.top/Article/details/gtdewrvnsx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ppjwa.cn/Article/details/gtlnboawur.html

[S48] C++：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtfrqqveno.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258.top/Article/details/gtownnvoyw.html

while (std::getline(in, line)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjqqfsev.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtvbohbnsy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtvgpiyzat.html

[S50] C++：格式化数字
来源：http://dali.andypj.xyz/Article/details/gtxbaibeql.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtyxldqlrz.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gtbhhqicho.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gtvasglmux.html

[S52] C++：const 与 noexcept
来源：http://dali.jlsjyb.cn/Article/details/gtnatrjafy.html

int size() const noexcept { return n_; }
来源：http://dali.hnqzz.top/Article/details/gtahzggxjb.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gtlepxlnxm.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gtvxtsljuf.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gtmczjzclw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ydzc1.top/Article/details/gtejrijdvr.html

[S55] C++：结构化绑定
来源：http://dali.daria6918.cn/Article/details/gttjliucmg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj202588.top/Article/details/gtvsllmdje.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gtgerotfxl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.iojbl.cn/Article/details/gtwwimlsfj.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gtsuyrvaaw.html

constexpr int N = 10;
来源：http://dali.9152youxi.cn/Article/details/gtzknwlvrp.html

[S58] C++：命名空间
来源：http://dali.pycfn.com/Article/details/gtzjhtunun.html


<!-- 参考信息 -->