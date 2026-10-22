代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.fengsongda.top/Article/details/gtgcbkvcrk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hfpthk.cn/Article/details/gtnksnbfwp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtzekdconz.html

[Q89] 判断表是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtcudszrfe.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pycfn.com/Article/details/gtkcacmfbn.html

[Q90] 生成序号列
来源：http://dali.chenzaomai.com/Article/details/gtyfvhhlng.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrckwwoj.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtfwuowipc.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gtoccfjyhc.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gteteacfyf.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gtqmkcycjz.html

#!/usr/bin/env bash
来源：http://dali.yj20258888.top/Article/details/gtqxipjnhm.html

set -euo pipefail
来源：http://dali.sysykeji.top/Article/details/gtojwpwfwj.html

[R02] 变量赋值与使用
来源：http://dali.andypj.xyz/Article/details/gtfrmuknck.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gtfpdbogno.html

[R03] 只读变量
来源：http://dali.xylfe.cn/Article/details/gtxqpknpim.html

readonly PI=3.14
来源：http://dali.feifeiyinyue.top/Article/details/gterippzit.html

[R04] 位置参数
来源：http://dali.yvedp.cn/Article/details/gtuborcmdz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hywenlv.cn/Article/details/gtczbrtmrv.html

[R05] 参数默认值
来源：http://dali.nanxinkj.top/Article/details/gtrrjvohtl.html

name="${1:-default}"
来源：http://dali.chenjidiqi.icu/Article/details/gtucecxkky.html

[R06] 判断命令是否存在
来源：http://dali.aibaodan.cn/Article/details/gtntunydce.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gttllpsnpf.html

[R07] if 判断文件
来源：http://dali.shangyingyoupin.top/Article/details/gtpsqykjdb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gtvejfhwtt.html

[R08] 数值比较
来源：http://dali.zhoulong.xyz/Article/details/gtbntzhlpl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gzhubu.top/Article/details/gtiofnbzif.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtpbntjzez.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sweek.top/Article/details/gtullteaem.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gtmiyuumid.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258.top/Article/details/gtmxdqxlgu.html

[R11] case 多分支
来源：http://dali.yuxming.cn/Article/details/gtizqzqnle.html

case "$1" in
来源：http://dali.fengsongda.top/Article/details/gthztoerti.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gtmascrcdj.html

stop)  echo "停止" ;;
来源：http://dali.cheryme.top/Article/details/gtlxozgjka.html

*)     echo "未知命令" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtwsmfiqeg.html

esac
来源：http://dali.cashguo.top/Article/details/gtggbxmtfk.html

[R12] for 遍历文件
来源：http://dali.gaohongyu789.top/Article/details/gttwqmuazu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fengsongda.top/Article/details/gtrmlqxxko.html

[R13] for 计数循环
来源：http://dali.9152youxi.cn/Article/details/gtiluoyqtx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gtzvpozffq.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gtnvjbhoag.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gtuzrdtbqj.html

[R15] while 逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtqdaakdmo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.iojbl.cn/Article/details/gtzxcrhtnc.html

[R16] until 等待条件
来源：http://dali.kuanghao11.cn/Article/details/gtsgyshlco.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtktulmqox.html

[R17] 数组定义与取值
来源：http://dali.cucudq.cn/Article/details/gtfdzvfzmt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnxiangtu.top/Article/details/gtgtwdzmyq.html

[R18] 遍历数组
来源：http://dali.gzhubu.top/Article/details/gtyqxpazcc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hfpthk.cn/Article/details/gtkjvjqryn.html

[R19] 数组长度
来源：http://dali.pycfn.com/Article/details/gtslzcrbzc.html

echo "${#arr[@]}"
来源：http://dali.yongpay.top/Article/details/gtjkugsklj.html

[R20] 关联数组（字典）
来源：http://dali.c1oappe.top/Article/details/gtfzzqxvlu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xylfe.cn/Article/details/gtbjthtaqz.html

[R21] 字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtahtukqxp.html

echo "${#s}"
来源：http://dali.pycfn.com/Article/details/gtsnwfxciv.html

[R22] 截取子串
来源：http://dali.cheryme.top/Article/details/gtpuzwmxwj.html

