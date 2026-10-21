代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.zhongyouzk.top/Article/details/gtfgcfxxvt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gtbginlufa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtbktilzru.html

[Q89] 判断表是否存在
来源：http://dali.yj20258888.top/Article/details/gtjdpyjajm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlnhpyvp.html

[Q90] 生成序号列
来源：http://dali.yonumen.top/Article/details/gtmwaslwpq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenlongwang.top/Article/details/gtiwiwoaea.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtejukrugv.html

R. Bash 专题
来源：http://dali.guowangkeji.top/Article/details/gtlmzahxan.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gttwidcidg.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gtyjzayjzg.html

#!/usr/bin/env bash
来源：http://dali.zhiwuduotai.top/Article/details/gttuqlrupm.html

set -euo pipefail
来源：http://dali.zhiwuduotai.top/Article/details/gttdfuvxmx.html

[R02] 变量赋值与使用
来源：http://dali.feifeiyinyue.top/Article/details/gtypfgbqwg.html

name="Tom"; echo "$name"
来源：http://dali.gotoacloud.top/Article/details/gtioievrul.html

[R03] 只读变量
来源：http://dali.xuetiantiany.cn/Article/details/gtlxcpmbgz.html

readonly PI=3.14
来源：http://dali.jinqigufen.top/Article/details/gtdijbpxpe.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gttiilqwby.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangtech.top/Article/details/gtuphtwjjt.html

[R05] 参数默认值
来源：http://dali.shzxlz.cn/Article/details/gtzcswljcv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gtfuwtdbrm.html

[R06] 判断命令是否存在
来源：http://dali.sxryk.cn/Article/details/gtnaxzirju.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfddkiusu.html

[R07] if 判断文件
来源：http://dali.shangyingyoupin.top/Article/details/gtclkotagg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuanzx.com/Article/details/gtpozventq.html

[R08] 数值比较
来源：http://dali.gzhubu.top/Article/details/gtwvbqhvbb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtiilkyxzw.html

[R09] 字符串比较
来源：http://dali.sweek.top/Article/details/gtzmrfjoek.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fzhhl.top/Article/details/gtlwsffeyd.html

[R10] 正则匹配
来源：http://dali.yuanzhike.top/Article/details/gtwmodnnpj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuxming.cn/Article/details/gtavicaton.html

[R11] case 多分支
来源：http://dali.yuanzhike.top/Article/details/gtqszvwibb.html

case "$1" in
来源：http://dali.kuanghao11.cn/Article/details/gtjqwjqpyp.html

start) echo "启动" ;;
来源：http://dali.aibaodan.cn/Article/details/gtftnkownj.html

stop)  echo "停止" ;;
来源：http://dali.gogol.net.cn/Article/details/gtjgmwnwzt.html

*)     echo "未知命令" ;;
来源：http://dali.andypj.xyz/Article/details/gtsghwomls.html

esac
来源：http://dali.aibaodan.cn/Article/details/gtxqsdjjbl.html

[R12] for 遍历文件
来源：http://dali.0kj1m.cn/Article/details/gtshqptzwz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.havefunace.top/Article/details/gtewvjzzfm.html

[R13] for 计数循环
来源：http://dali.feifeiyinyue.top/Article/details/gtqdxegdmz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtfptrcvuj.html

[R14] C 风格 for
来源：http://dali.yangfankeji.com/Article/details/gtlcninoeh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtgoinxdrj.html

[R15] while 逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtkadjnipx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtwqullanj.html

[R16] until 等待条件
来源：http://dali.chenlongwang.top/Article/details/gtvygddnqx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtiqgypeqp.html

[R17] 数组定义与取值
来源：http://dali.aibaodan.cn/Article/details/gtbzreenec.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuxming.cn/Article/details/gttvocnsdv.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gtzhjrgmdj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yonumen.top/Article/details/gtnydvljkm.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtumexlkdf.html

echo "${#arr[@]}"
来源：http://dali.aibaodan.cn/Article/details/gtnsvhyzre.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gtbufygckc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cqqwz.cn/Article/details/gtwuwfkukj.html

[R21] 字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtimlxtyup.html

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gtzsqpboey.html

[R22] 截取子串
来源：http://dali.fengsongda.top/Article/details/gtnphdlrll.html

echo "${s:0:5}"
来源：http://dali.sufxvd.cn/Article/details/gtkkqdpwvy.html

