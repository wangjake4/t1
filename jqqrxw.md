代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.kuanghao11.cn/Article/details/gtmtwxoals.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pengpengdd.cyou/Article/details/gttprtkzcm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuanzhike.top/Article/details/gthsdqokpv.html

[Q89] 判断表是否存在
来源：http://dali.yangfankeji.com/Article/details/gtxtewkjrg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ybcxt.top/Article/details/gtjczykblt.html

[Q90] 生成序号列
来源：http://dali.shangyingyoupin.top/Article/details/gtaxzmzcgh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zdqjudy.top/Article/details/gtjextjsve.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtzlqnsgto.html

R. Bash 专题
来源：http://dali.yvedp.cn/Article/details/gtyzpgksho.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gttpvpitcp.html

[R01] shebang 与严格模式
来源：http://dali.jqgfzy.top/Article/details/gtsghujhme.html

#!/usr/bin/env bash
来源：http://dali.nanxinkj.top/Article/details/gtjeyipphc.html

set -euo pipefail
来源：http://dali.yj202588.top/Article/details/gtjdxjvqpa.html

[R02] 变量赋值与使用
来源：http://dali.pycfn.com/Article/details/gtuctfgxkh.html

name="Tom"; echo "$name"
来源：http://dali.jqgufenzy.top/Article/details/gtezaghfmk.html

[R03] 只读变量
来源：http://dali.hysaishi.cn/Article/details/gtlyuiynsg.html

readonly PI=3.14
来源：http://dali.zdqjudy.top/Article/details/gtlajliclr.html

[R04] 位置参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtmesisfsl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigufen.top/Article/details/gtooycrzue.html

[R05] 参数默认值
来源：http://dali.hnqzz.top/Article/details/gtxcwujmub.html

name="${1:-default}"
来源：http://dali.xylfe.cn/Article/details/gtlntyzyfr.html

[R06] 判断命令是否存在
来源：http://dali.fengsongda.top/Article/details/gtxxxeelkx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gtnszugmwn.html

[R07] if 判断文件
来源：http://dali.sweek.top/Article/details/gttiavumba.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtqbzauomn.html

[R08] 数值比较
来源：http://dali.nanxuanxn.top/Article/details/gtycuojslx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenlongwang.top/Article/details/gtnzqtxsew.html

[R09] 字符串比较
来源：http://dali.c1oappe.top/Article/details/gtxmpzpgwe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtvrvkssdv.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gtdmmtfflx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxinkj.top/Article/details/gtokklcorl.html

[R11] case 多分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunfojfth.html

case "$1" in
来源：http://dali.zdqjudy.top/Article/details/gthzqocwwz.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gtbrpryrdk.html

stop)  echo "停止" ;;
来源：http://dali.xuanzx.com/Article/details/gtcjvdvhkb.html

*)     echo "未知命令" ;;
来源：http://dali.gzhubu.top/Article/details/gtvztmnmim.html

esac
来源：http://dali.hywenlv.cn/Article/details/gtomlrkspj.html

[R12] for 遍历文件
来源：http://dali.hammf.cn/Article/details/gtsexigqua.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgfzy.top/Article/details/gtxykfktoo.html

[R13] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gtrtoblzpt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtlrwbmwfp.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gtxipiutua.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtwowgkwkk.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtlvvmccpb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgufenzy.top/Article/details/gtnfxfgipr.html

[R16] until 等待条件
来源：http://dali.snrcjt.cn/Article/details/gtfjxyeazz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gtspjgqxfv.html

[R17] 数组定义与取值
来源：http://dali.hongshengwenyu.top/Article/details/gtkrxyvdtj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nwbrower.top/Article/details/gtupxvjweq.html

[R18] 遍历数组
来源：http://dali.shzxlz.cn/Article/details/gtfrpmqfjz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gtwqzzsrod.html

[R19] 数组长度
来源：http://dali.jinqigfzy.top/Article/details/gtvotykxea.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gthbbjngbb.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gterxmlywk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.redwolf501.top/Article/details/gtxjdnpxqc.html

[R21] 字符串长度
来源：http://dali.yj202588.top/Article/details/gtwhsqsjpt.html

echo "${#s}"
来源：http://dali.jinqigfzy.top/Article/details/gtlyzfryjt.html

[R22] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gthnewyisu.html