echo "${s:0:5}"
来源：http://dali.cucudq.cn/Article/details/gtpnzkihio.html

[R23] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gtcfrbzdcu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sxryk.cn/Article/details/gtxmgofpvu.html

[R24] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gtyonclqvn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yangfankeji.com/Article/details/gtiydqwriq.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gtcxvrniwc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.havefunace.top/Article/details/gtychumevb.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gtzkojzpqv.html

now=$(date +%F); echo "$now"
来源：http://dali.andypj.xyz/Article/details/gtdolqxcdl.html

[R27] 算术展开
来源：http://dali.tian-w.cn/Article/details/gtzqkpwgmc.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258.top/Article/details/gterrfmdio.html

[R28] 浮点运算
来源：http://dali.hywenlv.cn/Article/details/gtlnvslfiq.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangshuangyany.cn/Article/details/gtebubjzsw.html

[R29] 定义函数
来源：http://dali.tanke756.top/Article/details/gtbxmvncca.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jlsjyb.cn/Article/details/gticgkadef.html

[R30] 函数返回状态码
来源：http://dali.sweek.top/Article/details/gtifyeluhx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gthsweclgg.html

[R31] 局部变量
来源：http://dali.meibo888.top/Article/details/gtgtohuant.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258888.top/Article/details/gtntfcvzkb.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gtnaarhnmk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gteeokqldf.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gtwpxookzf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gtjufwyumo.html

[R34] 退出时清理
来源：http://dali.zhongyouzk.top/Article/details/gtjirecqdk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtauckakki.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gtikugkqam.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258888.top/Article/details/gtvrrezpjs.html

[R36] 并发执行多个任务
来源：http://dali.ehwqpu.com/Article/details/gtjutwbfmq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yueranfly.top/Article/details/gtckchimth.html

[R37] 把输出赋给变量
来源：http://dali.vqdsnc.cn/Article/details/gtybktpryy.html

files=$(ls -1)
来源：http://dali.nanxinkj.top/Article/details/gtahmqodds.html

[R38] 管道串联
来源：http://dali.zhixingplan.top/Article/details/gtorqhrkdp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fzhhl.top/Article/details/gtwsfekfaj.html

[R39] 重定向标准输出与错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmcodmxp.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gtjlslnymf.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gtmuingwdr.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gtuxijubux.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gtznoldzky.html

cmd >/dev/null 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtuvfimuju.html

[R42] 输入重定向
来源：http://dali.fzhhl.top/Article/details/gtxrqmsdrc.html

wc -l < a.txt
来源：http://dali.jinqigufen.top/Article/details/gtyiypnyyg.html

[R43] 按名字查找文件
来源：http://dali.bjfxy.top/Article/details/gtasqqrxiq.html

find . -name "*.log" -type f
来源：http://dali.fengsongda.top/Article/details/gtulogxttx.html

[R44] 按修改时间查找
来源：http://dali.hnqzz.top/Article/details/gtatsmjcfn.html

find . -mtime -7 -type f
来源：http://dali.chenzaomai.com/Article/details/gtemthnmyg.html

[R45] 批量删除
来源：http://dali.sxryk.cn/Article/details/gttwrwjnuo.html

find . -name "*.tmp" -delete
来源：http://dali.jiagoushi.top/Article/details/gtdgwhqusl.html

[R46] 递归替换文件内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubsvboyx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gtjywdubwq.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gtmimkzvgw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daria6918.cn/Article/details/gtzybocqmg.html

[R48] awk 取指定列
来源：http://dali.gogol.net.cn/Article/details/gtlpfhnvlz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtcdqazaqj.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gtuswegsig.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedrfgiro.html

[R50] awk 求和
来源：http://dali.aizwys.cn/Article/details/gtapigsppa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtgbwkghep.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gtvuxnsxxu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gtydwhkevi.html

[R52] 统计行数
来源：http://dali.yonumen.top/Article/details/gtvpgvoawi.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gtmzbilvmm.html

[R53] 查看文件头与实时尾
来源：http://dali.0kj1m.cn/Article/details/gtnpdewrbj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdodstldn.html

[R54] 比较两个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtabteihnb.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gtvloejtfh.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmvjvmrl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnxiangtu.top/Article/details/gtwlixchqi.html