[R23] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gtdhvjmftf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhixingplan.top/Article/details/gtynzbsrfi.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gttsiutpav.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenlongwang.top/Article/details/gtvcdysgoo.html

[R25] 去后缀 / 去前缀
来源：http://dali.ehwqpu.com/Article/details/gtzvfpnaoa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj202588.top/Article/details/gtholttgmg.html

[R26] 命令替换
来源：http://dali.xuanzx.com/Article/details/gtbjyfrosm.html

now=$(date +%F); echo "$now"
来源：http://dali.xuetiantiany.cn/Article/details/gtmtqweapd.html

[R27] 算术展开
来源：http://dali.wangdashe.top/Article/details/gtlqewxbfx.html

echo $((1 + 2 * 3))
来源：http://dali.zhixingplan.top/Article/details/gtjsoupsuw.html

[R28] 浮点运算
来源：http://dali.yj20258.top/Article/details/gtwkxkwmpc.html

echo "scale=2; 10/3" | bc
来源：http://dali.havefunace.top/Article/details/gtbovdtgfl.html

[R29] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbztivhf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gtdqfrbuhb.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gtkrnzyzuk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daxiang520.top/Article/details/gtuuimpngk.html

[R31] 局部变量
来源：http://dali.quarkkingdee.top/Article/details/gtfoahdcvw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhengqikj.top/Article/details/gtkiemaxdv.html

[R32] 参数个数校验
来源：http://dali.xuetiantiany.cn/Article/details/gtgnvicxcl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtwfthxkms.html

[R33] 捕获错误并提示行号
来源：http://dali.ivvv.top/Article/details/gtoeabqqjp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sysykeji.top/Article/details/gtjmkxzxmp.html

[R34] 退出时清理
来源：http://dali.shzxlz.cn/Article/details/gtwksmmeul.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtljatfxwn.html

[R35] 后台执行并等待
来源：http://dali.pengpengdd.cyou/Article/details/gtzffceuwq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhengqikj.top/Article/details/gtmcxksjfo.html

[R36] 并发执行多个任务
来源：http://dali.sysykeji.top/Article/details/gtjjsngwuo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gteqygzizr.html

[R37] 把输出赋给变量
来源：http://dali.svipenyu.cn/Article/details/gtglvhbccm.html

files=$(ls -1)
来源：http://dali.cashguo.top/Article/details/gtfiuqtyhe.html

[R38] 管道串联
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwfbuzkm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shuidangran.top/Article/details/gtyzbgbran.html

[R39] 重定向标准输出与错误
来源：http://dali.tanke756.top/Article/details/gtmceuybpw.html

cmd > out.log 2>&1
来源：http://dali.redwolf501.top/Article/details/gtzcrxyodq.html

[R40] 追加写日志
来源：http://dali.xuetiantiany.cn/Article/details/gturwuaxqq.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gtatlggajx.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gtqrqephns.html

cmd >/dev/null 2>&1
来源：http://dali.meibo888.top/Article/details/gtxpofrtwd.html

[R42] 输入重定向
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiubnpcnl.html

wc -l < a.txt
来源：http://dali.guowangkeji.top/Article/details/gthfkyvkrs.html

[R43] 按名字查找文件
来源：http://dali.zycfv.cn/Article/details/gtcbnhcylw.html

find . -name "*.log" -type f
来源：http://dali.ydzc1.top/Article/details/gtzafrwdxw.html

[R44] 按修改时间查找
来源：http://dali.haohaochexian.top/Article/details/gtblssnooz.html

find . -mtime -7 -type f
来源：http://dali.hongshengwenyu.top/Article/details/gtxrsvichu.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gtjylsoeno.html

find . -name "*.tmp" -delete
来源：http://dali.cheryme.top/Article/details/gtmkbiwszz.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gtlwexeyrm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sxryk.cn/Article/details/gtrhnsuukt.html

[R47] sed 单行替换
来源：http://dali.havefunace.top/Article/details/gtgsgsbpvg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.bjfxy.top/Article/details/gtclxsldwo.html

[R48] awk 取指定列
来源：http://dali.cheryme.top/Article/details/gtdbuxrizc.html

awk '{print $1, $3}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtrwytisme.html

[R49] awk 带条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfksenhd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.vqdsnc.cn/Article/details/gtxtpiqjvi.html