echo "${s:0:5}"
来源：http://dali.guannengcc.top/Article/details/gtsntztpil.html

[R23] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiivxawgp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gtoqnbsoeb.html

[R24] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtvmrlmkvl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gotoacloud.top/Article/details/gtugyexkpz.html

[R25] 去后缀 / 去前缀
来源：http://dali.quarkkingdee.top/Article/details/gtrdckpbsu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gtxucgrvoa.html

[R26] 命令替换
来源：http://dali.sysykeji.top/Article/details/gtonabtoom.html

now=$(date +%F); echo "$now"
来源：http://dali.tanke756.top/Article/details/gtmcqvlgqx.html

[R27] 算术展开
来源：http://dali.tanke756.top/Article/details/gtzgkuvunj.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gtzngwzfbf.html

[R28] 浮点运算
来源：http://dali.dianchejie.cn/Article/details/gtluxiredk.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuanzhike.top/Article/details/gtkqilgbcm.html

[R29] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gtjtpfoumw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jlsjyb.cn/Article/details/gtrslwskzd.html

[R30] 函数返回状态码
来源：http://dali.vqdsnc.cn/Article/details/gtlarqprqk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daxiang520.top/Article/details/gtwtrqvzfx.html

[R31] 局部变量
来源：http://dali.aizwys.cn/Article/details/gtimoqesif.html

f() { local x=1; echo "$x"; }
来源：http://dali.cdnleiting.top/Article/details/gtrrmnhdij.html

[R32] 参数个数校验
来源：http://dali.c1oappe.top/Article/details/gtzlgctzlj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gtluecqqvi.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gtlznlinvz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hywenlv.cn/Article/details/gtwatnwhee.html

[R34] 退出时清理
来源：http://dali.pengpengdd.cyou/Article/details/gtccqaxbae.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtaudfsiqt.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gtafwxeqix.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.meibo888.top/Article/details/gtcsyhzcvm.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gtgqvzkdqk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gtbtblprgq.html

[R37] 把输出赋给变量
来源：http://dali.iojbl.cn/Article/details/gtzerjscjx.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gtojysuzjo.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gtidwislrd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ybcxt.top/Article/details/gttvyfynge.html

[R39] 重定向标准输出与错误
来源：http://dali.havefunace.top/Article/details/gtwlhiuknc.html

cmd > out.log 2>&1
来源：http://dali.smart0.xyz/Article/details/gtyyyfbnbz.html

[R40] 追加写日志
来源：http://dali.xuetiantiany.cn/Article/details/gtoucmasxz.html

echo "log" >> out.log
来源：http://dali.bjfxy.top/Article/details/gttclnyjjk.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowesftpb.html

cmd >/dev/null 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtodfgooxh.html

[R42] 输入重定向
来源：http://dali.chenzaomai.com/Article/details/gtjsmfgmnw.html

wc -l < a.txt
来源：http://dali.cheryme.top/Article/details/gtgnyezmel.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gtrzmoffoy.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gtfpzjqhfl.html

[R44] 按修改时间查找
来源：http://dali.tian-w.cn/Article/details/gtxnhzawqp.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gtyyeroukh.html

[R45] 批量删除
来源：http://dali.yj202588.top/Article/details/gttojqmtcf.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gtiknarpoj.html

[R46] 递归替换文件内容
来源：http://dali.kuanghao11.cn/Article/details/gtgkyygolz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sufxvd.cn/Article/details/gtikcdbeje.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gtxymwbzrz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.mhx1999.top/Article/details/gtyddcxwzj.html

[R48] awk 取指定列
来源：http://dali.yvedp.cn/Article/details/gtavkslzdr.html

awk '{print $1, $3}' a.txt
来源：http://dali.guannengcc.top/Article/details/gttftqnopy.html

[R49] awk 带条件
来源：http://dali.havefunace.top/Article/details/gtzuufzcla.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.svipenyu.cn/Article/details/gtjrdezwtz.html

[R50] awk 求和
来源：http://dali.quarkkingdee.top/Article/details/gtbnihcktx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtndysoafi.html

[R51] 排序去重取前几
来源：http://dali.hfpthk.cn/Article/details/gtcmnvzoht.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangdashe.top/Article/details/gtuqfazktf.html

[R52] 统计行数
来源：http://dali.jqgufenzy.top/Article/details/gtushlljij.html