[R56] 远程拷贝
来源：http://dali.hammf.cn/Article/details/gtttzuggug.html

scp file user@host:/path/
来源：http://dali.gotoacloud.top/Article/details/gtnjoenxur.html

[R57] 远程执行命令
来源：http://dali.gzhubu.top/Article/details/gtxwikkuyw.html

ssh user@host 'uptime'
来源：http://dali.tanke756.top/Article/details/gtknpvzxuq.html

[R58] 下载文件
来源：http://dali.andypj.xyz/Article/details/gtrmoewwqs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzovciua.html

[R59] 发 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gtxxhlsjjc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gtwhqtbvbd.html

[R60] 只看 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gtcesgessl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.c1oappe.top/Article/details/gtbsfbpbau.html

[R61] 磁盘占用
来源：http://dali.jqgfzy.top/Article/details/gtvxydynpz.html

df -h;  du -sh *
来源：http://dali.yuxming.cn/Article/details/gtevuaigzb.html

[R62] 找最占空间的文件
来源：http://dali.ehwqpu.com/Article/details/gtlwvvyqoh.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gtwiuceghz.html

[R63] 内存与进程
来源：http://dali.jianghu66.top/Article/details/gtlgtufrsq.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gtxahanfkm.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gtmikrxthb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gtfwqfkwoe.html

[R65] 查看端口占用
来源：http://dali.yuanzhike.top/Article/details/gtlncuvuza.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gaohongyu789.top/Article/details/gtrjwnysei.html

[R66] 定时任务
来源：http://dali.tianlin.xyz/Article/details/gtsaiuiwnl.html

crontab -e;  crontab -l
来源：http://dali.quarkkingdee.top/Article/details/gtxavpkweh.html

[R67] 生成随机十六进制串
来源：http://dali.tian-w.cn/Article/details/gtskioiurr.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gtviwowmmj.html

[R68] 计算文件校验值
来源：http://dali.zhixingplan.top/Article/details/gtwjmuepmx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yonumen.top/Article/details/gtqbwwpjnj.html

[R69] 生成随机密码
来源：http://dali.xinyue.icu/Article/details/gttsmsjbvn.html

head -c 16 /dev/urandom | base64
来源：http://dali.shzxlz.cn/Article/details/gtbplzmwhe.html

[R70] 时间戳与互转
来源：http://dali.yuanzhike.top/Article/details/gtoxswpvqw.html

date +%s;  date -d @1700000000
来源：http://dali.gogol.net.cn/Article/details/gtkqbkekxf.html

[R71] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtgzqykukt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgufenzy.top/Article/details/gtgtbnsxcv.html

[R72] 等待端口就绪
来源：http://dali.yangfankeji.com/Article/details/gtijjvgrvs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtzgzfkedl.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gtmoixoatz.html

split -l 1000 big.log part_
来源：http://dali.gogol.net.cn/Article/details/gtvjgvrewq.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gtrukjgswj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yangfankeji.com/Article/details/gtholknesm.html

[R75] 导出环境变量
来源：http://dali.wangdashe.top/Article/details/gtjzbzeenp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnxiangtu.top/Article/details/gtimtqiifv.html

[R76] 使用临时文件
来源：http://dali.zhoulong.xyz/Article/details/gtkoxhxlhw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gtqsktcjqj.html

[R77] 读取用户输入
来源：http://dali.guannengcc.top/Article/details/gtbsoemgpx.html

read -rp "请输入: " ans
来源：http://dali.feifeiyinyue.top/Article/details/gtsssklgfk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gthgtwacxy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jyoumei.cn/Article/details/gtqhvrmgdp.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gtoxhrasyr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gogol.net.cn/Article/details/gtskbtrqtq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhongyouzk.top/Article/details/gtwvlguomz.html

time ./run.sh
来源：http://dali.chenjidiqi.icu/Article/details/gtxyqxewka.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtnmsutmhv.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gtyiwgvhsi.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtccydcglt.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtbovhpozk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gtkdefjoak.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.redwolf501.top/Article/details/gtjkdaqaxv.html