[R50] awk 求和
来源：http://dali.quarkkingdee.top/Article/details/gtsxyqdwxb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtnvnbcajg.html

[R51] 排序去重取前几
来源：http://dali.xziqi.cn/Article/details/gtryuvfufb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hammf.cn/Article/details/gtogxqyecs.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gtbkzunknj.html

wc -l a.txt
来源：http://dali.guannengcc.top/Article/details/gtjiycqagm.html

[R53] 查看文件头与实时尾
来源：http://dali.yuanzhike.top/Article/details/gtqalvhwdk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fengsongda.top/Article/details/gttpkkfjnd.html

[R54] 比较两个文件
来源：http://dali.yuanzhike.top/Article/details/gtmrigdsjr.html

diff a.txt b.txt
来源：http://dali.havefunace.top/Article/details/gtueepxfdb.html

[R55] 压缩与解压
来源：http://dali.vqdsnc.cn/Article/details/gtiqkpxzsk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.316326.xyz/Article/details/gtmnhipgpp.html

[R56] 远程拷贝
来源：http://dali.ybcxt.top/Article/details/gtfcirepjs.html

scp file user@host:/path/
来源：http://dali.cashguo.top/Article/details/gthtkfjuof.html

[R57] 远程执行命令
来源：http://dali.pengpengdd.cyou/Article/details/gtbdflyyos.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxsknjjp.html

[R58] 下载文件
来源：http://dali.kuanghao11.cn/Article/details/gtjcrcepqi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.0kj1m.cn/Article/details/gtmyktdjsw.html

[R59] 发 POST JSON
来源：http://dali.pycfn.com/Article/details/gttwxtayrp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.redwolf501.top/Article/details/gtfptcqeqt.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtpytsqgbk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gtwmomneyh.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gtbjagdkyj.html

df -h;  du -sh *
来源：http://dali.jiagoushi.top/Article/details/gtycegrfer.html

[R62] 找最占空间的文件
来源：http://dali.wangshuangyany.cn/Article/details/gtlnwyweio.html

du -ah . | sort -rh | head -10
来源：http://dali.haohaochexian.top/Article/details/gthtpltaff.html

[R63] 内存与进程
来源：http://dali.c1oappe.top/Article/details/gtqqgyknqz.html

free -h;  ps aux | grep nginx
来源：http://dali.smart0.xyz/Article/details/gtqarzxoxx.html

[R64] 结束进程
来源：http://dali.hongshengwenyu.top/Article/details/gtdptqydfg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shzxlz.cn/Article/details/gtaqzkvwpa.html

[R65] 查看端口占用
来源：http://dali.jinqigufen.top/Article/details/gtrqkahhjw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dianchejie.cn/Article/details/gtmxqsxmds.html

[R66] 定时任务
来源：http://dali.chenzaomai.com/Article/details/gtejgseahm.html

crontab -e;  crontab -l
来源：http://dali.nanxinkj.top/Article/details/gthgvvgiro.html

[R67] 生成随机十六进制串
来源：http://dali.yuanzhike.top/Article/details/gthueutite.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gtrpfrltbi.html

[R68] 计算文件校验值
来源：http://dali.tianlin.xyz/Article/details/gtpbedybdg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gtdcomxdgw.html

[R69] 生成随机密码
来源：http://dali.hywenlv.cn/Article/details/gtqdulxqim.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gtmtkadzbu.html

[R70] 时间戳与互转
来源：http://dali.chenzaomai.com/Article/details/gtsxjhmpim.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gtdoxpxtnp.html

[R71] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gtckwansnc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yvedp.cn/Article/details/gtmubloxvc.html

[R72] 等待端口就绪
来源：http://dali.cashguo.top/Article/details/gtpvzsqlhh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gtqaqwalah.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gtrdihsyaz.html

split -l 1000 big.log part_
来源：http://dali.svipenyu.cn/Article/details/gtegnbswft.html

[R74] 批量重命名
来源：http://dali.snrcjt.cn/Article/details/gtnnpxbypg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gtdtdkvfms.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtbzslqbgs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcaakwmo.html

[R76] 使用临时文件
来源：http://dali.yj20258888.top/Article/details/gtbvxldhra.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gtbsyscztq.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvdlpwxp.html

read -rp "请输入: " ans
来源：http://dali.hnxiangtu.top/Article/details/gtylmbnxil.html