wc -l a.txt
来源：http://dali.smart0.xyz/Article/details/gtbmcyuzim.html

[R53] 查看文件头与实时尾
来源：http://dali.tian-w.cn/Article/details/gtlvihpsdj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.mhx1999.top/Article/details/gtqhhaurie.html

[R54] 比较两个文件
来源：http://dali.yj20258.top/Article/details/gtcekoxgjo.html

diff a.txt b.txt
来源：http://dali.cqqwz.cn/Article/details/gthjtdhjvn.html

[R55] 压缩与解压
来源：http://dali.jinqigfzy.top/Article/details/gtzndryvrm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigfzy.top/Article/details/gtzvcpppup.html

[R56] 远程拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtvtzyxarf.html

scp file user@host:/path/
来源：http://dali.tanke756.top/Article/details/gtvfabyeax.html

[R57] 远程执行命令
来源：http://dali.jlsjyb.cn/Article/details/gtwoptofse.html

ssh user@host 'uptime'
来源：http://dali.tanke756.top/Article/details/gthsupiuph.html

[R58] 下载文件
来源：http://dali.ivvv.top/Article/details/gtqkmfxroo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gtqdpqabwq.html

[R59] 发 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gtykkdongk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shuidangran.top/Article/details/gtwgtisedu.html

[R60] 只看 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtplcsahwe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shuidangran.top/Article/details/gttcxsrvzv.html

[R61] 磁盘占用
来源：http://dali.hfpthk.cn/Article/details/gtbeqmpxhn.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gthxtlbvzo.html

[R62] 找最占空间的文件
来源：http://dali.shzxlz.cn/Article/details/gtreivocba.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gtpstrkntz.html

[R63] 内存与进程
来源：http://dali.quarkkingdee.top/Article/details/gtxajqqspo.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gtdbvlqmxg.html

[R64] 结束进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtaffnvbob.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fengsongda.top/Article/details/gtvttstezl.html

[R65] 查看端口占用
来源：http://dali.316326.xyz/Article/details/gtyitxlpfs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvpfwwsg.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gtihmwpamp.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblfwyhem.html

[R67] 生成随机十六进制串
来源：http://dali.pengpengdd.cyou/Article/details/gteytvljtk.html

openssl rand -hex 16
来源：http://dali.hammf.cn/Article/details/gtjwiyvmhh.html

[R68] 计算文件校验值
来源：http://dali.haohaochexian.top/Article/details/gtcrggtrhz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gtjvqnbrxt.html

[R69] 生成随机密码
来源：http://dali.cdnleiting.top/Article/details/gtuhlyptxn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gtfdwmlydk.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gtksrrizgm.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gtsfxtlwkf.html

[R71] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gtgyhtkcqk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxinkj.top/Article/details/gtstxygxfp.html

[R72] 等待端口就绪
来源：http://dali.hongshengwenyu.top/Article/details/gtqlwjjcjy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gthtywkoqv.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gtlfhfsshq.html

split -l 1000 big.log part_
来源：http://dali.guowangkeji.top/Article/details/gtrwcjnwns.html

[R74] 批量重命名
来源：http://dali.daxiang520.top/Article/details/gtnybbiyys.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuanzx.com/Article/details/gtsmpruode.html

[R75] 导出环境变量
来源：http://dali.haohaochexian.top/Article/details/gtcapfzqkw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tian-w.cn/Article/details/gtewrnnatn.html

[R76] 使用临时文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgwcovbf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gtymbhkpav.html

[R77] 读取用户输入
来源：http://dali.nanxuanxn.top/Article/details/gtolwsujrw.html

read -rp "请输入: " ans
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzzaypbp.html

[R78] 交互式菜单
来源：http://dali.xuetiantiany.cn/Article/details/gtpkzbcnlw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.redwolf501.top/Article/details/gtjcehbrrw.html

[R79] 解析命令行选项
来源：http://dali.ivvv.top/Article/details/gtgqabstdp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258.top/Article/details/gtabypalsu.html

[R80] 查看脚本执行耗时
来源：http://dali.hysaishi.cn/Article/details/gtdxxgkljp.html

time ./run.sh
来源：http://dali.xylfe.cn/Article/details/gtemxteycm.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gturisffyo.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtpyerjann.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtvkdsraaa.html

[S01] C：Hello World
来源：http://dali.gzhubu.top/Article/details/gtoozxehqk.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gtezlfgqmc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cdnleiting.top/Article/details/gtvtgsnyla.html