[S02] C：变量与格式化输出
来源：http://dali.guannengcc.top/Article/details/gtvnlgmrpz.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gtclexvwsi.html

[S03] C：读入整数
来源：http://dali.gogol.net.cn/Article/details/gtlicbvjch.html

int x; scanf("%d", &x);
来源：http://dali.mhx1999.top/Article/details/gtbpxkdgne.html

[S04] C：字符串复制
来源：http://dali.cheryme.top/Article/details/gtgqazgjiu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocriprjk.html

[S05] C：字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtzcdhoqmm.html

strlen(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgbbixnq.html

[S06] C：字符串比较
来源：http://dali.wangdashe.top/Article/details/gtiqamjsgu.html

strcmp(a, b) == 0
来源：http://dali.jlsjyb.cn/Article/details/gtmlupvyvi.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gtwzeqvqem.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gteglgtkpn.html

[S08] C：动态内存分配与释放
来源：http://dali.andypj.xyz/Article/details/gtqfpxhrgv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gtgwlpqkwj.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gtsbfhloop.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaedufkvd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gtqauwnkdr.html

int *p = &a;  *p = 5;
来源：http://dali.yangfankeji.com/Article/details/gttufhjfqm.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtqigeutet.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.316326.xyz/Article/details/gtqalpzznh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigufen.top/Article/details/gtnbceshiz.html

fclose(f);
来源：http://dali.yonumen.top/Article/details/gtublanofq.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gtmhmacsiz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcaqwslyg.html

[S13] C：宏定义
来源：http://dali.shuidangran.top/Article/details/gtlfoeiwax.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhongyouzk.top/Article/details/gtrmupkxty.html

[S14] C：枚举
来源：http://dali.dashuyun.cn/Article/details/gttuommuql.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cucudq.cn/Article/details/gtjkspmnkh.html

[S15] C：类型转换
来源：http://dali.jinqigfzy.top/Article/details/gtxkfwxxvc.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gtoiwlpzac.html

[S16] C：位操作置位
来源：http://dali.hfpthk.cn/Article/details/gtwdyfxabw.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gtqwgglgfo.html

[S17] C：安全拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtljbiedfy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yonumen.top/Article/details/gtbcyuuiww.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtleftfzam.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gtxkeorebo.html

[S19] C：快速排序
来源：http://dali.yanxiufei.cn/Article/details/gtibruwsdh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtqvdeoxhv.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gtiidrtkna.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gtlcguawsw.html

[S21] C：字符类别判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejautmuf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tanke756.top/Article/details/gtppxnqojt.html

[S22] C：字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gtrkfpqmuz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gtneljzgvt.html

[S23] C：随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopuvkmht.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuuipgkr.html

[S24] C：获取本地时间
来源：http://dali.pycfn.com/Article/details/gtpglttjhg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgufenzy.top/Article/details/gtzdwemdsl.html

[S25] C：内存拷贝
来源：http://dali.c1oappe.top/Article/details/gtseaufjsc.html

memcpy(dst, src, n);
来源：http://dali.zycfv.cn/Article/details/gtdjktjafz.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gttbmnvoyz.html

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gtvdtuauov.html

[S27] C：定义常量
来源：http://dali.andypj.xyz/Article/details/gtinuovjpv.html

const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtthpfhsmy.html

[S28] C：静态变量
来源：http://dali.zdqjudy.top/Article/details/gthkdexgmp.html

static int counter = 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumiefwgs.html

[S29] C：变参函数
来源：http://dali.gzhubu.top/Article/details/gthefnqygr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.andypj.xyz/Article/details/gttnqezejy.html

[S30] C：头文件保护
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlckhtmx.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gtjolyoyqy.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gtmlrwxnuu.html

#endif
来源：http://dali.gzhubu.top/Article/details/gtcbdnojqt.html

[S31] C++：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtrxodftkf.html

#include <iostream>
来源：http://dali.nanxuanxn.top/Article/details/gtrnutbeoh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gogol.net.cn/Article/details/gtbcqzqmbg.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gtupnrstai.html

std::string s = "hi";  s += "!";
来源：http://dali.fzhhl.top/Article/details/gtpehyvkmd.html

[S33] C++：vector 增删
来源：http://dali.quarkkingdee.top/Article/details/gtccjigkls.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangdashe.top/Article/details/gtivftbazh.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gtreoctwsk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gtcbayobpa.html

[S35] C++：map
来源：http://dali.xuanzx.com/Article/details/gtlcwmwuje.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtgxjwpebi.html

[S36] C++：unordered_map
来源：http://dali.dashuyun.cn/Article/details/gtxttwjtgl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtgblqzxyg.html

[S37] C++：set
来源：http://dali.jinghuilouyu.cn/Article/details/gtgytyeleq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenzaomai.com/Article/details/gtdaxpkxsz.html

[S38] C++：排序
来源：http://dali.xuanzx.com/Article/details/gtgvsgtzup.html

std::sort(v.begin(), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtshjlktsa.html

[S39] C++：自定义比较器排序
来源：http://dali.hongshengwenyu.top/Article/details/gtqgyfozji.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigfzy.top/Article/details/gtejvbllok.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnbaadjg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.andypj.xyz/Article/details/gtbimazaep.html

[S41] C++：类与构造函数
来源：http://dali.cqqwz.cn/Article/details/gtnvpcjhdp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gtpzqfdzim.html

[S42] C++：继承与虚函数
来源：http://dali.jqgufenzy.top/Article/details/gtcrsouemj.html

class B : public Base { public: void f() override {} };
来源：http://dali.yangfankeji.com/Article/details/gtazfeabzz.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gthkolbwoc.html

auto p = std::make_unique<int>(5);
来源：http://dali.xinyue.icu/Article/details/gtyunfazyw.html

[S44] C++：引用传参
来源：http://dali.zhengqikj.top/Article/details/gttwhtiscb.html

void inc(int &x) { ++x; }
来源：http://dali.birdmap.top/Article/details/gtntqlajiy.html

[S45] C++：lambda
来源：http://dali.iojbl.cn/Article/details/gtttwocwto.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zdqjudy.top/Article/details/gtyvlakpkn.html

[S46] C++：函数模板
来源：http://dali.gogol.net.cn/Article/details/gtamihjidf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jiagoushi.top/Article/details/gtjqsewfxm.html

[S47] C++：结构化绑定遍历
来源：http://dali.nanxinkj.top/Article/details/gtxfcuharw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cashguo.top/Article/details/gtgedgtrgk.html

[S48] C++：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtpmylirul.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gtocmalgot.html

while (std::getline(in, line)) { }
来源：http://dali.shzxlz.cn/Article/details/gtlrltnemp.html

[S49] C++：写文件
来源：http://dali.hywenlv.cn/Article/details/gtbhodirtr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gtuqmsocxg.html

[S50] C++：格式化数字
来源：http://dali.xuetiantiany.cn/Article/details/gtgoteojuo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtqoefzibk.html

[S51] C++：显式类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gtkfldgvun.html

static_cast<double>(a) / b
来源：http://dali.shuidangran.top/Article/details/gtrdcuncqf.html

[S52] C++：const 与 noexcept
来源：http://dali.guowangkeji.top/Article/details/gtaklxttzg.html

int size() const noexcept { return n_; }
来源：http://dali.pycfn.com/Article/details/gtthwekdue.html

[S53] C++：移动语义
来源：http://dali.yuxming.cn/Article/details/gtihkstvqk.html

std::vector<int> w = std::move(v);
来源：http://dali.sysykeji.top/Article/details/gtxajodcmk.html

[S54] C++：异常处理
来源：http://dali.pengpengdd.cyou/Article/details/gtbuusqetk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxinkj.top/Article/details/gtacajfczr.html

[S55] C++：结构化绑定
来源：http://dali.cashguo.top/Article/details/gtsqjruifp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gthsjczlrc.html

[S56] C++：optional
来源：http://dali.jqgufenzy.top/Article/details/gtqsneiccv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gthkcwausc.html

[S57] C++：编译期常量
来源：http://dali.zycfv.cn/Article/details/gtjmeojzru.html

constexpr int N = 10;
来源：http://dali.c1oappe.top/Article/details/gtkazfelkr.html

[S58] C++：命名空间
来源：http://dali.ybcxt.top/Article/details/gtketmkpit.html


<!-- 参考信息 -->