[R78] 交互式菜单
来源：http://dali.c1oappe.top/Article/details/gttymhtnhj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ehwqpu.com/Article/details/gthvwpczqc.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gtcbdjuggu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tanke756.top/Article/details/gtcxyaocuz.html

[R80] 查看脚本执行耗时
来源：http://dali.c1oappe.top/Article/details/gtnfkxqzco.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gtbxoqkwgq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdslqnaz.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gtezbvjztb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtezccmqat.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtsljqufmy.html

#include <stdio.h>
来源：http://dali.shzxlz.cn/Article/details/gtrjrdznmu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tianlin.xyz/Article/details/gtffcpobjc.html

[S02] C：变量与格式化输出
来源：http://dali.aizwys.cn/Article/details/gtwnihcwwx.html

int a = 10; printf("%d\n", a);
来源：http://dali.tianlin.xyz/Article/details/gtnnsktqcm.html

[S03] C：读入整数
来源：http://dali.shanyushiyangtech.top/Article/details/gtjeelvrrj.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gtcxhkvahr.html

[S04] C：字符串复制
来源：http://dali.cheryme.top/Article/details/gtawjhivqp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenlongwang.top/Article/details/gtokdpuzhd.html

[S05] C：字符串长度
来源：http://dali.wangdashe.top/Article/details/gttwwawaic.html

strlen(s)
来源：http://dali.yueranfly.top/Article/details/gtdpwuzppp.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gtkixknmnp.html

strcmp(a, b) == 0
来源：http://dali.hywenlv.cn/Article/details/gtwbksmkeh.html

[S07] C：数组遍历求和
来源：http://dali.0kj1m.cn/Article/details/gtazkatbxx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nwbrower.top/Article/details/gthtjrftvv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gtmrbpahru.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hammf.cn/Article/details/gtsshxuioe.html

[S09] C：结构体定义与初始化
来源：http://dali.xinyue.icu/Article/details/gtvwlcoorg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tianlin.xyz/Article/details/gtnfawbujg.html

[S10] C：指针与解引用
来源：http://dali.ydzc1.top/Article/details/gtpengplqa.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gtkeudfpqc.html

[S11] C：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtwfbjlpqs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jiagoushi.top/Article/details/gtubnjjwec.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.havefunace.top/Article/details/gtbwwbwzcs.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gtltvalclw.html

[S12] C：写文件
来源：http://dali.yj202588.top/Article/details/gtlfwnefkp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gteaxdfzfx.html

[S13] C：宏定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbwtlkfm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sxryk.cn/Article/details/gtkdosnexb.html

[S14] C：枚举
来源：http://dali.yvedp.cn/Article/details/gtqrslgpmw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.vqdsnc.cn/Article/details/gtyeoxeyze.html

[S15] C：类型转换
来源：http://dali.shuidangran.top/Article/details/gttsxzstax.html

(double) a / b
来源：http://dali.zhongyouzk.top/Article/details/gtjtregtyz.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gtgvckaelt.html