[S02] C：变量与格式化输出
来源：http://dali.jiagoushi.top/Article/details/gtvisbifnc.html

int a = 10; printf("%d\n", a);
来源：http://dali.ppjwa.cn/Article/details/gtzsormfcq.html

[S03] C：读入整数
来源：http://dali.hywenlv.cn/Article/details/gtmrerefrj.html

int x; scanf("%d", &x);
来源：http://dali.wangshuangyany.cn/Article/details/gtxvyusolx.html

[S04] C：字符串复制
来源：http://dali.jyoumei.cn/Article/details/gtlhmxmxhd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gtvoibuyef.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtgmqrsoob.html

strlen(s)
来源：http://dali.hysaishi.cn/Article/details/gtzzezcqxb.html

[S06] C：字符串比较
来源：http://dali.sweek.top/Article/details/gtymqnabnc.html

strcmp(a, b) == 0
来源：http://dali.bjfxy.top/Article/details/gtygeenfip.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gtjcympkzi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cheryme.top/Article/details/gtuptultta.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gtlcnsdbxz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.mhx1999.top/Article/details/gtpvkseyhd.html

[S09] C：结构体定义与初始化
来源：http://dali.chenzaomai.com/Article/details/gtmifxyiqx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zycfv.cn/Article/details/gtcsvmdrvf.html

[S10] C：指针与解引用
来源：http://dali.zhongyouzk.top/Article/details/gtrtbnhgbj.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gtsqtxdjzy.html

[S11] C：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtuhklxztl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnxiangtu.top/Article/details/gtyhtpudpy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangdashe.top/Article/details/gtorehpzlm.html

fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gtxwtvlvfj.html

[S12] C：写文件
来源：http://dali.aizwys.cn/Article/details/gtanwuwnyb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gtxlwlegwi.html

[S13] C：宏定义
来源：http://dali.yangfankeji.com/Article/details/gtvksliaon.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gtgghreznz.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gtbsuoxsir.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gtzataocro.html

[S15] C：类型转换
来源：http://dali.xuanzx.com/Article/details/gttcjtmheg.html

(double) a / b
来源：http://dali.tianlin.xyz/Article/details/gtjnmkhmko.html

[S16] C：位操作置位
来源：http://dali.fengsongda.top/Article/details/gtxatrhgdh.html

x |= (1 << 3);
来源：http://dali.jqgufenzy.top/Article/details/gthfyxzlpi.html

[S17] C：安全拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtedagqmku.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gtvujzjefu.html

[S18] C：命令行参数
来源：http://dali.sysykeji.top/Article/details/gtodiukpkc.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gtjyttkmqr.html

[S19] C：快速排序
来源：http://dali.zhiwuduotai.top/Article/details/gtgaymfkhc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtupqrtchb.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gtnrhiptgi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbprcnhx.html

[S21] C：字符类别判断
来源：http://dali.jqgufenzy.top/Article/details/gtfsjiicoh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.vqdsnc.cn/Article/details/gtimvbkyll.html

[S22] C：字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gtcvwigydy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangshuangyany.cn/Article/details/gtukmmvgko.html

[S23] C：随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcsxqbix.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cqqwz.cn/Article/details/gtttjuckxw.html

[S24] C：获取本地时间
来源：http://dali.mhx1999.top/Article/details/gtlvfktffv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gthtuxmeev.html

[S25] C：内存拷贝
来源：http://dali.yj20258888.top/Article/details/gtlqtbiawa.html

memcpy(dst, src, n);
来源：http://dali.mhx1999.top/Article/details/gtyoiftrdu.html

[S26] C：内存清零
来源：http://dali.xylfe.cn/Article/details/gtylbykgea.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gtsbvwvbsb.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gtrdvxsdjy.html

const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gthtfwomci.html

[S28] C：静态变量
来源：http://dali.fengsongda.top/Article/details/gtoryicxcm.html

static int counter = 0;
来源：http://dali.xziqi.cn/Article/details/gtedqaimym.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gtmeoeuocl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.feifeiyinyue.top/Article/details/gtbxdlplpf.html

[S30] C：头文件保护
来源：http://dali.shangyingyoupin.top/Article/details/gtewdnydla.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticeqfesr.html