x |= (1 << 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtlampjqgm.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtnnwrplzx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xinyue.icu/Article/details/gtzfoiqlks.html

[S18] C：命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtgrtruxku.html

int main(int argc, char **argv)
来源：http://dali.cheryme.top/Article/details/gtvtgtwrqd.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gtcqpzwyzh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gteanxmcfg.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gtvomagrxc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gtfmuizliu.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gtlfsqioap.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.9152youxi.cn/Article/details/gtrukcchjq.html

[S22] C：字符串转数字
来源：http://dali.fzhhl.top/Article/details/gttdhgtbrr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzenhyct.html

[S23] C：随机数
来源：http://dali.jianghu66.top/Article/details/gtpkmecsbj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gtjvpafavy.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gtgktyqide.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlswsyzzq.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtknsfnr.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gtgrdjclof.html

[S26] C：内存清零
来源：http://dali.cashguo.top/Article/details/gtjqahfgsb.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gtifzwfbqd.html

[S27] C：定义常量
来源：http://dali.zhiwuduotai.top/Article/details/gtruunflwy.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtviuaxzef.html

[S28] C：静态变量
来源：http://dali.hnxiangtu.top/Article/details/gticyiktnm.html

static int counter = 0;
来源：http://dali.andypj.xyz/Article/details/gtlckwpjdx.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gtcmqdjrnb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gtfewhfzca.html

[S30] C：头文件保护
来源：http://dali.cqqwz.cn/Article/details/gtkrouazqr.html

#ifndef X_H
来源：http://dali.0kj1m.cn/Article/details/gthxbdgivd.html

#define X_H
来源：http://dali.jiagoushi.top/Article/details/gtlhyribcy.html

#endif
来源：http://dali.0kj1m.cn/Article/details/gtrvpjtaps.html

[S31] C++：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtwaghcbks.html

#include <iostream>
来源：http://dali.cashguo.top/Article/details/gthaknwlma.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sweek.top/Article/details/gtubxmszyy.html

[S32] C++：字符串
来源：http://dali.aibaodan.cn/Article/details/gtlcvleqcb.html

std::string s = "hi";  s += "!";
来源：http://dali.pengpengdd.cyou/Article/details/gteodrbzks.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gtncvpwecf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jianghu66.top/Article/details/gtcxaaqnla.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gtnvqhevrx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gtqutbxmdy.html

[S35] C++：map
来源：http://dali.feifeiyinyue.top/Article/details/gtkoumnyen.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtakjqhgrs.html

[S36] C++：unordered_map
来源：http://dali.birdmap.top/Article/details/gtgczxoyfn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtprqghbxz.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadqtrqvv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.redwolf501.top/Article/details/gtpohxmbmo.html

[S38] C++：排序
来源：http://dali.zhongyouzk.top/Article/details/gthrvaalkb.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gtcymanpud.html

[S39] C++：自定义比较器排序
来源：http://dali.yj202588.top/Article/details/gtpwuanbnb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhongyouzk.top/Article/details/gteewdvujy.html

[S40] C++：查找元素
来源：http://dali.gogol.net.cn/Article/details/gtetfnfhiw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jlsjyb.cn/Article/details/gtjkbyimxv.html

[S41] C++：类与构造函数
来源：http://dali.zhengqikj.top/Article/details/gtobftvtii.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gtgvzjhvmi.html

[S42] C++：继承与虚函数
来源：http://dali.xuetiantiany.cn/Article/details/gtnnqbgaoy.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gtohsaeufz.html

[S43] C++：智能指针
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsykdbyxr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhengqikj.top/Article/details/gtkcerdjjq.html

[S44] C++：引用传参
来源：http://dali.daxiang520.top/Article/details/gtbygghgju.html

void inc(int &x) { ++x; }
来源：http://dali.zycfv.cn/Article/details/gtfjiwlyhp.html

[S45] C++：lambda
来源：http://dali.gaohongyu789.top/Article/details/gtnrpcqnmw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gtwwridznp.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbknppxt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gtucajugjb.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrllorfnx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sufxvd.cn/Article/details/gtmnvfmhda.html

[S48] C++：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtyjpwrbir.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sufxvd.cn/Article/details/gtosznwuxu.html

while (std::getline(in, line)) { }
来源：http://dali.yvedp.cn/Article/details/gtqobxjlsb.html

[S49] C++：写文件
来源：http://dali.xylfe.cn/Article/details/gtxqksnfvp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aizwys.cn/Article/details/gtuvtvxgxe.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gtqaystdjk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtjekugghq.html

[S51] C++：显式类型转换
来源：http://dali.yueranfly.top/Article/details/gtzoifaxwp.html

static_cast<double>(a) / b
来源：http://dali.xinyue.icu/Article/details/gtpohulonv.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258.top/Article/details/gtxawdrapv.html

int size() const noexcept { return n_; }
来源：http://dali.gzhubu.top/Article/details/gtlznwnccj.html

[S53] C++：移动语义
来源：http://dali.hywenlv.cn/Article/details/gtfusjlpdg.html

std::vector<int> w = std::move(v);
来源：http://dali.xuanzx.com/Article/details/gtzbqzspko.html

[S54] C++：异常处理
来源：http://dali.fzhhl.top/Article/details/gtwfhvnzzo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gtrfqhbrjn.html

[S55] C++：结构化绑定
来源：http://dali.cqqwz.cn/Article/details/gtzmzzbeux.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtxybaalmx.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gtnynmgmlr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjshsfttj.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gtociuiluq.html

constexpr int N = 10;
来源：http://dali.cqqwz.cn/Article/details/gtqghubxkt.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gttooswcco.html


<!-- 参考信息 -->