#define X_H
来源：http://dali.zhoulong.xyz/Article/details/gteliygruh.html

#endif
来源：http://dali.yonumen.top/Article/details/gtziakkebo.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtsdnbzhcq.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gtjgogaehi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.0kj1m.cn/Article/details/gtndxwmnfc.html

[S32] C++：字符串
来源：http://dali.redwolf501.top/Article/details/gtwopydyih.html

std::string s = "hi";  s += "!";
来源：http://dali.vqdsnc.cn/Article/details/gtlqtzqywd.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gthypaendu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gtdmiaubin.html

[S34] C++：遍历 vector
来源：http://dali.hfpthk.cn/Article/details/gtfeycraei.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuanzx.com/Article/details/gtlcdbxfyb.html

[S35] C++：map
来源：http://dali.shzxlz.cn/Article/details/gtyjjcdpny.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtqlxtwzmd.html

[S36] C++：unordered_map
来源：http://dali.hfpthk.cn/Article/details/gtqjzyqemo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtbvlfjyrq.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gtartluohd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cashguo.top/Article/details/gtvszsqokn.html

[S38] C++：排序
来源：http://dali.meibo888.top/Article/details/gtiyxmjrrw.html

std::sort(v.begin(), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gtevahbedv.html

[S39] C++：自定义比较器排序
来源：http://dali.aibaodan.cn/Article/details/gtslgwbjfz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnxiangtu.top/Article/details/gtpazodmfn.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gtnrhbivut.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwthkgkx.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gtuxdvmatl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hywenlv.cn/Article/details/gtdjnbaowo.html

[S42] C++：继承与虚函数
来源：http://dali.hammf.cn/Article/details/gtabrrdzfe.html

class B : public Base { public: void f() override {} };
来源：http://dali.zdqjudy.top/Article/details/gtsbugayqj.html

[S43] C++：智能指针
来源：http://dali.xinyue.icu/Article/details/gtyloztfvv.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gtrxtfjkhn.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gtsiccjmyu.html

void inc(int &x) { ++x; }
来源：http://dali.jlsjyb.cn/Article/details/gtqsvrjvpw.html

[S45] C++：lambda
来源：http://dali.andypj.xyz/Article/details/gtglgvnoca.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gtbcmqqfcs.html

[S46] C++：函数模板
来源：http://dali.jiagoushi.top/Article/details/gtorpbvjzp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dianchejie.cn/Article/details/gtynjvagvt.html

[S47] C++：结构化绑定遍历
来源：http://dali.ppjwa.cn/Article/details/gtefxxsvza.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.mhx1999.top/Article/details/gtdoufaiws.html

[S48] C++：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtnoizxxli.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangtech.top/Article/details/gtedhncroh.html

while (std::getline(in, line)) { }
来源：http://dali.c1oappe.top/Article/details/gtleenroyj.html

[S49] C++：写文件
来源：http://dali.dashuyun.cn/Article/details/gtxatfntkb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gogol.net.cn/Article/details/gtxudtkejk.html

[S50] C++：格式化数字
来源：http://dali.zhoulong.xyz/Article/details/gtxfwostxk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gthnjfbacp.html

[S51] C++：显式类型转换
来源：http://dali.gaohongyu789.top/Article/details/gttswxbgiz.html

static_cast<double>(a) / b
来源：http://dali.c1oappe.top/Article/details/gtmeliwygs.html

[S52] C++：const 与 noexcept
来源：http://dali.hfpthk.cn/Article/details/gtnnctxwrk.html

int size() const noexcept { return n_; }
来源：http://dali.hywenlv.cn/Article/details/gtzxcfdvlh.html

[S53] C++：移动语义
来源：http://dali.jinqigufen.top/Article/details/gtwsbstxcb.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gtpikvpkwt.html

[S54] C++：异常处理
来源：http://dali.birdmap.top/Article/details/gtwzqppgar.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigfzy.top/Article/details/gtxlhbrpcm.html

[S55] C++：结构化绑定
来源：http://dali.shuidangran.top/Article/details/gtluucmavy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ydzc1.top/Article/details/gtgniwpxha.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gtrofsvsxa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sysykeji.top/Article/details/gtmptarutw.html

[S57] C++：编译期常量
来源：http://dali.nwbrower.top/Article/details/gtgaeqcnkv.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gtlqizunci.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtuxhjyxlg.html


<!-- 参考信息 -->